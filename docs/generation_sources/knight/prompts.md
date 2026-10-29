# Промпты и результаты — Knight Kitty vs Dragon

Оригинальные формулировки промптов из доступной истории генерации. Версии моделей, которые нельзя точно установить, отмечены как неизвестные.

## 1. Полная VS-сцена

**Тип:** image_generation
**Модель:** OpenAI image_gen (в метаданных указано «DALL-E generation»; точная версия модели не раскрыта)
**Версия:** unknown
**Generation ID:** `c7e68dda-56a8-4866-9172-6e548382cd7b`
**Источники:** `01_references/kitty_reference.png`, `01_references/fighting_game_reference.png`
**Результат:** `02_generations/01_versus_composite.png`

**Промпт / запрос пользователя:**

```text
Create a dramatic pre-fight versus splash screen in the style of a fighting game intro. Image A is the visual reference for the knight cat character: use a cute small orange kitten wearing silver medieval armor and a light cape, holding a sword, preserving the adorable brave look. Place this knight cat on the RIGHT side of the frame in a fighting stance, facing left. Image B is a composition and mood reference for a versus screen: use a bold cinematic head-to-head layout with two fighters facing each other and a large glowing fiery "VS" in the center. On the LEFT side, depict a powerful dragon opponent facing right. The dragon should feel intimidating and battle-ready, with fantasy styling that matches the dramatic fighting-game presentation. Put both characters against a misty battlefield with heavy fog, moody atmosphere, and a dark fantasy combat setting. Make it feel like a polished game matchup screen, with strong contrast, dynamic lighting, and an epic showdown vibe. Do not copy the exact human fighters from Image B; only use its layout and versus-screen energy.
```

## 2. Knight Kitty, отдельный PNG

**Тип:** image_generation
**Модель:** OpenAI image_gen (DALL-E generation metadata)
**Версия:** unknown
**Generation ID:** `8b6fb5f4-9ffd-422a-bf09-034cc61bd41d`
**Источники:** `02_generations/01_versus_composite.png`
**Результат:** `02_generations/02_kitty_cutout.png`

**Промпт / запрос пользователя:**

```text
Create a standalone cutout asset of the kitten knight from the previously generated versus scene. Image A is the main style and character reference: match the same cute orange tabby kitten, silver medieval armor, cream cape, pink bow near the ear, determined expression, and sword. Generate only the knight kitty as the subject, full body, facing left in a battle-ready pose, with no other elements. Keep the visual style cinematic fantasy game art, highly detailed, clean edges, and suitable for compositing. Transparent background.
```

## 3. Дракон, первая версия

**Тип:** image_generation
**Модель:** OpenAI image_gen (DALL-E generation metadata)
**Версия:** unknown
**Generation ID:** `87b20d81-a882-409d-b72f-f65ff1cfd495`
**Источники:** `02_generations/01_versus_composite.png`
**Результат:** `02_generations/03_dragon_cutout_first.png`

**Промпт / запрос пользователя:**

```text
Create a standalone cutout asset of the dragon from the previously generated versus scene. Image A is the main style and creature reference: match the same huge menacing dragon with dark charcoal and deep red scales, glowing orange eyes, layered horns and spikes, roaring mouth with fiery glow, and cinematic fantasy rendering. Generate only the dragon as the subject, facing right, with no other elements. Keep the visual style cinematic fantasy game art, highly detailed, clean edges, and suitable for compositing. Transparent background.
```

## 4. VS на прозрачном фоне

**Тип:** image_generation
**Модель:** OpenAI image_gen (DALL-E generation metadata)
**Версия:** unknown
**Generation ID:** `6996e97f-ddf2-4dc2-b439-62b83396ea2b`
**Источники:** `02_generations/01_versus_composite.png`
**Результат:** `02_generations/04_vs_cutout.png`

**Промпт / запрос пользователя:**

```text
Create a standalone cutout asset of the central fighting-game text from the previously generated versus scene. Image A is the main reference. Generate only a large stylized fiery "VS" with the same fighting-game look: thick brushstroke-like flame lettering, bright yellow-orange core, red glow, dark outline, and energetic ember sparks. No characters, no scenery. Clean edges for compositing. Transparent background.
```

## 5. Пустой фон поля боя

**Тип:** image_generation
**Модель:** OpenAI image_gen (DALL-E generation metadata)
**Версия:** unknown
**Generation ID:** `8781d46c-4a25-4205-8ed3-10595f918f33`
**Источники:** `02_generations/01_versus_composite.png`
**Результат:** `02_generations/05_battlefield_background.png`

**Промпт / запрос пользователя:**

```text
Create the background only from the previously generated versus scene, with the characters and the central VS removed. Image A is the main reference. Show a dramatic foggy battlefield background in the same style: dark ruined medieval battlefield, smoky mist, gothic castle silhouette with spires in the distance, full moon in a cloudy night sky, tattered red banners, rocky scorched ground, embers, haze, and cinematic fantasy-game atmosphere. No kitten, no dragon, no VS text. Make it a clean empty background plate that matches the previous scene.
```

## 6. Исправление обрезания дракона

**Тип:** image_edit
**Модель:** OpenAI image_gen (DALL-E generation metadata)
**Версия:** unknown
**Generation ID:** `e2550848-1eee-4f3c-870c-fadfde76e454`
**Источники:** `02_generations/03_dragon_cutout_first.png`
**Результат:** `02_generations/06_dragon_cutout_fixed.png`

**Промпт / запрос пользователя:**

```text
Edit the provided image to fix the crop. Image A is the direct edit target: a fiery fantasy dragon isolated on a transparent background. Preserve the same dragon design, same black-and-red volcanic scales, glowing lava cracks, horns, wings, claws, roaring expression, and overall cinematic fantasy style. Expand and recompose the subject so the dragon is not awkwardly cut off: show a complete, well-framed dragon silhouette with enough empty margin around all edges, including the full head, jaw, wings, claws, torso, and tail. Keep it as a clean cutout asset on a transparent background, suitable for compositing. Do not add any scenery or text. Make the edges clean and natural, and avoid clipping any important body parts.
```

## 7. Заставка по Figma

**Тип:** html_creation
**Модель:** ChatGPT GPT-6 (среда текущей беседы; точная конфигурация на момент первоначальной сборки HTML не подтверждена)
**Версия:** unknown
**Результат:** `vibe_coding_vs_sdd_fighter_intro.html (недоступен для включения в текущий архив)`
**Figma:** https://www.figma.com/design/nwNQgVX23vume5ahkAwIBt/Untitled?node-id=190-224
**Изменения:** Фрейм Figma 1920x1080; подписи VIBE CODING и SDD. Фон статичен, герои въезжают, затем VS. Один HTML с встроенными изображениями.

**Промпт / запрос пользователя:**

```text
теперь создай html внедрив туда ассеты и чтобы была анимация слева появлется дракон выезжает слева направо а ктик выезажает спарава налево между ними ярко появляется vs фон все время отображается
```

## 8. Убрать дёргание после выезда

**Тип:** html_edit
**Модель:** ChatGPT GPT-6 (текущая беседа; точная конфигурация прошлого вызова неизвестна)
**Версия:** unknown
**Результат:** `vibe_coding_vs_sdd_fighter_intro_no_jitter.html (недоступен для включения в текущий архив)`
**Изменения:** Убраны overshoot-ключевые кадры 72/87% у dragon-arrive и 74/89% у kitty-arrive; финал статичный.

**Промпт / запрос пользователя:**

```text
убери лишнюю анимацию когда они выехали чтобы больше не дергались
```
