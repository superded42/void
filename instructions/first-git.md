---
title: Первые шаги в Git
---
# Как начать?

1. **Клон репозитория:**
```
git clone https://github.com/superded42/void.git
cd chest
npm install # Установка зависимостей проекта
npx quartz plugin install
```

Для `npm install` требуется `Node.js`, если его нет, то:

**Linux:**
```bash
sudo pacman -S nodejs npm
```

**Windows:**
- https://nodejs.org/
- Скачать LTS-версию или Current(22.x)
- Запустить установщик `.msi`, следовать инструкциям по умолчанию
- Перезапустить терминал, проверить версии:
```
node -v
npm -v
```

2. **Настройка удаленного доступа для пуша:**
   При первом пуше Git попросит логин и пароль на GitHub. В качестве пароля нельзя использовать свой обычный пароль - необходимо использовать токен (Personal Access Token). 
   **Как создать токен:**
   - Setting -> Developer settings -> Personal access tokens -> Tokens(classic).
   - Generate new token(classic).
   - Имя, срок действия (90 дней)
   - Отметить **repo**
   - Generate token
   - **Сразу скопировать и сохранить токен - он показывается лишь один раз**

3. **Указать время кэширования токена в git:**
```
git config --global credential.helper 'cache --timeout=3600' # 3600 секунд, можно поставить на свое усмотрение 
```
### [Публикация изменений](./push-newsynopsis.md)