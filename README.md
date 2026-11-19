# SyncLab — Simulador interactivo de sincronización

Proyecto web estático educativo para explorar mecanismos de sincronización de procesos e hilos.

## Cómo ejecutarlo en Visual Studio Code

1. Descomprime el ZIP y abre la carpeta `SyncLab_GitHub` en VS Code (**Archivo → Abrir carpeta**).
2. Abre `index.html` en tu navegador. También puedes usar la extensión **Live Server** y seleccionar **Open with Live Server**.
3. Prueba los controles de los módulos del simulador.

No requiere instalación de dependencias ni servidor backend. Funciona sin conexión a Internet.

## Contenido

- `index.html`: aplicación completa (HTML, CSS y JavaScript).
- `README.md`: instrucciones de ejecución y publicación.
- `.gitignore`: archivos locales que no deben subirse.

## Publicar en GitHub

1. Crea un repositorio nuevo en GitHub.
2. En la terminal de VS Code, dentro de esta carpeta, ejecuta:

```bash
git init
git add .
git commit -m "Agregar simulador SyncLab"
git branch -M main
git remote add origin https://github.com/TU_USUARIO/TU_REPOSITORIO.git
git push -u origin main
```

Sustituye `TU_USUARIO` y `TU_REPOSITORIO` por los tuyos. Si el repositorio remoto ya tiene archivos, revisa su historial antes de hacer push.

## GitHub Pages (opcional)

En el repositorio, abre **Settings → Pages** y elige **Deploy from a branch**, rama **main** y carpeta **/(root)**. Guarda la configuración. GitHub publicará la web desde `index.html`.

## Nota

Es una simulación didáctica de operaciones concurrentes; no ejecuta hilos reales del sistema operativo.
