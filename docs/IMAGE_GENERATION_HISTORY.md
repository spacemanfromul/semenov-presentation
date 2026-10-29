# Реестр промптов, моделей и результатов

Обновлено 29 октября 2026 года. Составлено по восьми уникальным предоставленным архивам и текстовой сводке Gemini из сообщения пользователя. Презентация не изменялась.

Проверены хеши 36 PNG из манифестов: 35 уникальных файлов, из них 24 результата генерации, 10 уникальных референсов и 1 кадр HTML-превью. Дополнительно проверены 3 видеофайла книги. Видеопромптов: 40 уникальных текстов. Пять вспомогательных кадров книги сохранены отдельно и не считаются результатами генерации.

## Модели и достоверность

- Изображения: ChatGPT image_gen / image_gen.text2im согласно описаниям архивов. Точный model ID не указан ни для одного результата. «DALL-E generation metadata» — название блока, а не подтверждение версии модели.
- Для семи генераций (богатырь и шесть ассетов Knight Kitty) сохранён текст, заявленный в архиве как полный промпт генератора. Для остальных доступны пользовательские запросы либо смысловые требования; это разные уровни точности.
- Gemini/Veo: имеются отзыв пользователя и новые сводки с заявленными успешными генерациями. Google Veo прямо назван в архиве огня; точная версия не указана. Статусы не проверены по исходным ответам инструмента или видеофайлам. Смешанные названия «Veo / Imagen Video Architecture» и «Google Imagen / Video Generation Model» сохранены как заявления сводок, а не установленная модель.
- Google Vids, Seedance, Kling AI/Motion Brush: целевые сервисы в подготовленных промптах; фактическая генерация этими сервисами не подтверждена.
- Сведения о gen_id и точности текста — из сопроводительных документов, а не независимого API-экспорта.
- Рекомендации внутри исходных документов сохранены как материал архива и не выполнялись как инструкции.

## Результаты изображений

| Источник / ID | Результат | Промпт | Совпадение с презентацией |
|---|---|---|---|
| ai_agents / 01_original_developer_ghost | [Первый программист и дух ИИ за клавиатурами; неоновые окна кода](<generation_registry/media/b860e6e494092585d961cd4da8d09e12510a51b11f02aa636cd86597238f3efb.png>) | Смысловые требования, не дословный промпт | Точного совпадения SHA-256 нет |
| ai_agents / 02_cyberpunk_scene | [Персонаж на основе фото, киберпанк-аниме, дух за спиной](<generation_registry/media/d85e84043fe979dc4b0af547e375d396d756acd906f09b799b7faf6a3b3a0f09.png>) | Смысловые требования, не дословный промпт | Точного совпадения SHA-256 нет |
| ai_agents / 03_transparent_samurai | [Отдельный ассет: дух-самурай в наушниках, прозрачный фон](<generation_registry/media/4a03566b4a413f5ed9a5962daf7c1e4ca39646a93c48dea7f5b9c5e5b65381c9.png>) | Смысловые требования, не дословный промпт | Точного совпадения SHA-256 нет |
| ai_agents / 04_male_samurai | [Мужчина-самурай с собранными волосами](<generation_registry/media/c7ed7c76657a0437facdf1b4c8c745e44a47affcd2b2d0cda988e316ab8a4db0.png>) | Смысловые требования, не дословный промпт | Точного совпадения SHA-256 нет |
| ai_agents / 05_simpler_anime | [Упрощение линий в направлении телевизионного аниме](<generation_registry/media/d2d454806d3d8de42677a850ddc34aae0636d64355b519642b15b92210975a62.png>) | Смысловые требования, не дословный промпт | Точного совпадения SHA-256 нет |
| ai_agents / 06_anime_revision | [Дальнейшее упрощение и уменьшение фактур](<generation_registry/media/3a63eec4c5e038193f3d3871c764fcdc511c79ac77336ea3c62915ece06d2c07.png>) | Смысловые требования, не дословный промпт | Точного совпадения SHA-256 нет |
| ai_agents / 07_tiger_samurai | [Дух с головой тигра, ещё более простое аниме](<generation_registry/media/a61c4a37c81c71fb8593d4db66721158fa38d05200f5dd140132b74b4c2173e0.png>) | Смысловые требования, не дословный промпт | Точного совпадения SHA-256 нет |
| ai_agents / 08_tiger_variant | [Дополнительный результат шага с тигром; ID генерации отдельно не указан](<generation_registry/media/1d1328608aa859a62ce2c260e467a4d5d798de7fd31651f91acc883e211fc74f.png>) | Смысловые требования, не дословный промпт | Точного совпадения SHA-256 нет |
| ai_agents / 09_tiger_no_ponytail | [Убран хвост/косичка у тигра, зелёный дым заменён на световые линии](<generation_registry/media/a528c424090afdc4e189cc85cc171c348122ee412226f7db69ba4eeb5db0c36b.png>) | Смысловые требования, не дословный промпт | Точного совпадения SHA-256 нет |
| bogatyr / 01_alexander_nevsky_inspired | [01_alexander_nevsky_inspired](<generation_registry/media/620f15fd270065f9ab26840b6c2dff5b197cab061caf3d092d08d44e87c9a254.png>) | Полный текст заявлен в архиве + запрос пользователя | Точного совпадения SHA-256 нет |
| bogatyr / 02_generic_bogatyr | [02_generic_bogatyr](<generation_registry/media/c3a6a7908cbc5c1c1a76db128e8cb65e1f36b71b856b60302ee961a241d7b07b.png>) | Пользовательский запрос; внутренний промпт не сохранён | Точного совпадения SHA-256 нет |
| bogatyr / 03_cyan_spirit | [03_cyan_spirit](<generation_registry/media/93afe604b19ed1fdd0fcb6b97c4cdc7beb8709f6945b29a45bfa4b456c6b6a26.png>) | Пользовательский запрос; внутренний промпт не сохранён | Точного совпадения SHA-256 нет |
| ai_fire / G01 | [Программист и бирюзовый дух — русский богатырь](<generation_registry/media/e00dc07e7fd92a4cb0e645af6506469079583083b5afc7afad0cc80c9121bf81.png>) | Пользовательский запрос; внутренний промпт не сохранён | Точного совпадения SHA-256 нет |
| ai_fire / G02 | [Русский богатырь: изменена причёска](<generation_registry/media/10cadaa0a507ae8ebabaf8eea54cb13328dcb965a19dfefebd19d40de540ac39.png>) | Пользовательский запрос; внутренний промпт не сохранён | Точного совпадения SHA-256 нет |
| ai_fire / G03 | [Персонаж держит бирюзовый огонь с надписью AI](<generation_registry/media/b74559a8abcb4a4704f4fda25c81bf4d94ce86094e14cc64a9f693ef1f6e4bed.png>) | Пользовательский запрос; внутренний промпт не сохранён | Точного совпадения SHA-256 нет |
| ai_fire / G04 | [Вертикальный формат 3:4](<generation_registry/media/b222cb64bb96983418064731c6d52c76879a05027eb3c9c96daf2af52f934493.png>) | Пользовательский запрос; внутренний промпт не сохранён | Точного совпадения SHA-256 нет |
| ai_fire / G05 | [Полная композиция для размещения справа на слайде](<generation_registry/media/3bf5884494d504e0dfdb65e42ead8616eb980cd5f1dbdad70e22cb26be1df2f8.png>) | Пользовательский запрос; внутренний промпт не сохранён | Точного совпадения SHA-256 нет |
| ai_fire / G06 | [Персонаж в лонгсливе из референса](<generation_registry/media/7251fc8a09479b1015d04fb9132f907c3b3389a38652391441a4d74c6e803095.png>) | Пользовательский запрос; внутренний промпт не сохранён | Точного совпадения SHA-256 нет |

## Дубликаты

- bogatyr / 00_original = ai_fire / R01. Один PNG, SHA-256 `7be04979da9b337842c46e5dbd8c4ed7144b9e61d17c1a06f45c10b33a778e74`. Хранится одна копия; все источники сохранены.

Предыдущий архив богатыря из вложения чата не добавлен повторно. Сравнение с его ранее прочитанными хешами подтверждает ту же цепочку. Отсутствие побайтного совпадения с ассетом не исключает использование после ресайза или обработки.

## Пользовательские запросы и полный промпт богатыря

# История генераций: программист и дух богатыря

Дата: 28 октября 2026 года.

## Модель и среда

- Все три изображения получены инструментом генерации изображений **ChatGPT `image_gen.text2im`**.
- В ответах инструмента присутствует поле **«DALL-E generation metadata»**. Это название блока метаданных; **точная версия модели / model ID не раскрыта**, поэтому нельзя достоверно утверждать, что это, например, DALL·E 3 или GPT Image 1.5.
- В доступных метаданных `edit_op: null`, `parent_gen_id: null`; результаты представлены как самостоятельные генерации. Их внешняя преемственность задана контекстом чата и референсом.
- Фон визуально черный при просмотре на темной подложке; наличие прозрачности можно проверить средствами редактирования PNG. Оригинальные PNG сохранены без обработки.

## 00 — Исходный референс

**Файл:** `00_original.png`  
**Источник:** изображение, загруженное пользователем (`image(9).png`).  
**Модель:** не указана; происхождение исходного изображения неизвестно.

## 01 — Богатырь по мотивам Александра Невского

**Файл:** `01_alexander_nevsky_inspired.png`  
**gen_id:** `89b26f6e-2a7c-4e15-beb6-2f00e7b8b5e8`

**Запрос пользователя (оригинальный):**
> замени самурая на русского богатыря тпа князя алксандра невского

**Текст, отправленный генератору (сохранен дословно):**
> A polished anime-comic sticker illustration on a fully transparent background depicts a focused modern programmer typing on a glowing purple-lit keyboard, while a large translucent Alexander Nevsky–inspired Russian warrior spirit looms behind him as a noble mentor. Crisp cel-shaded linework, cyan-and-gold magical ribbons, red fur-trimmed armor and cape, ornate heraldic details, and floating holographic code panels filled only with colorful abstract syntax lines create a dynamic neon overlay composition.

## 02 — Обычный русский богатырь

**Файл:** `02_generic_bogatyr.png`  
**gen_id:** `7d20af94-c0a2-429c-91a6-89bd63809b66`

**Запрос пользователя (оригинальный):**
> пусть это будет просто богатырь не князь Невский

**Полный внутренний промпт:** недоступен. Генерация произведена с опорой на этот запрос и историю беседы. Не следует считать приведенный запрос полной реконструкцией внутреннего промпта.

## 03 — Бирюзово-синий полупрозрачный дух

**Файл:** `03_cyan_spirit.png`  
**gen_id:** `2518a1f5-3ebe-4955-8bfa-21265bc06283`

**Запрос пользователя (оригинальный):**
> лицо как это дух и он весь должнен цвета сине берозвыц полу прозрачнй

**Полный внутренний промпт:** недоступен. Генерация произведена с опорой на этот запрос и историю беседы. Не следует считать приведенный запрос полной реконструкцией внутреннего промпта.

## Состав

- 1 оригинальное изображение;
- 3 результата генерации;
- `README.md` — история и текст запросов;
- `metadata.json` — машиночитаемые сведения и SHA-256 файлов.

**Примечание:** сохраняются только результаты текущей цепочки (исходник + 3 изменения), а не все изображения из других переписок проекта.


## Запросы цепочки AI Fire (дословно по архиву)

# Запросы для генерации и редактирования изображений

Важное ограничение: системные промпты, реально переданные встроенной модели генерации, не раскрыты.
В истории инструмента поле `prompt` пустое (`"prompt": ""`), поэтому ниже приведены **точные сообщения пользователя**, а не восстановленные внутренние промпты.

**Модель:** встроенный генератор изображений ChatGPT (`image_gen`); метаданные результатов содержат пометку `DALL-E generation metadata`. Точную версию модели по имеющимся данным определить нельзя.

## Последовательность

### G01: Программист и бирюзовый дух — русский богатырь

- **Запрос пользователя (дословно):** сделай российский вариант духа богатурь важно цвета не изменять цвет лица духа рук доспехи несльно выделяються
- **Вход:** R01
- **Результат:** `02_generated_images/G01_a_vibrant_digital_illustration_png_sticker_like_sc.png`
- **gen_id:** `27213cca-5120-44ad-af3b-88fe644fbf9b`
- **parent_gen_id:** `не указан`


### G02: Русский богатырь: изменена причёска

- **Запрос пользователя (дословно):** смени прическу на старорусского богатыря
- **Вход:** G01
- **Результат:** `02_generated_images/G02_программист_и_дух_богатырь_в_коде.png`
- **gen_id:** `693f6fba-e7ba-464f-8762-48a527ebbd1c`
- **parent_gen_id:** `не указан`


### G03: Персонаж держит бирюзовый огонь с надписью AI

- **Запрос пользователя (дословно):** на базе этого кадра из аниме сделай такой же где мужчина в руке держит берюзовый огонь и там надписьAI
- **Вход:** R02 + R03
- **Результат:** `02_generated_images/G03_неоновое_пламя_ai_в_ладони.png`
- **gen_id:** `93807dd6-360d-4ae0-acb0-81528d2450b3`
- **parent_gen_id:** `не указан`


### G04: Вертикальный формат 3:4

- **Запрос пользователя (дословно):** Задайте соотношение сторон 3:4
- **Вход:** G03
- **Результат:** `02_generated_images/G04_циановое_пламя_ai.png`
- **gen_id:** `c6df3305-1b44-44f1-8ec2-636029c64fe1`
- **parent_gen_id:** `93807dd6-360d-4ae0-acb0-81528d2450b3`


### G05: Полная композиция для размещения справа на слайде

- **Запрос пользователя (дословно):** ye;yj xnj,s herf cktdf yt,skf j,thpfyf cltkfq nfrjq ajhvfn xnj,s yt ghtpt gjvtcnfkfcm c ghjphfyxjv ajyt? yf ckfqlt ,ele hfpvtofnm cghfdf
- **Вход:** G04
- **Результат:** `02_generated_images/G05_аниме_воин_с_неоновым_пламенем_ai.png`
- **gen_id:** `8c25b181-b84c-42d8-a039-e6e34911acb0`
- **parent_gen_id:** `c6df3305-1b44-44f1-8ec2-636029c64fe1`


### G06: Персонаж в лонгсливе из референса

- **Запрос пользователя (дословно):** лонгслив вот такой должен быть на персонаже
- **Вход:** G05 + R04
- **Результат:** `02_generated_images/G06_лысый_маг_с_пламенем_ai.png`
- **gen_id:** `f564c27f-97bb-459e-95ee-f23efd89f78b`
- **parent_gen_id:** `8c25b181-b84c-42d8-a039-e6e34911acb0`


## Что не следует считать точным промптом

Строки в описании результата G01 (например, “A neon cyber-fantasy sticker illustration ...”) были описанием сгенерированного результата и не являются восстановленным внутренним промптом.


## Хронология AI-агентов (смысловая запись, не стенограмма)

# Хронология требований

### U01 — Концепция визуального сопровождения слайда
Нужно дополнить слайд фото или видео: «От одного сценария к платформе ИИ-агентов».

### U02 — Видео шаров
Сделаем в Google Vids: появляется один зелёный шарик, катится, подпрыгивает, из него появляется множество шариков; они зависают и снова объединяются; цикл.

### U03 — Ровно 8 шаров
Шариков 8 достаточно.

### U04 — Формат 1:1
Анимация будет в квадрате, место под текст не нужно.

### U05 — Alpha
У видео должен быть прозрачный фон.

### U06 — Liquid metal / mercury
Нужно как ртуть: катится, множится, потом соединяется.

### U07 — Storyboard
Предоставлена раскадровка шариков.

### U08 — Генерация первой иллюстрации
В стиле Shaman King: человек сидит за компьютером и кодит, за ним дух — ИИ-агент, который тоже кодит; у обоих реальные клавиатуры; перед ними строки кода.

### U09 — Замена человека
Замени героя на человека с предоставленной фотографии, но сохрани стиль аниме.

### U10 — Изолированный ассет
PNG с прозрачным фоном для правого нижнего угла слайда; дух в одежде самурая, в наушниках, на нём значок AI, убрать значки ChatGPT.

### U11 — Смена образа духа
Дух не девушка: нужен самурай-мужчина с собранными волосами.

### U12 — Упрощение
Упростить рисовку, как на предоставленном референсе Shaman King.

### U13 — Дальнейшее упрощение
Нужно радикально проще — очень простое аниме, без лишних фактур и свечений.

### U14 — Тигр-самурай
Дух должен стать самураем с головой тигра. Ещё проще стиль.

### U15 — Корректировка тигра и эффектов
У тигра не должно быть косички; зелёный дым похож на запах — убрать.

### U16 — Image-to-video
Зацикленная анимация с минимумом изменений: дух парит, все печатают пальцами, фон прозрачный, иллюстрация целиком в кадре и уменьшена; промпт для Google Vids.

### U17 — Финальная корректировка видеопромпта
Добавить в видеопромпт полупрозрачность духа.


## Видеопромпты

### ai_agents / agents-01 — 01_mercury_8_spheres.txt

Целевой сервис: Google Vids (целевой сервис); модель не установлена. Видео отсутствует. фактический запуск не подтверждён.

[Исходный текст](<generation_sources/ai_agents/prompts/video/01_mercury_8_spheres.txt>)

```text
Create a seamless looping square animation with a transparent background (alpha channel) in a minimal futuristic tech style. A single glowing neon-green sphere appears, smoothly rolls forward, and makes a small soft bounce. After the bounce, it splits into exactly 8 smaller glowing green spheres. The 8 spheres spread out slightly, remain close together, and hover in the air as a compact cluster, symbolizing multiple AI agents. The small spheres should have a soft neon glow and subtle pulsing light while hovering. After a short pause, they smoothly and synchronously merge back into one larger glowing sphere. The motion should feel clean, elegant, and presentation-friendly, with smooth timing, no text, and no extra objects. The loop should be seamless and continuous and the background must stay fully transparent throughout.
```

### ai_agents / agents-02 — 02_mercury_liquid_metal.txt

Целевой сервис: Google Vids (целевой сервис); модель не установлена. Видео отсутствует. фактический запуск не подтверждён.

[Исходный текст](<generation_sources/ai_agents/prompts/video/02_mercury_liquid_metal.txt>)

```text
Create a seamless looping square animation with a transparent background (alpha channel). Show a single mercury-like neon-green sphere that behaves like a small drop of liquid metal. It should smoothly roll forward like mercury, with soft natural deformation while moving. Then it lightly bounces and multiplies into exactly 8 smaller liquid spheres, as if one drop splits into many smaller droplets. The 8 droplets spread out slightly, stay relatively close together, and hover as a compact group. After a short moment, the droplets are drawn back together and merge smoothly into one single larger sphere, again with realistic liquid merging behavior. The motion should feel fluid, elegant, clean, and futuristic. Minimal tech style, soft neon-green glow, no text, no extra objects, fully transparent background, and a seamless continuous loop.
```

### ai_agents / agents-03 — 03_mercury_storyboard_8_seconds.txt

Целевой сервис: Google Vids (целевой сервис); модель не установлена. Видео отсутствует. фактический запуск не подтверждён.

[Исходный текст](<generation_sources/ai_agents/prompts/video/03_mercury_storyboard_8_seconds.txt>)

```text
Create an 8-second seamless looping animation, square 1:1 format, with a fully transparent alpha background.

Visual style: A glossy neon-green liquid metal sphere, resembling mercury, with realistic surface tension, fluid deformation, reflective highlights, and a subtle green glow. Minimalist premium 3D motion graphics.

Exact animation sequence:
0–1s: A single green liquid-metal sphere smoothly rolls from left to right, subtly deforming like a mercury droplet.
1–2s: The sphere makes one gentle elastic bounce, stretching slightly upward.
2–3s: During the bounce, the sphere physically splits into exactly 8 smaller liquid-metal droplets. The split must be continuous and fluid, not a sudden appearance of new spheres.
3–4s: All 8 droplets float outward and form a loose, balanced three-dimensional cluster.
4–5s: The 8 droplets hover motionlessly in the air, maintaining their individual spherical shapes.
5–6s: The droplets begin moving toward the center, attracted by an invisible force.
6–7s: All 8 droplets touch and physically fuse together through realistic liquid-metal surface tension, forming one single large sphere.
7–8s: The sphere settles back into its original shape and position, ready to repeat the animation seamlessly.

Important constraints: Exactly 8 smaller droplets, never more. Preserve the total volume of liquid throughout the transformation. All droplets must originate from the original sphere and visibly merge back together. No disappearing, teleporting, particle explosions, extra objects, text, shadows, ground plane, or camera movement. Fixed camera, centered composition, fully transparent background.
```

### ai_agents / agents-04 — 04_tiger_agent_loop.txt

Целевой сервис: Google Vids (целевой сервис); модель не установлена. Видео отсутствует. фактический запуск не подтверждён.

[Исходный текст](<generation_sources/ai_agents/prompts/video/04_tiger_agent_loop.txt>)

```text
Animate the uploaded image with extremely subtle motion. Preserve the original anime illustration, character designs, colors, and composition exactly.

CAMERA AND FRAMING — CRITICAL:
Use a fixed camera with absolutely no zoom, crop, pan, or camera movement. Scale down the entire original illustration uniformly to 75% of the video frame, keeping it perfectly centered. The FULL illustration must remain visible throughout the entire video, including the tiger's head, all floating code panels, both keyboards, hands, and green energy effects. Leave generous empty transparent margins on all four sides. Use "contain", NOT "cover". Never fill the frame by cropping the artwork.

ANIMATION:
- The tiger samurai AI spirit gently floats up and down in the air, moving only a few pixels.
- Both the human developer and the tiger spirit continuously type on their own keyboards with subtle, realistic finger movements.
- The human's body and face remain almost completely still.
- The tiger's body remains stable while gently hovering.
- The floating code panels remain in place, with very subtle blinking code lines.
- Green energy accents gently pulse without changing their shape.

LOOP:
Create a 6-second perfectly seamless animation loop. The final frame must match the first frame in position, scale, and appearance. No transitions, sudden movements, or scene changes.

BACKGROUND:
Fully transparent background with alpha channel. No environment, no floor, no shadows, no solid background.

STRICT RESTRICTIONS:
No camera zoom. No cropping. No reframing. No new objects. No additional fingers. No character redesign. No facial changes. No moving keyboards. No exaggerated animation. No text or logos. Preserve the exact original illustration.
```

### ai_agents / agents-05 — 05_tiger_agent_loop_semitransparent_FINAL.txt

Целевой сервис: Google Vids (целевой сервис); модель не установлена. Видео отсутствует. фактический запуск не подтверждён.

[Исходный текст](<generation_sources/ai_agents/prompts/video/05_tiger_agent_loop_semitransparent_FINAL.txt>)

```text
Animate the uploaded image with extremely subtle motion. Preserve the original anime illustration, character designs, colors, and composition exactly.

CAMERA AND FRAMING — CRITICAL:
Use a fixed camera with absolutely no zoom, crop, pan, or camera movement. Scale down the entire original illustration uniformly to 75% of the video frame, keeping it perfectly centered. The FULL illustration must remain visible throughout the entire video, including the tiger's head, all floating code panels, both keyboards, hands, and green energy effects. Leave generous empty transparent margins on all four sides. Use "contain", NOT "cover". Never fill the frame by cropping the artwork.

ANIMATION:
- The tiger samurai AI spirit gently floats up and down in the air, moving only a few pixels.
- The tiger samurai AI spirit must be semi-transparent / partially translucent, clearly ghostlike, while remaining fully visible.
- Both the human developer and the tiger spirit continuously type on their own keyboards with subtle, realistic finger movements.
- The human's body and face remain almost completely still.
- The tiger's body remains stable while gently hovering.
- The floating code panels remain in place, with very subtle blinking code lines.
- Green energy accents gently pulse without changing their shape.

LOOP:
Create a 6-second perfectly seamless animation loop. The final frame must match the first frame in position, scale, and appearance. No transitions, sudden movements, or scene changes.

BACKGROUND:
Fully transparent background with alpha channel. No environment, no floor, no shadows, no solid background.

STRICT RESTRICTIONS:
No camera zoom. No cropping. No reframing. No new objects. No additional fingers. No character redesign. No facial changes. No moving keyboards. No exaggerated animation. No text or logos. Preserve the exact original illustration.
```

### ai_fire / P01 — Первый подробный промпт: пламя и частицы

Целевой сервис: Gemini / Veo. Видео отсутствует. Gemini/Veo тестировался со слов пользователя; привязка теста к конкретному P-ID не установлена.

[Исходный текст](<generation_sources/ai_fire/AI_Fire_Archive/03_video_prompts/P01_Gemini.txt>)

```text
Create a perfectly seamless looping animation using the provided reference image.

**Animation:**
- The turquoise and cyan magical fire gently burns, flickers and flows upward continuously.
- The flame forms a stable, glowing magical sphere above the man's open palm.
- Small luminous particles and geometric fragments slowly float around the flame.
- The glowing "AI" letters remain perfectly sharp, readable, stationary and unchanged.
- The flame's brightness subtly pulses without changing its overall size or shape.

**Character:**
- The man remains completely still, like a static illustration.
- His hand, fingers, face, eyes, head, clothing and body do not move.
- Preserve the exact original anime art style, colors, facial features and clothing.

**Camera and composition:**
- Completely locked camera. No zoom, pan, rotation or shake.
- Preserve the entire character, extended hand and flame within the frame.
- Keep the original transparent background. Do not generate scenery.

**Perfect seamless loop:**
- Duration: 8 seconds.
- The first and last frames must be visually identical.
- All flame and particle movements must form continuous repeating cycles.
- No sudden changes, cuts, transitions or fade-in/fade-out.

Only the magical fire and surrounding particles are animated. Everything else stays perfectly still.
```

### ai_fire / P02 — Первый подробный промпт для Seedance

Целевой сервис: Seedance. Видео отсутствует. Gemini/Veo тестировался со слов пользователя; привязка теста к конкретному P-ID не установлена.

[Исходный текст](<generation_sources/ai_fire/AI_Fire_Archive/03_video_prompts/P02_Seedance.txt>)

```text
Use the provided image as the exact visual reference.

Create a perfectly seamless 8-second looping animation.

**Animate ONLY the turquoise magical AI flame above the man's palm.**

The magical fire gently burns, flickers and swirls upward in a continuous, smooth cycle. The flame maintains its original overall shape and position, forming a stable glowing energy sphere.

Small cyan particles softly shimmer and circulate around the flame. The glowing "AI" letters remain completely stationary, sharp and readable.

**Everything else must remain perfectly still:**
- The man's face, eyes, head and expression.
- His extended hand and fingers.
- His clothing and entire body.
- The camera and framing.

Preserve the exact original anime illustration style, colors, lighting and composition.

Keep the original transparent background. Do not add any scenery.

**LOOP REQUIREMENT:** The animation must return smoothly to its exact initial state. The first and last frames should match perfectly. No cuts, zooms, camera movement or transitions.

Only the turquoise flame and tiny glowing particles are moving.
```

### ai_fire / P03 — Уточнение: исключительно плавное пламя

Целевой сервис: Seedance. Видео отсутствует. Gemini/Veo тестировался со слов пользователя; привязка теста к конкретному P-ID не установлена.

[Исходный текст](<generation_sources/ai_fire/AI_Fire_Archive/03_video_prompts/P03_Seedance.txt>)

```text
Use the provided image as the exact visual reference.

Create a perfectly seamless 8-second looping animation.

Animate ONLY the turquoise magical AI flame above the man's palm.

The flame burns very smoothly, softly and continuously.  
Its motion is calm, fluid and stable, with slow organic swirling and gentle inner movement.  
The fire should look like a living magical energy sphere with soft flowing tongues of flame.  
No sudden flickering, no sharp jumps, no aggressive movement, no rapid pulsing, no erratic changes.

The overall flame shape, size and position remain stable at all times.  
The glowing "AI" letters inside the flame remain completely fixed, sharp and readable.  
Small glowing cyan particles drift slowly and smoothly around the flame with minimal motion.

Everything else must remain perfectly still:
- the man's face, eyes and expression
- the head and body
- the hand and fingers
- the clothing
- the camera and framing

Preserve the exact original anime illustration style, colors, lighting and composition.

Keep the original transparent background. Do not add any scenery.

LOOP REQUIREMENT:
The animation must be perfectly seamless.  
The first and last frames must match exactly.  
The flame motion should feel continuous and cyclical, with no visible restart point.

Only the flame and tiny particles are moving, and their motion must be very smooth and gentle.
```

### ai_fire / P04 — Короткая добавка: максимально спокойное пламя

Целевой сервис: Seedance. Видео отсутствует. Gemini/Veo тестировался со слов пользователя; привязка теста к конкретному P-ID не установлена.

[Исходный текст](<generation_sources/ai_fire/AI_Fire_Archive/03_video_prompts/P04_Seedance.txt>)

```text
Motion intensity: very low. Prioritize smoothness and stability over visible animation.
```

### ai_fire / P05 — Короткая добавка: немного более живое

Целевой сервис: Seedance. Видео отсутствует. Gemini/Veo тестировался со слов пользователя; привязка теста к конкретному P-ID не установлена.

[Исходный текст](<generation_sources/ai_fire/AI_Fire_Archive/03_video_prompts/P05_Seedance.txt>)

```text
Motion intensity: low. The flame should feel alive, but still very smooth and controlled.
```

### ai_fire / P06 — Короткий negative prompt против рывков

Целевой сервис: Seedance. Видео отсутствует. Gemini/Veo тестировался со слов пользователя; привязка теста к конкретному P-ID не установлена.

[Исходный текст](<generation_sources/ai_fire/AI_Fire_Archive/03_video_prompts/P06_Seedance.txt>)

```text
Avoid strobing, jitter, frame-to-frame wobble, shape instability, sudden deformation, or noisy flicker.
```

### ai_fire / P07 — Подробный промпт с полным кадрированием

Целевой сервис: Gemini / Veo. Видео отсутствует. Gemini/Veo тестировался со слов пользователя; привязка теста к конкретному P-ID не установлена.

[Исходный текст](<generation_sources/ai_fire/AI_Fire_Archive/03_video_prompts/P07_Gemini.txt>)

```text
Animate the provided reference image into a perfectly seamless 8-second looping video.

**CRITICAL — FULL IMAGE FIT:**
Preserve the ENTIRE original illustration. Fit the complete character and all visual elements inside the video frame.

Use "contain" framing, NOT "cover" or crop.

If necessary, scale DOWN the entire illustration uniformly to fit within the frame. Add empty transparent space around the character.

Leave at least 10% safe margins on ALL FOUR SIDES.

The head, shoulders, entire extended arm, hand, torso and complete turquoise AI flame must remain fully visible throughout the video.

NEVER crop, zoom in, stretch or cut off any part of the original image.

**ANIMATION:**
Only the turquoise magical AI fire gently burns.

The flame moves extremely smoothly, with slow, continuous, fluid motion. Soft tongues of fire flow upward and gently circulate inside a stable glowing sphere.

No sudden flickering, jitter, shaking, rapid pulsing or abrupt changes.

Keep the glowing "AI" letters sharp, readable and completely stationary.

**CHARACTER:**
The entire character remains perfectly motionless. No movement of the face, eyes, head, hands, fingers, clothing or body.

**CAMERA:**
Completely static camera. No zoom, pan, rotation, camera shake or reframing.

**BACKGROUND:**
Preserve the original transparent background if supported. Do not add scenery or background objects.

**SEAMLESS LOOP:**
The first and last frames must match visually. Flame movement must be slow, periodic and continuous, without any visible restart, transition or fade.

Duration: 8 seconds.

Prioritize full character visibility, perfectly stable composition and extremely smooth flame animation over dramatic effects.
```

### ai_fire / P08 — Пламя вместо желе: физика горения

Целевой сервис: Gemini / Veo. Видео отсутствует. Gemini/Veo тестировался со слов пользователя; привязка теста к конкретному P-ID не установлена.

[Исходный текст](<generation_sources/ai_fire/AI_Fire_Archive/03_video_prompts/P08_Gemini.txt>)

```text
Animate the provided image into an 8-second seamless looping video.

CRITICAL: The turquoise magical fire must behave like REAL BURNING FIRE, not liquid, jelly, smoke or a moving energy blob.

FIRE ANIMATION:
- The main glowing sphere remains completely stationary, maintaining its original size, position and overall silhouette.
- Only individual tongues of cyan flame are animated.
- Thin flame tongues emerge from the base, naturally rise upward, stretch into sharp tips and gradually disappear.
- New flame tongues continuously replace the disappearing ones.
- The flame edges flicker subtly and naturally, like real fire burning in slow motion.
- Small glowing embers gently rise and fade away.
- The bright turquoise core remains stable.
- The glowing "AI" letters remain perfectly still and readable.

STRICTLY FORBIDDEN:
- No jelly-like movement.
- No rubbery deformation.
- No morphing, wobbling or bouncing.
- No breathing, expanding or contracting of the sphere.
- No liquid waves or rotating energy blobs.
- No movement of the entire fireball.
- No random image distortion.
- No sudden flickering or frame-to-frame jitter.

CHARACTER:
The man, face, eyes, clothes, hand and fingers remain absolutely motionless. Animate only the small individual flame tongues and glowing embers.

COMPOSITION:
Static camera. Preserve the entire original image using CONTAIN framing. Scale down uniformly if necessary. Keep at least 10% safe margins on every side. Never crop any part of the character or fire.

Keep the original anime style and colors. Preserve the transparent background if supported.

LOOP:
8-second continuous animation with natural, steady combustion. The first and last frames should visually match without a jump or transition.

The final result must look like a real turquoise flame burning steadily above a completely motionless hand, NOT a gelatinous glowing object.
```

### ai_fire / P09 — Очень короткий вариант: огонь

Целевой сервис: Gemini / Veo. Видео отсутствует. Gemini/Veo тестировался со слов пользователя; привязка теста к конкретному P-ID не установлена.

[Исходный текст](<generation_sources/ai_fire/AI_Fire_Archive/03_video_prompts/P09_Gemini.txt>)

```text
Animate only the turquoise fire above the hand.
The fire must burn like real flame, with small flame tongues rising upward.
Do not animate the character.
Do not crop the image.
Keep the whole image fully visible.
Static camera.
Seamless loop.
No jelly, no blob motion, no wobbling.
```

### ai_fire / P10 — Короткий вариант: огонь + стабильный шар

Целевой сервис: Gemini / Veo. Видео отсутствует. Gemini/Veo тестировался со слов пользователя; привязка теста к конкретному P-ID не установлена.

[Исходный текст](<generation_sources/ai_fire/AI_Fire_Archive/03_video_prompts/P10_Gemini.txt>)

```text
Only animate the turquoise flame.
It should burn like real fire, with thin flame tongues moving upward.
The fireball shape stays stable.
The character stays completely still.
Keep the full image visible in frame.
Static camera.
Seamless loop.
No jelly motion, no morphing, no wobble.
```

### ai_fire / P11 — Минимальный вариант: огонь

Целевой сервис: Gemini / Veo. Видео отсутствует. Gemini/Veo тестировался со слов пользователя; привязка теста к конкретному P-ID не установлена.

[Исходный текст](<generation_sources/ai_fire/AI_Fire_Archive/03_video_prompts/P11_Gemini.txt>)

```text
Real burning turquoise flame only.
Static character.
Full image in frame.
No crop.
No jelly motion.
Seamless loop.
```

### ai_fire / P12 — Оживить фото, короткий вариант 1

Целевой сервис: Gemini / Veo. Видео отсутствует. Gemini/Veo тестировался со слов пользователя; привязка теста к конкретному P-ID не установлена.

[Исходный текст](<generation_sources/ai_fire/AI_Fire_Archive/03_video_prompts/P12_Gemini.txt>)

```text
Animate the image into a seamless loop.
Do not change the pose.
Keep the character still.
Only animate the turquoise fire.
Keep the full image visible.
No crop.
Static camera.
```

### ai_fire / P13 — Оживить фото, короткий вариант 2

Целевой сервис: Gemini / Veo. Видео отсутствует. Gemini/Veo тестировался со слов пользователя; привязка теста к конкретному P-ID не установлена.

[Исходный текст](<generation_sources/ai_fire/AI_Fire_Archive/03_video_prompts/P13_Gemini.txt>)

```text
Animate this image as a seamless loop.
Do not change the pose.
Only animate the fire.
Keep the whole image in frame.
No crop.
```

### ai_fire / P14 — Оживить фото, короткий вариант 3

Целевой сервис: Gemini / Veo. Видео отсутствует. Gemini/Veo тестировался со слов пользователя; привязка теста к конкретному P-ID не установлена.

[Исходный текст](<generation_sources/ai_fire/AI_Fire_Archive/03_video_prompts/P14_Gemini.txt>)

```text
Animate the photo.
Seamless loop.
Do not change the pose.
Only animate the fire.
Keep the full image visible.
```

### ai_fire / P15 — Оживить фото, финальная короткая версия

Целевой сервис: Gemini / Veo. Видео отсутствует. Gemini/Veo тестировался со слов пользователя; привязка теста к конкретному P-ID не установлена.

[Исходный текст](<generation_sources/ai_fire/AI_Fire_Archive/03_video_prompts/P15_Gemini.txt>)

```text
Animate this image as a seamless loop.
Do not change the pose.
Keep the character still.
Only animate the turquoise fire.
Keep the whole image fully visible.
No crop.
Static camera.
No jelly motion.
```

### ai_fire / P16 — Пламя, частицы, осколки в области ладони

Целевой сервис: Gemini / Veo. Видео отсутствует. Gemini/Veo тестировался со слов пользователя; привязка теста к конкретному P-ID не установлена.

[Исходный текст](<generation_sources/ai_fire/AI_Fire_Archive/03_video_prompts/P16_Gemini.txt>)

```text
Animate this image as a seamless loop.
Do not change the pose.
Keep the character completely still.
Animate only the turquoise energy in the hand area: the flame, glowing particles and small energy fragments.
Keep the whole image fully visible.
No crop.
Static camera.
No jelly motion.
```

### ai_fire / P17 — Чуть подробнее: пламя, частицы, осколки

Целевой сервис: Gemini / Veo. Видео отсутствует. Gemini/Veo тестировался со слов пользователя; привязка теста к конкретному P-ID не установлена.

[Исходный текст](<generation_sources/ai_fire/AI_Fire_Archive/03_video_prompts/P17_Gemini.txt>)

```text
Animate this image as a seamless loop.
Do not change the pose.
Keep the character completely still.
Animate only everything in the hand area: the turquoise flame, glowing particles and floating energy fragments.
The energy should move softly and naturally like real flame and light particles.
Keep the whole image fully visible.
No crop.
Static camera.
No jelly motion, no morphing.
```

### ai_fire / P18 — Ультракороткая версия с частицами

Целевой сервис: Gemini / Veo. Видео отсутствует. Gemini/Veo тестировался со слов пользователя; привязка теста к конкретному P-ID не установлена.

[Исходный текст](<generation_sources/ai_fire/AI_Fire_Archive/03_video_prompts/P18_Gemini.txt>)

```text
Seamless loop.
Do not change the pose.
Keep the character still.
Animate only the turquoise flame, particles and energy fragments in the hand area.
Keep the full image visible.
No crop.
Static camera.
No jelly motion.
```

### ai_fire / P19 — Финальная версия с частицами, повтор в ответе

Целевой сервис: Gemini / Veo. Видео отсутствует. Gemini/Veo тестировался со слов пользователя; привязка теста к конкретному P-ID не установлена.

[Исходный текст](<generation_sources/ai_fire/AI_Fire_Archive/03_video_prompts/P19_Gemini.txt>)

```text
Animate this image as a seamless loop.
Do not change the pose.
Keep the character completely still.
Animate only the turquoise flame, glowing particles and floating energy fragments in the hand area.
Keep the whole image fully visible.
No crop.
Static camera.
No jelly motion.
```

### ai_fire / P20 — Подсказка для областной анимации

Целевой сервис: Kling AI / Motion Brush. Видео отсутствует. Gemini/Veo тестировался со слов пользователя; привязка теста к конкретному P-ID не установлена.

[Исходный текст](<generation_sources/ai_fire/AI_Fire_Archive/03_video_prompts/P20_Kling.txt>)

```text
The turquoise magical fire burns naturally. Small flame tongues rise upward. Glowing particles and energy fragments slowly float upward. Smooth, continuous movement. The character and camera remain completely still.
```

## Машиночитаемые данные

[Полный каталог JSON](<IMAGE_GENERATION_CATALOG.json>)

[Сопроводительные документы и исходные тексты](<generation_sources>)

Визуальное сопоставление изображений со слайдами не выполнялось; связи по слайдам приведены только для точных совпадений SHA-256.

## Дополнение: сводки генераций Gemini от 29 октября 2026

Добавлено 15 промптов: 5 про аиста, 3 про огонь, 3 про духа-тигра и 4 для Bento. В сводках заявлены 8 успешных результатов и 4 превышения лимита; 3 концепта Bento — резервные.

**Предел подтверждения:** в новых ZIP находятся только Markdown и JSON. Видеофайлов и исходных ответов API нет. Ссылки googleusercontent сохранены как идентификаторы из сводок, не проверялись и не скачивались. Ссылка при статусе Quota Exceeded не считается подтверждением существующего ролика. Версии Veo/Imagen не установлены.

Контекст Bento: обслуживание банкоматов, терминалов и офисного оборудования; тёмно-серый/тёмно-синий стиль с зелёными акцентами; формат 9:16. Для инженера указаны референсы 26546_3.jpg и 26544.jpg; сами файлы не приложены.

| Источник / ID | Статус по сводке | Заявленная модель |
|---|---|---|
| gemini_stork / stork-1 | Превышен лимит генерации (Quota Exceeded) | Google Video Generation Model (Veo / Imagen Video Architecture) |
| gemini_stork / stork-2 | Превышен лимит генерации (Quota Exceeded) | Google Video Generation Model (Veo / Imagen Video Architecture) |
| gemini_stork / stork-3 | Успешно сгенерировано (Success) | Google Video Generation Model (Veo / Imagen Video Architecture) |
| gemini_stork / stork-4 | Успешно сгенерировано (Success) | Google Video Generation Model (Veo / Imagen Video Architecture) |
| gemini_stork / stork-5 | Превышен лимит генерации (Quota Exceeded) | Google Video Generation Model (Veo / Imagen Video Architecture) |
| gemini_fire / fire-1 | Success | Google Veo (Video Generation Model) |
| gemini_fire / fire-2 | Success | Google Veo (Video Generation Model) |
| gemini_fire / fire-3 | Success | Google Veo (Video Generation Model) |
| gemini_tiger / tiger-1 | Видео успешно создано | Google Video Generation Model |
| gemini_tiger / tiger-2 | Видео успешно создано | Google Video Generation Model |
| gemini_tiger / tiger-3 | Достигнут лимит генераций | Google Video Generation Model |
| gemini_bento / bento-engineer | Успешно сгенерировано и отредактировано — по сводке Gemini | Google Imagen / Video Generation Model |
| gemini_bento / bento-van | Резервный концепт; запуск не подтверждён | Не установлена; резервный концепт |
| gemini_bento / bento-office | Резервный концепт; запуск не подтверждён | Не установлена; резервный концепт |
| gemini_bento / bento-monitoring | Резервный концепт; запуск не подтверждён | Не установлена; резервный концепт |

### gemini_stork / stork-1 — Уставший аист взлетает из туч с сеткой светящихся шаров без надписей. Сверху на высокой скорости пролетают футуристичные космолеты с неоновыми шлейфами. Вертикальный формат 9:16, без текста.

[Источник](<generation_sources/gemini_stork/generation_details.json>)

Статус: Превышен лимит генерации (Quota Exceeded). Точная модель: не установлена.

Референс: Пользовательское изображение (26567.png)

```text
A tired white stork barely flying out of heavy clouds, holding a heavy sagging net filled with glowing glass orbs without any text or labels. In the upper bright sky, sleek ultra-futuristic white spaceships without text zoom past at extreme speed, leaving vibrant neon light trails. Vertical 9:16 aspect ratio, clean image, no text, no letters, no logos
```

Идентификатор результата из сводки (не проверен): `http://googleusercontent.com/generated_video_content/9848761165852556735`.

### gemini_stork / stork-2 — Аист с тяжелой сеткой шаров едва машет крыльями над облаками. Космолеты со сверхзвуковой скоростью обгоняют его.

[Источник](<generation_sources/gemini_stork/generation_details.json>)

Статус: Превышен лимит генерации (Quota Exceeded). Точная модель: не установлена.

Референс: Пользовательское изображение (26567.png)

```text
A tired white stork barely flying out of heavy clouds, holding a heavy sagging net filled with glowing glass orbs without any text. In the upper sky, futuristic white spaceships zoom past at extreme speed leaving neon light trails. Vertical 9:16 aspect ratio, clean image, no text
```

Идентификатор результата из сводки (не проверен): `http://googleusercontent.com/generated_video_content/17948258586391326612`.

### gemini_stork / stork-3 — Повторная генерация ролика с аистом и пролетающими над ним космолетами без надписей.

[Источник](<generation_sources/gemini_stork/generation_details.json>)

Статус: Успешно сгенерировано (Success). Точная модель: не установлена.

Референс: Пользовательское изображение (26567.png)

```text
A tired white stork barely flying out of heavy clouds, holding a heavy sagging net filled with glowing glass orbs without text. Futuristic white spaceships without text zoom past at extreme speed leaving neon light trails. Vertical 9:16 aspect ratio, clean image, no text
```

Идентификатор результата из сводки (не проверен): `http://googleusercontent.com/generated_video_content/5579085052287335189`.

### gemini_stork / stork-4 — Аист в нижней части кадра тяжело машет крыльями. В верхней части неба со сверхскоростью пролетают неоновые космолеты.

[Источник](<generation_sources/gemini_stork/generation_details.json>)

Статус: Успешно сгенерировано (Success). Точная модель: не установлена.

Референс: Пользовательское изображение (26567.png)

```text
A tired white stork carrying a sagging net with glowing orbs struggling to fly out of heavy clouds at the bottom of the frame, flapping wings heavily. Sleek futuristic spaceships zoom past overhead at extreme speed in the upper sky leaving neon light trails. Vertical 9:16 aspect ratio, clean image without any text, letters, or logos
```

Идентификатор результата из сводки (не проверен): `http://googleusercontent.com/generated_video_content/4703822479141048157`.

### gemini_stork / stork-5 — Новый сценарий: Аист вылетает из обломков, с ним ровняются два космолета с ИИ-роботами за штурвалом. Космолеты резко ускоряются и уходят в точку, а аист роняет один из шариков.

[Источник](<generation_sources/gemini_stork/generation_details.json>)

Статус: Превышен лимит генерации (Quota Exceeded). Точная модель: не установлена.

Референс: Пользовательское изображение (26567.png)

```text
A white stork carrying a sagging net of glowing orbs flies out from debris and wreckage. Two sleek spaceships driven by AI robots at the steering wheels pull up alongside the stork, then rapidly accelerate forward. The camera turns to reveal the spaceships shrinking into the distance as a tiny point of light, while the stork slowly flies along, dropping one of the glowing orbs from the net. Vertical 9:16 aspect ratio, clean image without any text, letters, or logos
```

Идентификатор результата из сводки (не проверен): `http://googleusercontent.com/generated_video_content/1165661417998847355`.

### gemini_fire / fire-1 — Огонь AI — итерация 1

[Источник](<generation_sources/gemini_fire/generation_history.json>)

Статус: Success. Точная модель: не установлена.

Запрос пользователя: Сгенери видео что оно начиналось с этой картинки и заканчивалась, зацикленно видео где только огонь анамирован

Референс: 26873.png

```text
Seamlessly looping animation where only the blue fire with the text AI in the hand is flickering and burning animatedly, while the rest of the character and background remains completely static, video language Russian
```

Идентификатор результата из сводки (не проверен): `http://googleusercontent.com/generated_video_content/10956677535435591445`.

### gemini_fire / fire-2 — Огонь AI — итерация 2

[Источник](<generation_sources/gemini_fire/generation_history.json>)

Статус: Success. Точная модель: не установлена.

Запрос пользователя: Видео 3:4 соотношение

Референс: 26873.png

```text
Seamlessly looping animation in 3:4 aspect ratio where only the blue fire with the text AI in the hand is flickering and burning animatedly, while the rest of the character and background remains completely static, video language Russian
```

Идентификатор результата из сводки (не проверен): `http://googleusercontent.com/generated_video_content/11678346155341770777`.

### gemini_fire / fire-3 — Огонь AI — итерация 3

[Источник](<generation_sources/gemini_fire/generation_history.json>)

Статус: Success. Точная модель: не установлена.

Запрос пользователя: Человек молчит

Референс: 26873.png

```text
make the person completely silent with mouth closed and static, seamlessly looping animation in 3:4 aspect ratio where only the blue fire in the hand is animatedly burning and flickering
```

Идентификатор результата из сводки (не проверен): `http://googleusercontent.com/generated_video_content/3008906743293916940`.

### gemini_tiger / tiger-1 — Программист и дух-тигр — итерация 1

[Источник](<generation_sources/gemini_tiger/video_generation_history.md>)

Статус: Видео успешно создано. Точная модель: не установлена.

```text
Animate this image with extremely subtle motion. Fixed camera with no zoom, crop, pan, or camera movement, scaled down uniformly to 75% of the frame, perfectly centered, showing the full illustration without cropping. The ghostlike spirit behind gently floats up and down in the air. Both the human developer and the spirit continuously type on their keyboards with subtle, realistic finger movements. The human's body and face remain almost completely still. Floating code panels remain in place with subtle blinking code lines, and green energy accents gently pulse. Seamless animation loop. Video language Russian.
```

Идентификатор результата из сводки (не проверен): `http://googleusercontent.com/generated_video_content/10183960774905378336`.

### gemini_tiger / tiger-2 — Программист и дух-тигр — итерация 2

[Источник](<generation_sources/gemini_tiger/video_generation_history.md>)

Статус: Видео успешно создано. Точная модель: не установлена.

```text
Full illustration scaled down and contained completely within the frame without cropping any part, including the full ghost spirit at the top, full tiger, hands, and keyboards. Wide transparent margins on all sides to fit the entire illustration vertically inside the frame. The ghostlike spirit behind gently floats up and down in the air. Both the human developer and the spirit continuously type on their keyboards with subtle, realistic finger movements. Floating code panels remain in place with subtle blinking code lines, and green energy accents gently pulse. Seamless animation loop. Video language Russian.
```

Идентификатор результата из сводки (не проверен): `http://googleusercontent.com/generated_video_content/9616593392110582593`.

### gemini_tiger / tiger-3 — Программист и дух-тигр — итерация 3

[Источник](<generation_sources/gemini_tiger/video_generation_history.md>)

Статус: Достигнут лимит генераций. Точная модель: не установлена.

```text
Full illustration of a human developer typing on a keyboard with a tiger spirit typing behind him. The illustration is centered in the frame with wide black vertical and horizontal margins on all sides, ensuring 100% of the graphic including the top of the spirit's head and the bottom of the keyboard is visible with plenty of extra padding around it. Gentle animation of subtle typing and floating energy. Seamless loop. Video language Russian.
```

Идентификатор результата из сводки (не проверен): `http://googleusercontent.com/generated_video_content/7522265922855520058`.

### gemini_bento / bento-engineer — Инженер за обслуживанием терминала

[Источник](<generation_sources/gemini_bento/user_supplied_summary.json>)

Статус: Успешно сгенерировано и отредактировано — по сводке Gemini. Точная модель: не установлена.

Инструмент по сводке: `video_generation.generate_video_from_inputs`.

Референс: 26546_3.jpg — сотрудник в тёмно-синем поло с зелёными акцентами; 26544.jpg — брендированный терминал

```text
change the polo shirt color to dark navy blue with bright green trim as shown in 26546_3.jpg, vertical 9:16 aspect ratio, clean video without text, video language Russian
```

Идентификатор результата из сводки (не проверен): `http://googleusercontent.com/generated_video_content/11373166932662345389`.

### gemini_bento / bento-van — Выездной сервис / 24/7

[Источник](<generation_sources/gemini_bento/user_supplied_summary.json>)

Статус: Резервный концепт; запуск не подтверждён. Точная модель: не установлена.

```text
White service van with green brand stripes driving smoothly along modern city highway, sleek cinematic motion blur background, seamless driving loop, video language Russian
```

### gemini_bento / bento-office — Офисное оборудование и IT

[Источник](<generation_sources/gemini_bento/user_supplied_summary.json>)

Статус: Резервный концепт; запуск не подтверждён. Точная модель: не установлена.

```text
Modern green bank branch interior, self-service payment terminal screen displaying green checkmark animation, glowing LED lights, clean high-tech atmosphere, seamless loop, video language Russian
```

### gemini_bento / bento-monitoring — Мониторинг и аналитика

[Источник](<generation_sources/gemini_bento/user_supplied_summary.json>)

Статус: Резервный концепт; запуск не подтверждён. Точная модель: не установлена.

```text
Close up of high-tech digital map interface showing green dots and operational metrics for bank equipment, glowing green data lines, seamless loop animation, video language Russian
```

## Дополнение: книга и Knight Kitty — 29 октября 2026

Четыре поступивших ZIP подтверждены как побайтные дубликаты по SHA-256; повторно в реестр не включены. Два новых архива: book и knight.

### Книга: исходник и техническая обработка

Генерационный промпт и модель исходного MP4 неизвестны. Два WebM — производные одного MP4, а не новые ИИ-генерации. Упоминание GPT-6 в README относится к ассистенту, собравшему архив, и не определяет генератор видео. Кодеки — технические параметры из манифеста, не названия моделей.

- [source/video_original.mp4](<generation_registry/media/bdcbcf1c7acedad14157f94c1d69d5ec3730f196a56a52cdff694d8e4910915f.mp4>) — 1280×720, 10.005 с, h264/aac; Исходное видео пользователя; модель/сервис генерации не подтверждены. Совпадение с ассетом: не установлено; слайды: прямая связь не установлена.

- [results/kniga_transparent.webm](<generation_registry/media/345621d5fd14bc1b60abc27520f009a3985530b7e88e5039939f537653b60756.webm>) — 1280×720, 10.008 с, vp9/opus; Техническое преобразование уже существующего видео; не отдельная ИИ-генерация. Модель исходника неизвестна. Совпадение с ассетом: не установлено; слайды: прямая связь не установлена.

- [results/kniga_transparent_compact.webm](<generation_registry/media/5b914cd49860868648a248c2100f9e1983c4ff057ab6707c4c80ec922006780e.webm>) — 1280×720, 10.008 с, vp9/opus; Техническое преобразование уже существующего видео; не отдельная ИИ-генерация. Модель исходника неизвестна. Совпадение с ассетом: не установлено; слайды: прямая связь не установлена.

[Точные реплики пользователя про книгу](<generation_sources/book/prompts/01_actual_dialogue.md>)

[Реконструкция технического задания — НЕ оригинальный промпт](<generation_sources/book/prompts/02_reconstructed_processing_task.md>)

[Связанные реконструкции других промптов — не включены в общий счёт](<generation_sources/book/prompts/03_related_prompts_other_assets.md>)

### Knight Kitty vs Dragon

Добавлено 6 результатов генерации с полными текстами промптов по манифесту. Точная версия image_gen неизвестна. 2 исходных референса и 1 кадр HTML сохранены отдельно; исходные HTML в ZIP отсутствуют.

#### knight-1: Итоговая композиция VS

[Результат PNG](<generation_registry/media/18b94b42d6cc2a8c0765fbc28ead17a35344bf08cc3d818b491990cc13556844.png>)

gen_id: `c7e68dda-56a8-4866-9172-6e548382cd7b`. Совпадение с ассетом: не установлено; слайды: прямая связь не установлена.

```text
Create a dramatic pre-fight versus splash screen in the style of a fighting game intro. Image A is the visual reference for the knight cat character: use a cute small orange kitten wearing silver medieval armor and a light cape, holding a sword, preserving the adorable brave look. Place this knight cat on the RIGHT side of the frame in a fighting stance, facing left. Image B is a composition and mood reference for a versus screen: use a bold cinematic head-to-head layout with two fighters facing each other and a large glowing fiery "VS" in the center. On the LEFT side, depict a powerful dragon opponent facing right. The dragon should feel intimidating and battle-ready, with fantasy styling that matches the dramatic fighting-game presentation. Put both characters against a misty battlefield with heavy fog, moody atmosphere, and a dark fantasy combat setting. Make it feel like a polished game matchup screen, with strong contrast, dynamic lighting, and an epic showdown vibe. Do not copy the exact human fighters from Image B; only use its layout and versus-screen energy.
```

#### knight-2: Отдельный Knight Kitty

[Результат PNG](<generation_registry/media/147d5d686b616893c888959185b477ab415b982ec080eb4205fb652f97e018f0.png>)

gen_id: `8b6fb5f4-9ffd-422a-bf09-034cc61bd41d`. Совпадение с ассетом: не установлено; слайды: прямая связь не установлена.

```text
Create a standalone cutout asset of the kitten knight from the previously generated versus scene. Image A is the main style and character reference: match the same cute orange tabby kitten, silver medieval armor, cream cape, pink bow near the ear, determined expression, and sword. Generate only the knight kitty as the subject, full body, facing left in a battle-ready pose, with no other elements. Keep the visual style cinematic fantasy game art, highly detailed, clean edges, and suitable for compositing. Transparent background.
```

#### knight-3: Первая версия дракона с обрезанием

[Результат PNG](<generation_registry/media/5421b00c296b430a5d674465bc5fbbb821334500e72f5b41aa945cca12dc33a2.png>)

gen_id: `87b20d81-a882-409d-b72f-f65ff1cfd495`. Совпадение с ассетом: не установлено; слайды: прямая связь не установлена.

```text
Create a standalone cutout asset of the dragon from the previously generated versus scene. Image A is the main style and creature reference: match the same huge menacing dragon with dark charcoal and deep red scales, glowing orange eyes, layered horns and spikes, roaring mouth with fiery glow, and cinematic fantasy rendering. Generate only the dragon as the subject, facing right, with no other elements. Keep the visual style cinematic fantasy game art, highly detailed, clean edges, and suitable for compositing. Transparent background.
```

#### knight-4: Надпись VS

[Результат PNG](<generation_registry/media/077149ba55f7a50f0343108c7c99d8c90d8fb596fbde4a527c61969473d7cc7b.png>)

gen_id: `6996e97f-ddf2-4dc2-b439-62b83396ea2b`. Совпадение с ассетом: не установлено; слайды: прямая связь не установлена.

```text
Create a standalone cutout asset of the central fighting-game text from the previously generated versus scene. Image A is the main reference. Generate only a large stylized fiery "VS" with the same fighting-game look: thick brushstroke-like flame lettering, bright yellow-orange core, red glow, dark outline, and energetic ember sparks. No characters, no scenery. Clean edges for compositing. Transparent background.
```

#### knight-5: Фон

[Результат PNG](<generation_registry/media/6be844b9b9296a65ce5723c8c191175fcfcc6b74c701a61301b2db3aacde25ad.png>)

gen_id: `8781d46c-4a25-4205-8ed3-10595f918f33`. Совпадение с ассетом: не установлено; слайды: прямая связь не установлена.

```text
Create the background only from the previously generated versus scene, with the characters and the central VS removed. Image A is the main reference. Show a dramatic foggy battlefield background in the same style: dark ruined medieval battlefield, smoky mist, gothic castle silhouette with spires in the distance, full moon in a cloudy night sky, tattered red banners, rocky scorched ground, embers, haze, and cinematic fantasy-game atmosphere. No kitten, no dragon, no VS text. Make it a clean empty background plate that matches the previous scene.
```

#### knight-6: Дракон с исправленным кадрированием

[Результат PNG](<generation_registry/media/21afab8fdc61166d291a88739b439ee01425500e9e83a0153103e13dac15e799.png>)

gen_id: `e2550848-1eee-4f3c-870c-fadfde76e454`. Совпадение с ассетом: не установлено; слайды: прямая связь не установлена.

```text
Edit the provided image to fix the crop. Image A is the direct edit target: a fiery fantasy dragon isolated on a transparent background. Preserve the same dragon design, same black-and-red volcanic scales, glowing lava cracks, horns, wings, claws, roaring expression, and overall cinematic fantasy style. Expand and recompose the subject so the dragon is not awkwardly cut off: show a complete, well-framed dragon silhouette with enough empty margin around all edges, including the full head, jaw, wings, claws, torso, and tail. Keep it as a clean cutout asset on a transparent background, suitable for compositing. Do not add any scenery or text. Make the edges clean and natural, and avoid clipping any important body parts.
```

[Вся последовательность запросов Knight Kitty, включая HTML-анимацию](<generation_sources/knight/prompts.md>)

Два запроса на создание/правку HTML сохранены в technical_operations каталога и не считаются видеопромптами.
