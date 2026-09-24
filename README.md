# Galaxia de flores amarillas — lista para GitHub Pages

Adaptación de la referencia proporcionada: https://cdn.dedicacodes.com/t/galaxia-nebulosa-flores-amarillas/1.0.0/index.html
Se conservan el diseño, las frases, las imágenes y el audio de esa referencia.

## Publicar desde GitHub
1. Descomprime el ZIP.
2. Crea un repositorio en GitHub, por ejemplo `galaxia-flores`.
3. En Add file → Upload files, arrastra los archivos y las carpetas extraídos. `index.html` debe quedar en la raíz del repositorio, junto a `config.js`, `assets` y `vendor`. No subas el ZIP cerrado ni una carpeta adicional que encierre todo.
4. Confirma con Commit changes.
5. Abre Settings → Pages → Build and deployment.
6. En Source selecciona Deploy from a branch.
7. Selecciona `main` y `/(root)` y pulsa Save.
8. Cuando finalice el despliegue, Pages mostrará el enlace de tu página. Si aún está en proceso, revisa Actions.

Documentación oficial: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Personalizar
Abre `config.js` en el editor de GitHub o en VS Code.
- `titulo`: el encabezado. Por ejemplo: "Flores amarillas para Geysa 🌻".
- `frases`: cambia los textos conservando las comillas y comas.
- `fotos`: rutas de las imágenes que flotan; puedes reemplazar los PNG de assets.
- `musica`: ruta del MP3. Puedes reemplazar assets/musica.mp3.
Guarda los cambios en GitHub para actualizar la página.

## Controles
Toca el girasol para iniciar la experiencia y el audio.
Arrastra con el ratón o un dedo para girar la cámara.
Usa la rueda, dos dedos o + / − para acercar y alejar.
♫ controla la música; Ⅱ / ▶ pausa o reanuda las órbitas.
↺ restaura la vista; ⛶ solicita pantalla completa si el navegador la admite.

## Mejoras
Controles visibles, interacción táctil unificada, adaptación al cambiar el tamaño de pantalla, animación ajustada al tiempo entre fotogramas, reutilización de texturas de frases repetidas, controles con etiquetas accesibles y respeto de la preferencia de movimiento reducido.
Three.js, las imágenes y el audio están incluidos. La fuente manuscrita se carga desde Google Fonts; si no está disponible se usa una fuente cursiva del dispositivo. Requiere un navegador con WebGL.

## Procedencia
Diseño y contenido original: página de DedicaCodes indicada arriba. Esta adaptación no cambia la titularidad del material original. Three.js se distribuye con su licencia MIT en vendor/THREE-LICENSE.txt.

## Comprobaciones realizadas
Sintaxis de los scripts, integridad de las imágenes y presencia de los archivos locales. La comprobación visual interactiva no se pudo completar porque el navegador de revisión no puede acceder al servidor local. No se ha publicado en ninguna cuenta de GitHub.

