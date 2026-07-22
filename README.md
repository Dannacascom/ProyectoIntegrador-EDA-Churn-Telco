# Análisis y Predicción de Fuga de Clientes en una Empresa Telco

## Descripción
Análisis exploratorio de un dataset de clientes de una empresa de telecomunicaciones para identificar los factores que influyen en la fuga de clientes.
El proyecto incluye la limpieza y transformación de los datos, el análisis exploratorio, la visualización de resultados y la construcción de un modelo de regresión logística en Python.También se desarrolló un dashboard en Power BI para presentar los principales hallazgos de manera interactiva.

## Pregunta de investigación
**¿Qué factores influyen en la fuga de clientes de una empresa de telecomunicaciones y cómo pueden utilizarse para predecir qué clientes tienen mayor probabilidad de abandonar la empresa?**

## Fuente de datos
Dataset **Telco Customer Churn**, proporcionado por el docente con fines académicos.

El conjunto de datos contiene información demográfica, contractual y relacionada con los servicios utilizados por los clientes, incluyendo:

- Tipo de contrato
- Antigüedad del cliente
- Servicio de internet
- Soporte técnico
- Seguridad en línea
- Método de pago
- Cargos mensuales
- Cargos totales
- Fuga del cliente

## Herramientas utilizadas
- **Python**
- **Google Colab**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn**
- **Statsmodels**
- **Power BI**

## Proceso
- Carga y exploración inicial del dataset
- Revisión de tipos de datos
- Conversión de la variable `TotalCharges` a formato numérico
- Identificación y eliminación de valores nulos
- Eliminación de variables sin valor analítico
- Transformación de la variable objetivo `Churn`
- Análisis estadístico de variables numéricas
- Análisis de la fuga según las características de los clientes
- Creación de visualizaciones
- Transformación de variables categóricas en variables dummy
- Selección de variables estadísticamente significativas
- División de los datos en conjuntos de entrenamiento y prueba
- Escalado de variables
- Entrenamiento de un modelo de regresión logística
- Evaluación mediante métricas, matriz de confusión y curva ROC
- Creación de un dashboard interactivo en Power BI

## Resultados
- Aproximadamente el **26.58 % de los clientes** abandonó la empresa.
- Los clientes con contratos **mes a mes** presentan una mayor probabilidad de fuga.
- El método de pago **electronic check** se relaciona con una mayor fuga de clientes.
- Los clientes con servicio de **fibra óptica** presentan una mayor proporción de abandono.
- No contar con **soporte técnico** aumenta la probabilidad de fuga.
- No contar con **seguridad en línea** también se relaciona con una mayor fuga.
- Los contratos de uno o dos años favorecen la permanencia de los clientes.
- El modelo de regresión logística obtuvo una exactitud cercana al **80 %**.
- La curva ROC alcanzó un área bajo la curva aproximada de **0.84**.

## Mi aporte al proyecto

Mi principal contribución fue el diseño y desarrollo del **dashboard interactivo en Power BI**, estructurado en tres secciones: resumen general, perfil de clientes y factores de fuga.
El dashboard integra indicadores clave y visualizaciones que permiten analizar la tasa de abandono, la permanencia de los clientes y la relación de la fuga con variables como el tipo de contrato, el servicio de internet, el método de pago y el soporte técnico.

## Conclusión
Este proyecto permitió identificar los principales factores relacionados con la fuga de clientes en una empresa de telecomunicaciones. Los resultados muestran que los contratos de corta duración, el pago mediante cheque electrónico y la falta de servicios como soporte técnico y seguridad en línea aumentan la probabilidad de abandono.
Por otro lado, los contratos de largo plazo y la contratación de servicios adicionales favorecen la permanencia de los clientes. El modelo de regresión logística permitió estimar la fuga con una exactitud cercana al 80 %, mientras que Power BI facilitó la presentación interactiva de los principales hallazgos.

## Integrantes
- **Luis Henríquez**
- **Danna Casco**
- **Mía Elvir**
