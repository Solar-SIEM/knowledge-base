# Solar SIEM Knowledge Base

База знаний Solar SIEM на MkDocs + Material, публикуется на GitHub Pages.

## Локальный запуск

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
mkdocs serve
```

Сайт будет доступен на http://127.0.0.1:8000

## Публикация

Пуш в ветку `main` автоматически собирает и деплоит сайт на GitHub Pages
(см. `.github/workflows/deploy.yml`).

Перед первым деплоем включите GitHub Pages в настройках репозитория:
Settings → Pages → Source → Deploy from a branch → `gh-pages` / `root`.

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
