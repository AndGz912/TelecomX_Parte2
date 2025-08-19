# TelecomX_Parte2

---

## 📊 Predicción de Cancelación de Clientes en - TelecomX

Este proyecto tiene como objetivo **predecir la cancelación de clientes (churn)** en una empresa de telecomunicaciones(TelecomX), utilizando diferentes algoritmos de Machine Learning y comparando su rendimiento.  

El análisis permite identificar qué clientes están más propensos a cancelar el servicio y qué variables influyen en su decisión, ayudando a la empresa a diseñar estrategias de retención más efectivas.  

---

## 🚀 Tecnologías Utilizadas
- **Python 3.10** 🐍 
- **Google Colab / Jupyter Notebook**
- **Bibliotecas principales**:
  - `pandas` → Manipulación y limpieza de datos.
  - `numpy` → Cálculos numéricos.
  - `matplotlib` & `seaborn` → Visualización de datos.
  - `scikit-learn` → Modelos predictivos y métricas de evaluación.

---

## 📂 Estructura del Proyecto
- TelecomX_Parte2.ipynb # Notebook principal con el análisis completo

---
  
## 🔍 Flujo del Proyecto
1. **Exploración y preprocesamiento de datos**:
   - Limpieza de valores nulos y categóricos.
   - Estandarización de variables.
   - Codificación de variables categóricas con *One-Hot Encoding*.

2. **Modelos predictivos utilizados**:
   - **Regresión Logística**
   - **Random Forest**
  
3. **Evaluación de modelos**:
   - Accuracy, Precision, Recall, F1-Score.
   - Matriz de confusión.
   - Importancia de variables (*Random Forest*).

---

## 📈 Resultados Visuales

### 🔹 Comparación de Métricas entre Modelos
![Comparación de métricas](comparacion_metricas.png)

### 🔹 Importancia de Variables (Random Forest)
![Importancia de variables](importancia_variables_RF.png)

### 🔹 Matriz de Confusión - Random Forest
![Matriz de confusión RF](matriz_confusion_Random_Forest.png)

### 🔹 Matriz de Confusión - Regresión Logística
![Matriz de confusión RL](matriz_confusion_Regresion_Logistica.png)

---

## 🔑 Interpretación de Variables Relevantes

- **Regresión Logística** → Variables como el tiempo de contrato y el tipo de plan tienen fuerte peso en la cancelación.  
- **Random Forest** → La variable más importante fue el **tipo de contrato**, seguida del **tiempo de antigüedad del cliente** y **métodos de pago**.  

---

## 💡 Estrategias de Retención Propuestas

1. **Fidelización de clientes con contrato mensual**: ofrecer beneficios por migrar a contratos de mayor permanencia.  
2. **Ofertas personalizadas**: descuentos o paquetes especiales a clientes con alto consumo de datos.  
3. **Mejora en la experiencia de pago**: optimizar métodos de pago electrónicos para reducir la fricción.  
4. **Atención proactiva**: contactar a clientes en riesgo antes de que cancelen, basándose en las variables más predictivas.  

---

## ✅ Conclusiones

- El modelo de **Random Forest** fue el que **mejor desempeño obtuvo** con valores superiores en **Accuracy y Recall**, lo que lo convierte en la mejor opción para predecir el *churn*.  
- La **Regresión Logística** mostró un desempeño estable y sencillo de interpretar, siendo útil como modelo base.  
- La variable con mayor importancia predictiva fue **`tenure (antigüedad del cliente)`**, seguida de las variables relacionadas con **servicios contratados** y **métodos de pago**.  
- Estrategias de retención sugeridas:
  - Programas de fidelización para clientes con menor tiempo en la compañía.
  - Ofertas personalizadas según los servicios contratados.
  - Flexibilidad en métodos de pago para reducir la fricción.
 
---

## 🧑‍💻 Autor
👤 **Andrew Gonzales Zeña**  
📧 [andrew_gz1103@outlook.com](mailto:andrew_gz1103@outlook.com)  
💼 Estudiante de **Ingeniería de Sistemas (UTP)** | **Especialización en Ciencia de Datos (ALURA LATAM)**
📍 Lima, Perú  

---

## ⭐ Cómo contribuir
Si quieres mejorar este proyecto:  
1. Haz un fork 🍴  
2. Crea una nueva rama `feature/nueva-funcionalidad`  
3. Envía un PR 🚀  

---

## 📌 Nota
Este proyecto es parte de mi proceso de aprendizaje en **Ciencia de Datos** y representa uno de mis primeros proyectos de predicción con Machine Learning.














