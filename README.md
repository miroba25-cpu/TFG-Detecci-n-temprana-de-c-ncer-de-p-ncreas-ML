# TFG — Detección temprana de Cáncer de Páncreas mediante *Machine Learning* a partir de Biomarcadores Urinarios

Miriam Romero Bautista · Ingeniería de la Salud, mención en Ingeniería Biomédica · Universidad de Sevilla · 2025-2026  

Este repositorio contiene el código desarrollado durante la fase de Experimentación, centrado principalmente en la aplicación de técnicas de Machine Learning supervisado para la detección temprana del Adenocarcinoma Ductal Pancreático (PDAC) a partir de biomarcadores urinarios, utilizando el dataset público de Kaggle.


## Contenido

### Experimentación

Cuadernos Jupyter con el pipeline completo: preprocesamiento, análisis exploratorio, entrenamiento de los 63 modelos (3 escenarios × 3 estrategias × 7 algoritmos), evaluación e interpretabilidad clínica con SHAP y DALEX.

- TFG-Experimentación.ipynb 
- TFG-Experimentación.html
  
### Datos suplementarios

- Anexo I. Fundamentos teóricos de los algoritmos de Machine Learning utilizados.
- Anexo II. Contenido adicional de la experimentación.
- Anexo III. Declaración de uso de herramientas de Inteligencia Artificial.
- Imágenes: Figuras generadas durante el análisis exploratorio y el entrenamiento de modelos.

## Dataset

**Debernardi et al. (2020)** — *A combination of urinary biomarker panel and PancRISK score for earlier detection of pancreatic cancer: A case-control study*. PLoS Medicine, 17(12).  
Disponible en: [Kaggle — Urinary Biomarkers for Pancreatic Cancer](https://www.kaggle.com/datasets/johnjdavisiv/urinary-biomarkers-for-pancreatic-cancer)


## Tecnologías utilizadas

- **Python 3.12** · Jupyter Notebook · Kaggle
- `scikit-learn` · `xgboost` · `pandas` · `numpy`
- `matplotlib` · `seaborn`
- `shap` · `dalex`


## Cómo ejecutar

1. Abre los notebooks en [Kaggle](https://www.kaggle.com/) o en local con Jupyter
2. Añade el dataset de Debernardi et al. desde Kaggle como input
3. Para DALEX, instala las dependencias sin internet:
```python
!pip install /kaggle/input/dalex/dalex-1.8.0-py3-none-any.whl
!pip install /kaggle/input/plotly-pack/plotly-6.7.0-py3-none-any.whl
```
4. Ejecuta las celdas en orden desde la primera

