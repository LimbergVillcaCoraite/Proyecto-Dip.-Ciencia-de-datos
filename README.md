# Proyecto-Dip.-Ciencia-de-datos
Archivos fuentes del proyecto de ciencia de datos, incluye tambien el notebook y el tableau
# 🎓 Proyecto de Ciencia de Datos: Análisis y predicción del bajo rendimiento académico en la unidad educativa San José Obrero

### Autor: Limberg Villca Coraite
### Universidad: Universidad Mayor de San Simón
### Repositorio: [GitHub - LimbergVillcaCoraite/Proyecto-Dip.-Ciencia-de-datos](https://github.com/LimbergVillcaCoraite/Proyecto-Dip.-Ciencia-de-datos.git)

## 📊 Descripción General
Este proyecto aplica técnicas de *machine learning* para predecir la probabilidad de que un estudiante repruebe, utilizando exclusivamente datos académicos. Se evaluaron varios modelos, optimizados mediante búsqueda de hiperparámetros, para identificar el que ofrece el mejor rendimiento predictivo.

---

## 🔧 Tecnologías y Librerías Utilizadas
- Python 3.9+
- Jupyter Notebook
- Scikit-learn
- Pandas & NumPy
- Matplotlib & Seaborn

---
---
## ✅ Modelos probados
- Logistic Regression
- XGBoost
- XGBoost
- Gradient Boosting
- SVM
- MLP
- LightGBM
- CatBoost
---

## 🗂️ Estructura del Proyecto
```
proyecto_ciencia_datos/
├── /Proyecto-Dip.-Ciencia-de-datos/
├── /Proyecto-Dip.-Ciencia-de-datos/README.md
├── /Proyecto-Dip.-Ciencia-de-datos/requirements.txt
├── /Proyecto-Dip.-Ciencia-de-datos/Codigo fuente
├── /Proyecto-Dip.-Ciencia-de-datos/Documentos
├── /Proyecto-Dip.-Ciencia-de-datos/Gráficos
└── /Proyecto-Dip.-Ciencia-de-datos/data-source/

```

---

## 🚀 Instrucciones para Ejecutar el Proyecto

1. **Clona el repositorio**
```bash
git https://github.com/LimbergVillcaCoraite/Proyecto-Dip.-Ciencia-de-datos.git
cd Proyecto-Dip.-Ciencia-de-datos.git
```

2. **Crea y activa un entorno virtual** (opcional pero recomendado)
```bash
python -m venv venv
source venv/bin/activate  # En Windows: venv\Scripts\activate
```

3. **Instala las dependencias necesarias**
```bash
pip install -r requirements.txt
```

4. **Abre el cuaderno Jupyter**
```bash
jupyter notebook ./Codigo fuente/proyecto_ciencia_de_datos.ipynb

**También puedes ejecutarlo directamente en Google Colab:**  
🔗 [https://colab.research.google.com/drive/1zkWX89JU6IW6N8T1Umz4BIQFn2K_l-LI](https://colab.research.google.com/drive/1zkWX89JU6IW6N8T1Umz4BIQFn2K_l-LI?usp=sharing)

```

---

## 🧬 Lógica del Proyecto
- Se divide el conjunto de datos en entrenamiento y prueba.
- Se prueban múltiples modelos: Logistic Regression, Random Forest, XGBoost, Gradient Boosting, SVM, MLP, LightGBM y CatBoost.
- Se realiza *Grid Search* con validación cruzada para afinar los hiperparámetros (→ `param_grids`).
- Se elige el mejor modelo según el F1-score ponderado.
- Se analizan métricas como Precisión, Recall y se visualiza la matriz de confusión.

---

## 📉 Resultados Clave
- Alta precisión en la predicción de estudiantes aprobados.
- Menor rendimiento en la detección de estudiantes reprobados.
- Se sugiere que esta debilidad puede deberse a la falta de variables socioeconómicas, familiares o emocionales en el conjunto de datos.

---

## 💼 Recomendaciones
- Incluir variables no académicas para mejorar la capacidad predictiva del modelo.
- Ajustar los hiperparámetros en `param_grids` según las necesidades del problema.
- Probar técnicas de *feature engineering* o *ensembles* avanzados.

---

## 💬 Contacto
¿Tienes preguntas o sugerencias? Abre un *issue* o contáctame vía GitHub.

---

> "Un buen modelo no solo aprende de los datos, también cuestiona lo que falta en ellos."
