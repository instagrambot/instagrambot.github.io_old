---
layout: post
title: "Installation on Windows"
date: 2017-10-13 23:29:00 +0900
tags: blog
comments: false
lang: ukr
---
#Інструкція по установці на Windows

**Важливо! Прочитайте інструкцію від початку до кінця, а потім дійте! Хай щастить!**

## Установка Python 3

1. Перейдіть на сайт [Python](https://www.python.org/downloads/).
2. Виберіть відповідну вам версію (залежить від операційної системи).
3. Скачайте.
4. Запустіть інсталятор.
5. Дотримуйтесь інструкції, яку пропонує вам установник. Поставте галочку на "Add Python 3.x to Path" і натисніть на Install Now (дивіться малюнок нижче). Якщо ви досвідчений користувач, виберіть Customize installation.
![Install Python 3 and add to PATH](/assets/install_python_on_Windows.PNG "Install Python 3 and add to PATH")

##Завантаження проекту з GitHub

Є два варіанти скачування проекту:

a) Перейдіть по посиланню https://github.com/instagrambot/instabot. Натисніть на "Clone or download", а потім на "Download ZIP". Розпакуйте.

b) Установка клієнта Git:
1. Перейдіть на сайт [Git](https://git-scm.com/downloads).
2. Виберіть відповідну вам версію (залежить від операційної системи).
3. Скачайте.
4. Запустіть інсталятор.
5. Дотримуйтесь інструкції, яку пропонує вам установник (натискайте на Next). Можете налаштувати клієнт самостійно, якщо ви - досвідчений користувач.
6. Після установки запустіть командний рядок.
7. У командному рядку наберіть.
``` python
git clone https://github.com/instagrambot/instabot
```
і натисніть на Enter.

*** Вітаю! Ви завантажили проект! ***

## Установка instabot у віртуальне оточення Python

У командному рядку наберіть.
``` python
pip install -U instabot
```
і натисніть Enter.