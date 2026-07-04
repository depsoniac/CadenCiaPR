# Cadencia - página para GitHub Pages

Landing page estática para presentar Cadencia, el editor de subtítulos multipista.

## Cómo subirla a GitHub Pages

1. Descomprime este ZIP.
2. Sube el contenido de la carpeta `cadencia-github-page` a la raíz de tu repositorio.
3. En GitHub entra a **Settings > Pages**.
4. En **Build and deployment**, elige **Deploy from a branch**.
5. Selecciona `main` y la carpeta `/root`.
6. Guarda y espera a que GitHub publique la página.

## Cambia estos enlaces

En `index.html` busca `https://github.com/depsoniac/Cadencia` y cambia el usuario/repositorio si tu repo se llama distinto.

También puedes cambiar el botón de releases:

```html
https://github.com/depsoniac/Cadencia/releases
```

## Notas de assets

- `assets/gifs/censuras-manuales-premiere.gif` y `assets/gifs/palabras-a-marcadores-premiere.gif` sí llegaron como GIFs funcionales y fueron recortados para no iniciar en negro.
- Varios GIFs subidos llegaron como un solo cuadro negro. Para que la página no se vea rota, dejé capturas y placeholders bonitos. Cuando tengas los GIFs buenos, reemplaza las imágenes de las tarjetas por tus GIFs reales o ponles el mismo nombre y actualiza el `src`.
- El PDF original queda incluido como `Cadencia-presentacion.pdf` por si quieres enlazarlo desde la página.
