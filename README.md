# Practica_15Dic
Practicas de MLops

Práctica: Detección de Anomalías con Isolation Forest y One-Class SVM

Explica los resultados obtenidos además de los métodos para detectar #anomalías (debes explicarlo NO solo mencionarlo)

El método de Isolation Forest es un método de detección de anomalías basado en árboles de decisión.
El algoritmo funciona dividiendo el conjunto de datos en subconjuntos aleatorios y luego seleccionando aleatoriamente una característica y dividiendo los datos en función de un valor umbral óptimo. Este proceso se repite hasta que se detecta una anomalía o hasta que se alcanza un nivel de profundidad máximo. El algoritmo es eficiente y escalable, y funciona bien incluso en conjuntos de datos con muchas dimensiones. Sin embargo, el algoritmo no funciona bien en
conjuntos de datos con muchas anomalías, y no funciona bien en conjuntos de datos con muchas dimensiones. El algoritmo también funciona mejor cuando las anomalías son más pequeñas que las muestras normales.

Práctica: Diferenciación entre Data Drift y Concept Drift

¿Cómo cambia el rendimiento del modelo en situaciones de data drift y concept drift?
La precisión del modelo inicial es de 0.9. Cuando se hizo el ajuste en los datos (En la simulación del Data Drift), se cambió también la distribución de los mismos, la precisión del modelo disminuye a .89, por lo que sí impactó, no de manera tan considerable, pero sí se vio una ligera degradación en el performance del modelo.
La precisión del modelo cuando se hizo la simulación del concept drift subió a 0.97, por lo que se puede decir que mejoró

Practica: Creación de un dashboard para monitorear modelo de Datos

Práctica Monitoreo de Modelos.
Un ejemplo de la distancia de Jensen-Shannon es la distancia de Jensen-Shannon entre dos distribuciones de Bernoulli con parámetros p y q.
al ser la distancia 0.05, se puede decir que las distribuciones son similares
Y la Distancia de Wasserstein: 0.0 indica que las distribuciones son iguales

Practica: Evaluación del Modelo 

-Los resultados reflejan precisión y exactitud al 100%, no hay error, se pude considerar que presenta un overfitting
-De acuerdo a la matriz de confusion, observamos que no existen falsos positivos ni falsos negativos, el ajuste es perfecto. 




