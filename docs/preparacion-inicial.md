# Preparación inicial

Revisión realizada el 16 de noviembre de 2026 en Windows.

## Programas revisados

| Programa | Resultado | Para qué sirve | Si hace falta |
|---|---|---|---|
| Node.js | Disponible como Node v24.22.1 en el entorno actual. | Ejecuta herramientas JavaScript, incluido el proyecto de esta carpeta. | El instalador oficial de Windows está en [nodejs.org](https://nodejs.org/en/download/). Incluye npm, que no apareció instalado en esta revisión. |
| npm | No encontrado. | Descarga y organiza las piezas que un proyecto de Node necesita. | Se instala junto con Node.js desde [nodejs.org](https://nodejs.org/en/download/). |
| FFmpeg | Disponible, versión 9.0. | Convierte y prepara audio y video para los clips. | Si en otro equipo falta, la página de FFmpeg enlaza compilaciones para Windows: [ffmpeg.org/download.html](https://ffmpeg.org/download.html). |
| ffprobe | Disponible, versión 9.0. | Lee duración y datos técnicos de audio y video; viene en la misma distribución de FFmpeg. | Se obtiene junto con FFmpeg desde la página anterior. |
| CapCut de escritorio | No apareció en el menú de aplicaciones ni en las ubicaciones habituales revisadas. | Abre el proyecto de montaje para que la persona haga la exportación final. | Descarga oficial: [CapCut para Windows](https://www.capcut.com/resource/capcut-for-windows). |
| Python | Disponible, versión 3.14.7. | Puede servir para herramientas auxiliares; todavía no sabemos si hará falta. | No se requiere instalarlo ahora. |

Node fue encontrado dentro del entorno que usa esta herramienta. Eso no garantiza que Node esté instalado para todos los programas de Windows. npm no fue encontrado como comando. No se instaló ningún programa.

## Carpeta creada

`videos/prueba/` contiene una carpeta para cada etapa: `guion`, `voz`, `tiempos`, `escenas`, `material`, `clips` y `montaje`. El video empieza en la etapa 1, Guion.

`videos/estado.json` registra los videos y su etapa actual. Al preguntar «¿en qué estado está mi proyecto?», se puede revisar este registro y las carpetas para responder con el estado de cada video.

## Claves

El archivo local `config/keys.env` está vacío y Git lo ignora. No se deben guardar claves reales en ningún archivo que se suba al repositorio.

## No instalado

No se instaló nada. Si el usuario quiere usar CapCut en esta máquina, tendrá que instalarlo desde la página oficial indicada arriba. Para Node/npm se puede descargar Node.js desde su página oficial si se necesita fuera del entorno de Codex.

