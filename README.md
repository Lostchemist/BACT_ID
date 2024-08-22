# README: Proyecto de Identificación Bacteriana

## Resumen

Este proyecto se centra en el desarrollo y prueba de dos modelos, **ResNet** y **RamanNet**, para identificar especies bacterianas utilizando datos de espectroscopía Raman. Además, se evaluaron varios modelos de aprendizaje automático, como k-Nearest Neighbors (kNN), Análisis Discriminante Lineal (LDA), Análisis de Componentes Principales (PCA), Análisis Discriminante de Mínimos Cuadrados Parciales (PLSDA), Random Forest (RandForest) y Máquinas de Soporte Vectorial (SVM). Los resultados de estos modelos se compararon en función de su rendimiento en un conjunto de datos de referencia, con pruebas adicionales en conjuntos de datos de ajuste fino y clínicos.

## Estructura de Carpetas

### 1. **Bact_ID**
Este es el directorio principal del proyecto. Contiene los siguientes subdirectorios:

#### a. **data**
Esta carpeta contiene todos los conjuntos de datos utilizados en el proyecto:

- **Conjunto de Datos de Referencia:** Utilizado para el entrenamiento y las pruebas iniciales de los modelos.
- **Conjunto de Datos de Prueba:** Utilizado para evaluar el rendimiento de los modelos después del entrenamiento.
- **Conjunto de Datos de Ajuste Fino:** Un conjunto de datos más pequeño utilizado para ajustar finamente los modelos, especialmente para adaptarse a las variaciones de los datos clínicos.
- **Conjunto de Datos Clínicos:** Datos del mundo real utilizados para probar la robustez de los modelos después del ajuste fino.

*Nota:* Dado el tamaño de los datos, los enlaces a los conjuntos de datos originales se proporcionarán para su descarga.
Enlace al [https://github.com/csho33/bacteria-ID](#) del autor de los datos.

#### b. **RamanNet**
Esta carpeta contiene todos los recursos relacionados con el modelo RamanNet:

- **Códigos Originales:** Enlace al [https://github.com/nibtehaz/RamanNet](#) del autor.
- **Jupyter Notebooks:** Contiene notebooks para el entrenamiento y prueba del modelo RamanNet en los conjuntos de datos proporcionados.

#### c. **ResNet**
Esta carpeta contiene todos los recursos relacionados con el modelo ResNet:

- **Código Original:** La implementación original del modelo ResNet.
- **Jupyter Notebooks:** Contiene notebooks para el entrenamiento y prueba del modelo ResNet en los conjuntos de datos proporcionados.

#### d. **OtherModels**
Esta carpeta contiene notebooks de Jupyter que evalúan el rendimiento de varios otros modelos de aprendizaje automático en el conjunto de datos de referencia. Estos modelos incluyen:

- k-Nearest Neighbors (kNN)
- Análisis Discriminante Lineal (LDA)
- Análisis de Componentes Principales (PCA)
- Análisis Discriminante de Mínimos Cuadrados Parciales (PLSDA)
- Random Forest (RandForest)
- Máquinas de Soporte Vectorial (SVM)

#### e. **images**
Esta carpeta contiene todas las gráficas y visualizaciones utilizadas en la presentación del proyecto. Estas incluyen:

- Gráficas que muestran el rendimiento de diferentes modelos.
- Visualizaciones de los datos y predicciones de los modelos.
- Otras visualizaciones obtenidas del Análisis Exploratorio de Datos (EDA).

#### f. **presentation**
Esta carpeta contiene el archivo de presentación que proporciona una visión general del proyecto. La presentación resume los objetivos, metodología, resultados y conclusiones del proyecto.

#### g. **EDA**
Esta carpeta contiene dos notebooks de Jupyter dedicados al Análisis Exploratorio de Datos (EDA). Estos notebooks proporcionan información sobre los datos de referencia, tales como:

- Resúmenes estadísticos.
- Distribuciones de datos.
- Visualizaciones que ayudan a comprender las características de los conjuntos de datos.

## Cómo Utilizar

### Modelo RamanNet:
1. Navega a la carpeta **RamanNet**.
2. Abre los Jupyter notebooks para explorar el proceso de entrenamiento y prueba del modelo RamanNet.
3. Sigue las instrucciones en los notebooks para replicar los experimentos.

### Modelo ResNet:
1. Navega a la carpeta **ResNet**.
2. Abre los Jupyter notebooks para explorar el proceso de entrenamiento y prueba del modelo ResNet.
3. Sigue las instrucciones en los notebooks para replicar los experimentos.

### Otros Modelos:
1. Navega a la carpeta **OtherModels**.
2. Abre los Jupyter notebooks para ver la implementación y comparación de rendimiento de diferentes modelos de aprendizaje automático en el conjunto de datos de referencia.

### Presentación:
1. Ve a la carpeta **presentation** para ver el resumen del proyecto y los resultados.
2. La presentación proporciona una visión general de los objetivos, metodología, resultados y conclusiones del proyecto.

### Análisis Exploratorio de Datos:
1. Navega a la carpeta **EDA** para abrir los notebooks que proporcionan un análisis en profundidad del conjunto de datos de referencia.
2. Estos notebooks son útiles para comprender la estructura y características del conjunto de datos antes de aplicar cualquier modelo de aprendizaje automático.

## Conclusión

Este proyecto ofrece un enfoque integral para la identificación bacteriana utilizando datos de espectroscopía Raman. Al comparar modelos de aprendizaje profundo como ResNet y RamanNet con métodos tradicionales de aprendizaje automático, se busca determinar el enfoque más efectivo para una clasificación bacteriana precisa y confiable.
