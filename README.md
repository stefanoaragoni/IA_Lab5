> Comparación de Resultados 1.1 - KNN

Al comparar los datos del modelo KNN creado con la librería y los datos del modelo creado sin la librería, se puede observar que el modelo que utilizó una libreria es un poco más exacto. Esto se hace evidente al comparar las calificaciones de exactitud, que son de 0.93 y 0.91 para el modelo que utiliza y no utiliza una librería respectivamente. 

Adicionalmente, al comparar las matrices de confusión, se puede observar que el modelo que utiliza una librería presenta menos falsos negativos al igual que menos falsos positivos. Estas dos métricas de desempeño permiten afirmar que el modelo creado con una librería fue una mejor implementación. 

Cabe destacar que estas dos métricas son válidas ya que los datos se encontraban balanceados.

Por otro lado, es importante mencionar que el modelo creado con la librería es capaz de hacer el respectivo modelo de manera más rápida. Esto siendo importante en casos cuando se está manejando grandes cantidades de información y se requiere de un algoritmo optimizado.


> Comparación de Resultados 1.2 - SVM

Al comparar los datos del modelo SVM creado con la librería y los datos del modelo creado sin la librería, se puede observar que el modelo que utilizó una libreria es un poco más exacto. Esto se hace evidente al comparar las calificaciones de exactitud, que son de 0.88 y 0.89 para el modelo que utiliza y no utiliza una librería respectivamente. 

Adicionalmente, al comparar las matrices de confusión, se puede ver tanto el modelo que utiliza librerías como el que no, tienen casi la misma cantidad de falsos positivos y falsos negativos, lo que demuestra la validez y presición del modelo creado. 

Por otro lado, es importante mencionar que el modelo creado con la librería es capaz de hacer el respectivo modelo de manera más rápida. Esto siendo importante en casos cuando se está manejando grandes cantidades de información y se requiere de un algoritmo optimizado.

> ¿Cómo difirieron los grupos creados por ambos modelos?
Para el modelo KNN, los grupos creados por el algoritmo que utiliza librerias y el algoritmo que no utiliza librerias conincidieron en su gran mayoría. El 93% de las predicciones realizadas por estos modelos conincidieron entre si. 

Para el modelo SVM, los grupos creados por los dos algoritmos coincidieron en su totalidad. Esto significa que ambos modelos deberían realizar las mismas predicciones al proporsionarles la misma información de entrada.


>  ¿Cuál de los modelos fue más rápido?

El modelo de KNN puede fue más rápido en la fase de entrenamiento ya que simplemente almacena el conjunto de datos de entrenamiento en la memoria. Por otro lado, SVM es más rápido en la fase de predicción, ya que utiliza el hiperplano para hacer predicciones. 

En conclusión el KNN fue más rápido para analizar los datos. 

> ¿Qué modelo usarían?

Se utilizaria el KNN pues fue más rapido y presento mayor exactitud. Esto es relevantes pues para Datasets más grandes se busca un modelo rápido y exacto que cumpla con las expectativas del analizador. 

