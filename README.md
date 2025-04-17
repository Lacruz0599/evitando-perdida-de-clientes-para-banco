# Predicción de Deserción de Clientes — Beta Bank

Beta Bank ha identificado una tendencia preocupante: sus clientes están abandonando el banco de forma gradual. Dado que **retener clientes existentes es más rentable que adquirir nuevos**, se planteó el desafío de construir un modelo predictivo que permita anticipar la deserción y tomar medidas preventivas.

## 🎯 Objetivo

Desarrollar un modelo de Machine Learning que prediga si un cliente abandonará el banco próximamente, maximizando el valor de la métrica **F1 Score** (mínimo aceptado: 0.59) y evaluando su rendimiento adicional mediante la métrica **AUC-ROC**.

## ⚙️ Descripción del Proyecto

- Exploración y preprocesamiento de los datos de clientes, incluyendo balanceo de clases.
- Evaluación de múltiples algoritmos:
  - `DecisionTreeClassifier`
  - `RandomForestClassifier`
  - `LogisticRegression`
- Aplicación de técnicas de **sobremuestreo** para mitigar el desbalanceo de clases.
- Comparación de métricas F1 y AUC-ROC para seleccionar el modelo más eficaz.

## ✅ Resultados

- **Modelo seleccionado:** `DecisionTreeClassifier`
- **F1 Score alcanzado:** 0.77
- **AUC-ROC:** 0.857
- Se identificó el impacto negativo del desbalanceo de clases y se corrigió mediante técnicas de sobremuestreo, lo cual permitió superar con holgura el umbral mínimo requerido.

## 📌 Conclusión

El modelo desarrollado ha demostrado un **alto rendimiento en la identificación de clientes propensos a desertar**, lo que permite a Beta Bank implementar acciones preventivas para **reducir la pérdida de clientes** y, en consecuencia, **aumentar la rentabilidad y competitividad** de la institución.

Gracias a su alta precisión y sensibilidad, este modelo se puede integrar en procesos estratégicos de fidelización para ofrecer incentivos personalizados, mejorar la experiencia del cliente y anticiparse a conductas de abandono.

---

## 🧠 Tecnologías y herramientas

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

---

## 📬 Contacto

**César Eduardo Cruz Cabrera**  
📧 cesar.eduardo.cruz.cabrera@gmail.com  
💼 [LinkedIn](https://www.linkedin.com/in/cesar-eduardo-cruz-cabrera)

---
