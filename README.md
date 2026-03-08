# Telecom X – Parte 2: Predicción de Cancelación (Churn) con Machine Learning

## 📣 Contexto del Desafío

Este proyecto representa la segunda fase del análisis de churn para **Telecom X**. Después del éxito en el análisis exploratorio, ahora formo parte del equipo de **Machine Learning** con la misión de desarrollar modelos predictivos que identifiquen clientes con alta probabilidad de cancelación.

## 🎯 Objetivos

- Desarrollar un pipeline completo de Machine Learning para predicción de churn
- Comparar múltiples algoritmos de clasificación
- Identificar variables críticas que influyen en la cancelación
- Entregar insights accionables para el negocio

📊 Telecom X – Predicción de Churn con Machine Learning
🎯 Objetivos
#	Objetivo
1	Preparar datos (codificación, normalización)
2	Análisis de correlación y selección de variables
3	Entrenar ≥2 modelos de clasificación
4	Evaluar con métricas (Accuracy, Precision, Recall, F1, AUC)
5	Interpretar importancia de variables
6	Conclusiones estratégicas
🛠️ Tecnologías
Lenguaje: Python 3.8+

Librerías:

ML: Scikit-learn (LogisticRegression, KNN, DecisionTree, RandomForest, GridSearchCV)

Datos: Pandas, NumPy, Statsmodels (VIF)

Visualización: Matplotlib, Seaborn

📊 Pipeline
text
1. Preprocesamiento → 2. Feature Selection → 3. Modelado → 4. Evaluación
🏆 Resultados
Modelo	F1-Score	AUC-ROC
Random Forest	0.735	0.891
Regresión Logística	0.709	0.873
Árbol Decisión	0.625	0.785
KNN	0.648	0.812
🔍 Top Factores Predictivos
Tenure (antigüedad) - Mayor peso

Contract Type - Mensual = +riesgo

Monthly Charges - +cargo = +riesgo

Online Security - Ausencia = +40% riesgo

Tech Support - Factor protector

💡 Conclusiones Estratégicas
Ventana crítica: primeros 12 meses

Acción: incentivar contratos anuales y servicios de seguridad

Impacto: reducir churn 15-25% en 6 meses

ROI estimado: 300-400% anual
