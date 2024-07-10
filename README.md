# casino_telegram_bot
Casino bot in Telegram messenger with support for many modes and rich functionality.
---
Installation requires:
* Install dependencies: ``pip install -r requirements.txt ``
* create a *logo.gif* of the casino logo and add it to the root directory of the project
* create the necessary chats and channels
* fill in constants in files *_main.py_*,*_sql.py_*,*_key_board.py_*
* create a session for the tg account from which the cryptocurrencies will be activated
---
The functionality of the project:
* Replenishment via cryptocurrencies of such exchanges as Bitpapa, Bitzlato, Cryptobot
* Replenishment via Qiwi, as well as through direct cryptocurrency transfers
* The withdrawal is made manually, after receiving the request in the appropriate channel
* Modes:
* * 21 (points) for 2-6 players among themselves and for 1 player from the casino (there is support for private and open rooms)
* * solo games: dice, basketball, darts,... _(supported both in chat and in personal chat with a bot)_
* * multiplayer mode: the same That solo, only in the chat between the players and wins then
---
Казино бот в мессенджере Телеграм с поддержкой многих режимов и богатым функционалом.
---
Для установки требуется:
* Установить зависимости: ```pip install -r requirements.txt```
* создать *logo.gif* - лого казино и добавить в корневой каталог проекта
* создать необходимые чаты и каналы
* заполнить константы в файлах *main.py*,*sql.py*,*key_board.py*
* создать сессию для тг аккаунта, с которого будут активироваться крипточеки
---
Функционал проекта:
* Пополнение через крипточеки таких бирж, как Bitpapa, Bitzlato, Cryptobot
* Пополнение через Qiwi, а также через прямые переводы криптовалюты
* Вывод совершается в ручном виде, после получения заявки в соответствующем канале
* Режимы:
* * 21(очко) для 2-6 игроков между собой и для 1 игрока с казино(есть поддержка приватных и открытых комнат)
* * соло игры: кубик, баскетбол, дартс,... _(поддерживаются как в чате, так и в личном чате с ботом)_
* * многопользовательский режим: тоже самое, что соло, только в чате между игроками и выигрывает тот, кто набрал больше очков(если победителей несколько, то для них создается ещё одна игра) _(поддерживается открытый режим и закрытый, когда вход в игру только по паролю)_
* Чаты могут стать партнерами, тогда они будут получать % с депозитов клиентов, которые пришли из их чата
* Также есть реферальная система для самих клиентов
* Возможность пересылать между профилями деньги, благодаря системе промокодов
