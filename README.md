# Laboratorio 2: 
# Maria Jose Rodriguez, Karen Tatiana Olarte, Maria Jose Bedoya.

# Análisis estadístico y exploración gráfica de la base de datos de Pokémon.
A continación se presentaran las respuestas interpretativas a las preguntas formuladas en este laboratorio.
# 1.	¿Cuál es el promedio, mínimo y máximo de los atributos base (HP, Ataque, Defensa, Velocidad) de todos los Pokémon?
En los resultados se puede ver como en HP(puntos de vida) se tiene un mínimo de 1 y un máximo de 223 mientras que el promedio es de 73.3 lo que significa que existen Pokémon muy débiles en comparación con Pokémon con una capacidad elevada de resistencia, así mismo se puede evidenciar como el promedio de los Pokémon se inclina hacia la parte baja, dejando ver que en promedio un Pokémon normal soportaría unos cuantos ataques, sin embargo el HP puede ser una debilidad o fortaleza importante en una pelea debido a su gran diferencia entre el mínimo y máximo. por otro lado, el promedio de ataque (attrack) de 85.68 con un rango de 10-190 es el promedio más alto de los atributos, demostrando así que los Pokémon están diseñados para enfocarse en el ataque en un combate. la diferencia entre su rango nos deja ver como varían sus estilos en un enfrentamiento. Defense cuenta con un promedio de 79.92 en un rango de 15-230, de aquí podemos resaltar que este el valor máximo es el más alto de los cuatro atributos, no obstante, su promedio se puede considerar bajo, por lo que demuestra que hay una gran desigualdad en este atributo. Además, la velocidad muestra un promedio bajo, lo que indica que en general el Pokémon no se caracteriza por su velocidad, sin embargo, se presenta de nuevo la brecha o diferencia entre los Pokémon. En términos generales se puede observar cómo hay una relación entre ataque y defensa con una inclinación al attrack, lo que indica que los Pokémon se enfocan o especializan con el objetivo de ataque, también se puede evidenciar como la variedad en los atributos de los Pokémon permiten crear una estrategia que se adapta a diferentes escenarios que requieren de enfoques y estrategias especializadas y estudiadas.

# 2. Con base al histograma de la distribución de los valores de Base Exp interpretar si la distribución es simétrica o sesgada.

<img width="706" height="565" alt="image" src="https://github.com/user-attachments/assets/4eb308e4-b4a5-4caa-8684-bab2277d7487" />


 La distribución de los valores de Base Exp (Base Experience) en el histograma muestra como la mayoría de los valores varian entre aproximadamente 50 y 200, ubicados a la izquierda, mientras que solo unos pocos alcanzan valores mayores a 300, ubicado a la derecha, por lo que se puede ver como la distribución se extiende en esta dirección, lo que nos da como resultado una distribución sesgada positiva.
Esto nos indica que la mayoría de Pokémon tienen una Base Exp baja o mediana y tan solo unos pocos osciolan en valores superiores, generalmente Pokemon raros o legendarios. 

# 3. Con base a la gráfica identifique qué tipo Pokémon tiene el ataque más alto en promedio.


<img width="1253" height="731" alt="image" src="https://github.com/user-attachments/assets/5f63df6a-4b02-47e4-9426-cdb110f478bf" />

En la grafica se puede observar la distribución de los valores de  ataque de base (Attrack Base) según el tipo de Pokémon, en este caso Type1. 
Al observar la grafica se puede observar como los Pokémon Dragon, Fighting y Ground presentan las medianas (raya de color negro) más altas de ataque, por lo que este tipo de Pokémon poseen el ataque más alto en promedio, por lo que serían los Pokémon más ofensivos en combate; a diferencia de  Fairy y bug quienes cuentan con un promedio de ataque bajo. 

# 4. ¿Cuál es el top 5 de especies (species) más frecuentes en el dataset?

En este top 5 en primer lugar tenemos a Paradox Pokémon con 22 registros, seguido de Mouse Pokémon con 14 registros, en tercer y cuarto lugar se encuentran los Fox y Dragon Pokémon con 9 registros cada uno, por ultimo en quinto lugar esta pumpkin Pokémon con 8 registros.
como se puede apreciar Paradox Pokémon cuenta con una alta frecuenciaen el dataset en comparación con el resto de especies del top 5, las cuáles estan en promedio entre 9 y 14, lo que podría indicar una gran variedad en las formas y/o variantes de esta especie.

# 5. Según el siguiente gráfico de barras, ¿Qué tipo es más comun?
<img width="1048" height="728" alt="image" src="https://github.com/user-attachments/assets/a73f3898-bcbd-4d9a-91a3-b1ca8b511ce6" />

El gráfico representa la distribución de Pokémon según su tipo (type1),aquí se observa que el tipo más común o abundante es watercomunes ,seguido muy de cerca por Bug, mientras que los tipos como Flying, Fairy yFihting lo que sugiere especies menos comunes como los Pokémon legendarios.

# 6. Con base a la correlación entre HP, Attrack Base, Defense base y Speed Base ¿Qé atributos estan más relacionados entre si?

En la correlación de los atributos se pudo evidenciar que: HP Base – Attack Base con 0.504 y Attack Base – Defense Base con 0.427 tienen una relación Moderada y positiva, HP Base – Defense Base con 0.292, Attack Base – Speed Base con 0.369 y HP Base – Speed Base con 0.199 tienen una relación débil y positiva, mientras que Defense Base – Speed Base con -0.062 tiene una relación débil y negativa.
Demostrando así que los atributos mas correlacionados son HP Y Attrack, por lo que los Pokémon que tienen un HP alto tienden a tener un ataque más ofensivo, a pesar de esto su correlación sigue siendo moderada por lo que no se puede considerar una relación directa, por otro lado tenemos las relaciones débiles pero positivas quienes nos indican que estos atributos estan reativamente equilibradas y por ultimo tenemos la relación débil y negativa que nos indica que la  relación entre la defensa y la velocidad es casi nula. Por lo que en general se podría decir que los atributos de los Pokémon varian y son independientes.

# 7. Teniendo en cuenta el unto anterior y el mapa de calor interprete los resultados.

<img width="775" height="663" alt="image" src="https://github.com/user-attachments/assets/cb5507c1-8e1e-48b4-ab20-6061e7d1fcf1" />

En este mapa de calor se puede ver de forma grafica lo que se menciono anteriormente; muestra como la relación más fuerte entre los atributos es HP Base y Attrack Base (o.50) segudo de Attrack Base y Defense Base (0.40) mientras que las otras relaciones son débiles pero positivas y que la relación estre Defense Base y Speed Base es débil y negativa, teniendo en cuenta que un coeficiente de correlación de 1 o cercano a 1 indica una correlación positiva fuerte, se puede decir que cada atributo contribuye de forma independiente al desempeño general del Pokémon.

# 8. ¿Existe relación entre el peso de un Pokémon y su capacidad de ataque? 

<img width="1062" height="694" alt="image" src="https://github.com/user-attachments/assets/291069a6-0197-4a40-9f1e-f3bd10034c30" />

Teniendo en cuenta el diagrama de disperción se puede decir que no existe una relación directa entre el peso de un Pokémon y su capaccidad de ataque, puesto que los puntos se encuentran muy dispersos, en especifico en Pokémon de bajo peso(200kg) con una amplia variabilidad en el Attrack, lo que indica que un mayor peso no garantiza una mayor o menor capacidad ofensiva.

# 9. Dtermine el promedio de altura y peso por tipo principal (Type1) e interprete que tipo  el tiende a tener Pokémon más grandes

El promedio de altura y peso por tipo principal Type1 muestra que los Pokémon del tipo Steel (acero) son, en general, los más grandes y pesados del conjunto de datos, con una altura promedio de 2.33 metros y un peso promedio de 239.07 kg. Le siguen los de tipo Dragon, que también presentan dimensiones notoriamente altas (2.26 m en promedio) y un peso considerable (140.67 kg).
Por lo que se puede observar que los Pokémon tipo Steel tienden a poseer una estructura física de gran tamaño, probablemente debido a su composición metálica lo que los hace más pesados y altos en comparación con otros tipos. por otro lado, los Pokémon de tipo Normal y Electric se ubican entre los más pequeños y ligeros.

# 10. ¿Qué tipo de Pokémon tiende a ser más rapido? 
<img width="874" height="688" alt="image" src="https://github.com/user-attachments/assets/db3ed724-9c74-4950-86eb-d6b8cd5b1209" />

De acuerdo con el gráfico, el Pokémon que tiende a ser másrapido son los Pokémon tipo electrick, ya que en comparación con los tipos Ground y Flying. Esto se evidencia porque su distribución de velocidad base se concentra en valores más altos, con una mediana alrededor de los 90-100 puntos y varios casos que superan los 150 puntos de velocidad.

# Factores influyentes en las estadisticas Base de Pokémon.
Con base a lo anteriormente mencionado en este trabajo se puede decir que, el análisis general del conjunto de datos de Pokémon revela que las estadísticas base están influenciadas por una combinación de factores físicos (como el peso y la altura), el tipo elemental y las características de especie, sin embargo no existe una correlación fuerte entre todas las variables, pero sí se identifican tendencias claras que diferencian los grupos de Pokémon, como lo pudimos ver en algunos de los gráficos pasados. 
En conclusión, el análisis de datos Pokémon muestra que las características físicas influyen parcialmente, pero son el tipo elemental y el rol estratégico los factores que más determinan las estadísticas base, reflejando una estructura equilibrada y diversa en el diseño de cada especie.
