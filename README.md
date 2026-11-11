# pgfornament-han 2026/11/11
A pgfornament library for Chinese traditional motifs and patterns. We also provide three beamer themes namely XiaoShan, HeavenlyClouds and TianQing based on these motifs. With some modifications, these themes can also be used to create posters using the `beamerposter` package. Sample .tex files for beamer presentations and posters are provided; or [start editing your own presentations and posters on Overleaf](https://github.com/liantze/pgfornament-han/wiki) with these themes.

以 pgfornament 宏包的机制，实现绘制汉风图纹。在此基础上设计了三款beamer主题：「萧山」(XiaoShan)、「神马浮云」(HeavenlyClouds)、「天青」(TianQing)，并可略加修改应用在海报设计上。详情请参考范例 .tex 文档，或[从这里的快速链接在Overleaf上打开模板](https://github.com/liantze/pgfornament-han/wiki)编辑自己的项目。

## Maintainers 宏包维护
LianTze Lim 林莲枝 (liantze@gmail.com)

## Contributors 开发人员
Chennan Zhang (23637935@qq.com) drew the motifs using a CAD application,
re-drew them in `TikZ`, and granted permission for these to be turned into
a library suitable for use with the `pgfornament` package by LianTze Lim.

所有图纹均由张晨南以 CAD 设计、以TikZ绘制，再由林莲枝转为适用 pgfornament 机制的宏包代码。

## License 许可协议
[LaTeX Project Public License (LPPL 1.3c)](https://www.latex-project.org/lppl/lppl-1-3c/)

## Brief change log
### 2024-10-22
- Adds samples of posters using the Xiaoshan, HeavenCLouds and TianQing themes.

### 2026-11-11
- Patch for make compatible with upstream changes in `pgfornament`.

### 2023-10-29
- `cncolours.sty` now has more colour names, loaded using package options `cas-rgb(*)` and `cas-cmyk(*)`
- Beamer colours in HeavenlyClouds and TianQing themes are now easier to customise.

### 2023-04-23
- TianQing theme added.
- Fixed block title spacing-related bug in XiaoShan theme.

### 2019-08-10
- Adds a horse motif `\pgfornamenthan{78}`. Used as the progress bar marker in the HeavenlyClouds beamer theme, as befitting its Chinese name 神马浮云.

### 2019-07-24
- Small bug fix for HeavenlyClouds to allow multiple `\section`.

### 2018-05-15
- Added Traditional Chinese names and 3 new colours to `cncolours.sty` (v1.1)
 - Added a new Beamer theme, HeavenlyClouds, using `pgfornament-han` elements

 ### 0.32 (2018-04-09) 
 - Changed to date versioning for the package bundle, as it now contains multiple LaTeX styles
 - Added Xiaoshan beamer theme as a demonstration of using the ornaments.

### 0.31 (2018-04-04)
- The package documentation is now compiled with Fandol to avoid font problems when viewed on some computers. 
- Information about colours provided by the `cncolours.sty` package is now available as an appendix.

### 0.3 (2018-04-01)
- Renamed `pgfornamenthan.sty` to `pgfornament-han.sty` and correspondingly the documentation file.
- Initial submission to CTAN.

### 0.2 (2018-02-11)
- Adds cloud ornaments.

### 0.1 (2017-12-27)
- Initial version on Github with 32 ornaments.