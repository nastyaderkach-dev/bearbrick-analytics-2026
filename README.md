# bearbrick-analytics-2026
Bearbrick: аудит аналітики 3 жовтня – 1 листопада

- `index.html` — дашборд аудиту аналітики
- `calendar.html` — календар робіт до Нового року: https://nastyaderkach-dev.github.io/bearbrick-analytics-2026/calendar.html

## Як правити календар

1. Відкрити `calendar.html` → олівець «Edit this file».
2. Знайти потрібний текст через Ctrl/Cmd+F.
   - Ключові дати — блоки `<div class="date">…</div>` (клас `hot` — червона рамка).
   - Календар по тижнях — рядки `<tr>` у таблиці `class="cal"`; колір клітинки задає клас: `done` — зроблено, `run` — щотижнева робота, `act` — активний етап, `key` — ключова подія, без класу — порожньо.
   - Напрями — блоки `<details class="ws" id="ws1">…</details>`; кожен крок — рядок `<tr><td class="d">Коли</td><td>Що робимо</td><td class="get">Що отримаємо</td></tr>`.
   - «Від чого залежить» — список `<ul class="deps">`.
3. Внизу «Commit changes». Сторінка оновиться за 1–2 хвилини.
