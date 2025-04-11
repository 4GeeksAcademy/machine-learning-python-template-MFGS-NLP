📝 Instrucciones

Sistema de detección de enlaces spam

Queremos implementar un sistema que sea capaz de detectar automáticamente si una página web contiene spam o no basándonos en su URL.

Paso 1: Carga del conjunto de datos

El conjunto de datos se puede encontrar en esta carpeta de proyecto bajo el nombre url_spam.csv. Puedes cargarlo en el código directamente desde el siguiente enlace:

https://raw.githubusercontent.com/4GeeksAcademy/NLP-project-tutorial/main/url_spam.csv
O descargarlo y añadirlo a mano en tu repositorio.

Paso 2: Preprocesa los enlaces

Utiliza lo visto en este módulo para transformar los datos para compatibilizarlos con el modelo que queremos entrenar. Segmenta las URLs en partes según sus signos de puntuación, elimina las stopwords, lematiza, etcétera.

Asegúrate de dividir convenientemente el conjunto de datos en train y test como hemos visto en lecciones anteriores.

Paso 3: Construye un SVM

Comienza a resolver el problema implementando un SVM con los parámetros por defecto. Entrénalo y analiza sus resultados.

Paso 4: Optimiza el modelo anterior

Después de entrenar el SVM, optimiza sus hiperparámetros utilizando un grid search o un random search.

Paso 5: Guarda el modelo

Almacena el modelo en la carpeta correspondiente.