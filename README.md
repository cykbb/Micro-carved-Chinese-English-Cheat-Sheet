# Micro-carved Chinese-English Cheat Sheet

[中文](#中文说明) | [English](#english)

## 中文说明

这是一个为 NTU EE6497 / IE4497 课程整理的高度压缩中英文速查表，使用 LaTeX 制作，内容覆盖概率复习、贝叶斯推断、线性回归、混合模型、EM、采样方法、神经网络与深度学习等主题。仓库同时保留源码和已生成的 PDF，方便直接查看或继续修改。

### 文件结构

- `main.tex`: 速查表主体内容。
- `preamble.tex`: LaTeX 宏包、字体和排版设置。
- `image/`: 文档中使用的图片资源。
- `main.pdf`: 已编译好的 PDF 版本。

### 编译方式

推荐使用 XeLaTeX 编译，因为文档使用了 `xeCJK` 和中文字体设置。

```bash
latexmk -xelatex main.tex
```

如果没有安装 `latexmk`，也可以运行：

```bash
xelatex main.tex
```

### 环境要求

- TeX Live 或 MacTeX。
- XeLaTeX。
- `PingFang SC` 和 `Times New Roman` 字体。macOS 通常自带这些字体；如果在其他系统上编译，可在 `preamble.tex` 中替换为本机可用字体。

## English

This repository contains a compact Chinese-English cheat sheet for the NTU EE6497 / IE4497 course, typeset in LaTeX. It covers probability review, Bayesian inference, linear regression, mixture models, EM, sampling methods, neural networks, deep learning, and related course topics. Both the source files and the generated PDF are included so the sheet can be viewed directly or edited further.

### Project Structure

- `main.tex`: Main cheat sheet content.
- `preamble.tex`: LaTeX packages, fonts, and layout settings.
- `image/`: Image assets used by the document.
- `main.pdf`: Precompiled PDF output.

### Build

XeLaTeX is recommended because the document uses `xeCJK` and CJK font configuration.

```bash
latexmk -xelatex main.tex
```

If `latexmk` is unavailable, run:

```bash
xelatex main.tex
```

### Requirements

- TeX Live or MacTeX.
- XeLaTeX.
- `PingFang SC` and `Times New Roman` fonts. These are usually available on macOS. On other systems, update the font names in `preamble.tex` before compiling.
