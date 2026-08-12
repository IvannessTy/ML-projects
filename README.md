# Machine Learning Projects

Репозиторий с проектами по машинному обучению: от подготовки и исследования данных до обучения, сравнения и оценки моделей.

## Проекты

### 1) Moscow Real Estate Analysis

- Анализ рынка недвижимости Москвы и прогнозирование стоимости продажи и аренды квартир.
- EDA, предобработка данных, feature engineering, географические признаки OpenStreetMap и сравнение различных моделей регрессии.
- Модели: Ridge, KNN, Decision Tree, Random Forest, Gradient Boosting, SVR и MLP.
- Файл: `projects/Moscow real estate analysis/moscow_real_estate_analysis.ipynb`
- Подробнее: `projects/Moscow real estate analysis/README.md`

## Структура репозитория

```text
│   README.md
│   requirements.txt
│
└───projects
    └───Moscow real estate analysis
            moscow_real_estate_analysis.ipynb
            README.md
```

Каждый проект находится в отдельной директории и содержит собственный README с описанием задачи, данных, использованных методов и полученных результатов.

## Как запустить локально

1. Установить необходимые зависимости:

```bash
pip install -r requirements.txt
```

2. Открыть notebook нужного проекта в Jupyter Notebook, JupyterLab или другой совместимой среде.