# Mi Yanet

Página romántica de una sola vista para Erik y Yanet. Incluye portada, frases cambiantes, nuestra historia, carrusel de momentos, álbum de fotos, quiz y pie de página. Usa HTML, CSS y JavaScript puro, sin frameworks ni dependencias.

## Cómo abrirla

Abre `Index.html` en el navegador. Si los módulos JavaScript no cargan desde el archivo local, inicia un servidor estático, por ejemplo con `npx serve` o con Live Server de VS Code.

## Estructura

- `Index.html`: única página, con todas las secciones.
- `CSS/`: estilos por sección. `main.css` solo importa los demás archivos.
- `JS/`: un módulo por sección, con funciones `initXxx`. `main.js` los importa y los ejecuta cuando carga la página.
- `Assets/`: fotos, iconos y la canción `EVERYTHING.mp3`.

## Música

La canción se reproduce en bucle. Arranca al hacer clic en el botón de la cortina inicial, porque los navegadores bloquean el audio automático.
