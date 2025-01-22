# 📊 Análisis de Empresas que Cotizan en Bolsa

Bienvenido a este repositorio, creado para facilitar el análisis y valuación de empresas que cotizan en la bolsa estadounidense mediante diferentes herramientas financieras. Este proyecto está orientado a quienes desean explorar datos financieros, realizar valuaciones por descuento de flujos de caja y analizar ratios clave de empresas. A continuación, se describen los principales componentes del repositorio y cómo utilizarlos.

---

## 🔄 Contenidos del Repositorio

### 1. **Datos Financieros.ipynb**
Este código permite:
- 🔹 Obtener datos de balances, precios y otros indicadores clave de una empresa o ETF.
- 🔹 Acceder a información financiera utilizando la API de Alpha Vantage.

### 2. **DCF.ipynb**
En este notebook se puede:
- 🔹 Realizar la valuación de una empresa utilizando el método de **Discounted Free Cash Flow (DCF)**.
- 🔹 Proyectar flujos de caja futuros y calcular el valor presente neto.

### 3. **Análisis de Balances.ipynb**
Con este código podrás:
- 🔹 Calcular los ratios financieros más importantes para analizar la salud financiera de una empresa.
- 🔹 Comparar diferentes métricas para evaluar desempeño y riesgo.

---

## ⚙️ Requisitos

Para utilizar este repositorio, necesitarás:
1. **API Key de Alpha Vantage**: Se obtiene de forma gratuita [a través de su página oficial](https://www.alphavantage.co/support/#api-key).
2. **Python 3.x** y las siguientes librerías instaladas:
   ```python
   import pandas as pd
   import matplotlib.pyplot as plt
   import requests
   from matplotlib.ticker import MaxNLocator
   import numpy as np
   
---

## ❗ Limitaciones y Recomendaciones

1. **🛑 Disclaimer:** Este código no constituye una recomendación de inversión. Los resultados obtenidos deben ser analizados con cautela y complementados con investigación adicional.
2. **🔎 Precisión de los Datos:** Muchos de los datos proporcionados por Alpha Vantage pueden contener errores o inconsistencias. Se recomienda verificar la información con otras fuentes antes de tomar decisiones.
3. **🇺🇸 Empresas Estadounidenses:** Este análisis está diseñado principalmente para empresas estadounidenses. Al trabajar con ADRs (American Depositary Receipts), los datos se presentan en la moneda de origen de la empresa, lo que puede dificultar la comparación con los precios cotizantes.

---

## 👨‍💼 Autor

Este proyecto fue desarrollado por **Nicolás Scelza**. Si tienes preguntas, comentarios o sugerencias, no dudes en abrir un issue en el repositorio.

---

¡Gracias por utilizar este repositorio! Espero que te sea de utilidad para tus análisis financieros. 📊📈
