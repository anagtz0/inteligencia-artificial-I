P1.2 Clasificación
Análisis de Factores Asociados a la Infertilidad Masculina

Este análisis se plantea hacer con 5 diferentes modelos:
- Regresión Logística
- Linear Discriminant Analysis (LDA)
- Random Forest
- Support Vector Machines
- Redes neuronales

Posteriormente, a través de la evaluación de métricas como exactitud, precisión, sensibilidad, f1-score y la matriz de confusión en los datos de prueba se elegirá el mejor modelo para este fenómeno. 

Para esto, se usará la base de datos obtenida de [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/244/fertility). Estos datos fueron obtenidos de 100 voluntarios sanos estudiantes de la Universidad de Alicante de edades de entre 18 y 36 años. Se les pidió una muestra de semen posterior a 3 a 6 días de abstinencia, para después analizar la muestra de acuerdo a la guía de la Organización Mundial de la Salud. Además, se les pidió responder un cuestionario sobre su estilo de vida, hábitos y estado de salud.

La base de datos tiene las siguientes variables y cómo fueron previamente normalizadas por las personas que crearon la base de datos:

| Descripción variable | Valores (min. y max.) | Normalizada |
|-----------|-----------|-----------|
| Estación en la que el análisis fue realizado    | (1) invierno, (2) primavera, (3) verano, (4) otoño    | (-1, -0.33, 0.33, 1)    |
| Edad  | 18-36    | Valores entre 0 y 1    |
| Enfermedades en la infancia (i. e. sarampión, paperas, varicela, polio) | (1) Sí, (2) No | (0, 1) |
| Accidentes o traumas serios | (1) Sí, (2) No | (0, 1) |
| Intervenciones quirurgicas | (1) Sí, (2) No | (0, 1) |
| Fiebres altas en los últimos años | (1) hace menos de 3 meses, (2) hace más de 3 meses, (3) no | (-1, 0, 1)|
| Frecuencia de consumo de alcohol | (1) varias veces al día, (2) todos los días, (3) varias veces a la semana, (4) una vez a la semana, (5) casi nunca o nunca | Valores entre 0 y 1|
| Hábito de fumar | (1) nunca, (2) ocasionalmente, (3) diario | (-1, 0, 1)|
| Número de horas que pasan sentados por día | 1-16 | Valores entre 0 y 1|
| Diagnóstico | (1) Normal, (2) Alterado | (N, O) |

Este proyecto incluye los siguientes documentos:
- [Reporte en formato ipynb](./P%20P2.%20623201.ipynb)
- [Reporte en formato html](./P%20P2.%20623201.html)
- [Base de datos](https://archive.ics.uci.edu/dataset/244/fertility)
