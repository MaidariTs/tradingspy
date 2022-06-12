# tradingspy
Telegram-bot.
### Описание
Telegram-bot, который отправляет изменение котировок "BTC-USD"с платформы Binance.
### Технологии
ccxt~=1.51.51
flake8==3.9.2
flake8-docstrings==1.6.0
pytest==6.2.5
python-dotenv==0.19.0
python-telegram-bot==13.7
requests==2.26.0
isort~=5.9.3
yapf~=0.31.0
### Запуск проекта в dev-режиме
- Установите и активируйте виртуальное окружение
- Установите зависимости из файла requirements.txt
```
pip install -r requirements.txt
``` 
- В папке с файлом manage.py выполните команду:
```
python manage.py runserver
```
### Для успешного функционирования бота
Необходимо доабвить в репозиторий папку ".env",
в которой указать свои переменные и их значения:
BINANCE_API_KEY
BINANCE_PRIVATE_KEY
BINANCE_MARKET_TYPE
TELEGRAM_TOKEN
TELEGRAM_CHAT_ID

### Авторы
Майдари
@maidaritsydenov
tmaidari@mail.ru