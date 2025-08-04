# Análisis de Evasión de Clientes - Telecom X

Este repositorio contiene el desarrollo del desafío propuesto por el programa **Oracle Next Education (ONE)** en colaboración con **Alura**, enfocado en el análisis exploratorio de datos (EDA) aplicado a un caso real de **evasión de clientes (Churn)** para la empresa ficticia **Telecom X**.

## Descripción del Desafío

La empresa Telecom X está atravesando un problema serio de deserción de clientes, con una tasa de abandono cercana al 27%. Como analista de datos, fui contratado para:

- Extraer los datos a través de una API en formato JSON.
- Realizar el tratamiento, limpieza y normalización de los datos (ETL).
- Realizar un análisis exploratorio para identificar posibles causas del abandono.
- Entregar un informe detallado que sirva como insumo para el equipo de Ciencia de Datos, quienes desarrollarán un modelo predictivo de Churn.

Este desafío pone en práctica las habilidades adquiridas en los cursos del programa, incluyendo el uso de herramientas como **Python**, **Pandas** y **Matplotlib**.


##  Tecnologías y Librerías Utilizadas

- Python 3.10+
- Pandas
- Matplotlib
- NumPy
- JSON
- Google Colab (entorno de desarrollo)


##  Flujo del Proyecto

1. **Extracción de Datos**  
   Acceso a una API para obtener los datos en formato JSON.

2. **Transformación y Limpieza (ETL)**  
   - Normalización del dataset  
   - Renombrado de columnas  
   - Corrección de tipos de datos  
   - Estandarización de strings  
   - Eliminación de duplicados e inconsistencias  

3. **Análisis Exploratorio de Datos (EDA)**  
   Exploración de variables categóricas y numéricas para encontrar patrones asociados al Churn.

4. **Visualización de Resultados**  
   Gráficos e interpretaciones que permiten comprender el comportamiento de los clientes que abandonan el servicio.

5. **Informe Final**  
   Documento con conclusiones y recomendaciones estratégicas basadas en el análisis.


## Principales Hallazgos

- El abandono se concentra en los **primeros meses** del contrato.
- Los contratos **mensuales** tienen una **mayor tasa de evasión**.
- Clientes con **gastos bajos** son más propensos a abandonar.
- Métodos de **pago electrónico** y **factura electrónica** están fuertemente relacionados con la deserción.
- Los usuarios que no contratan **servicios adicionales** (protección, soporte, seguridad) tienen mayor propensión al retiro.
