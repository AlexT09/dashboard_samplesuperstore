# Dashboard Sample Superstore — 3D

Dashboard web 3D del dataset Sample Superstore.

![Página principal](assets/screenshots/inicio.png)

![Dashboard de ventas](assets/screenshots/dashboard.png)

- `index.html`: página principal (antes `3DWebDashboard.html`).
- `Dashboard Superstore.dc.html`: dashboard embebido en la página principal. Sigue el formato de un
  dashboard ejecutivo (filtros, KPIs con variación anual y un insight debajo de cada gráfico); sin
  filtros, los insights son los textos del EDA.
- `dashboard_core.js`: filtros, KPIs e insights del dashboard.
- `dashboard_data.json`: figuras y datos que carga el dashboard.
- `support.js`, `assets/`, `favicon.ico`: recursos de la página (capturas en `assets/screenshots/`).

`dashboard_core.js` y `dashboard_data.json` vienen del proyecto
[proyecto_superstorep](https://github.com/AlexT09/proyecto_superstorep) (`3DWebDashboard/`), donde se
generan con `python dashboard/build_dashboard.py`.

Para verlo localmente, sirve la carpeta con cualquier servidor estático, por ejemplo:

```
python -m http.server 8000
```

y abre http://localhost:8000/.
