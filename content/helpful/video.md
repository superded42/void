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

---
# Вставка из Rutube:
```
<div style="width: 100%; aspect-ratio: 16 / 9;">
<iframe width="720" height="405" src="https://rutube.ru/play/embed/ffa8bd3988e8b549411a6a3d7420fa74/" style="border: none;" allow="clipboard-write; autoplay" allowFullScreen></iframe>
</div>
```

[Петров С.В. - Квантовая механика - 1. Введение в квантовую механику. Часть 1](https://rutube.ru/video/ffa8bd3988e8b549411a6a3d7420fa74/)

<div style="width: 100%; aspect-ratio: 16 / 9;">
<iframe width="720" height="405" src="https://rutube.ru/play/embed/ffa8bd3988e8b549411a6a3d7420fa74/" style="border: none;" allow="clipboard-write; autoplay" allowFullScreen></iframe>
</div>

---
# Вставка из vkvideo:
Работает только если  src копировать до &hash и заменять `vkvideo.ru` на `vk.com`. Пока что видео отображается только в obsidian. vkvideo глючный, лучше использовать этот костыль:

```
<div style="width: 100%; aspect-ratio: 16 / 9;">
  <iframe
    src="https://vk.com/video_ext.php?oid=-176441665&id=456252770"
    style="width: 100%; height: 100%; border: 0;"
    allowfullscreen>
  </iframe>
</div>
```

[Ахмедов Э.Т. - Общая теория относительности - 1. Основные понятия СТО](https://vkvideo.ru/video-176441665_456252770?from=search&search_track_code=video_761f66cdgfnIJU6tws7QTPWp-ozRdm-hQOtu7wIua3sQzAEBJ-jjjJd3EcSAk4UfrMPW3YUyPvwtrjysVCF-fHGgbmZkdWcUBetZaRMUEZI8vEtKCa6sfIA5siPMo_v9ma0dAxnp5YW6YhD_k5WSeMKspbjkQF1AmQq-fKCE9G1woGIQEf_jgrpnHPqEmYnEFQlJuuEhLu0cv1nfIU0KD45fkZmHZHkSGhV4mvY)

<div style="width: 100%; aspect-ratio: 16 / 9;">
  <iframe
    src="https://vk.com/video_ext.php?oid=-176441665&id=456252770"
    style="width: 100%; height: 100%; border: 0;"
    allowfullscreen>
  </iframe>
</div>

---
# Вставка из YouTube
*Замедляют в РФ. Проще по-старинке пользоваться ссылками*.

```
<div style="width: 100%; aspect-ratio: 16 / 9;">
  <iframe
    src="https://www.youtube.com/embed/DIKtrSj-QeU"
    style="width: 100%; height: 100%; border: 0;"
    allowfullscreen>
  </iframe>
</div>
```

[Попов С.Б. - Астрофизика - 1. История становления автрономии](https://youtu.be/DIKtrSj-QeU?si=Luf5k2pyAhZB7qIc)

<div style="width: 100%; aspect-ratio: 16 / 9;">
  <iframe
    src="https://www.youtube.com/embed/DIKtrSj-QeU"
    style="width: 100%; height: 100%; border: 0;"
    allowfullscreen>
  </iframe>
</div>