# Ai Image Prompts

[English](README.md) | [Français](README.fr.md) | [Español](README.es.md) | [中文](README.zh-CN.md) | [日本語](README.ja.md) | **Русский**

Галерея промптов для генерации изображений

##  ️ Быстрая галерея

Копируемые подсказки с целевыми моделями. Внесите свой собственный вклад через PR в `prompts.md`.

##Стили, которые работают
Стиль: Быстрый фрагмент
|---|---|
Фото: `shot on 35mm, golden hour, shallow depth of field, kodak portra`
Иллюстрация: `flat vector illustration, bold shapes, limited palette`
| 3D | `octane render, isometric, soft studio lighting`
Пиксель, `16-bit pixel art, limited color palette, crisp outlines`
Издательство: `magazine cover layout, dramatic lighting, high contrast`

##  Example Пример подсказок

**Средиземноморье**
```
a lighthouse on a cliff in fog, muted blues and greys, editorial photography, moody --ar 16:9 --v 6
```

**SDXL/Flux**
```
minimalist workspace, warm morning light through blinds, a designer's desk with notebook and laptop, 85mm, soft shadows, photorealistic
```

**Идеограмма (текст)**
```
neon sign reading "OPEN SOURCE" in cursive, dark wall background, night photography
```

## ps Советы
- парам соотношений сторон (`--ar`) на Midjourney; для SDXL устанавливаются размеры непосредственно
Отрицательные подсказки (SD): `blurry, watermark, extra fingers, text artifacts`
Итерационные семена, а не слова — небольшие изменения слов бьют оптовые переписывания

##  Style Ключевые слова чит-лист

| Эффект | Ключевые слова
|---|---|
Оригинальное название: `photorealistic, 85mm, f/1.8, natural light`
Оригинальное название: `cinematic still, anamorphic, Kodak Portra`
| 3D | `octane render, subsurface scattering, studio HDRI`
Изображение: `flat vector, limited palette, editorial illustration`
| Винтаж | `1970s photograph, film grain, faded colors`

##  ️ Мидджори парамс

[Перенаправлено с Dos]
|---|---|
| `--ar 16:9` | Соотношение сторон |
`--stylize 250` - художественная свобода (0-1000)
| `--chaos 30` | Изменение между сетками |
| `--no text, watermark` | Отрицательная подсказка |
↑ `--style raw` | Less MJ-opinionated
| `--cref [url]` | Характеристика
| `--sref [url]` | Ссылка на стиль

##  ️ Состав вокаба

`rule of thirds` · `negative space` · `leading lines` · `dutch angle` · `low-angle hero shot` · `macro detail` · `rim lighting` · `golden hour` · `blue hour` · `chiaroscuro`

## s Инструменты

**Flux** — открытые веса, лучшая типография
**SDXL/SD3.5** — настраивается с помощью LoRA
- **ComfyUI** - управление узлом
**InvokeAI** — полированный локальный интерфейс
**Fooocus** — SDXL

---
## Участие

Pull request'ы приветствуются — открой PR, он будет проверен и принят. Ведёт [aixisstudio](https://github.com/aixisstudio), автор [Snitch](https://github.com/aixisstudio/Snitch) — open-source application firewall.

## Лицензия: MIT
