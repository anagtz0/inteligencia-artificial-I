##  Regresión logística y validación cruzada
En este proyecto se analizan los casos de sobrevivencia en el Titanic y variables que podrían haber contribuido a que salieran con vida, utilizando regresión logística y validación cruzada.
La base de datos original se encuentra en Kaggle, llamada [Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)
La base de datos contiene las siguientes columnas:

* PassengerId: Número del 1 al 891 con el número de identificación del pasajero. Esta variable, no será considerada para este proyecto, debido a que no aporta información que pueda predecir la supervivencia de un pasajero y su relación con su estatus económico.
* Survived: Esta columna indica si sobrevivió el pasajero o no. 1 = No, 1 = Sí.
* Pclass: Tipo de clase dentro del barco. 1 = primera clase, 2 = segunda clase, 3 = tercera clase.
* Name: Nombre del pasajero. Esta variable tampoco será integrada al modelo por las mismas razones.
* Sex: Sexo del pasajero. 'male' o 'female'.
* Edad: Valor numérico con la edad del pasajero.
* SibSp: Número de hermanos o parejas del pasajero a bordo.
* Parch: Número de padres o hijos del pasajero a bordo.
* Ticket: Número de ticket. Esta variable tampoco se utilizará para el modelo.
* Fare: Tarifa pagada por el pasajero.
* Cabin: Número de cabina. También se excluirá del modelo.
* Embarked: Puerto de embarcación. C = Cherbourg, Q = Queenstown o S = Southampton.

Este proyecto incluye los siguientes documentos:
- [Reporte en formato ipynb](./A2.1%20623201.ipynb)
- [Reporte en formato html](./A2.1%20623201.html)
- [Base de datos](https://www.kaggle.com/datasets/yasserh/titanic-dataset)
