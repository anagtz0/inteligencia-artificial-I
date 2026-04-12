Este es un tutorial donde se habla de PCA y Sistemas de recomendaciones (usos y cómo funcionan). También se adjunta un archivo html donde el usuario califica 15 películas y al final se arrojan 10 recomendaciones en base a eso. 


Para la parte de PCA se utiliza la base de datos `breast_cancer` de la librería Scikit-learn. Esta base de datos tiene 2 clases de la variable objetivo, tiene 30 variables y 569 observaciones. Para más información puede acceder a este link: https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic




Por el contrario, para la parte de Sistemas de recomendaciones primero se utiliza la base de datos `wine` también de esta librería. Esta base de datos tiene 3 clases de la variable objetivo. Tiene una cantidad de 178 observaciones y 13 variables. PAra más información de esta base de datos puedes acceder a este link: https://archive.ics.uci.edu/ml/machine-learning-databases/wine/wine.data


Para la segunda parte de sistemas de recomendación, también se utilizan los archivos `u.item` y `u.data` para la recomendación de películas. Ambos archivos están incluidos en esta carpeta. El archivo `u.data` tiene 4 columnas: `user_id`, `movie_id`, `rating` y `timestamp`. Tiene 100000 observaciones. El archivo `u.item` se usa para asociar el id de una película con la información de esa película, para mejor interpretabilidad del usuario.


En este proyecto se incluyen los siguientes documentos:
- [Reporte en formato ipynb](./A3.1%20623201.ipynb)
- [Reporte en formato html](./A3.1%20623201.html)
- [Base de datos breast cancer](https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic)
- [Base de datos wine](https://archive.ics.uci.edu/ml/machine-learning-databases/wine/wine.data)
- [Base de datos películas](./u.data)
- [Base de datos items películas](./u.item)
- [Aplicación recomendación de películas](./index.html)





