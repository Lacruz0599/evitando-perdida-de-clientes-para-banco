# 🏦 Predicción de Deserción de Clientes — Beta Bank

Beta Bank ha detectado una tendencia creciente de abandono por parte de sus clientes. Considerando que **retener clientes existentes es significativamente más rentable que adquirir nuevos**, se planteó el desafío de desarrollar un modelo de machine learning que permita anticipar con precisión la deserción y así tomar medidas proactivas para evitarla.

---

## 🎯 Objetivo

Construir un modelo de clasificación binaria que permita predecir si un cliente está en riesgo de abandonar el banco próximamente, optimizando la métrica **F1 Score** (umbral mínimo requerido: `0.59`) y evaluando el rendimiento adicional mediante la métrica **AUC-ROC**.

---

## ⚙️ Descripción del Proyecto

El desarrollo del modelo incluyó las siguientes etapas:

- **Análisis exploratorio y limpieza de datos:** Evaluación de la calidad, distribución y correlaciones.
- **Balanceo de clases:** Se aplicaron técnicas de **sobremuestreo** para contrarrestar el desbalance en la variable objetivo.
- **Entrenamiento de modelos base:**
  - Árbol de Decisión (`DecisionTreeClassifier`)
  - Bosque Aleatorio (`RandomForestClassifier`)
  - Regresión Logística (`LogisticRegression`)
- **Evaluación comparativa:** Se analizaron los modelos usando las métricas F1 Score y AUC-ROC para seleccionar el más eficaz.

---

## ✅ Resultados

- **Modelo final elegido:** `DecisionTreeClassifier`  
- **F1 Score alcanzado:** `0.77`  
- **AUC-ROC:** `0.857`  
- El uso de técnicas de sobremuestreo permitió **mejorar significativamente la capacidad del modelo** para identificar clientes propensos a desertar, superando ampliamente el umbral mínimo requerido.

---

## 📌 Conclusión

El modelo predictivo desarrollado ha demostrado un **alto nivel de precisión y sensibilidad**, convirtiéndose en una herramienta estratégica para Beta Bank. Su implementación puede ayudar a:

- **Reducir la pérdida de clientes**, 
- **Aumentar la rentabilidad**, 
- **Fortalecer la fidelización** mediante incentivos personalizados y mejoras en la experiencia del cliente.

Gracias a su rendimiento, este modelo puede integrarse fácilmente en sistemas de CRM o procesos analíticos internos orientados a la **retención proactiva de clientes**.

---

## 🧠 Tecnologías y Herramientas

- **Lenguaje:** Python  
- **Análisis y procesamiento de datos:** Pandas, NumPy  
- **Modelado y evaluación:** Scikit-learn  
- **Visualización de datos:** Matplotlib, Seaborn  

---

## 👤 Autor

**César Eduardo Cruz Cabrera**  
📧 cesareduardocruzcabrera@gmail.com  
💼 [LinkedIn - César Eduardo Cruz Cabrera](https://www.linkedin.com/in/cesar-eduardo-cruz-cabrera)
