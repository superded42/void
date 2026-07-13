---
title: Сливание новой ветки с основной
---
# Чтобы слить новую ветку с основной нужно:

## I. Создание Pull Request на GitHub
### Вариант А: интерфейс GitHub
1. После пуша новой ветки зайди в репозиторий:
   https://github.com/superded42/void
2. Pull request -> New pull request 
3. Выбор:
   * base: `v5`
   * compare: `newbranch/mechanics`
4. Заголовок и описание
5. `Create pull request` 
### Вариант Б: Через GitHub CLI
```bash
gh pr create --base v5 --head newbranch/mechanics --title "Добавлен новый конспект" --body "Описание изменений"
```

---
## II. Слияние
1. Так как настроено **требование успешных проверок**, то необходимо дождаться, пока GitHub соберет сайт.
2. Ожидать, пока автор репозитория проверит изменения, после чего они будут запушены в основную ветку.
---
## III. Удаление ветки, если она слита:
```bash
git checkout v5
git branch -d newbranch/mechanics # удалить локальную ветку
```

Также ее можно удалить на GitHub в разделе Pull Request
   
---
## IV. Обновление  локальной `v5`
```bash
git checkout v5
git pull origin v5
```
