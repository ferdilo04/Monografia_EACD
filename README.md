# ENTREGABLE MONOGRAFIA ESPECIALIZACIÓN EN ANALITICA Y CIENCIA DE DATOS 
# GRUPO
- **Diego Fernando Londoño**
- **Yeny Patricia Vergara** 

# Proyecto: Modelo de Predicción de Tiempo de Espera De Los Asegurados en Accidentes de Tránsito

Predecir el tiempo de espera en la atención de un asegurado durante una incidencia o accidente de tránsito desarrollando un modelo de Machine Learning con el fin de facilitar la asignación adecuada del gestor de seguros.


## Contenido

- **NoteBook/01_Ajustar_dataset_inicial.ipynb**: Notebook para ajustar datos inciales en el dataset final con limpieza y generación de variables adicionales.
- **NoteBook/02_Analisis_Exploratorio.ipynb**: Notebook de analisis exploratorio.
- **NoteBook/03_Limpieza_prepocesamiento.ipynb**: Notebook de prepocesamiento de datos para generar el dataset final ajustado.
- **NoteBook/04_Entrenamiento_ejecucion_modelo.ipynb**: Notebook debidamente documentado con el código para entrenamiento, evaluación y selección del modelo.
- **NoteBook/05_Modelo_Completo.ipynb**: Notebook completo que agrupa todos los pasos en un solo lugar (Ajuste y lipieza DataSet, preprocesamiento,particionamiento, entrenamiento y evaluación).
- **DataSet_aseguradora.xlsx**: Data cruda inicial sin ningún tipo de tratamiento.
- **DataSet_PREDITIMESACC_v1.xlsx**: Dataset inicial ajustada con información de los datos a trabajar (Versión 1.0).
- **DataSet_PREDITIMESACC_V2.xlsx**: Dataset actualizado con información del clima (Versión 2.0).
- **DataSet_PREDITIMESACC_V3.xlsx**: Dataset actualizado con información de la ubicación de origen y dirección generada desde el campo descripción (Versión 3.0).
- **DataSet_PREDITIMESACC_V4.xlsx**: Dataset actualizado con información ubicación en terminos de latitud y longitud (Versión 4.0).
- **DataSet_PREDITIMESACC_V5.xlsx**: **Dataset Final** actualizado con información ubicación en terminos de distancia entre origen y destino (Versión Final 5.0).
- **Documentos/Cronograma.xlsx**: Cronograma de ejecución monografia 2025_02.
- **Documentos/EstadodelArte/Resumen estado del arte.xlsx**: Información del estado del arte en modelos similares.
- **Documentos/EstadodelArte/Resumen estado del arte.xlsx**: Información del estado del arte en modelos similares.
- **Documentos/Monografia_ModeloPredictivoTASAT_EACD_2025_02.docx**:Monografia 2025_02 Semestre II -> Modelo de predicción de tiempo de espera de un asegurado en accidente de tránsito (Versión Final del documento en Word).
- **Documentos/Monografia_ModeloPredictivoTASAT_EACD_2025_02.pdf**:Monografia 2025_02 Semestre II -> Modelo de predicción de tiempo de espera de un asegurado en accidente de tránsito (Versión Final del documento en pdf).
- **Documentos/Detalle_ajuste_hiperparametros/Ajustes V1**: Detalle en excel de los ajustes de hiperparametros con *GridSearchCV* y *RandomizedSearch* basados en el R2 de entrenamiento para 12 modelos.
- **Documentos/Detalle_ajuste_hiperparametros/Ajustes V2**: Detalle en excel de los ajustes de hiperparametros con *GridSearchCV* basados en el R2 de entrenamiento y R2 des test para 10 modelos.
- **Documentos/Detalle_ajuste_hiperparametros/RESUMEN_COMPLETO_HIPERPARAMETROS.xlsx**: Resumen consolidado de ajustes de hiperparametros.




## Pasos para ejecutar el Notebook

- Se puede ejecutar los Notebook directamente desde Colab en el siguiente enlace:
Modelo: [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1xwDWz_EMBLOzOTxIhov6jOxgKw-UDou6) 
 
- En caso de no tener acceso a Colab, se puede usar el Notebook de este repositorio NoteBook/05_Modelo_Completo.ipynb o modelo de elección, se deben seguir los siguientes paso:
	- **Paso 1**: Se descarga el Notebook del repositorio y se carga en un ambiente que se pueda ejecutar preferiblemente Colab.
	- **Paso 2**: Una vez carga el Notebook en un ambiente que se puede ejecutat seguir los paso que allí están debidamente documentados, correr cada una de las secciones de código en el orden que están en el Notebook.
- El Dataset está referenciado al enlace público del repositorio, no es necesario hacer ningún cambio para que se importe en el Notebook
