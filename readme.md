# PROYECTO LAURA ROMERO JIMENEZ

### Criterios de evaluacion: Aquellas que presentan un asterisco se consideran esenciales

- Análisis Exploratorio de los datos.*
- Gestión de nulos. *
- Visualización de datos con matplotlib y seaborn.*
- Estadística descriptiva e inferencial.
- A/B testing


##  Dinámica del Ejercicio

El ejercicio tiene datos de una empresa en relacion a la informacion relevante de sus clientes (***Customer Loyalty History***) y la informacion de la reserva de vuelos de los mismos (***Customer Flight Activity***)

El ejercicio se dividia en 3 fases y estas a la vez en subfases.

### **FASE 1** Exploracion y limpieza

- Fase 1.1: 

        - Exploracion Datos: En esta fase hay que explorar los dos dataframes, para detectar valores nulos, filas duplicadas, columnas irrelevantes, incongruencias en el tipo de datos, o detectar qué correcciones tipográficas se pueden hacer.

        - Se han unido los dos dataframe en este caso unando un merge de tipo inner. 


    
- Fase 1.2: 

        - Limpieza de Datos: En el ejercicio se ha hecho eliminacion de una columna, eliminacion de duplicados, imputacion de nulos, así como modificación de tipos de datos y los dataframes con los datos limpios se han guardado en archivos de tipo csv para poder trabajar con ellos en las fases posteriores. 


### **FASE 2** Visualización

En la fase 2 se han hecho varios diagramas para la visualizacion de datos, que han permitido responder de manera sencilla a unas preguntas que se nos planteaban, sobre distribución de datos entre grupos, o relación entre entre dos variables (ejemplo distancia y puntos acumulados por el cliente). 
Para la resolución del ejercicio se han hecho barplots, pieplots y scatterplot. 

### **FASE 3**

- Fase 3.1: Preparacion de los datos: Para lo cual se han preparado 5 dataframes con la informacion de vuelos reservados por cada grupo. 

- Fase 3.2: Estadística descriptiva: Para cada grupo se hace un estudio descriptivo que incluye media, mediana y desviación típica. 

- Fase 3.3: Estadistica inferencial: Se compara la reserva de vuelos entre grupo test y grupo control según el nivel educativo de los clientes. Para ello se comienza con test de normalidad, a continuación test homogeneidad de varianzas, y, por último, se utiliza el test MannWhitney que evalua la homogeneidad de las medianas entre grupos. 



## RETOS Y CONCLUSIONES:

A la hora de realizar el ejercicio, los mayores retos han sido preparar los datos para poder realizar la estadística inferencial, así como elegir cual era el diagrama de elección para poder mejorar la visualización de datos. 