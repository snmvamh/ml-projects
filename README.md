# ML Projects

Сборник учебных и практических проектов по машинному обучению (курс Machine Learning, DSBA/ICEF, НИУ ВШЭ, 2025/2026), а также самостоятельных экспериментов.

Каждый ноутбук — отдельная задача: от разведочного анализа данных до обучения и оценки моделей.

## Проекты

| Ноутбук | Задача | Основные инструменты |
|---|---|---|
| `notebooks/PandasMatplotlibML.ipynb` | Практика анализа и визуализации данных | pandas, matplotlib, seaborn |
| `notebooks/LinearRegressionKNN.ipynb` | Линейная регрессия и k-ближайших соседей | scikit-learn, seaborn |
| `notebooks/LinearModelsML.ipynb` | Линейные модели (теория и практика) | scikit-learn |
| `notebooks/TreesRandomForestML.ipynb` | Решающие деревья и случайный лес | scikit-learn, matplotlib |
| `notebooks/BacteriaML.ipynb` | Классификация (bacteria dataset) | scikit-learn, numpy |
| `notebooks/StellarML.ipynb` | Классификация астрономических объектов | scikit-learn, numpy |
| `notebooks/PhonemesML.ipynb` | Классификация фонем | scikit-learn, pandas |
| `notebooks/RecognizerML.ipynb` | Задача распознавания | scikit-learn, pandas |
| `notebooks/GenomicsML.ipynb` | ML на геномных данных с эмбеддингами | scikit-learn, sentence-transformers |
| `notebooks/G_ood_girlsHW🚗Auto.ipynb` | Регрессия на данных об автомобилях | scikit-learn, pandas |

## Структура

```
ml-projects/
├── notebooks/   # Jupyter-ноутбуки с проектами
├── src/         # переиспользуемый код (при необходимости)
├── data/        # локальные данные (не коммитятся)
├── models/      # сохранённые модели (не коммитятся)
└── README.md
```

## Стек

Python, NumPy, pandas, scikit-learn, matplotlib, seaborn.

## Как запустить

Ноутбуки открываются в Jupyter или Google Colab. Для локального запуска:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn
jupyter notebook
```
