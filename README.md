# zhlipsum

[![Build Status](https://img.shields.io/travis/Stone-Zeng/zhlipsum.svg)](#continuous-build-status)
[![Build status](https://ci.appveyor.com/api/projects/status/rhftdsngpgp9u0xh?svg=true)](#continuous-build-status)
[![CTAN](https://img.shields.io/ctan/v/zhlipsum.svg)](https://www.ctan.org/pkg/zhlipsum)
[![GitHub release](https://img.shields.io/github/release/Stone-Zeng/zhlipsum/all.svg)](https://github.com/Stone-Zeng/zhlipsum/releases/latest)

## 欢迎使用 zhlipsum （中文乱数假文）

本宏包提供了中文乱数假文的功能，可用于测试中文 LaTeX 文档。`zhlipsum` 支持 UTF-8、GBK 和 Big5 编码。

### 基本用法

```latex
\zhlipsum
\zhlipsum*[1-5]
\zhlipsum[6-10,18][name=trad]
```

更多信息可从宏包文档 [zhlipsum.pdf](http://mirror.ctan.org/macros/latex/contrib/zhlipsum/zhlipsum.pdf) 中获取。

### 贡献

如果您有任何改进意见或者功能需求，欢迎提交 [issue](https://github.com/Stone-Zeng/zhlipsum/issues) 或 [pull request](https://github.com/Stone-Zeng/zhlipsum/pulls)。

### 许可证

除文本数据外，本模板的发布遵守 [LaTeX Project Public License](http://www.latex-project.org/lppl.txt)（版本 1.3c 或更高）。

文本数据的许可证见该 [README](https://github.com/Stone-Zeng/zhlipsum/blob/master/data/README.md)。

<br>

## Welcome to zhlipsum (Chinese dummy text)

This package provides an interface to dummy text in Chinese language, which will be useful for testing Chinese documents.

`zhlipsum` supports UTF-8, GBK and Big5 encodings.

### Basic usage

```latex
\zhlipsum
\zhlipsum*[1-5]
\zhlipsum[6-10,18][name=trad]
```

More information can be found in the package documentation [zhlipsum-en.pdf](http://mirror.ctan.org/macros/latex/contrib/zhlipsum/zhlipsum-en.pdf).

### Continuous build status

| Distribution | Platform | Status |
| :----------: | :------: | :----: |
| TeX Live     | Linux    | [![Build Status][1.1]][travis]   |
| TeX Live     | macOS    | [![Build Status][1.2]][travis]   |
| TeX Live     | Windows  | [![Build Status][2.1]][appveyor] |
| MiKTeX       | Linux    | [![Build Status][1.3]][travis]   |
| MiKTeX       | macOS    | [![Build Status][1.4]][travis]   |

[1.1]: https://travis-matrix-badges.herokuapp.com/repos/Stone-Zeng/zhlipsum/branches/master/1
[1.2]: https://travis-matrix-badges.herokuapp.com/repos/Stone-Zeng/zhlipsum/branches/master/2
[1.3]: https://travis-matrix-badges.herokuapp.com/repos/Stone-Zeng/zhlipsum/branches/master/3
[1.4]: https://travis-matrix-badges.herokuapp.com/repos/Stone-Zeng/zhlipsum/branches/master/4
[2.1]: https://appveyor-matrix-badges.herokuapp.com/repos/Stone-Zeng/zhlipsum/branch/master/1

[travis]:   https://travis-ci.org/Stone-Zeng/zhlipsum
[appveyor]: https://ci.appveyor.com/project/Stone-Zeng/zhlipsum

### Contributing

[Issues](https://github.com/Stone-Zeng/zhlipsum/issues) and [pull requests](https://github.com/Stone-Zeng/zhlipsum/pulls) are always welcome.

### License

Except for the text data, this work may be distributed and/or modified under the conditions of the [LaTeX Project Public License](http://www.latex-project.org/lppl.txt), either version 1.3c of this license or (at your option) any later version.

Licenses of text data can be found in this [README](https://github.com/Stone-Zeng/zhlipsum/blob/master/data/README.md).

-----

Copyright (C) 2017&ndash;2019 by Xiangdong Zeng.
