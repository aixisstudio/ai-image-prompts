# Ai Image Prompts

[English](README.md) | [Français](README.fr.md) | [Español](README.es.md) | [中文](README.zh-CN.md) | [日本語](README.ja.md) | **Русский**

Галерея промптов для генерации изображений

_Подробное содержимое (списки, ссылки, описания) ведётся на английском — разделы ниже помогут сориентироваться._

## 🖼️ The prompt gallery

Copyable prompts with target models. Contribute your own via PR to `prompts.md`.

## 🎨 Styles that work
| Style | Prompt fragment |
|---|---|
| Photo | `shot on 35mm, golden hour, shallow depth of field, kodak portra` |
| Illustration | `flat vector illustration, bold shapes, limited palette` |
| 3D | `octane render, isometric, soft studio lighting` |
| Pixel | `16-bit pixel art, limited color palette, crisp outlines` |
| Editorial | `magazine cover layout, dramatic lighting, high contrast` |

## 🧪 Example prompts

**Midjourney**
```
a lighthouse on a cliff in fog, muted blues and greys, editorial photography, moody --ar 16:9 --v 6
```

**SDXL / Flux**
```
minimalist workspace, warm morning light through blinds, a designer's desk with notebook and laptop, 85mm, soft shadows, photorealistic
```

**Ideogram (text)**
```
neon sign reading "OPEN SOURCE" in cursive, dark wall background, night photography
```

## 📐 Tips
- Aspect ratio params (`--ar`) on Midjourney; for SDXL set dimensions directly
- Negative prompts (SD): `blurry, watermark, extra fingers, text artifacts`
- Iterate seeds, not words — small word changes beat wholesale rewrites

## 🎨 Style keywords cheat-sheet

| Effect | Keywords |
|---|---|
| Photoreal | `photorealistic, 85mm, f/1.8, natural light` |
| Filmic | `cinematic still, anamorphic, Kodak Portra` |
| 3D | `octane render, subsurface scattering, studio HDRI` |
| Illustrated | `flat vector, limited palette, editorial illustration` |
| Vintage | `1970s photograph, film grain, faded colors` |

## ⚙️ Midjourney params

| Param | Does |
|---|---|
| `--ar 16:9` | Aspect ratio |
| `--stylize 250` | Artistic freedom (0-1000) |
| `--chaos 30` | Variation between grid |
| `--no text, watermark` | Negative prompt |
| `--style raw` | Less MJ-opinionated |
| `--cref [url]` | Character reference |
| `--sref [url]` | Style reference |

## 🖼️ Composition vocab

`rule of thirds` · `negative space` · `leading lines` · `dutch angle` · `low-angle hero shot` · `macro detail` · `rim lighting` · `golden hour` · `blue hour` · `chiaroscuro`

## 🧩 Tools

- **Flux** — open weights, best typography
- **SDXL/SD3.5** — customizable via LoRAs
- **ComfyUI** — node-graph control
- **InvokeAI** — polished local UI
- **Fooocus** — dead-simple SDXL

---
## Участие

Pull request'ы приветствуются — открой PR, он будет проверен и принят. Ведёт [aixisstudio](https://github.com/aixisstudio), автор [Snitch](https://github.com/aixisstudio/Snitch) — open-source application firewall.

## Лицензия: MIT
