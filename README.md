# Estrategias-de-inversion-multifactorial
# 🧠 Cartera de Inversión Basada en CAPM

Este proyecto aplica el modelo **CAPM (Capital Asset Pricing Model)** para construir una cartera de inversión optimizada. La selección de activos se basa en:

- ✅ Alpha positiva (rendimiento no explicado por el mercado)
- ✅ Beta moderada (control del riesgo sistémico)

## 📊 Métricas calculadas

- Rentabilidad anualizada
- Volatilidad anualizada
- Ratio de Sharpe
- Máximo Drawdown
- Alpha y Beta frente al IBEX 35

## 📈 Visualización

Incluye un gráfico comparativo del rendimiento acumulado de la cartera frente al IBEX 35 como benchmark.

## ⚙️ Librerías utilizadas

- `pandas`, `numpy`, `yfinance`
- `statsmodels` para regresión lineal (CAPM)
- `matplotlib` para visualización

## 📁 Estructura

- `Estrategias de inversión multifactorial.ipynb`: Script principal con todo el flujo de trabajo.
- `README.md`: Este archivo con la descripción del proyecto.

## ✍️ Autor

**Jorge Sánchez**  
Estudiante de Big Data & Business Analytics con formación en Finanzas y ADE.  
Interesado en modelos cuantitativos aplicados al análisis financiero y selección de carteras.

## 🚀 ¿Cómo ejecutarlo?

1. Asegúrate de tener Python 3 y las siguientes librerías instaladas:

```bash
pip install pandas numpy yfinance statsmodels matplotlib
