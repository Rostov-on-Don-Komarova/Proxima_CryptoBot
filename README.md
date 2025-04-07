Проект «Крипто-бот»
-
Состав: Комарова Алёна, Шарков Владимир
-
Описание проекта: Proxima CryptoBot – простой, но достаточно функциональный Телеграм-бот. Его возможности:
Конвертация 6 различных валют;
Конвертация 6 различных криптовалют;
Запрос и сохранение данных о пользователе (его никнейм, id в телеграмм и (позже подумаю как это реализовать) часовой пояс).
-
Работа:  
1) Пользователь по желанию регистрируется.
2) Данные сохраняются в базу данных.
3) Бот готов к работе!
-
Технологии:
Работа с Телеграм: pyTelegramBotAPI (telebot)
База данных: sqlite3
Бэкенд: datetime, requests
Необходимое API: Binance API, ExchangeRate API
-
Зоны ответственности*: 
Алёна – работа с БД, работа с datetime, обработка ответов серверов API (работа с requests)
Владимир – обработка сообщений пользователя, отправка сообщений-ответов пользователю 



*Зоны отвственности могут изменяться


Цель проекта «Крипто-бот», его функционал и особенности.
-
Создать Телеграм-бота, конвертирующего курсы валют и криптовалют, а также способного симулировать покупку и продажу пользователем валют и криптовалют. 

Функционал
-
•	Регистрация пользователя и сохранение данных в БД (ник, часовой пояс, id в Телеграмм)
С помощью определенной команды пользователь сможет пройти регистрацию и пользоваться возможностями бота в полном объёме

•	Конвертация курсов
Актуальную информацию можно получить с помощью надежного API

•	Симуляция покупки и продажи активов (исключительно как игра)
В базе данных будет храниться информация о виртуальном балансе пользователя, которым сам пользователь будет управлять с помощью интуитивно понятных команд

Самая важная часть проекта – работа с БД. Однако есть множество других аспектов работы над этим проектом - например, работа с API и Телеграмм. 
Конечный результат можно будет использовать как игру, в которой можно почувствовать себя криптотрейдером. Но этот бот модет помогать и настоящим криптотрейдерам всегда знать самый свежий курс своих активов.

