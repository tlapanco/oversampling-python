# Oversampling python 

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)

Este proyecto se aplican técnicas de sobremuestreo para la materia de Sistemas Inteligentes para la carrera de  Ingeniería en sistemas computacionales.

El [archivo](https://github.com/tlapanco/oversampling-python/blob/main/Prostate_Cancer.csv) utilizado para este trabajo, refleja los resultados de estudios sobre cancer de prostata en un formato de separación por comas, tomando en cuentas la columna `diagnosis_result` teniendo dos posibles valores `M` ó `B`

Resultados:

```bash
              precision    recall  f1-score   support

           B       0.88      0.70      0.78        10
           M       0.82      0.93      0.88        15

    accuracy                           0.84        25
   macro avg       0.85      0.82      0.83        25
weighted avg       0.84      0.84      0.84        25
```
