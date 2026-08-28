# Machine Learning Projects

Репозиторий с проектами по машинному обучению: от подготовки и исследования данных до обучения, сравнения и оценки моделей.

## Проекты

### 1) Moscow Real Estate Analysis

- Анализ рынка недвижимости Москвы и прогнозирование стоимости продажи и аренды квартир.
- EDA, предобработка данных, feature engineering, географические признаки OpenStreetMap и сравнение различных моделей регрессии.
- Модели: Ridge, KNN, Decision Tree, Random Forest, Gradient Boosting, SVR и MLP.
- Файл: `projects/Moscow real estate analysis/moscow_real_estate_analysis.ipynb`
- Подробнее: `projects/Moscow real estate analysis/README.md`

### 2) Penguin Species Classification with KNN

- Классификация видов пингвинов по физическим характеристикам.
- Масштабирование признаков, сравнение разных значений `k`, визуализация решающих границ и собственная реализация KNN.
- Модель: K-Nearest Neighbors.
- Файл: `projects/Penguin species classification with KNN/penguin_knn_classification.ipynb`
- Подробнее: `projects/Penguin species classification with KNN/README.md`

### 3) Diamond Price Prediction

- Прогнозирование стоимости бриллиантов по их физическим и категориальным характеристикам.
- Анализ корреляций, One-Hot Encoding, масштабирование и сравнение линейной модели с L1/L2 регуляризацией.
- Модели: Linear Regression, Ridge и Lasso.
- Файл: `projects/Diamond price prediction/diamond_price_prediction.ipynb`
- Подробнее: `projects/Diamond price prediction/README.md`

### 4) Linear Regression and Gradient Descent from Scratch

- Реализация линейной регрессии и градиентной оптимизации с нуля на NumPy.
- Gradient Descent, Mini-batch SGD, затухающий learning rate, L2 регуляризация и Huber Loss.
- Собственная модель применяется к прогнозированию стоимости автомобилей.
- Файл: `projects/Linear regression and gradient descent from scratch/linear_regression_gradient_descent.ipynb`
- Подробнее: `projects/Linear regression and gradient descent from scratch/README.md`


### 5) Tweet Sentiment Classification

- Бинарная классификация тональности твитов о коронавирусе.
- Собственный tokenizer, CountVectorizer, TF-IDF, stemming и фильтрация редких токенов.
- Модель: Logistic Regression.
- Лучший test accuracy среди проверенных вариантов: около `0.868`.
- Файл: `projects/Tweet sentiment classification/tweet_sentiment_classification.ipynb`
- Подробнее: `projects/Tweet sentiment classification/README.md`

## Структура репозитория

```text
│   README.md
│   requirements.txt
│
└───projects
    ├───Moscow real estate analysis
    │       moscow_real_estate_analysis.ipynb
    │       README.md
    │
    ├───Penguin species classification with KNN
    │       penguin_knn_classification.ipynb
    │       README.md
    │
    ├───Diamond price prediction
    │       diamond_price_prediction.ipynb
    │       README.md
    │
    ├───Linear regression and gradient descent from scratch
    │       linear_regression_gradient_descent.ipynb
    │       README.md
    │
    └───Tweet sentiment classification
            tweet_sentiment_classification.ipynb
            README.md
```

Каждый проект находится в отдельной директории и содержит собственный README с описанием задачи, данных, использованных методов и полученных результатов.

## Как запустить локально

1. Установить необходимые зависимости:

```bash
pip install -r requirements.txt
```

2. Открыть notebook нужного проекта в Jupyter Notebook, JupyterLab или другой совместимой среде.
