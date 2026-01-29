# 🥛 Evaluación de la Calidad de la Leche mediante Machine Learning

Este repositorio contiene un estudio completo y un modelo predictivo para categorizar la calidad de la leche en tres niveles (**Bajo**, **Medio** y **Alto**) basándose en sus propiedades físico-químicas.



## 👥 Autores
* **Felipe Santiago Goicolea Guerra**
* **Matias Elier Labraña Abarca**
* **Marcelo Andres Yañez Barrientos**
*Magister Data Science (2025) - Universidad de las Américas, Santiago, Chile.*

## 📋 Resumen del Proyecto
El proyecto sigue la metodología **CRISP-DM** para abordar un problema crítico en la industria láctea: la lentitud y el costo de los análisis de laboratorio tradicionales. 

### Fases del Proyecto:
1. **Análisis Exploratorio (EDA):** Visualización de la distribución de pH, temperatura y grasa.
2. **Preprocesamiento:** Manejo de datos duplicados y escalamiento de variables.
3. **Modelado:** Entrenamiento de algoritmos de clasificación (Random Forest, SVM, etc.).
4. **Evaluación:** Comparativa de desempeño mediante matrices de confusión y métricas de precisión.

## 📊 Dataset
El archivo `milknew.csv` incluye 1,059 registros con las siguientes características:
- pH, Temperatura, Sabor, Olor, Grasa, Turbidez y Color.

## 🛠️ Requisitos e Instalación
Para ejecutar este notebook, clona el repositorio e instala las librerías necesarias:

```bash
git clone [https://github.com/tu-usuario/nombre-del-repo.git](https://github.com/tu-usuario/nombre-del-repo.git)
cd nombre-del-repo
pip install -r requirements.txt