# Tesis Ingenieria Mecatronica
## Exploración del uso de técnicas de machine learning para obtener proyecciones  del comportamiento de la pandemia COVID 19 en Colombia.

Para la realizacion de esta tesis en primer lugar se tuvo que realizar un preprocesamiento a los datos del Instituto Nacional de Salud (INS), con el fin pasar a tener como llave primaria el ID de casos a tener la fecha diaria y en como valores la cantidad de casos diarios, esto se realiza con el archivo pre_procesamiento.ipynb.

Para poder implementar modelos epidemiologicos es necesario hayar sus parametros los cuales varian constantemente, estos se hayan directamente del comportamiento de la variable a predecir, para esto se utiliza el archivo Hallando_Beta.ipynb.

Por ultimo se realiza la implementacion de todos los modelos para las predicciones en 5, 10 y 20 dias, esto se hace con el progrmana Implementacion_tecnicas.ipynb. Debido a que la red neuronal LSTM al momento de su entrenamiento tiene un tiempo considerablemente largo, esta se realiza en un programa por separado llamado lstm_5_dias.ipynb 
(para predecir 10 y 20 dias se debe cambiar la variable test_data)

En el documento Informe.pdf se presenta el informe final detallando como se realizó el trabajo exploratorio.




