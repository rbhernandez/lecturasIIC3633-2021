# Matrix Factorization Techniques for Recommender Systems

En el artículo *Matrix Factorization Techniques for Recommender Systems*, se describe un sistema recomendador que forma parte de una de las principales áreas del *collaborative filtering (CF),* denominada *latent factor models*, pero basada *matrix factorization*, argumentando que ésta técnica ha estado presente en las realizaciones más exitosas del área mencionada. La inclusión de *matrix factorization* permite una mayor flexibilidad para modelar una gran variedad de situaciones de la vida real y es conocida por combinar una buena **escalabilidad** con una **predicción precisa**. De esta forma, se hace énfasis en el uso de *Matrix factorization models*, describiendo sus principales desafíos, cualidades por las que deberían ser utilizados y una definición matemática de su funcionamiento.

Una de las cosas que más me gustó fue la incorporación del sesgo en la ecuación  que calcula el *rating* que un usuario otorgará a un ítem. 

![](https://i.imgur.com/CGOV8rw.png)

Esto porque permite una predicción más precisa al considerar comportamientos que suele tener el usuario en una plataforma. A pesar de que el texto recomienda buscar modelos que incluyen el sesgo en otros trabajos, a mí parecer, la explicación es muy clara y suficiente, por lo que no hace falta mostrar un modelo más complejo. Además, se toma en consideración que los sesgos para ítems y para usuarios puedan ser dinámicos, lo que demuestra mayor precisión pues refleja la naturaleza de las situaciones de la vida real como la variación en la popularidad de un ítem entre un período y otro, o el cambio en el gusto o valoración promedio de los usuarios.

Otro aspecto que me gustó del artículo fue el recurso utilizado al final de contar acerca del *Netflix Prize*, ya que una vez que se explicaron los contenidos de *Matrix Factorization*, se cuenta una historia real en la que se utilizó esta técnica, logrando que como lectores quedemos más motivados con el tema y nos interesemos en aprender más. Además, nos demuestra que los algoritmos no quedan sólo en la teoría y el papel, sino que son aplicados incluso en plataformas que usamos a diario.

Finalmente, dado que la última lectura fue acerca de *collaborative filtering (CF)* para sistemas recomendadores, es interesante ver cómo en este artículo se muestra una mejora a un área de *CF*, puesto que después de leer sobre una nueva técnica, nace la motivación por mejorar el rendimiento actual de los algoritmos para hacer recomendaciones mediante modificaciones en diversos parámetros o procedimientos, tal como ocurre en el caso de *Matrix Factorization*. Fomentando así la curiosidad por investigar sobre nuevas mejoras.




