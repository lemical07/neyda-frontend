# NEYDA — Frontend

Sistema de Gestión Clínica | Interfaz de usuario

**Stack:** HTML5 · CSS3 · JavaScript Vanilla
**Deploy:** Netlify → `neyda-clinic.app`

## Estructura

```
assets/
  css/   → variables.css · main.css · components.css
  js/    → config.js · api.js · auth.js · utils.js
  img/   → logo.svg · favicon.ico
pages/
  dashboard.html
  pacientes/  → lista · nuevo · editar · detalle
  citas/      → agenda · nueva · editar
  historial/  → paciente · consulta-nueva · consulta-detalle
index.html    → Login
netlify.toml  → Redirects config
```

## Configuración

Editar `assets/js/config.js` con la URL del backend en Render:

```js
const API_BASE_URL = 'https://<tu-servicio>.onrender.com/neyda';
```

## Ramas

- `main` → producción
- `dev`  → desarrollo activo
