# WildPriceAlertBot

## Автор
- Анна Котова
- Telegram: @ankotova

##  Описание
Этот бот создан для отслеживания изменения цен товаров на сайте WILDBERRIES и отправки уведомлений пользователю. 
Бот регулярно проверяет текущие цены на указанные товары на Wildberries. Если цена товара изменяется, бот отправляет уведомление в Telegram. История цен: бот может хранить историю изменения цен для анализа и статистики. 

## Технологии
- Python 3.9.10
- Парсинг данных: Selenium, API Wildberries
- База данных: SQLite или PostgreSQL
- Уведомления: Python-telegram-bot


## Инструкция по запуску
Клонировать репозиторий и перейти в него в командной строке:
```
git clone git@github.com:AnnaKotovapr/WildPriceAlertBot.git
cd WildPriceAlertBot
```
Cоздать и активировать виртуальное окружение:
```
python -m venv env
source venv/Scripts/activate
```
Установить зависимости из файла requirements.txt:
```
pip install -r requirements.txt
