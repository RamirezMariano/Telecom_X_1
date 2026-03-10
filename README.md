# Telecom X - Análisis de Evasión de Clientes (Churn)

## Descripción del proyecto
Este proyecto analiza los factores asociados a la cancelación de clientes (churn) en Telecom X.  
El objetivo es identificar patrones en los datos que permitan comprender por qué algunos clientes abandonan el servicio y cómo la empresa podría mejorar sus estrategias de retención.

El análisis se realizó utilizando Python y bibliotecas de análisis de datos para explorar el comportamiento de los clientes y detectar variables que influyen en la evasión.

---

## Objetivos
- Analizar la distribución del churn en la base de clientes.
- Identificar variables que puedan influir en la cancelación del servicio.
- Obtener insights que ayuden a mejorar las estrategias de retención de clientes.

---

## Herramientas utilizadas
- Python
- Pandas
- Matplotlib
- Seaborn
- Google Colab

---

## Proceso de análisis

### 1. Extracción de datos
Los datos fueron cargados desde una API en formato JSON y convertidos en un DataFrame utilizando Pandas.

### 2. Transformación y limpieza
Se revisaron los tipos de datos, valores nulos e inconsistencias.  
Algunas columnas fueron convertidas a formato numérico para facilitar el análisis.

### 3. Análisis exploratorio de datos (EDA)
Se realizaron visualizaciones para analizar la relación entre el churn y diferentes variables categóricas y numéricas como:

- Tipo de contrato
- Método de pago
- Tipo de servicio de internet
- Antigüedad del cliente
- Cargos mensuales y totales

---

## Principales insights
El análisis exploratorio permitió identificar algunos patrones relevantes:

- Los clientes con **contratos mensuales** presentan una mayor tasa de churn.
- Los clientes con **menor antigüedad** tienen mayor probabilidad de cancelar el servicio.
- Los **cargos mensuales elevados** pueden estar asociados con mayores tasas de evasión.

---

## Recomendaciones
A partir del análisis se sugieren algunas posibles acciones:

- Incentivar contratos de mayor duración para aumentar la retención.
- Implementar estrategias de fidelización para clientes nuevos.
- Analizar los planes con cargos mensuales elevados para mejorar la satisfacción del cliente.
- Desarrollar modelos predictivos de churn para anticipar cancelaciones.
- 
