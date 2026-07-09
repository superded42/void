---
title: Установка Git. Регистрация в GitHub
unlisted: true
---
# Что такое Git?
Git - система контроля версий, которая позволяет отслеживать изменения в файлах и работать совместно

---
# Git на Linux (пример Arch Linux):
1. Установка Git:
```bash
sudo pacman -S git
```
2. Проверка установки:
```bash
git --version
```
3. Имя и email:
```bash
git config --global user.name "Введи имя"
git config --global user.email "Введи почту"
```
# Git на Windows:
1. Скачать установщик с официального сайта Git: https://git-scm.com/download/win
2. Инструкции установщика можно оставить по умолчанию, но лучше обратить внимание на следующие пункты:
   
   - **Select Components**: оставить все галочки.
   - **Choosing the default editor**: выбрать редактор по умолчанию (рекомендуется **Vim** или **Nano**).
   - **Adjusting your PATH environment**: выбрать **«Git from the command line and also from 3rd-party software»** (рекомендуется).
   - **Choosing HTTPS transport backend**: оставить **«Use the OpenSSL library»**.
   - **Configuring the line ending conversions**: выбрать **«Checkout Windows-style, commit Unix-style line endings»** (рекомендуется).
   - **Choosing terminal emulator**: выбрать **«Use MinTTY»** (рекомендуется).
   
3. Проверить установку:
```
git --version
```
4. Имя и email:
```
git config --global user.name "Введи имя"
git config --global user.email "Введи email"
```

---
# Что такое GitHub?
GitHub - это веб-сервис для хранения, управления и совместной разработки кода, основанный на системе контроля версий Git.
# Впервые на GitHub?
1. Регистрация:
   - https://github.com.
   - Sign up (в правом верхнем углу).
2. Дождаться выдачи прав коллаборатора от автора репозитория
3. Уведомление придет на почту или на GitHub 

## [Первые шаги в Git](./first-git.md)