# PROJECT_MAP.md — корень GitHub Pages

## Обзор

- **Назначение:** ответ `200 OK` на `https://antonovvladimirchebara-debug.github.io/` для Яндекс Вебмастер (метатег) и редирект посетителей на блог.
- **Стек:** статический HTML, GitHub Pages.
- **Связанный проект:** [moex-oi-analyst](https://github.com/antonovvladimirchebara-debug/moex-oi-analyst) — основной блог по пути `/moex-oi-analyst/`.

## Файлы

| Файл | Назначение |
|------|------------|
| `index.html` | `yandex-verification`, meta refresh на блог |
| `robots.txt` | `Sitemap:` на карту сайта блога `/moex-oi-analyst/sitemap.xml` |
| `README.md` | Краткое описание репозитория |

## Команды

```bash
cd /home/vladi/projects/antonovvladimirchebara-debug.github.io
git add -A && git commit -m "chore: ..." && git push origin main
```

## Хронология

| Дата | Коммит | Описание |
|------|--------|----------|
| 2026-04-01 | 98485a3 | Первый коммит: index + README |
| 2026-04-01 | 24ccf62 | docs: PROJECT_MAP.md |
| 2026-04-01 | 2328011 | feat: robots.txt с Sitemap на блог |

## Текущее состояние

- Pages: ветка `main`, корень `/`, URL <https://antonovvladimirchebara-debug.github.io/>
- `robots.txt` отдаётся с корня и указывает на sitemap блога (дополнительно к отправке sitemap в консолях поиска).
