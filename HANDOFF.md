# HANDOFF — rclone-server-app

_Обновлено: 2026-10-31 · ветка: `main`_

## Кратко
Статические страницы (главная + privacy policy) для OAuth-приложения Google «rclone-server» (проект GCP rclone-server), публикуются через GitHub Pages из `main` (корень).

## Что сделано
- [2026-10-31] index.html, privacy.html, .nojekyll; включены GitHub Pages.

## Что дальше
1. [ ] Указать URL главной и политики в Google Cloud Console → OAuth consent screen / Branding, добавить домен `denysnew.github.io` в Authorized domains.
2. [ ] Перевести приложение в Production; создать OAuth client (Desktop) и переподключить rclone `gdrive` со своим client_id.

## Принятые решения
- Репозиторий публичный — GitHub Pages на бесплатном плане работает только для публичных.
- Контакт — ссылка на GitHub-профиль, без email.

## Состояние кода
Чистый статический HTML, сборки нет. Секретов в репозитории нет и быть не должно.
