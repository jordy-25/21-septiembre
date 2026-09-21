# Para Yessica 💛

Micrositio romántico interactivo preparado para publicarse con GitHub Pages.

## Publicación en GitHub Pages

1. Crea un repositorio nuevo en GitHub.
2. Sube todo el contenido de esta carpeta a la raíz del repositorio.
3. En GitHub abre:
   **Settings → Pages**
4. En **Build and deployment** selecciona:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/ (root)`
5. Guarda los cambios.

GitHub generará una URL similar a:

`https://TU-USUARIO.github.io/NOMBRE-DEL-REPOSITORIO/`

## Contenido

- `index.html`: experiencia completa.
- `.nojekyll`: evita que GitHub Pages procese el sitio con Jekyll.

## Nota técnica

Las fotografías, audio y video están integrados dentro del propio HTML para que el proyecto sea sencillo de publicar.

La escena 3D usa Three.js desde CDN, por lo que necesita conexión a Internet al abrirse.

El diseño incluye adaptación para escritorio, tablet y teléfono.
