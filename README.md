# 🧪 Clasificación de Setas

Este proyecto de aprendizaje automático tiene como objetivo predecir si una seta es comestible o venenosa basándose en sus características físicas, como el color del sombrero, el olor, la forma del tallo, entre otros.

El dataset utilizado contiene **8124 muestras** y **23 características** categóricas, y está disponible públicamente desde el repositorio de UCI Machine Learning.

📂 **Dataset**:  
https://raw.githubusercontent.com/kanchitank/Mushroom-Classification/master/mushrooms.csv

---

## 📌 Objetivos del proyecto

1. Cargar y explorar el conjunto de datos
2. Procesar variables categóricas con `LabelEncoder`
3. Eliminar variables no informativas
4. Analizar correlaciones entre características
5. Reducir la dimensionalidad con PCA
6. Dividir el dataset en entrenamiento y prueba
7. Entrenar y optimizar múltiples modelos:
   - Árbol de Decisión
   - Random Forest
   - SVM
   - Naive Bayes
   - KNN
   - Regresión Logística
8. Visualizar matriz de confusión y clasificación
9. Dibujar el árbol de decisión con `graphviz`

---

## ⚙️ Instalación

```bash
git clone https://github.com/tuusuario/clasificacion-setas.git
cd clasificacion-setas
python -m venv venv
source venv/bin/activate     # En Windows: venv\Scripts\activate
pip install -r requirements.txt
````

## 🖼️ Visualizaciones
  . Matriz de confusión

  . Árbol de decisión exportado con **graphviz**

  . Heatmap de correlación

  . Gráfico de barras de clases

## 🧠 Mejora futura
  . Validación cruzada para todos los clasificadores

  . Evaluación de balanceo y métodos SMOTE

  . Conversión a una aplicación web con Flask o Streamlit

## 📝 Licencia
Uso académico y libre distribución citando fuente original del dataset y autor del código.
