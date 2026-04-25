# Walkthrough 360 — Cántalo Fútbol Fest

Sitio estático Pannellum para publicar online con GitHub Pages.

## Desarrollo local

```bash
py -m http.server 8000
```

Abrir:

```txt
http://localhost:8000/index.html
```

## Actualizar imágenes con más calidad

Para mejorar la resolución después, reemplazar las imágenes dentro de:

```txt
Render/Render HD/
```

Mantener exactamente los mismos nombres de archivo para no romper rutas del walkthrough.

Ejemplo:

```txt
Render/Render HD/Render S01 Portal.png
```

Después ejecutar:

```bash
git add Render/Render\ HD/
git commit -m "chore: update hd renders"
git push
```

GitHub Pages tomará los cambios automáticamente cuando el repo esté publicado desde `main` / `/root`.
