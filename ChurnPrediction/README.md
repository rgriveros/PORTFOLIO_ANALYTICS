# Análisis de Abandono de Clientes (Customer Churn Prediction)

Este proyecto aplica **Machine Learning (Regresión Logística)** al dataset **Telco Customer Churn (IBM, Kaggle)** con el objetivo de predecir qué clientes tienen mayor probabilidad de cancelar el servicio en los próximos 30 días.  
El análisis está orientado a reproducibilidad, trazabilidad y aplicación en escenarios reales de negocio.

---

## Objetivos
- Predecir la probabilidad de abandono de clientes (churn).
- Identificar patrones críticos: tipo de contrato, antigüedad, cargos mensuales.
- Generar una lista priorizada de clientes en riesgo para acciones comerciales.
- Evaluar métricas de desempeño (ROC-AUC, precisión, recall, matriz de confusión).

## Aplicación práctica
- El modelo genera un TOP 20 de clientes en riesgo, permitiendo al equipo comercial:
- Contactar de forma personalizada a clientes con mayor probabilidad de abandono.
- Diseñar ofertas específicas para clientes nuevos con cargos altos.
- Monitorear la efectividad de las intervenciones con KPIs de retención.

---

## ⚙️ Tecnologías utilizadas
- **Python** (pandas, numpy, scikit-learn, matplotlib, seaborn)
- **Google Colab / Jupyter Notebooks**
- **GitHub** para versionado y portafolio

---

## Principales hallazgos
- **Tasa global de churn:** 26.54% (1 de cada 4 clientes abandona).  
- **Contratos mes a mes:** 15x más riesgo que contratos de dos años.  
- **Antigüedad baja (<3 meses):** clientes nuevos son los más propensos a abandonar.  
- **Cargos mensuales altos:** correlacionan con mayor probabilidad de churn.  
- **Modelo de Regresión Logística:** ROC-AUC = **0.84**, excelente capacidad discriminatoria.  

---

## Cómo replicar
1. Clonar el repositorio:
   ```bash
   git clone https://github.com/RGRIVEROS-PORTFOLIO/PORTFOLIO_ANALYTICS.git

