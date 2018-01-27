# [MarkdownKatex](https://github.com/zyuzhi/MarkdownKatex-typecho)

MardownKatex是一个原生支持Latex公式的typecho插件。是基于[ParseDown](https://github.com/erusev/parsedown)和[ParseDown-Extra](https://github.com/erusev/parsedown-extra)开发的，Latex渲染使用的是[KaTeX](https://github.com/Khan/KaTeX)的JS库，渲染速度飞快。

## 使用示例

这是我博客的一个例子。

![MarkdownKatexDemoBlog.png][1]

```md
这是一个行内公式$f(x)=a \cdot x^2+b \cdot x+c$

这是一个独立的居中公式$$x=\frac{1}{2}$$
```

typecho渲染效果如下所示。

![MarkdownKatexDemo.png][2]

1. 行内的内联公式使用单个`$`符号包围
2. 独立的居中公式使用`$$`包围

### DEMO

1. [https://blog.zyuzhi.me/2018/01/27/MarkdownKatex-For-Typecho.html](https://blog.zyuzhi.me/2018/01/27/MarkdownKatex-For-Typecho.html)
2. [https://blog.zyuzhi.me/2016/09/22/Matrix-Euler-AxisAngle-Quaternion.html](https://blog.zyuzhi.me/2016/09/22/Matrix-Euler-AxisAngle-Quaternion.html)

## 插件安装

从[这里](https://github.com/zyuzhi/MarkdownKatex-typecho/archive/master.zip)下载zip包，解压并将文件夹名称重命名为`MardownKatex`，并在后台插件管理中启用即可。

更新时需要 禁用插件→更新插件→启用插件。

Have Fun With Latex.

## Features
- 常用MarkDown语法支持继承自[ParseDown](https://github.com/erusev/parsedown)和[ParseDown-Extra](https://github.com/erusev/parsedown-extra)，语法支持详情请戳→[http://parsedown.org/tests/](http://parsedown.org/tests/)
- 支持内联公式（`$`）和独立公式（`$$`）
- 兼容highlight.js对代码块的高亮
- Katex使用0.8.3版本，使用的BOOTCSS的JS库CDN
- ParseDown使用1.6版本
- ParseDown-Extra使用0.7版本

## TODO
1. 后台配置Katex加载的CDN地址
2. 后台配置是否启用highlight.js渲染代码

## License
> Copyright (c) 2018 zyuzhi  
> License: [The MIT License.](https://github.com/zyuzhi/MarkdownKatex-typecho/blob/master/LICENSE)

[1]: https://github.com/zyuzhi/MarkdownKatex-typecho/raw/master/MarkdownKatexDemoBlog.png
[2]: https://github.com/zyuzhi/MarkdownKatex-typecho/raw/master/MardownKatexDemo.png