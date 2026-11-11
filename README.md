# HOI4 / TNO Modding Resources · HOI4 / TNO 模组制作资源合集

Tutorials, documentation and tools for building TNO-style mods. 做 TNO 风格 mod 的教程、文档与工具合集。

**[网页版 / Web version](index.html)** · [English](en.html)

---

## Icons & Portraits / GFX

| Resource | Description | 说明 |
| --- | --- | --- |
| [TNO GFX Search](https://fallingstory.github.io/gfx-search/) | Search icons and textures across the whole mod by name. See the source image and asset path instantly — check here before making new assets. | 全模组 GFX 检索站：按名字搜图标、贴图，直接看到原图与资源路径，做资产前先在这查重。 |
| [Collin's Icon Guide (video)](https://www.youtube.com/watch?v=qdEh626E-7c) | A full walkthrough of drawing a TNO-style focus icon, using Realm of Ash as the example. | 以 Realm of Ash 为例，完整走一遍 TNO 风格国策图标的绘制流程。 |
| [HOI4 Portrait Tutorial (TNO/EoaNB style)](https://www.youtube.com/watch?v=UwEc_vno1IA) | From historical photo to TNO-style leader portrait: retouching and colouring workflow. | 从原始历史照片到 TNO 风格人物立绘的修图与上色流程。 |
| [Photo Restoration in 16 Minutes](https://www.youtube.com/watch?v=XZnm1JJj2pw) | Most portraits start as historical photos. Covers denoising, damage repair and colouring. | 立绘素材大多是历史照片，这期讲去噪、补损、上色。 |
| [Paint.NET Palette Import](https://www.getpaint.net/doc/latest/WorkingWithPalettes.html) | Official docs on importing a custom palette — handy for reusing the TNO font colours. | 把 TNO 字体配色做成调色板并导入的官方文档。 |
| [Portrait Workflow Chart](https://drive.google.com/file/d/1WavQAu7tUwVySOOeVOxTe0FRDB-wCyRc/view) | A branching flowchart from picking a photo, through retouching, to exporting DDS. | 从选图、修图到导出 DDS 的分支流程图。 |
| [Europeana](https://www.europeana.eu/en) | Aggregator of European archives — high-resolution historical photos and event imagery. | 欧洲档案馆聚合站，找高分辨率历史照片与事件图。 |

## Code · GUI & Scripting / 代码

| Resource | Description | 说明 |
| --- | --- | --- |
| [GUI Asset Guidelines (Wiki)](https://hoi4.paradoxwikis.com/Graphical_user_interface) | Sizes, naming, nine-slice slicing and import rules for GUI assets — the general baseline. | GUI 素材的尺寸、命名、九宫格切割与导入规范，通用基础。 |
| [Scripted GUI Guide](https://docs.google.com/document/d/1bcyw6ohpZXgUH89jQzwqBIuE_aqJcthDo9529Rqwzls/edit) | Writing scripted GUIs from scratch: triggers, effects and how they map to each other. | 从零写 scripted GUI：触发器与效果对照。 |
| [Official Scripted GUI Examples](https://steamcommunity.com/sharedfiles/filedetails/?id=1678247250) | Paradox's example collection — the most reliable starting point for learning the syntax. | Paradox 官方范例合集，学语法最稳的起点。 |
| [Scripted GUI (Wiki)](https://hoi4.paradoxwikis.com/Scripted_GUI) | Syntax overview and common pitfalls; read alongside the two entries above. | 语法总览与常见坑，和上面两份配合看。 |
| [Events (Wiki)](https://hoi4.paradoxwikis.com/Events) | Structure of events, news events and super events — start here for your first event. | 事件、新闻事件、超事件的基础结构，写第一个 event 从这里开始。 |
| [State Modding (Wiki)](https://hoi4.paradoxwikis.com/State_modding) | Data structures for creating and editing states, including state description panels. | 建州、改州、州介绍面板所需的数据结构。 |
| [NSB Armor Effects Cheatsheet](https://docs.google.com/document/d/1WiMwLlka6cioyIQB4hG4rNFZI8DZmvkEEvKcQyLzAVY/edit) | Quick reference for driving the new armour system from effects. | 新装甲系统在 effect 里的速查。 |
| [Intelligence Report Templates](https://docs.google.com/document/d/1B4lJnmyeYO5q8LkKKIZGdp3wwxSbB2D-YZwvyRrG-Ps/edit) | Ready-made templates and phrasing for writing intelligence report events. | 写 Intelligence Report 事件可直接套用的模板与措辞。 |
| [HOI4 Variables (Wiki)](https://hoi4.paradoxwikis.com/Variables) | Variable scopes and access patterns — required reading for complex effects. | 变量作用域与访问方式，写复杂 effect 必备。 |
| [CWTools HOI4 Config Reference](https://cwtools.github.io/cwtools-hoi4-config/) | The game script parsed into structured docs — the fastest way to check valid effect parameters. | 把游戏脚本解析成结构化文档，查 effect 合法参数特别快。 |
| [Script Profiler](https://forum.paradoxplaza.com/forum/threads/script-profiler-in-1-6-0.1158737/) | Run the game with -profile and read the report to find laggy effects. | 用 -profile 跑性能报告，定位卡顿的 effect。 |

## Tools & Plugins / 工具与插件

| Resource | Description | 说明 |
| --- | --- | --- |
| [draw.io Focus Tree Converter](https://flaxbeard.github.io/tno-draw-io-converter/) | Draw a focus tree in draw.io and convert it straight into HOI4 focus code. | 在 draw.io 里画国策树，一键转成 HOI4 focus 代码。 |
| [VSCode: HOI4 Mod Utilities](https://marketplace.visualstudio.com/items?itemName=Chaofan.hoi4modutilities) | Localisation and GFX preview plus syntax highlighting — strongly recommended. | 本地化与 GFX 预览、语法高亮，写 mod 强烈推荐。 |
| [GitLens (VSCode)](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens) | See who last touched each line — invaluable when tracking down regressions. | 查看每行代码的修改者，协调查错很好用。 |
| [OCRmyPDF](https://github.com/ocrmypdf/OCRmyPDF) | Adds a text layer to scanned PDFs so old documents become searchable. | 给扫描版 PDF 加文字层，方便检索旧资料。 |
| [Zotero](https://www.zotero.org/start) | Reference manager — keeps lore research and sources in order. | 文献管理，整理 lore 资料来源。 |
| [ShareX](https://getsharex.com/) | Screenshot, screen recording and GIF capture in one tool — great for tutorial images. | 截图、录屏、GIF 一体，做教程图和小样很方便。 |
| [Veed Subtitles](https://www.veed.io/) | Auto-generates and translates subtitles — useful when cutting archival footage. | 自动生成字幕并翻译，处理档案影像素材时用。 |
| [Political Pie Chart Generator](https://docs.google.com/spreadsheets/d/1EsLnfiwNbaV1OZgOSPdqMw425irVUneIkdnxFm3HQBQ/edit) | Fill in a Google Sheet and it generates parliament pie charts. | 在 Google Sheets 填数据即可生成议会饼图。 |

## Video Tutorials / 视频教程

| Resource | Description | 说明 |
| --- | --- | --- |
| [AI for HOI4 Modding](https://www.youtube.com/watch?v=pH_VpBs0mIk) | Practical demos of using AI to generate or rewrite scripts and help with assets. | 用 AI 生成或改写脚本、辅助做素材的实操演示。 |
| [[HOI4 Modding] Creating Custom GUI](https://www.youtube.com/watch?v=QvJ4h3XCXO8) | Builds a custom GUI window from scratch. | 从零搭一个自定义 GUI 窗口。 |
| [High Quality Maps with QGIS](https://www.youtube.com/watch?v=DPVKcQf0rik) | Using QGIS to produce state borders and map artwork. | 制作州界与地图素材的 QGIS 流程。 |

## Misc / 其他

| Resource | Description | 说明 |
| --- | --- | --- |
| [Title Case Tool](https://capitalizemytitle.com/) | Keeps focus names and localisation capitalisation consistent. | 统一 focus 名称与本地化的大小写风格。 |
| [Batch Rename Guide](https://www.maketecheasier.com/batch-rename-files-in-windows/) | Batch-renaming DDS and PNG files. | 批量处理 DDS / PNG 文件名时用。 |

---

## Suggested learning order / 建议学习顺序

1. Start with the GUI asset guidelines — correct sizes and naming save a lot of rework.
2. Watch the icon videos, then use GFX Search to match existing assets.
3. Begin scripting with the official Scripted GUI examples, then the variables and profiler entries.
4. Use the draw.io converter: lay the tree out first, generate code second.

<sub>中文：先看 GUI 规范 → 图标看视频 + GFX 搜索器 → 脚本从官方 Scripted GUI 示例入手 → 国策树用 draw.io 转换器。</sub>

## License

The list itself is released under CC0. All linked content belongs to its respective authors.

