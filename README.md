<h2>Телеграм бот, помогающий тестировщику сгенерировать файл</h2>

> **Статус проекта:**
>
> 🟢 Поддерживается (активный) 

## Цели и Задачи
* Бот принимает на входе тип и размер файла, а на выходе отдаёт сам файл.
* Это может пригодиться, когда на сайте есть ограничение на размер загрузки фото и нужно проверить граничные значения.

## 🖼 Скриншоты

Стартовое меню:

![image](https://raw.githubusercontent.com/Atamanenko-qa/Create_file_bot/refs/heads/main/Start_bot.png)

После выбора файла:

![image](https://raw.githubusercontent.com/Atamanenko-qa/Create_file_bot/refs/heads/main/Generation_bot.png)

## 💻 Технологии

* Python
* Библиотека `telebot`

## ⏬ Установка на локальном компьютере

1. Скачать проект

2. Создать бота и через [@BotFather](https://t.me/BotFather) и вставить в проекте свой токен от бота

3. Создаём виртуальное окружение внутри папки проекта.

``` markdown
python3 -m venv env
```
Где env — имя создаваемого виртуального окружения. Рекомендуется выбирать имя, которое отражает суть проекта.

Для MacOS:

``` markdown
source venv/bin/activate
```

Для Windows:

``` markdown
myenv\\Scripts\\activate
```


4. Устанавливаем библиотеки

``` markdown
python3 -m pip install pyTelegramBotAPI
```

5. Запускаем
``` markdown
python3 main.py
```

## Автор

Атаманенко Дмитрий ([@dmitry_atamanenko](https://t.me/dmitry_atamanenko))
