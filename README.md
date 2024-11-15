# Ironkaggle-
Análisis de Datos del Mercado Inmobiliario
Este proyecto tiene como objetivo predecir los precios de propiedades inmobiliarias basándose en diversas características. El proceso incluye la limpieza de datos, selección de características, y modelado utilizando XGBoost como modelo principal.
Pasos Realizados
Adquisición de Datos: Se descargaron y prepararon los datos del mercado inmobiliario.
Limpieza y Selección: Se limpiaron los datos eliminando registros incompletos y columnas irrelevantes (como la fecha). Se seleccionaron las características más relevantes para predecir el precio.
Modelo: Se eligió XGBoost como el modelo principal debido a su rendimiento robusto en este tipo de tareas de predicción. Aunque se probaron técnicas de escalado, el modelo funcionó bien sin necesidad de escalado.
Escalado de Datos: Se exploraron dos métodos de escalado:
Sin embargo, se determinó que XGBoost no requiere escalado previo para obtener buenos resultados.
MinMaxScaler: Transforma los datos a un rango entre 0 y 1.
StandardScaler: Normaliza los datos para que tengan media 0 y desviación estándar 1.

Librerías Utilizadas
Pandas, Numpy: Para la manipulación de datos.
XGBoost: Para la predicción.
Scikit-learn: Para preprocesamiento y evaluación.
Licencia
Este proyecto está bajo la Licencia MIT.
