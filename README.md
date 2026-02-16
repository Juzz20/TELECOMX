# 📊 Análisis de Evasión de Clientes (Churn) — Telecom X

## 🧾 Descripción del Proyecto

Este proyecto tiene como objetivo analizar la evasión de clientes (Churn) en la empresa Telecom X, identificando los factores que influyen en la cancelación del servicio. A través del análisis exploratorio de datos, se buscan patrones que permitan comprender el comportamiento de los clientes y proponer estrategias de retención.

---

## 🎯 Objetivos

- Comprender la distribución del churn en la base de clientes.
- Identificar variables asociadas a la cancelación del servicio.
- Analizar características demográficas, contractuales y de consumo.
- Proponer recomendaciones basadas en datos para reducir la evasión.

---

## 📂 Dataset

Los datos provienen de una API en formato JSON e incluyen información sobre:

- Datos demográficos de clientes
- Servicios contratados
- Tipo de contrato
- Método de pago
- Cargos mensuales y totales
- Estado de churn (cancelación)

---

## 🧹 Limpieza y Preparación de Datos

Se realizaron los siguientes pasos:

- Carga de datos desde la API
- Conversión a DataFrame de Pandas
- Verificación de tipos de datos
- Conversión de variables categóricas a formato binario
- Tratamiento de valores faltantes
- Corrección de inconsistencias

---

## 📊 Análisis Exploratorio de Datos

Se analizaron variables categóricas y numéricas para identificar patrones relevantes.

### Principales hallazgos:

- Los contratos mensuales presentan la mayor tasa de churn.
- Los clientes nuevos son más propensos a cancelar.
- Los cargos mensuales elevados se asocian a mayor evasión.
- La fibra óptica muestra mayor tasa de cancelación.
- El método de pago Electronic Check presenta alto churn.
- El género no influye significativamente.

---

## 📈 Variables Analizadas

### Categóricas

- Género
- Tipo de contrato
- Método de pago
- Servicio de internet
- Facturación electrónica
- Servicios adicionales

### Numéricas

- Antigüedad (Tenure)
- Cargo mensual (MonthlyCharges)
- Total gastado (TotalCharges)

---

## 💡 Conclusiones

El churn está fuertemente relacionado con:

- Bajo compromiso contractual
- Antigüedad reducida
- Altos costos mensuales
- Determinados servicios y métodos de pago

Los clientes nuevos con contratos mensuales y cargos elevados representan el segmento de mayor riesgo.

---

## 🚀 Recomendaciones

- Incentivar contratos de largo plazo
- Mejorar la experiencia de clientes nuevos
- Revisar la relación precio-valor en planes costosos
- Promover métodos de pago automáticos
- Implementar modelos predictivos de abandono

---

## 🛠️ Tecnologías Utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Google Colab 

---

## ▶️ Cómo Ejecutar el Proyecto

1. Clonar el repositorio o descargar los archivos.
2. Abrir el notebook en Google Colab o Jupyter.
3. Instalar las dependencias necesarias.
4. Ejecutar las celdas en orden.

---


## 📄 Licencia

Uso educativo y demostrativo.
