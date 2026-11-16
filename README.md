# Wantalyze · Lab Notes

Blog estático de la Serie Biblioteca Vintage. Cada entrada se genera a diario en Google Drive y se sincroniza aquí.

```
index.html              librero: lee posts.json y muestra las portadas
posts.json              manifiesto, de la entrada más nueva a la más vieja
posts/NNN-slug/
  index.html            el artículo
  miniatura.png         portada 1200x1800 (og:image)
```

Para verlo en local: `python3 -m http.server` y abre http://localhost:8000 (el `fetch` de posts.json no funciona con `file://`).
