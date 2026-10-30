# Ai Image Prompts

[English](README.md) | [Français](README.fr.md) | [Español](README.es.md) | [中文](README.zh-CN.md) | **日本語** | [Русский](README.ru.md)

画像生成プロンプト集

## 中国のプロンプトギャラリー

ターゲットモデルでコピー可能なプロンプト。 `prompts.md` に PR で自分に貢献します。

## 働くスタイル
| スタイル | プロンプト |
|---|---|
| 写真 | `shot on 35mm, golden hour, shallow depth of field, kodak portra` |
| イラスト | `flat vector illustration, bold shapes, limited palette` |
| 3D | `octane render, isometric, soft studio lighting` | 3D | 3D | `octane render, isometric, soft studio lighting` | 3D | 3D | 3D | 3D | 3D | 3D | 3D | 4D | 3D | 3D | 3D | 3D | 3D | 3D | 3D | 3D | 3D | 3D | 3D | 3D | 3D | 3D | 3D | 3D | 3D | 3D | 3D | 4D | 3D | 3D | 3D | 3D | 3D | 3D | 3D | 3D | 3D | 3D | 3D | 3D | 3D | 4D | 4D | 4D | 4D | 4D | 4D | 4D | 4D | 4D | 4D | 4D | 4D | 4D | 4D | 4D | 4D | 4D | 4D | 4D | 4D | 4D | 4D | 4D | 4D | 4D | 4D | 4D | 4D | 4D | 4D | 4D | 4D | 4D | 4D | 4D | 4D | 4D | 4D
| ピクセル | `16-bit pixel art, limited color palette, crisp outlines` |
| 編集 | `magazine cover layout, dramatic lighting, high contrast` |

## 🧪 例プロンプト

**シドニー**
```
a lighthouse on a cliff in fog, muted blues and greys, editorial photography, moody --ar 16:9 --v 6
```

**SDXL/変化**
```
minimalist workspace, warm morning light through blinds, a designer's desk with notebook and laptop, 85mm, soft shadows, photorealistic
```

**イデグラム(テキスト)**
```
neon sign reading "OPEN SOURCE" in cursive, dark wall background, night photography
```

## 📐のヒント
- MidjourneyのAspectの比率のparams (`--ar`);SDXLセット次元のために直接
- 負のプロンプト(SD): `blurry, watermark, extra fingers, text artifacts`
- 種子を反復し、言葉ではなく - 小さな単語は卸売の書き換えを打ちます

## トレンドスタイルキーワードチートシート

| 効果 | キーワード |
|---|---|
| フォトリアル | `photorealistic, 85mm, f/1.8, natural light` |
| 映画 | `cinematic still, anamorphic, Kodak Portra` |
| 3D | `octane render, subsurface scattering, studio HDRI` | 3D | 3D | `octane render, subsurface scattering, studio HDRI` | 3D | 3D | 3D | 3D | 3D | 3D | 3D | 4D | 3D | 3D | 3D | 3D | 3D | 3D | 3D | 3D | 3D | 3D | 3D | 3D | 3D | 3D | 3D | 3D | 3D | 3D | 3D | 4D | 3D | 3D | 3D | 3D | 3D | 3D | 3D | 3D | 3D | 3D | 3D | 3D | 3D | 4D | 4D | 4D | 4D | 4D | 4D | 4D | 4D | 4D | 4D | 4D | 4D | 4D | 4D | 4D | 4D | 4D | 4D | 4D | 4D | 4D | 4D | 4D | 4D | 4D | 4D | 4D | 4D | 4D | 4D | 4D | 4D | 4D | 4D | 4D | 4D | 4D | 4D
| イラスト | `flat vector, limited palette, editorial illustration` |
| ヴィンテージ | `1970s photograph, film grain, faded colors` |

## ⚙ ️ ️

| パラム | はく | はく |
|---|---|
| `--ar 16:9` | アスペクト比 |
| `--stylize 250` | 芸術的自由(0-1000) |
| `--chaos 30` | 格子のバリエーション |
| `--no text, watermark` | ネガティブ・プロンプト |
| `--style raw` | 少ないMJ-opinionated |
| `--cref [url]` | キャラクターリファレンス |
| `--sref [url]` | スタイルリファレンス |

## ️️ コンポジション vocab

`rule of thirds`・`negative space`・`leading lines`・`dutch angle`・`low-angle hero shot`・`macro detail`・`rim lighting`・`golden hour`・`blue hour`・`chiaroscuro`

## 🧩 ツール

-**Flux** - オープン重量、最高のタイポグラフィ
- **SDXL/SD3.5** — LoRAsでカスタマイズ可能
- **ComfyUI** — ノードグラフ制御
- **InvokeAI** — 洗練されたローカルUI
- **Fooocus** — デッドスimple SDXL

---
## 貢献

プルリクエストを歓迎します。レビューしてマージします。[aixisstudio](https://github.com/aixisstudio) による管理 — オープンソースのアプリケーションファイアウォール [Snitch](https://github.com/aixisstudio/Snitch) の作者です。

## ライセンス: MIT
