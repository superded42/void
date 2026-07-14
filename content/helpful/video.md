---
title: Вставка видео
date: 2026-07-14
type: example
---
# Костыль
Большинство сайтов дает собственный `<inframe>`: **Поделиться -> Встроить / Код вставки плеера -> Копировать.** Для наилучшего отображения на сайте лучше всего вставлять `<inframe>` в этот костыль:
```
<div style="width: 100%; aspect-ratio: 16 / 9;">

</div>
```
# Вставка из Rutube:
```
<div style="width: 100%; aspect-ratio: 16 / 9;">
<iframe width="720" height="405" src="https://rutube.ru/play/embed/ffa8bd3988e8b549411a6a3d7420fa74/" style="border: none;" allow="clipboard-write; autoplay" allowFullScreen></iframe>
</div>
```
<div style="width: 100%; aspect-ratio: 16 / 9;">
<iframe width="720" height="405" src="https://rutube.ru/play/embed/ffa8bd3988e8b549411a6a3d7420fa74/" style="border: none;" allow="clipboard-write; autoplay" allowFullScreen></iframe>
</div>
# Вставка из vkvideo:
src копировать до &hash. Сайт глючный, лучше использовать этот костыль:
```
<div style="width: 100%; aspect-ratio: 16 / 9;">
  <iframe
    src="https://vk.com/video_ext.php?oid=-176441665&id=456252770"
    style="width: 100%; height: 100%; border: 0;"
    allowfullscreen>
  </iframe>
</div>
```
<div style="width: 100%; aspect-ratio: 16 / 9;">
  <iframe
    src="https://vk.com/video_ext.php?oid=-176441665&id=456252770"
    style="width: 100%; height: 100%; border: 0;"
    allowfullscreen>
  </iframe>
</div>
# Вставка из YouTube
*Замедляют в РФ. Проще по-старинке пользоваться ссылками*
https://youtu.be/DIKtrSj-QeU?si=Luf5k2pyAhZB7qIc
```
<div style="width: 100%; aspect-ratio: 16 / 9;">
  <iframe
    src="https://www.youtube.com/embed/DIKtrSj-QeU"
    style="width: 100%; height: 100%; border: 0;"
    allowfullscreen>
  </iframe>
</div>
```
<div style="width: 100%; aspect-ratio: 16 / 9;">
  <iframe
    src="https://www.youtube.com/embed/DIKtrSj-QeU"
    style="width: 100%; height: 100%; border: 0;"
    allowfullscreen>
  </iframe>
</div>