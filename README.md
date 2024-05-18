<h2>UI Автотесты на фреймворке Cypress/h2>

> **Статус проекта:**
>
> 🟢 Поддерживается (активный) 

## Цели и Задачи
Автоматизировать часть проверок регресса с помощью Cypress

## 🖼 Скриншоты

Стартовое меню:

![image](https://raw.githubusercontent.com/German-D/tg_credit_cards/main/bot_menu.png)

После выбора карты Visa:

![image](https://raw.githubusercontent.com/German-D/tg_credit_cards/main/visa_card.png)


## 💻 Технологии

* Python 2.0
* Библиотека `telebot`
* Библиотека `faker`

## ⏬ Установка на локальном компьютере

Клонируем удалённый репозиторий на локальную машину:

```markdown
git clone git@github.com:German-D/tg_credit_cards.git
```
Создать бота и через [@BotFather](https://t.me/BotFather) и вставить в проекте свой токен от бота

Создаём виртуальное окружение внутри папки проекта.
Далее команды для MacOS (для windows инуструкция [есть вот тут](https://realpython.com/python-virtual-environments-a-primer/#create-it))

``` markdown
python3 -m venv venv
```

``` markdown
source venv/bin/activate
```

``` markdown
source venv/bin/activate
```
Устанавливаем библиотеки

``` markdown
python3 -m pip install pyTelegramBotAPI
```

``` markdown
python3 -m pip install faker
```

Запускаем
``` markdown
python3 card_bot.py
```

## Автор

Дольников Герман (Телеграм @dolnikov)
