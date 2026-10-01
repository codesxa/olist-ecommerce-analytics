# Olist E-Commerce Analytics

Аналитический проект на реалистичном e-commerce датасете по мотивам [Olist (бразильский маркетплейс)](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce).

## Стек технологий

- **Python 3.12+**, **Pandas**, **NumPy**
- **SQLAlchemy**
- **Seaborn** / **Matplotlib** для визуализации
- **SciPy** для статистических тестов
- **Poetry** для управления зависимостями

## Как запустить

```bash
# Установка Poetry
pip install poetry

# Клонирование и переход в проект
git clone https://github.com/codesxa/olist-ecommerce-analytics.git
cd olist-ecommerce-analytics

# Установка зависимостей
poetry install

# Запуск Jupyter
poetry run jupyter notebook
```

## Структура проекта
```text
olist-ecommerce-analytics/
├── notebooks/     # Jupyter-ноутбуки с анализом
├── src/           # Переиспользуемые Python-модули
├── data/          # Данные о продажах
├── images/        # Изображения для README
└── reports/       # Итоговые отчёты
```
