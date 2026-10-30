# Ai Image Prompts

[English](README.md) | **Français** | [Español](README.es.md) | [中文](README.zh-CN.md) | [日本語](README.ja.md) | [Русский](README.ru.md)

Galerie de prompts image avec résultats — Midjourney, SD, Flux

La galerie rapide

Invitations à copier avec des modèles cibles. Contribuez le vôtre via PR à `prompts.md`.

Styles qui fonctionnent
Style
|---|---|
Photo: `shot on 35mm, golden hour, shallow depth of field, kodak portra`
Illustration
CdPH0X
Pixel : `16-bit pixel art, limited color palette, crisp outlines`
Éditorial

Exemples d'invites

**Midjourney**
```
a lighthouse on a cliff in fog, muted blues and greys, editorial photography, moody --ar 16:9 --v 6
```

**SDXL / Flux**
```
minimalist workspace, warm morning light through blinds, a designer's desk with notebook and laptop, 85mm, soft shadows, photorealistic
```

**Idéogramme (texte)**
```
neon sign reading "OPEN SOURCE" in cursive, dark wall background, night photography
```

Conseils
- Params de rapport d'aspect (`--ar`) sur Midjourney; pour les dimensions de réglage SDXL directement
- Invitations négatives (SD) : `blurry, watermark, extra fingers, text artifacts`
- Itérer les graines, pas les mots — petits changements de mots battre les réécritures de gros

Style mots clés triche-feuille

Mots clés
|---|---|
Photoréalistes `photorealistic, 85mm, f/1.8, natural light`
Filmique
CdPH0X
Illustré
Vintage

Params de Midjourney

Le param, ça fait quoi ?
|---|---|
Taux d'aspect
`--stylize 250`: Liberté artistique (0-1000)
`--chaos 30`
`--no text, watermark`
Moins d'opinions MJ
Référence des caractères
`--sref [url]`

Composition Vocab

`rule of thirds` · `negative space` · `leading lines` · `dutch angle` · `low-angle hero shot` · `macro detail` · `rim lighting` · `golden hour` · `blue hour` · `chiaroscuro`

Outils

- ** Flux** — poids ouverts, meilleure typographie
- **SDXL/SD3.5** — personnalisable via LoRAs
- **ComfyUI** — contrôle des nœuds
- **InvokeAI** — UI locale polie
- **Fooocus** — simple et mort SDXL

---
## Contribuer

Les pull requests sont les bienvenues : ouvre une PR, elle sera relue et fusionnée. Maintenu par [aixisstudio](https://github.com/aixisstudio), auteur de [Snitch](https://github.com/aixisstudio/Snitch), pare-feu applicatif open source.

## Licence: MIT
