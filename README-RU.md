# Европа лето 2026 — фронтенд для GitHub Pages

Это статический PWA-сайт по финальным файлам маршрута:

- `Маршрут_Европа_2026_финал.html`
- `Маршрут_Европа_2026_подробный_финал.md`

Для деплоя на GitHub Pages загрузите содержимое этой папки:

- `index.html`
- `data.js`
- `config.js`
- `manifest.webmanifest`
- `sw.js`
- `icon-192.png`
- `icon-512.png`

## Что ещё нужно сделать

1. Развернуть backend из второй папки на Vercel.
2. После деплоя backend открыть `config.js` и вставить URL вида:
   `https://ВАШ-ПРОЕКТ.vercel.app/api/concierge`
3. Закоммитить изменения в GitHub Pages-репозиторий.

## Если сайт показывает старую версию

Сделайте hard refresh или очистите service worker-кеш в Safari/Chrome.
