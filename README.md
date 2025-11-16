Структура таблицы
Поле	Тип	Описание
id	INT AUTO_INCREMENT	Уникальный ID (автоинкремент)
name	VARCHAR(255)	Название организации
city	VARCHAR(100)	Город
type	VARCHAR(50)	Тип НКО (ано, фонды, etc)
description	TEXT	Описание деятельности
address	TEXT	Физический адрес
phone	VARCHAR(50)	Телефон
email	VARCHAR(100)	Email
website	VARCHAR(255)	Сайт
latitude	DECIMAL(10,8)	Широта для карты
longitude	DECIMAL(11,8)	Долгота для карты
photo_url	VARCHAR(500)	Ссылка на фото
is_active	BOOLEAN	Активна ли организация
created_at	TIMESTAMP	Дата создания
updated_at	TIMESTAMP	Дата обновления
