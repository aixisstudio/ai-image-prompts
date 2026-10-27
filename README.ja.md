# Ai Image Prompts

[English](README.md) | [Français](README.fr.md) | [Español](README.es.md) | [中文](README.zh-CN.md) | **日本語** | [Русский](README.ru.md)

画像生成プロンプト集

_詳細なコンテンツ（リスト・リンク・説明）は保守のため英語です。以下のセクションがガイドになります。_

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

---
## 貢献

プルリクエストを歓迎します。レビューしてマージします。[aixisstudio](https://github.com/aixisstudio) による管理 — オープンソースのアプリケーションファイアウォール [Snitch](https://github.com/aixisstudio/Snitch) の作者です。

## ライセンス: MIT
