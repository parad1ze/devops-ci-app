# devops-ci-app

Сделайте обязательными lint, test и image для main. Для анонимной загрузки на VM откройте публичный доступ на странице пакета GHCR. В PR выполняются проверки, публикация разрешена только при push в main.

GET /health возвращает status=ok.

Gunicorn запускает приложение из app.app:app.
