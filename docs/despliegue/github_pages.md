---
title: Despliegue en GitHub Pages
---

# Despliegue en GitHub Pages

GitHub Pages permite publicar la documentación como un sitio web estático.

## Preparación

El proyecto se almacena en un repositorio de GitHub.

Docusaurus genera los archivos estáticos de la web mediante el comando `npm run build`.

## Publicación

GitHub Actions ejecuta un workflow que instala las dependencias, construye la web y publica el contenido generado.

## Comprobación

Una vez finalizado el despliegue, se accede a la URL pública para comprobar que la documentación funciona correctamente.
