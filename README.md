# 💳 Scoring de Clientes para Tarjetas de Crédito

👋 ¡Hola! Soy Víctor, Científico de Datos.  
En este proyecto desarrollé un modelo para predecir la probabilidad de que un solicitante de tarjeta de crédito sea aceptado o rechazado, usando técnicas de machine learning y métricas sólidas.

## 🔍 Introducción
Analizamos un conjunto de datos de clientes con información financiera (A1..A14) para encontrar patrones que ayuden a tomar decisiones de crédito más seguras y eficientes.  
Se implementó un pipeline con preprocesamiento, búsqueda de hiperparámetros y calibración para asegurar que las probabilidades predichas sean realistas.

## 🎯 Objetivos
- 📈 Identificar qué variables son más relevantes para la decisión de crédito.  
- ✅ Validar el modelo con métricas robustas (ROC-AUC, PR-AUC).  
- 🤖 Construir una herramienta que permita puntuar nuevos solicitantes con un umbral de decisión ajustable.  

## 📌 Hallazgos Clave
- Algunas variables numéricas muestran una fuerte relación con la aprobación/rechazo.  
- El modelo elegido (**XGBoost calibrado**) ofrece una alta capacidad de discriminación:  
  - **ROC-AUC:** 0.91  
  - **PR-AUC:** 0.89  
- La importancia de variables por *Permutation Importance* confirma que ciertas características financieras son críticas en la decisión.

## 🚀 Conclusiones
- 🛠️ El modelo puede integrarse en procesos de scoring para priorizar solicitudes de bajo riesgo.  
- 🎯 Ajustar el *threshold* permite controlar la tasa de falsos positivos y negativos según la estrategia de negocio.  
- 🤝 La calibración de probabilidades mejora la confianza en la interpretación de resultados.
🎯 Ajustar el threshold permite controlar la tasa de falsos positivos y negativos según la estrategia de negocio.

🤝 La calibración de probabilidades mejora la confianza en la interpretación de resultados.


