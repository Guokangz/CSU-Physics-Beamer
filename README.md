# CSU Physics Beamer

A Beamer presentation template for physics academic talks at Central South University (中南大学物理学术报告).

Based on / forked from [Sakulyn/CSU-Beamer](https://github.com/Sakulyn/CSU-Beamer),
which is itself modified from [THU-beamer-template](https://github.com/FangWHao/THU-beamer-template)
and the SINTEF/Sapienza theme lineage
(original theme by Federico Zenith, SINTEF; adapted by Andrea Gasparini for Sapienza).

## Features

- 16:9 widescreen (paper 16 cm × 9 cm)
- XeLaTeX + ctex, full Chinese support
- Native LaTeX math (`\usefonttheme[onlymath]{serif}`)
- Built-in environments: blocks, columns, sidepic, chapter, TikZ
- Suitable for physics academic reports
- Compiles on Linux / Windows

## Fonts

- XeLaTeX / xeCJK is used for CJK typesetting.
- LXGWWenKai bundled with the template is used optionally for Chinese titles.
- Body fonts follow the local TeX/system font configuration.

## Compile

Run twice with XeLaTeX:

```bash
xelatex csu-beamer.tex
xelatex csu-beamer.tex
```

Output: `csu-beamer.pdf` (a compiled preview is included in the repository).

## License

GPL v3, inherited from the upstream template. See [LICENSE](LICENSE).
