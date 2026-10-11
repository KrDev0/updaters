# Publicación de actualizaciones

Sube `lasted.json` y `changelog.md` a la carpeta `mega/` de la rama pública `main` del repositorio `KrDev0/updaters`.

`lasted.json` es el manifiesto que consultará MegaDownloader. Su URL pública configurada en la app es:

```text
https://raw.githubusercontent.com/KrDev0/updaters/refs/heads/main/mega/lasted.json
```

Para cada lanzamiento:

1. Publica el ZIP nuevo en la página oficial `https://kr-dev.site/?app=mega`.
2. Cambia `version` por la versión nueva en formato semántico, por ejemplo `4.0.1-beta`.
3. Actualiza `releaseNotes` con un resumen breve y agrega el detalle a `changelog.md`.
4. Publica ambos archivos en GitHub. No marques `version` como nueva antes de que el ZIP esté disponible en la página oficial.

La app comparará el campo `version` con su versión compilada. Si hay una versión posterior, mostrará las novedades y permitirá abrir la página oficial para que el usuario decida si descarga el ZIP. El manifiesto no inicia descargas ni reemplaza archivos.
