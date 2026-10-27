# NovarixNetwork — Industrial 1.7.10

Структура:
- server/    папка сервера (ядро Thermos, моды, плагины)
- launcher/  Gravit Launcher (LaunchServer)
- website/   главная страница сайта (index.html)
- database/  скрипт создания базы MySQL

## Порядок запуска
1. Скачай ядро Thermos 1.7.10 (GitHub, репозиторий CyberdyneCC/Thermos, Releases), положи в server/ и назови thermos.jar.
2. Запусти server/start.bat. Он остановится с сообщением про EULA. Прочитай условия Mojang, и если согласен, создай eula.txt со строкой: eula=true
3. Запусти start.bat ещё раз, дождись Done, введи stop.
4. Скачай моды из server/mods/MODS.txt (CurseForge или страницы авторов) в server/mods, плагины из server/plugins/PLUGINS.txt в server/plugins.
5. Запусти сервер, зайди клиентом 1.7.10 по адресу localhost. Если в логе есть ошибки, пришли мне лог.
6. Установи MySQL (или Laragon), выполни database/create-db.sql и поменяй пароль в нём.
7. Поставь Gravit Launcher по его документации в папку launcher/ (раздел launcher/README.md).
8. Открой website/index.html в браузере, чтобы посмотреть сайт. Позже сайт можно перенести в Azuriom как тему.

Скачивай всё только с официальных страниц.
