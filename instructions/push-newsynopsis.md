---
title: Публикация изменений
---
# Как публиковать изменения?
## Пошаговая инструкция:

 0. **Находясь в void/:**

 1. **Переключиться на v5 (основная ветка) и обновить ее:**
```bash
git checkout v5
git pull origin v5
```

2. **Создать новую ветку для изменений:**
  Название ветки должно отображать суть изменения:
```bash
git checkout -b newbranch/mechanics
```

3. **Добавить изменения в /content, пример:**
```bash
nano content/test/newsynopsis.md
```
Если изменения вносятся через [obsidian](./obsidian.md) , то нужно следить за названием ветки в правом нижнем углу.

4. **Коммит изменений:**
```bash
git add content/
git commit -m "Добавлен новый конспект по механике"
```

5. **Пуш ветки на GitHub:**
```bash
git push origin newbranch/mechanics
```
   Если ветка создана впервые, то Git предложить команду с -u:
```bash
git push -u origin newbranch/mechanics
```

6. **Далее необходимо [слить](./pull-request.md) новую ветку с основной веткой v5**.
