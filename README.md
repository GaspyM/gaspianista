# Gaspianista

Sitio estatico multipagina para `Gaspianista`, listo para deploy en Netlify.

## Estructura

- `index.html`: inicio en espanol
- `proyecto.html`: pagina de proyecto en espanol
- `catalogo.html`: pagina de partituras en espanol
- `plataformas.html`: pagina de plataformas en espanol
- `en/`, `pt/`, `it/`: versiones en ingles, portugues e italiano
- `styles.css`: estilos compartidos
- `grand-piano.png`: imagen principal del piano
- `assets/flags/`: banderas PNG para selector de idioma
- `netlify.toml`: configuracion de Netlify

## Deploy en Netlify

No requiere build.

- Build command: vacio
- Publish directory: `.`

## GitHub

Pasos sugeridos:

1. `git init`
2. `git add .`
3. `git commit -m "Initial site setup"`
4. Crear repo en GitHub
5. `git remote add origin <URL_DEL_REPO>`
6. `git branch -M main`
7. `git push -u origin main`
