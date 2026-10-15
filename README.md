# Portfolio de Luz Carou García

Sitio estático de dos archivos: `index.html` y `style.css`. No necesita instalar nada ni compilar.

## Publicarlo en GitHub Pages

1. Creá una cuenta en [github.com](https://github.com) si no tenés una.
2. Creá un repositorio nuevo, público. Para tener la dirección `https://TU-USUARIO.github.io`, el repositorio tiene que llamarse exactamente `TU-USUARIO.github.io`. Con cualquier otro nombre, la dirección será `https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/`.
3. Subí `index.html`, `style.css` y este `README.md` (botón **Add file → Upload files**) y confirmá con **Commit changes**.
4. En el repositorio, entrá a **Settings → Pages**. En **Build and deployment**, elegí **Deploy from a branch**, la rama `main` y la carpeta `/ (root)`, y guardá.
5. Esperá uno o dos minutos. GitHub muestra la dirección del sitio en esa misma pantalla.

## Cambiar el contenido

- **Textos y links:** editá `index.html` (en GitHub, con el ícono del lápiz). Cada nota está en un bloque `<article class="piece">`; cada puesto, en un `<article class="job">`.
- **Colores y tipografía:** están al principio de `style.css`, en `:root`.
- **Agregar una nota:** copiá un bloque `<article class="piece">…</article>`, pegalo debajo y cambiá fecha, título, link y descripción.

## Decisiones de privacidad

El sitio es público, así que no incluye fecha de nacimiento, domicilio ni teléfono. Solo figuran el mail y LinkedIn. Si querés sumar el teléfono, agregalo en la sección de contacto de `index.html`.
