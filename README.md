# practica-html-css

Esta es mi página HVEO

Antes de poder visualizarla, debes ir a Extensiones (se encuentra en la barra de la izquierda) y descargarte browsersync.
Una vez instalado, hacer click derecho encima de la carpeta <practica-html> y seleccionarla opción BrowserSync Start.

Instalar BrowserSync en el proyecto local:

```
npm install browser-sync --save-dev
```

Añadir un script en Package.json:

```
{
  "scripts": {
    "start": "browser-sync start --server --files 'index.html css/*.css'"
  },

```

Inicializar app dentro de "practica-html"

```
npm run start

```
