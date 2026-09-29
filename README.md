# Автотесты интернет-магазина на Page Object

Финальный проект курса [«Автоматизация тестирования с помощью Selenium и Python»](https://stepik.org/course/575): автотесты для учебного интернет-магазина [selenium1py.pythonanywhere.com](http://selenium1py.pythonanywhere.com/), написанные с помощью паттерна Page Object.

## Запуск

```bash
pip install -r requirements.txt
pytest -v --tb=line --language=en test_main_page.py
```

Параметр `--language` задаёт язык интерфейса (по умолчанию `en`).
