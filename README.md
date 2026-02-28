# 📊 TelecomX – Predicción de Cancelación de Clientes (Churn)

## 📌 Descripción

Este proyecto desarrolla un modelo predictivo para anticipar la cancelación de clientes (churn) en la empresa TelecomX utilizando técnicas de Machine Learning supervisado.

El objetivo es identificar clientes con alta probabilidad de cancelar el servicio y apoyar la toma de decisiones estratégicas orientadas a la retención.

---

## 🎯 Objetivos

- Preparar y limpiar los datos para modelado.
- Analizar la relación entre variables y la cancelación.
- Implementar modelos de clasificación.
- Evaluar el desempeño mediante métricas estándar.
- Interpretar las variables más relevantes.
- Generar conclusiones estratégicas basadas en datos.

---

## 🛠 Tecnologías Utilizadas

- Python 3  
- Pandas  
- NumPy  
- Seaborn  
- Matplotlib  
- Scikit-learn  

---

## 🔎 Metodología

1. Limpieza y transformación de datos.
2. Codificación de variables categóricas (One-Hot Encoding).
3. Análisis de correlación y análisis dirigido.
4. División en conjunto de entrenamiento y prueba.
5. Entrenamiento de modelos:
   - Regresión Logística (con estandarización y balanceo de clases).
   - Random Forest (con balanceo de clases).
6. Evaluación mediante:
   - Accuracy
   - Precision
   - Recall
   - F1-score
   - Matriz de confusión.
7. Análisis de importancia de variables.

---

## 📈 Resultados

- La Regresión Logística mostró mayor capacidad de detección de clientes en riesgo (Recall más alto).
- Random Forest presentó mayor exactitud global.
- El tipo de contrato y la antigüedad del cliente fueron factores determinantes en la cancelación.

Dado que el objetivo del negocio es anticipar la cancelación, se priorizó el modelo con mayor capacidad de detección de churn.

---

## 📌 Conclusión

El modelo predictivo permite a TelecomX adoptar un enfoque preventivo en la gestión de clientes, facilitando la implementación de estrategias de retención basadas en evidencia cuantitativa.
