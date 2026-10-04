# Mi Letra Linda — publicación en Netlify

Este sitio es estático. Netlify puede publicarlo directamente desde esta carpeta; el archivo de entrada es `index.html`.

## Antes de publicar

Reemplaza en `index.html` los marcadores por tus datos reales:

- `PEGA-AQUI-TU-LINK-DE-CHECKOUT`
- `PEGA-AQUI-TU-WHATSAPP`
- `PEGA-AQUI-TU-EMAIL`
- `PEGA-AQUI-TU-PIXEL-DE-META` (opcional)

## Publicar con GitHub

1. Crea un repositorio en GitHub y sube el contenido de esta carpeta, con `index.html` en la raíz.
2. En Netlify, elige **Add new site** → **Import an existing project** y conecta GitHub.
3. Selecciona el repositorio. Para esta página no hace falta comando de build; deja vacíos **Build command** y **Publish directory** como `.` (raíz).
4. Pulsa **Deploy site**.

Cada actualización que subas a la rama conectada iniciará otro despliegue.

