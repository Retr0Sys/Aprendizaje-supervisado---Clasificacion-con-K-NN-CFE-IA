# Aprendizaje-supervisado---Clasificacion-con-K-NN
Modelo sencillo de clasificación de IA por vecinos, creado en Python.

Utilizamos un modelo de clasificación simple para predecir si un tumor es maligno o benigno utilizando el algoritmo de k-vecinos más cercanos (k-NN). El modelo se entrenó con un conjunto de datos que incluye mediciones de tumores mamarios, lo que permite realizar predicciones basadas en la similitud con casos previamente clasificados.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

![ia](https://github.com/user-attachments/assets/9f11b96d-53c6-4bf8-9801-eba50dfe0269)


-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Variables seleccionadas
  radius_mean: promedio del radio de las células.
  texture_mean: promedio de la textura de la imagen.
  perimeter_mean: promedio del perímetro de las células.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Minimos y máximos de las variables

Las variables utilizadas en el modelo se encuentran dentro de los siguientes rangos de valores, lo que es crucial para la normalización y el análisis de los datos:

Radio: de 6.98 a 28.1

Textura: de 9.71 a 39.3

Perímetro: de 43.8 a 189

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Ejemplos de predicción

  <img width="1290" height="185" alt="Captura de pantalla 2025-09-02 211642" src="https://github.com/user-attachments/assets/fd5f1166-7cb2-4ed5-abe9-082223ee6e10" />

  <img width="1289" height="181" alt="Captura de pantalla 2025-09-02 211707" src="https://github.com/user-attachments/assets/9827c202-68ee-4b6d-85fa-507d8dd8f5ec" />

  <img width="1285" height="147" alt="image" src="https://github.com/user-attachments/assets/793e927f-22c3-43f0-83cb-fe6f8374de30" />


-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Análisis de datos 
  El análisis de las predicciones del modelo sugiere una correlación entre los rangos de las variables y la probabilidad aproximada de que un tumor sea clasificado como maligno.       Específicamente, se   observan las siguientes tendencias:

Radio: Existe una mayor probabilidad de clasificación maligna para valores de radio entre 11 y 22.

Textura: Los tumores con una textura entre 14 y 27 presentan más posibilidades de ser malignos.

Perímetro: Se ha encontrado una mayor incidencia de tumores malignos con perímetros entre 85 y 140.
