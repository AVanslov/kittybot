# Kittybot - телеграм бот, который отправляет свежие фотографии котиков

## О проекте

Телеграм бот был создан для тренировки работы с библиотекой python-telegram-bot.

## Языки и библиотеки
![Python](https://img.shields.io/badge/-Python-black?style=for-the-badge&logo=python)
![Telegram API](https://img.shields.io/badge/-python_telegram_bot-black?style=for-the-badge&logo=telegram)
![JSON](https://img.shields.io/badge/-JSON-black?style=for-the-badge&logo=JSON)
![OS](https://img.shields.io/badge/-.env-black?style=for-the-badge&logo=OS)

## Установка

***Клонировать репозиторий и перейти в него в командной строке:***

git clone 
cd kittybot
Cоздать и активировать виртуальное окружение:
```
git clone git@github.com:your_username_in_github/kittybot.git

Для Windows:
python -m venv venv
source venv/Script/activate

Для Linux/MacOS:
python3 -m venv venv
source venv/bin/activate
```
***Установить зависимости из файла requirements.txt:***

```
python -m pip install --upgrade pip
pip install -r requirements.txt
```

***Как заполнить .env:***

**TOKEN=** здесь впишите token, который вам отправит бот [BotFather](https://t.me/BotFather) после создания бота

**CHAT_ID=** можно получить у этого [бота](https://t.me/userinfobot) - значение id - это ваш chat_id 

## Запуск проекта

```
python3 kittybot.py
```

***Автор***
Бучельников Александр