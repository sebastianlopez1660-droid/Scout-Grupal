# Scout Grupal

App de scouting de futbol (Sebastian Lopez).

Es una aplicacion estatica de un solo archivo: todo el HTML, CSS y JavaScript
esta empaquetado dentro de `index.html`, sin dependencias externas ni build.

## Ver en local

Abrir `index.html` directamente en el navegador, o levantar un servidor estatico:

```bash
python3 -m http.server 8000
# http://localhost:8000
```

## Desplegar en Vercel

1. Importar este repositorio en https://vercel.com/new
2. Framework Preset: **Other**
3. Build Command: vacio · Output Directory: `.` (raiz del repo)
4. Deploy

Vercel sirve `index.html` desde la raiz, no hace falta ningun paso de build.
