# Proyecto de Análisis de Datos de Competidoras de Esgrima (modalida florete femenino)

Este proyecto analiza datos de competidoras de esgrima, explorando la relación entre factores como la edad, la puntuación acumulada, el número de victorias y las "victorias inesperadas". Los resultados se presentan mediante diversos gráficos y estadísticas descriptivas.

---

## Contenido

### Archivos principales
- **`data/df_final.csv`**: Dataset principal con los datos utilizados en el análisis.
- **Scripts principales**:
  - `main.py`: Código para el análisis exploratorio y generación de gráficos.
  
---

## Hipótesis
-Estudio sobre la correlación positiva entre un mayor puntaje acumulado en competición y el número de victorias
-Estudio sobre la influencia de la edad en las victorias. Menores de 20 años y mayores de 40 tienden a ganar menos.

---

## Objetivos del Proyecto

1. Visualizar y analizar las relaciones entre las variables principales del dataset:
   - Edad de las competidoras.
   - Puntuación acumulada.
   - Número de victorias totales.
   - Victorias inesperadas ("upsets").
2. Identificar patrones relacionados con el desempeño de las competidoras según su edad y puntuación inicial.
3. Presentar los resultados mediante visualizaciones claras y comprensibles.

---

## Análisis Realizado

- **Correlaciones**: Se evaluaron las relaciones entre variables numéricas, como la edad, el número de victorias y la puntuación actual.
- **Gráficos generados**:
  - Mapas de calor para analizar las correlaciones entre variables.
  - Gráficos de caja (boxplots) para estudiar la distribución de puntos por edad y país.
  - Gráficos de barras para mostrar puntajes promedio por competencia.

---

## Resultados Destacados

1. Las competidoras en el rango de edad entre 30 y 40 años tienden a alcanzar los puntajes más altos.
2. Las victorias inesperadas se concentran principalmente en competidoras con puntuaciones iniciales bajas.
3. No se observaron puntuaciones altas ni victorias inesperadas para competidoras mayores de 40 años.

---

## Tecnologías Utilizadas

- **Python**:
  - Bibliotecas principales: `pandas`, `matplotlib`, `seaborn`, `numpy`.
- **Visualizaciones**: Creación de gráficos mediante `seaborn` y `matplotlib`.

---

## Archivos Grandes

Puedes descargar el archivo `df_final.csv` desde el siguiente enlace:
[Descargar df_final.csv]: https://drive.google.com/file/d/1J8D8CgOJGUZXRLuZ0-8j8uU4B3wA0NCs/view?usp=sharing