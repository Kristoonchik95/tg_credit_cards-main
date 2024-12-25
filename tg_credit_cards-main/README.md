<h2>Телеграм бот, который генерирует номера банковских карт</h2>

> **Статус проекта:**
>
> 🟢 Поддерживается (активный) 

## Цели и Задачи
Помочь QA инженеру быстро получить нужный номер карты при тестировании в тестовой среде.

Бот геренирует номера тестовых банковских карт:
* Номера карт проходят проверку на алгоритм Луна
* Можно получить номер карты: Visa, Maestro, Mastercard, JCB

## 🖼 Скриншоты

Стартовое меню:

![image](https://raw.githubusercontent.com/Kristoonchik95/tg_credit_cards-main/refs/heads/main/tg_credit_cards-main/static/menu.jpg)

После выбора карты JCB:

![image](https://raw.githubusercontent.com/Kristoonchik95/tg_credit_cards-main/refs/heads/main/tg_credit_cards-main/static/jcb.jpg)

Если текст не совпал ни с одной кнопкой:

![image](https://raw.githubusercontent.com/Kristoonchik95/tg_credit_cards-main/refs/heads/main/tg_credit_cards-main/static/error.jpg)


## 💻 Технологии

* Python
* Библиотека `telebot`
* Библиотека `faker`

## ⏬ Установка на локальном компьютере

1. Скачать проект
   
2. Создать бота и через [@BotFather](https://t.me/BotFather) и вставить в проекте свой токен от бота

3. Создаём виртуальное окружение внутри папки проекта.
Далее команды для MacOS (для windows инуструкция [есть вот тут](https://realpython.com/python-virtual-environments-a-primer/#create-it))

``` markdown
python3 -m venv venv
```

``` markdown
source venv/bin/activate
```
4. Устанавливаем библиотеки

``` markdown
python3 -m pip install pyTelegramBotAPI
```

``` markdown
python3 -m pip install faker
```

5. Запускаем
``` markdown
python3 card_bot.py
```

## Автор

Кристина Трофимова ([@TKris95](https://t.me/@TKris95))
