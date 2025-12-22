# 📈 Financial Markets Monitor (Real-Time Pipeline)

Este proyecto implementa un pipeline ETL (Extract, Transform, Load) para monitorear activos financieros en tiempo real y analizar oportunidades de diversificación.

## 🎯 Objetivo del Proyecto
Automatizar la descarga de datos de mercado para identificar correlaciones entre activos de riesgo (Bitcoin, S&P 500) y activos de refugio (Oro).

## 🧠 Hallazgos Económicos
* **Descorrelación de Activos:** Se calculó un coeficiente de Pearson de **0.10** entre Bitcoin y Oro.
* **Tesis de Inversión:** Esta baja correlación sugiere que ambos activos pueden convivir en un portafolio eficiente (Teoría Moderna de Portafolios), ya que los movimientos de volatilidad del mercado Cripto no contagian directamente al mercado de Commodities.

## 🛠 Stack Tecnológico
* **Python:** Scripting y automatización.
* **Librerías:** * `yfinance`: Conexión a API de Yahoo Finance.
    * `pandas`: Limpieza de Time Series y manejo de datos nulos (ffill).
    * `seaborn`: Generación de mapas de calor (Heatmaps) para matrices de correlación.
* **Tableau:** Visualización interactiva con ejes duales (Dual Axis) para comparar precios de distinta escala.

## 📊 Dashboard Interactivo
Puedes ver la comparación visual de **Bitcoin vs Oro** en el siguiente tablero:
👉 [VER DASHBOARD EN TABLEAU PUBLIC]https://public.tableau.com/app/profile/axel.giraldo/viz/MonitorMercadosFinancieros/Hoja9?publish=yes

---
*Proyecto realizado como parte del Portafolio de Economía Computacional.*
