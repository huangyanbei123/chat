# Сайт с чатом

Этот пример - с одной стороны учебный, с другой - в нём реализованые важнейшие вещи, которые обычно требуются при разработке сайтов:

- Обычные страницы, которые проходят через роутер
- Шаблонизация EJS, (ejs-locals: partials, helpers, layouts)
- JSON-сервис (та же страница по сути)
- Авторизация (Express, Connect, MongoDB)
- Закрытая страница (`/chat`, требует авторизации)
- Чат при помощи Sock.JS, интеграция с авторизацией (можно использовать Socket.IO или ws.js)
- Работа с базой данных (MongoDB, Mongoose)
- Асинхронные цепочки вызовов (Async.js)
- Логирование (winston + фабрика логгеров по модулю)
- Кластеризация (общая архитектура подходит + clusterMaster по желанию)
- Архитектура пригодна для разработки и расширения

# Использование

1. `git clone`
2. `npm start`
3. `open http://127.0.0.1:3000`

Войти в сайт можно будет через ссылку "Войти" справа.

Выбирайте любое имя пользователя и пароль: если пользователя нет - он сгенерируется автоматом,
если такое имя уже есть, то соответствие пароля проверяется.