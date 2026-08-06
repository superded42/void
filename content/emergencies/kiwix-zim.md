---
title: Установка Kiwix. Создание .zim архива
unlisted: "true"
---
# KIWIX
**KIWIX** - оффлайн браузер, который читает файлы из сильносжатых архивов формата .zim
## Установка KIWIX
```
sudo pacman -S kiwix-desktop kiwix-tools
```
## Запуск KIWIX
```
kiwix-desktop
```
# zimwriterfs
**zimwriterfs** - программа для создания .zim архивов
## Установка zimwriterfs
```
sudo pacman -S zimwriterfs
```
## Доп. ImageMagick
**ImageMagick** - программа для создания иконок(?)
**Установка:**
```
sudo pacman -S imagemagick
```
## Пример использования zimwriterfs
```
# команда создает иконку для сайта. favicon.png должен располагаться в основной папке сайта
convert -size 48x48 xc:red favicon.png 

# команда создает сам .zim архив
zimwriterfs --welcome=zim-instruction.html --illustration=favicon.png --language=rus --name=zim-maker --title="zim-maker" --description="Инструкция по созданию .zim в zimwriterfs" --creator=zimwritesfs --publisher=superded42 ~/Downloads/zim ~/Documents/kiwix-files/zim-maker.zim
```

`--welcome=zim-instrucion.html` - основная страница сайта.
`--illustration=favicon.png` - иконка сайта.
`--language=rus` - язык сайта.
`--name=zim-maker` - идентификатор сайта.
`--title="zim-maker"` - отображение названия сайта.
`--description="Инструкция по созданию .zim в zimwriterfs"` - описание.
`--creator=zimwriterfs` - автор сайта.
`--publisher=superded42` - создатель архива.
`~/Downloads/zim` - путь к скачанному сайту.
`~/Documents/kiwix-files/zim-maker.zim` - путь к созданному архиву.