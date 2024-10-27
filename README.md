# Бот-стартер Telegram основан на [grammY](https://grammy.dev)
### Форк [Borodutch - telegram-bot-starter](https://github.com/Borodutch/telegram-bot-starter)

Пожалуйста, насладитесь этим стартовым шаблоном для ботов Telegram, основанным на [grammY](https://grammy.dev). Он включает в себя наиболее распространенные промежуточные модули, интеграцию с MariaBD, выбор языка и интернационализацию

# Установка и локальный запуск

1. Клонируйте это репо: `git clone https://github.com/WEBzaytsev/tg-bot-starter`.
2. Запустите [базу данных mariadb (mysql)](https://mariadb.com) локально, например с помощью docker - [linuxserver/mariadb](https://hub.docker.com/r/linuxserver/mariadb 'linuxserver/mariadb').
3. Создайте `.env` с переменными окружения, перечисленными ниже
4. Запустите `yarn` в корневой папке
5. Запустите `yarn dev`.

И вы можете приступать к работе! Не стесняйтесь делать форки и отправлять запросы на исправление. Спасибо!

# Переменные окружения

- `TOKEN` - токен бота Telegram
- `DB_HOST` - URL базы данных mariadb, поддерживает нейминг docker compose, например umnichka_db
- `DB_PORT` - Порт базы данных mariadb
- `DB_NAME` - Имя базы данных mariadb
- `DB_USER` - Имя пользователя базы данных mariadb
- `DB_PASSWORD` - Пароль пользователя базы данных mariadb
- `OPENAI_API_KEY` - API ключ OpenAI
- `OPENAI_BASE_URL` - Базовый URL OpenAI
- `OPENAI_MODEL` - Модель OpenAI
- `MAX_TOKENS` - Максимальное количество токенов

Также, пожалуйста, ознакомьтесь с `.env.sample`.

# Лицензия

MIT — используйте для любой цели. Будет здорово, если вы сможете оставить ссылку на оригинальных разработчиков. Спасибо!
