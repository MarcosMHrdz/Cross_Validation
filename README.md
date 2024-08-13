![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

#Laboratorio | Validación cruzada

En este laboratorio, crearemos un modelo sobre el problema de clasificación binaria de abandono de clientes. Utilizará el archivo `files_for_lab/Customer-Churn.csv`.



### Instrucciones

1. Aplicar SMOTE para sobremuestrear los datos

    - Utilice regresión logística para ajustar el modelo y calcular la precisión del modelo.
    - Utilice el clasificador de árbol de decisión para ajustar el modelo y calcular la precisión del modelo.
    - Comparar las precisiones de los dos modelos.


2. Aplicar TomekLinks para reducir la resolución

    - Es importante recordar que no hace iguales las dos clases sino que sólo quita los puntos de la clase mayoritaria que están cerca de otros puntos de la clase minoritaria.
    - Utilice regresión logística para ajustar el modelo y calcular la precisión del modelo.
    - Utilice el clasificador de árbol de decisión para ajustar el modelo y calcular la precisión del modelo.
    - Comparar las precisiones de los dos modelos.
    - También puedes aplicar este algoritmo una vez más y comprobar cómo ha cambiado el desequilibrio en las dos clases desde la última vez.