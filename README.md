# TablEF en GitHub Pages

Este sitio ya está preparado en esta carpeta:

- `index.html` (copiado desde `Downloads/TablEF. Guía de EF.html`)
- `.nojekyll` (para evitar problemas de procesado en GitHub Pages)

## Publicar (opción simple)

1. Crea un repositorio nuevo en GitHub, por ejemplo: `tablef-pages`.
2. Sube el contenido de esta carpeta (`index.html`, `.nojekyll`, `README.md`) a la rama `main`.
3. En GitHub: **Settings → Pages**.
4. En **Build and deployment** selecciona:
   - **Source**: `Deploy from a branch`
   - **Branch**: `main` / `(root)`
5. Guarda y espera 1-2 minutos.
6. Tu web quedará en una URL como:
   - `https://TU-USUARIO.github.io/tablef-pages/`

## Publicar desde terminal (rápido)

```powershell
cd tablef-pages
git init
git add .
git commit -m "Publicar TablEF en GitHub Pages"
git branch -M main
git remote add origin https://github.com/TU-USUARIO/tablef-pages.git
git push -u origin main
```

Luego activa GitHub Pages en Settings como se indica arriba.
