# MarkWell Brand System & Project Context

Единый репозиторий контекста проекта MarkWell: бренд, сайт, визуальная система, брошюры, продуктовые материалы, roadmap и правила работы с AI.

## Роль репозитория

Source of truth для всех новых чатов, задач, дизайнеров, разработчиков и подрядчиков по MarkWell.

Главная идея: **MarkWell продаёт не просто вытяжку, а новый стандарт рабочего пространства мастера: чистота, контроль пыли, комфорт, эстетика, технологичность и забота о здоровье.**

## Как работать с ChatGPT

В начале нового чата можно писать:

```txt
Открой актуальный контекст MarkWell из репозитория и работай по нему. Главный вход: docs/00_PROJECT_INDEX.md и config/AI_CONTEXT_PROMPT.md.
```

После важных решений обновлять:

- `docs/CHANGELOG_CONTEXT.md`
- `docs/07_OPEN_QUESTIONS.md`
- `tasks/ROADMAP.md`

В память ChatGPT сохранять только устойчивые факты по явной команде: **«запиши в память»**.

## Структура

```txt
config/
  AI_CONTEXT_PROMPT.md
  markwell.project.config.json
docs/
  00_PROJECT_INDEX.md
  01_BRAND_CONTEXT.md
  02_VISUAL_SYSTEM.md
  03_WEBSITE_AUDIT.md
  04_SITE_STRUCTURE_TZ.md
  05_BROCHURE_TZ.md
  06_ASSET_AUDIT.md
  07_OPEN_QUESTIONS.md
  CHANGELOG_CONTEXT.md
tasks/
  ROADMAP.md
.github/
  ISSUE_TEMPLATE/task.md
```

## Источники первичного контекста

- Текущий сайт: `https://markwell.online/`
- PDF-ТЗ по сайту: `Сайт MarkWell.pdf`
- Расширенное PDF-ТЗ по сайту: `Сайт MarkWell (1).pdf`
- PDF-ТЗ по брошюре: `Брошюра MarkWell.pdf`
- Загруженные изображения и рендеры из проекта ChatGPT.

## Статус

`v0.1` — первичная база проекта: аудит, структура сайта, визуальная система, брошюра, roadmap, открытые вопросы и правила ведения контекста.
