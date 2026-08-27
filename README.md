# Casa Nat & Ro 🏡

App de finanzas personales compartidas para Nat y Ro.

- **Stack:** HTML + CSS + JS vanilla, un solo archivo (`index.html`).
- **Backend:** Supabase (tabla `casa_data`, fila `id = 'main'`, columnas `data jsonb` y `updated_at`).
- **Sync:** polling REST cada 10 s contra `/rest/v1/casa_data`.
- **Hosting:** GitHub Pages, desplegado por `.github/workflows/deploy-pages.yml` en cada push a `main`.

## Desarrollo

No hay build. Abrí `index.html` en el navegador o serví la carpeta:

```bash
python3 -m http.server 8000
```
