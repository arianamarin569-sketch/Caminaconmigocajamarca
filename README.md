# Camina Conmigo — sitio web

Sitio estático preparado para publicarse con GitHub Pages.

## Publicación

1. Sube `index.html`, `.nojekyll` y la carpeta `assets` a la raíz del repositorio.
   El logo por sí solo no es suficiente: deben quedar publicados también los otros 109 archivos de `assets`.
   Si usas la página web de GitHub, haz la carga en dos tandas porque el cargador web admite un máximo limitado de archivos por operación; como alternativa, usa GitHub Desktop.
2. Las 100 fotografías de la galería están directamente dentro de `assets`, con nombres web seguros desde `galeria-001.jpeg` hasta `galeria-100.jpeg`. La página las ordena y agrupa automáticamente en nueve secciones según la lista entregada.

   La lista original incluye además 10 copias dentro de “Cercado del terreno (archivos repetidos)”. Esos archivos terminados en nombres como `(1)(1).jpeg` son duplicados y la página los omite deliberadamente.
3. En GitHub, abre **Settings > Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**.
5. Elige la rama `main`, la carpeta `/ (root)` y guarda.

El archivo `index.html` usa rutas relativas, por lo que funciona tanto en un dominio de GitHub Pages como en un dominio personalizado.

Después de publicar, comprueba que estas dos direcciones abran imágenes reales y no una página de error:

- `https://TU-DOMINIO/assets/hero-visita-navidena.jpeg`
- `https://TU-DOMINIO/assets/galeria-001.jpeg`

Si falta una fotografía o su nombre no coincide, la galería mostrará un recuadro con el nombre exacto del archivo que debe subirse.
