# Análisis de Evasión de Clientes – Telecom X LATAM

Este proyecto forma parte del desafío de analítica de datos de Telecom X, cuyo objetivo es identificar los factores que influyen en la cancelación de servicios por parte de los clientes (churn).  
Utilizando Python, Google Colab y bibliotecas de ciencia de datos, se desarrolló un análisis completo desde la carga hasta la visualización de datos.

---

## Objetivos

- Comprender el comportamiento de los clientes que cancelan.
- Identificar patrones de evasión según variables categóricas y numéricas.
- Proponer recomendaciones para reducir la tasa de churn.

---

## Estructura del Proyecto
├── TelecomX_Data.json         # Fuente de datos en formato JSON
├── TelecomX_LATAM.ipynb       # Notebook de análisis con todo el proceso ETL + EDA
├── TelecomX_diccionario.md    # Diccionario de variables
├── README.md                  # Este archivo

---

## Tecnologías utilizadas

- Python
- Google Colab
- Pandas
- Matplotlib & Seaborn
- GitHub

---

## Flujo del Análisis

1. **Extracción de datos** desde una API pública (formato JSON)
2. **Transformación y limpieza** de valores inconsistentes
3. **Creación de nuevas variables** como `DailyCharges` y `TotalServices`
4. **EDA** con análisis descriptivo, gráficos, cruces por categoría y correlaciones
5. **Informe final** con conclusiones y recomendaciones
6. **Extras**: matriz de correlación y visualizaciones adicionales

---

## Resultados destacados

- Los contratos mensuales y el método de pago `electronic check` tienen mayor churn.
- Los clientes con menos tiempo (`tenure`) y pocos servicios contratados son más propensos a cancelar.
- Las visualizaciones ayudaron a respaldar hallazgos con evidencia gráfica.

---

## Recomendaciones

- Implementar estrategias de fidelización en contratos de corto plazo.
- Promover métodos de pago automáticos.
- Reforzar servicios adicionales como soporte técnico y seguridad en línea.

---

## ✍Autor

**Sebastián Gómez C.**  
Proyecto educativo para formación en Ciencia de Datos con Google Colab y GitHub. ALURALATAM
