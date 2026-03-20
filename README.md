# 📘 TP N°1 - Visión por computadora I - CEIA 

## Integrantes 
- Mariel Gaitan
- Gaspar Rivollier

## Objetivo

Aplicar técnicas de análisis y corrección de imágenes:

- Histogramas en escala de grises
- Corrección de color (White Patch)

## Consignas: 

▪ Parte 1 (imágenes en /white_patch):
1. Implementar el algoritmo White Patch para librarnos de las diferencias de color de iluminación.
2. Mostrar los resultados obtenidos y analizar las posibles fallas (si es que las hay) en el caso de
White patch.

▪ Parte 2:
1. Para las imágenes img1_tp.png y img2_tp.png leerlas con OpenCV en escala de grisas y
visualizarlas.
2. Elija el numero de bins que crea conveniente y grafique su histograma, compare los histogramas
entre si. Explicar lo que se observa, si tuviera que entrenar un modelo de clasificación/detección
de imágenes, considera que puede ser de utilidad tomar como ‘features’ a los histogramas?

## Estructura del repositorio:

- assets/
  - white_patch/
  - img1_tp.png
  - img2_tp.png
- notebooks/
  - white_patch_implementation.ipynb

## Desarrollo del TP 

Este trabajo está desarrollado en el notebook `white_patch_implementation.ipynb` y autodocumentado utilizando celdas de markdown. 

## Cómo ejecutar utilizando uv

1. Activar el entorno virtual:
   ```bash
   source .venv/bin/activate.ps1
   ```
2. Instalar dependencias (si no están instaladas):
   ```bash
   uv sync
   ```
3. Correr el notebook con Jupyter:
   ```bash
   jupyter notebook notebooks/white_patch_implementation.ipynb

Se puede ejecutar sin necesidad de uv si se tienen instaladas las librerías mencionadas en `pyproject.toml`.
