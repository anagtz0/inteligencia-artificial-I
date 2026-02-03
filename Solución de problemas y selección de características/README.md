## A1.3 Solución de problemas y selección de características

Este proyecto analiza el rendimiento académico de estudiantes mediante un modelo de regresión lineal múltiple. El flujo de trabajo incluye la exploración y preparación de los datos, la transformación de variables categóricas en variables dummy y la selección de características a partir de análisis de correlación y significancia estadística. Con las variables seleccionadas se entrena un modelo de regresión lineal, evaluando su desempeño en conjuntos de entrenamiento y prueba mediante métricas como R² y el error cuadrático medio (MSE), evitando la fuga de datos.

La base de datos original se puede encontrar [aquí](https://archive.ics.uci.edu/dataset/320/student+performance)

La base de datos contiene la siguiente información:

* Escuela (objeto): Nombre de la escuela; 'GP' o 'MS'
* Sexo (objeto): Femenino o Masculino; 'M' o 'F'
* Edad (entero): Edad del estudiante; de 15 a 22
* HorasDeEstudio (entero): Horas de estudio por semana; 1 - <2hrs = 1, 2 - 5hrs = 1, 5 - 10hrs = 3, >10hrs = 4.
* Reprobadas (entero): Número de materias reprobadas; 1-2 materias = n, >3 = 4
* Internet (objeto): Acceso a internet; 'yes' o 'no'
* Faltas (entero): Número de faltas a clases; de 0 a 93
* G1 (entero): Calificación de primer periodo; de 0 a 20
* G2 (entero): Calificación de segundo periodo; de 0 a 20
* G3 (entero): Calificación final; de 0 a 20.

  Este proyecto incluye los siguientes documentos:
- [Reporte en formato ipynb](./A1.3%20623201.ipynb)
- [Reporte en formato html](./A1.3%20623201.html)
- [Base de datos](./A1.3%20Calificaciones.csv) 
