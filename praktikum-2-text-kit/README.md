# text-kit

Учебный проект: набор функций для работы со строками, датами, числами
и проверки данных. Точка запуска — `app/main.py`.

## Дерево проекта
text-kit/
├── app/
│ ├── init.py
│ ├── main.py — точка запуска: константы, main(), вызов
│ ├── utils/
│ │ ├── init.py
│ │ ├── text.py — clean_spaces, shorten, initials, slug
│ │ └── dates.py — parse_date, format_date, is_weekend, days_between
│ └── services/
│ ├── init.py
│ ├── statistics.py — average, median, spread, count_values
│ └── validation.py — is_email, normalize_phone, is_phone, password_problems
├── tests/
│ ├── test_text.py
│ ├── test_dates.py
│ ├── test_statistics.py
│ └── test_validation.py
└── README.md

