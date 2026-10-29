# Скворцов Александр — сайт-резюме

Сайт: https://skvortsov-alexander.github.io

Собран на шаблоне [Academic Pages](https://github.com/academicpages/academicpages.github.io) (Jekyll) и публикуется через GitHub Pages автоматически при каждом пуше в ветку `main`.

## Где что лежит

- `_pages/about.md` — главная страница: «Обо мне», ключевые результаты, навыки, образование
- `_pages/tochka.md` — опыт работы в Точка банке
- `_pages/tbank-bdm.md` — опыт работы в Т-банке
- `_data/navigation.yml` — меню «Опыт работы»
- `_config.yml` — имя, город, университет, почта в боковой панели
- `images/` — фото и логотипы

## Локальный запуск

```bash
bundle install
bundle exec jekyll serve
```

Затем откройте http://localhost:4000
