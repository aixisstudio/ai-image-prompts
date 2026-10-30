# Ai Image Prompts

[English](README.md) | [Français](README.fr.md) | [Español](README.es.md) | **中文** | [日本語](README.ja.md) | [Русский](README.ru.md)

图像生成提示词画廊 — Midjourney、SD、Flux

# # # 即时画廊 #

可复制带有目标模型的提示. 通过PR向`prompts.md`贡献自己的力量.

□ □ 工作样式
QQ 样式 QQ 提示片段 QQ
|---|---|
图片: `shot on 35mm, golden hour, shallow depth of field, kodak portra`
说明 `flat vector illustration, bold shapes, limited palette`
三维 `octane render, isometric, soft studio lighting`
# # 像素 # # `16-bit pixel art, limited color palette, crisp outlines` # # # #
• `magazine cover layout, dramatic lighting, high contrast`编辑

□ □ □ 示例提示

** 杂项**
```
a lighthouse on a cliff in fog, muted blues and greys, editorial photography, moody --ar 16:9 --v 6
```

** SDXL / 流量**
```
minimalist workspace, warm morning light through blinds, a designer's desk with notebook and laptop, 85mm, soft shadows, photorealistic
```

** 图像(文本)**
```
neon sign reading "OPEN SOURCE" in cursive, dark wall background, night photography
```

#####小费
- 中途岛的光谱比参数(`--ar`);直接用于SDXL设定维度
- 负提示( SD): `blurry, watermark, extra fingers, text artifacts`
- 斜体种子,不是单词——小字变化比批发重写

# # # # 样式关键词欺骗表

效果 关键词
|---|---|
照片真实 `photorealistic, 85mm, f/1.8, natural light`
电影 `cinematic still, anamorphic, Kodak Portra`
三维 `octane render, subsurface scattering, studio HDRI`
`flat vector, limited palette, editorial illustration` 请检查date=中的日期值 (帮助)
`1970s photograph, film grain, faded colors` 请检查access-date=中的日期值 (帮助)

□□□□ 中途岛抛物

{\fn黑体\fs22\bord1\shad0\3aHBE\4aH00\fscx67\fscy66\2cHFFFFFF\3cH808080}你觉得呢?
|---|---|
`--ar 16:9` 光谱比
* `--stylize 250` 艺术自由(0-1000) *
`--chaos 30` 网格之间的变化
`--no text, watermark` 负速率
`--style raw` 减 MJ - opinion
`--cref [url]` 字符参考
`--sref [url]` 样式参考

□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□□

`rule of thirds` → `negative space` → `leading lines` → `dutch angle` → `low-angle hero shot` → `macro detail` → `rim lighting` → `golden hour` → `blue hour` → `chiaroscuro`

##### 工具

- **Flux**——开放重量,最佳排印
- **SDXL/SD3.5**——可通过LORAs定制
- **ComfyUI**——节点控制
-**InvokeAI**——当地UI磨损
- ** Fooocus** - 死气沉沉的SDXL

---
## 贡献

欢迎提交 Pull Request，我们会审查并合并。由 [aixisstudio](https://github.com/aixisstudio) 维护，他也是开源应用防火墙 [Snitch](https://github.com/aixisstudio/Snitch) 的作者。

## 许可证: MIT
