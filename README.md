# Cadencia - Página de GitHub

Página estática lista para publicarse con **GitHub Pages + GitHub Actions**.

## Estructura

- `index.html` - página principal
- `assets/` - imágenes, GIFs y recursos
- `.github/workflows/deploy-pages.yml` - acción automática para publicar en GitHub Pages
- `.nojekyll` - evita que GitHub Pages procese el sitio con Jekyll

## Cómo subirlo

1. Crea o abre tu repositorio en GitHub.
2. Sube **todo el contenido de esta carpeta** a la raíz del repo, no dentro de otra carpeta.
3. Haz commit en la rama `main`.
4. Ve a **Settings → Pages**.
5. En **Build and deployment**, elige **GitHub Actions**.
6. Ve a **Actions** y espera a que termine `Deploy static site to GitHub Pages`.
7. Tu página quedará disponible en la URL de GitHub Pages del repo.

## Notas

Este sitio no necesita instalación ni compilación. Es HTML/CSS estático con assets locales.
