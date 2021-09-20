# Context-Aware Recommender Systems

En este *paper* se presenta el uso del contexto como atributo para hacer una recomendación. Se comienza ejemplificando situaciones cotidianas en que el contexto nos ha ayudado a tomar decisiones y luego se define el concepto "contexto" tanto en términos generales como para áreas vinculadas con sistemas de recomendación, las cuales van agregando ciertos elementos propios a su definición. Debido a estas múltiples definiciones, se han establecido dos clasificaciones para el contexto: (1) un set de atributos observables y (2) no observable, siendo la primera categoría la utilizada principalmente en el estudio. También se habla de cómo el contexto es modelado para utilizarse en sistemas recomendadores, cómo se obtiene (explícitamente, implícitamente y por inferencia) y se detallan tres paradigmas de la incorporación del contexto en los modelos de recomendación, tanto de manera individual como en forma combinada.


Una de las cosas que me parecieron más interesantes fue que, en modelos estudiados anteriormente hablamos sobre la manera de obtener *feedback* y diferenciamos entre *feedback* explícito e implícito, y cuando nos referimos a éste último hacemos énfasis en el comportamiento del usuario según películas que ha visto o productos que ha comprado, pero no se había mencionado en ninguna ocasión que las preferencias del usuario podrían estar relacionadas con su contexto. Es más, en *feedback* implícito se tiene el objetivo de construir un perfil de usuario, pero solo a partir de *items* con los que ha interactuado. Por lo cual, incluir el contexto, es una herramienta útil para enriquecer este perfil y acotar la lista de elementos a recomendar. Me parece intrigante que en el caso de la obtención del contexto, se mencione la Inferencia como una tercera forma de obtener información sobre éste, pero que en el caso de la obtención de *feedback* no hayamos leído literatura donde se mencione, la obtención de *feedback* por inferencia con herramientas de minería de datos.

Otra cosa muy interesante es el Paradigma de *Contextual Post-Filtering*, ya que en éste se hace una recomendación inicialmente sin utilizar el contexto en la data y luego los *items* recomendados son refinados con el uso del contexto. Este proceso llama mi atención porque permite la aplicación de los contenidos que hemos abordado en el curso en forma cronológica, es decir, una vez que hemos visto varios algoritmos, nos encontramos en una etapa en que podemos refinar nuestros resultados con el uso de herramientas nuevas, como lo es el uso de información acerca del contexto.

Finalmente, hay que mencionar que en el texto se rescata que el mejor paradigma de incorporación del contexto en sistemas recomendadores, va a depender del caso de uso y que aún queda mucho por estudiar en cuanto a cómo desarrollar un sistema con un alto desempeño en este ámbito. Además, haber distinguido la obtención de  contexto en forma implícita de la obtención por inferencia, entrega un valor adicional y una mayor consideración en incorporar herramientas de minería de datos en nuestro futuro proyecto.









