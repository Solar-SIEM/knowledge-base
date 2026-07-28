# Solar SIEM Knowledge Base

База знаний Solar SIEM — справочный ресурс по продукту, который описывает возможности системы, процессы сбора событий, детектирования угроз и реагирования на инциденты. Она помогает пользователям и специалистам по безопасности быстрее разбираться в работе Solar SIEM и находить готовые сценарии для решения типовых задач.

🔗 Сайт: https://solar-siem.github.io/knowledge-base/

## Локальный запуск

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
mkdocs serve
```

Сайт будет доступен на http://127.0.0.1:8000

## Структура

```
docs/
  index.md
  getting-started/
  detections/
  playbooks/
mkdocs.yml
requirements.txt
```
