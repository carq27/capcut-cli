# Plan: editor automático de video para YouTube

**Estado:** preparación inicial; no se ha escrito código.  
**Fecha:** 16 de noviembre de 2026

## Objetivo

Convertir un guion escrito por la persona en un proyecto que se pueda abrir en CapCut. La persona exportará el video final desde CapCut. El sistema nunca escribirá ni completará el guion.

## Reglas de trabajo

- Haremos una etapa a la vez y en el orden indicado.
- No empezaremos la siguiente etapa hasta que la actual funcione y guarde su resultado en un archivo.
- Cada etapa usará el resultado de la anterior y guardará su propio resultado para poder revisarlo.
- Explicaremos los pasos y errores con palabras sencillas.
- Las claves de servicios irán en `config/keys.env`, un archivo local excluido de GitHub. Nunca se pondrán claves reales en el código ni en los archivos de resultados.

## Ocho etapas

| N.º | Etapa | Trabajo | Resultado guardado |
|---|---|---|---|
| 1 | Guion | Recibir el guion que la persona escribió aparte. No redactarlo ni cambiarlo. | Texto original en la carpeta del video. |
| 2 | Voz | Convertir el guion en audio con una voz de IA. | Archivo de audio. |
| 3 | Tiempos | Marcar el segundo en que suena cada palabra. | Archivo de tiempos. |
| 4 | Planificación | Dividir el guion en escenas según lo que se verá. | Archivo con las escenas. |
| 5 | Material | Buscar fotos o videos reales en bancos gratuitos. | Material y registro de su fuente. |
| 6 | Revisión | Pedir a una IA que revise si cada material coincide con la narración. | Archivo con el resultado de la revisión. |
| 7 | Clips | Crear un clip por escena con su duración exacta. | Clips y un índice de clips. |
| 8 | Montaje | Ordenar los clips en un proyecto de CapCut. La persona exportará el video final. | Proyecto que se abre en CapCut. |

Una etapa estará lista cuando su resultado se haya creado y pueda revisarse. Acordaremos los servicios concretos cuando llegue cada etapa, antes de usar claves o instalar dependencias.

## Preferencias del canal

- Nombre provisional: Dr. Faceless (por confirmar).
- Idioma: español (variante por confirmar).
- Voz: por definir.
- Formato del video: por definir.
- CapCut: versión por confirmar.

## Decisiones pendientes

Se preguntó por idioma y formato, voz, tipo de material, versión de CapCut y repositorio. Aún no hay respuestas registradas, por eso las preferencias correspondientes quedan por definir. Esta carpeta está conectada al repositorio GitHub `renezander030/capcut-cli`.

## Alcance

Este documento describe el plan. No genera guiones, no instala programas y no implementa las ocho etapas.

