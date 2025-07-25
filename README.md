# 🚀 Telecom X ETL Challenge

[![Python](https://img.shields.io/badge/python-3.11-blue.svg)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/pandas-2.3.1-yellow)](https://pandas.pydata.org/)
[![NumPy](https://img.shields.io/badge/numpy-2.0.1-orange)](https://numpy.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

---

## 🔍 Descripción

**Telecom X** es un proyecto/challenge dentro de la formación “Aprendiendo a hacer ETL G8 - ONE”. Consiste en extraer, transformar y analizar un conjunto de datos de clientes de una compañía de telecomunicaciones, aplicando buenas prácticas de Data Engineering.

---

## 🎯 Propósito

1. **Aprender** el flujo completo de un proceso ETL (Extract‑Transform‑Load).
2. **Practicar** técnicas de limpieza, normalización y enriquecimiento de datos.
3. **Visualizar** insights clave de negocio a través de gráficas.
4. **Documentar** y estructurar el código para producción y aprendizaje.

---

## 🛠 Tecnologías

- **Lenguaje**: Python 🐍
- **Librerías**:
    - [pandas](https://pandas.pydata.org/)
    - [NumPy](https://numpy.org/)
    - [Matplotlib](https://matplotlib.org/)
- **Notebook**: Jupyter Notebook ☕
- **Formato de datos**: JSON, CSV

---

## ⚙️ Estructura del Proyecto

```text
TelecomX_ETL_Challenge/
├── data/
│   ├── TelecomX_Data.json    # Datos originales
│   └── TelecomX_Cleaned.csv  # Datos transformados
├── notebooks/
│   └── TelecomX_ETL_Solution.ipynb  
├── LICENSE
└── README.md
````

---

## 🚀 Cómo Empezar

1. **Clonar el repositorio**

   ```bash
   git https://github.com/sandovaldavid/TelecomX-ETL-Challenge.git
   cd TelecomX-ETL-Challenge
   ```

2. **Crear y activar un entorno virtual**

   ```bash
   python3 -m venv venv
   source venv/bin/activate  # Linux/macOS
   venv\Scripts\activate     # Windows
   ```

3. **Instalar dependencias**

   ```bash
   pip install -r requirements.txt
   ```

4. **Registrar environment como Kernel para Jupyter**

   ```bash
       python -m ipykernel install --user --name ETL-env --display-name "Python (ETL-env)"
   ```

5.**Abrir el Notebook**

   ```bash
   # Version clásica de Jupyter
   jupyter notebook
    # O si prefieres la versión más moderna
   jupyter lab
   ```

---

## 📊 Features & Gráficas

* ✅ **ETL Completo**: extracción de JSON, transformación (flatten, limpieza, buckets), carga a CSV.
* 📈 **Análisis Descriptivo**: `describe()`, detección de valores nulos y outliers.
* 📉 **Visualizaciones**:

    * Distribución de **Churn**
    * Histograma de **Tenure**
    * Boxplot de **Monthly Charges** vs. Churn
    * Matriz de correlación de variables numéricas

---

## 📄 Licencia

Este proyecto está bajo la Licencia MIT.
¡Disfruta y aprende! 🎉
