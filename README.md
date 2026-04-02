# Assets

Центральное хранилище для ресурсов, логотипов и шаблонов.

## Структура

```
assets/
├── images/           # логотипы и картинки
│   ├── uspu-logo.png
│   └── qaguru-logo.svg
├── templates/        # шаблоны для проектов
│   ├── .gitignore
│   ├── README.md
│   ├── pytest.ini
│   └── conftest.py
└── .github/
    └── workflows/
        └── sync.yml
```

## Использование в README профиля

```markdown
<img src="https://raw.githubusercontent.com/1DimonNT/assets/main/images/uspu-logo.png" width="120" />
<img src="https://raw.githubusercontent.com/1DimonNT/assets/main/images/qaguru-logo.svg" width="120" />
```

## Шаблоны для новых проектов

При создании нового проекта используйте файлы из папки `templates/`:
- `.gitignore` — готовый для Python
- `README.md` — шаблон описания проекта
- `pytest.ini` — конфигурация pytest
- `conftest.py` — базовая фикстура с Selenoid
