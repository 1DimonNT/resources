# Название проекта

Краткое описание проекта.

## Технологии
- Python 3.12+
- pytest
- selenium
- allure

## Установка

```bash
git clone https://github.com/1DimonNT/название-проекта.git
cd название-проекта
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## Запуск тестов

```bash
pytest tests/ -v --alluredir=allure-results
allure serve allure-results
```

## Лицензия
MIT
