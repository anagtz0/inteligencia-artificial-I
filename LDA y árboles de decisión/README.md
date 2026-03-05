##  LDA y árboles de decisión
En este proyecto se analizan los casos de sobrevivencia en el Titanic y variables que podrían haber contribuido a que salieran con vida, creando dos modelos; unos con LDA (least Discriminant Analysis) y árboles de decisión. 
La base de datos original se encuentra en Kaggle, llamada [Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)
La base de datos utilizada para la creación de los modelos se descargaron de el reporte "[Solución de problemas y validación cruzada](https://github.com/anagtz0/inteligencia-artificial-I/tree/main/Regresi%C3%B3n%20log%C3%ADstica%20y%20validaci%C3%B3n%20cruzada)". Las cuatro bases de datos usadas corresponden a los valores de `X_train_scaled`, `X_test_scaled`, `y_train` y `t_test`, debido a que estas variables ya pasaron por el proceso de limpieza de datos y corrección de problemas. Los archivos para `y` contienen la variable `Survived`, donde 1 es "sí sobrevivió" y 0 es "no sobrevivió".

Los archivos de `X`contienen lo siguente:
Pclass: Tipo de clase dentro del barco. 1 = primera clase, 2 = segunda clase, 3 = tercera clase. Sin embargo, fue estandarizada, usando media 0 y desviación estándar 1.
Sex_male: Sexo del pasajero. 1 = Male y 0 = Female.
Edad: Valor numérico con la edad del pasajero. Variable estandarizada.
SibSp: Número de hermanos o parejas del pasajero a bordo. Variable estandarizada
Parch: Número de padres o hijos del pasajero a bordo.Variable estandarizada.
Fare: Tarifa pagada por el pasajero. Variable estandarizada.
Cabin: Número de cabina. También se excluirá del modelo.
Embarked_Q: Puerto de embarcación. 1 = Queensland.
Embarked_S: 1 = Southampton.

Este proyecto incluye los siguientes documentos:
- [Reporte en formato ipynb](./A2.2%20623201.ipynb)
- [Reporte en formato html](./A2.2%20623201.html)
- [y_train](./y_train.csv)
- [y test](./y_test.csv)
- [X_train_scaled](./X_train_scaled.csv)
- [X_test_scaled](./X_test_scaled.csv)

