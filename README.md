# Sistema de Votación por Tramos para Eurovisión 2025

Este repositorio contiene un sistema alternativo de votación para Eurovisión 2025, basado en la asignación de puntos por tramos de posiciones. El objetivo es valorar de forma más amplia la posición obtenida por cada país, otorgando puntos a más participantes y diferenciando mejor los resultados intermedios.

## Descripción del sistema

En lugar de asignar puntos únicamente a los 10 primeros puestos, se otorgan puntos a los países según el bloque de posiciones en el que hayan quedado, siguiendo la siguiente escala:

- Puesto 1: **12 puntos**
- Puesto 2: **10 puntos**
- Puesto 3: **8 puntos**
- Puestos 4 y 5: **7 puntos**
- Puestos 6 y 7: **6 puntos**
- Puestos 8 y 9: **5 puntos**
- Puestos 10, 11 y 12: **4 puntos**
- Puestos 13, 14, 15 y 16: **3 puntos**
- Puestos 17, 18, 19 y 20: **2 puntos**
- Puestos 21, 22, 23 y 24: **1 punto**
- Puestos 25 y 26: **0 puntos**

## Archivos generados

- `tabla_jurado_tramos.xlsx`: Tabla de puntos asignados por el jurado a cada país.
- `tabla_publico_tramos.xlsx`: Tabla de puntos asignados por el televoto a cada país.
- `tabla_total_tramos.xlsx`: Tabla de puntos totales (jurado + televoto) por país.
- `data_cleaned.json`: Datos crudos utilizados para el análisis.

## Uso

1. Asegúrate de tener Python 3 y las librerías necesarias (`pandas`, etc.).
2. Ejecuta el cuaderno `test.ipynb` para reproducir el análisis y generar los archivos Excel.
3. Analiza los resultados en los archivos Excel generados.

## Créditos

Idea de Berme Rubio ([x.com/bermerubio](https://x.com/bermerubio))

---

Este proyecto no está afiliado a la UER ni a Eurovisión.