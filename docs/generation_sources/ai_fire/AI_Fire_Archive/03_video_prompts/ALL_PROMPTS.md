# Все промпты для анимации бирюзового огня AI

> Собрано по переписке на 28.10.2026. Это **предложенные текстовые промпты**, а не отчёт об успешной генерации видео.
> Ни одна модель для генерации видео не была запущена непосредственно в этом чате; пользователем упоминались тесты в Gemini.

## Обозначения

- **Gemini / Veo** — целевой сервис. Конкретная использованная версия Veo неизвестна.
- **Seedance** — целевая модель в сервисе видеогенерации; версия не указана.
- **Kling AI** — целевой сервис с выделением области Motion Brush; версия не указана.

## Индекс

- **P01** — Gemini / Veo: Первый подробный промпт: пламя и частицы
- **P02** — Seedance: Первый подробный промпт для Seedance
- **P03** — Seedance: Уточнение: исключительно плавное пламя
- **P04** — Seedance: Короткая добавка: максимально спокойное пламя
- **P05** — Seedance: Короткая добавка: немного более живое
- **P06** — Seedance: Короткий negative prompt против рывков
- **P07** — Gemini / Veo: Подробный промпт с полным кадрированием
- **P08** — Gemini / Veo: Пламя вместо желе: физика горения
- **P09** — Gemini / Veo: Очень короткий вариант: огонь
- **P10** — Gemini / Veo: Короткий вариант: огонь + стабильный шар
- **P11** — Gemini / Veo: Минимальный вариант: огонь
- **P12** — Gemini / Veo: Оживить фото, короткий вариант 1
- **P13** — Gemini / Veo: Оживить фото, короткий вариант 2
- **P14** — Gemini / Veo: Оживить фото, короткий вариант 3
- **P15** — Gemini / Veo: Оживить фото, финальная короткая версия
- **P16** — Gemini / Veo: Пламя, частицы, осколки в области ладони
- **P17** — Gemini / Veo: Чуть подробнее: пламя, частицы, осколки
- **P18** — Gemini / Veo: Ультракороткая версия с частицами
- **P19** — Gemini / Veo: Финальная версия с частицами, повтор в ответе
- **P20** — Kling AI / Motion Brush: Подсказка для областной анимации

---

## P01 — Первый подробный промпт: пламя и частицы
**Адресат:** Gemini / Veo

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

## P02 — Первый подробный промпт для Seedance
**Адресат:** Seedance

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

## P03 — Уточнение: исключительно плавное пламя
**Адресат:** Seedance

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

## P04 — Короткая добавка: максимально спокойное пламя
**Адресат:** Seedance

```text
Motion intensity: very low. Prioritize smoothness and stability over visible animation.
```

## P05 — Короткая добавка: немного более живое
**Адресат:** Seedance

```text
Motion intensity: low. The flame should feel alive, but still very smooth and controlled.
```

## P06 — Короткий negative prompt против рывков
**Адресат:** Seedance

```text
Avoid strobing, jitter, frame-to-frame wobble, shape instability, sudden deformation, or noisy flicker.
```

## P07 — Подробный промпт с полным кадрированием
**Адресат:** Gemini / Veo

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

## P08 — Пламя вместо желе: физика горения
**Адресат:** Gemini / Veo

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

## P09 — Очень короткий вариант: огонь
**Адресат:** Gemini / Veo

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

## P10 — Короткий вариант: огонь + стабильный шар
**Адресат:** Gemini / Veo

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

## P11 — Минимальный вариант: огонь
**Адресат:** Gemini / Veo

```text
Real burning turquoise flame only.
Static character.
Full image in frame.
No crop.
No jelly motion.
Seamless loop.
```

## P12 — Оживить фото, короткий вариант 1
**Адресат:** Gemini / Veo

```text
Animate the image into a seamless loop.
Do not change the pose.
Keep the character still.
Only animate the turquoise fire.
Keep the full image visible.
No crop.
Static camera.
```

## P13 — Оживить фото, короткий вариант 2
**Адресат:** Gemini / Veo

```text
Animate this image as a seamless loop.
Do not change the pose.
Only animate the fire.
Keep the whole image in frame.
No crop.
```

## P14 — Оживить фото, короткий вариант 3
**Адресат:** Gemini / Veo

```text
Animate the photo.
Seamless loop.
Do not change the pose.
Only animate the fire.
Keep the full image visible.
```

## P15 — Оживить фото, финальная короткая версия
**Адресат:** Gemini / Veo

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

## P16 — Пламя, частицы, осколки в области ладони
**Адресат:** Gemini / Veo

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

## P17 — Чуть подробнее: пламя, частицы, осколки
**Адресат:** Gemini / Veo

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

## P18 — Ультракороткая версия с частицами
**Адресат:** Gemini / Veo

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

## P19 — Финальная версия с частицами, повтор в ответе
**Адресат:** Gemini / Veo

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

## P20 — Подсказка для областной анимации
**Адресат:** Kling AI / Motion Brush

```text
The turquoise magical fire burns naturally. Small flame tongues rise upward. Glowing particles and energy fragments slowly float upward. Smooth, continuous movement. The character and camera remain completely still.
```
