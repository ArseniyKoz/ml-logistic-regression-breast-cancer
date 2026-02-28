# Классификация Breast Cancer: Logistic Regression

Pet-проект по бинарной классификации с ROC/PR-анализом и матрицей ошибок.

## Что сделано

- Обучение логистической регрессии на `load_breast_cancer`.
- Оценка ROC-AUC и PR-кривых.
- Анализ качества через confusion matrix.

## Стек

- Python
- NumPy
- scikit-learn
- Matplotlib
- Jupyter Notebook

## Как запустить

```bash
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook practice_4.ipynb
```

## Результаты

Собран полный цикл классификации: подготовка, обучение, оценка, визуализация метрик.

## Чему научился

- Сравнивать ROC и PR для дисбалансных классов.
- Интерпретировать пороговые решения модели.

## Ограничения и что улучшить

- Добавить подбор порога и сравнение с деревьями/ансамблями.

## Автор

Арсений Козлов - [github.com/ArseniyKoz](https://github.com/ArseniyKoz)


