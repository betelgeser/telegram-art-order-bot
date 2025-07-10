# telegram-art-order-bot
# Telegram Art Order Bot

Python-бот для Telegram, который собирает заявки на рисунки через пошаговый диалог и сохраняет их в Google Таблицу с использованием Sheets API.

## Возможности

- Взаимодействие с пользователем через Telegram
- Сбор информации: персонаж, тип рисунка, стиль, фон, наличие HP, дополнительные пожелания
- Расчёт стоимости заявки
- Сохранение данных в Google Sheets

## Технологии

- Python
- python-telegram-bot
- gspread
- oauth2client
- Google Sheets API

## Установка

1. Установите зависимости:
   ```bash
   pip install -r requirements.txt
Разместите файл credentials.json в корне проекта (не публикуйте его на GitHub).

Убедитесь, что сервисный аккаунт имеет доступ «Редактор» к вашей Google Таблице.

В файле art_bot.py:

Замените имя таблицы и листа на свои

Замените токен бота на ваш

Запустите:

bash
python art_bot.py
