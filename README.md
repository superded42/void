#  VOID — цифровой склад с конспектами (форк Quartz)

Это **форк** генератора статических сайтов **[Quartz](https://github.com/jackyzha0/quartz).**

Готовый сайт доступен по адресу:

https://superded42.github.io/void

---

##  Структура папок (основные)

```
chest/
├── content/ # ← заметки 
│ ├── index.md # главная страница
│ ├── подраздел/
│ │ ├── index.md # страница раздела
│ │ └── конспект.md
│ └── ...
├── quartz/ # движок Quartz 
├── quartz.config.ts # конфигурация сайта
├── package.json # зависимости
└── .github/ # настройки GitHub Actions 
```


---

##  Важные замечания

- Основная благодарность автору [jackyzha0](https://github.com/jackyzha0). Все права на движок принадлежат ему.
- Лицензия: MIT (как и у оригинального Quartz).
