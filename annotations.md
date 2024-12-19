# Annotations
1. What if the disease is only visible in the bottom part of the leaves? It won't be visible by satellites.
2. How long will be the validity of the algorithm? as climate change affects the way climate change develop.
3. Podemos asumir que parte del train set es para para testear.

# Questions
1. En un primer approach, ¿Cuál es la mejor manera de evaluar la independencia lineal de los puntos de un dataset? asumir

2. ¿Qué hacer si estoy seguro de que no hay una relación física con el fenómeno pero mis datos me muestran cierta relación? Mejorar los datos.

3. ¿Cómo evaluar la necesidad de balancear las clases? A ojo. Para la profe sin duda hay necesidad de balancear. Se podría cambiar el problema a Healthty and Unhealthty. Luego entrenar un modelo que trabaje unicámente clasificando las clases Unhealthty.  

4. Cómo cambia todo cuando me encuentro con una variable que no sigue una distribución normal? (CropCoveredArea) No pasa nada, lo que dijimos que debe ser normal es la distribución del ruido.

5. Revisar el análisis bivariado Category vs Crop Type. ¿Qué se puede concluir? En general cómo concluir a partir de estos análisis? Experiencia. No se necesita que una variable se comporte de manera muy distinta por cada una de las clases para que tenga una ingerencia en la decisión. La computadora es la que va a ir al detalle así que dejar que ella haga ese trabajo.

8. Tengo muchas variables categoricas que no son ordinales pero tienen una alta cardinalidad ¿Si quisiera hacer one-hot encoding terminaría con muchas columnas? Probar, probar, probar. Pasarlas a one-hot encoding y remover variables de poca importancia.

Todo se trata de probar. Pocas reglas están escritas.

#Models to test:
KNeighbors (Discarded because of high dimensionality)
Hyperplane-Perceptron
LDA
Logistic Regression
SVM