# CTeX 临时论坛

由于 [原 CTeX 论坛](http://bbs.ctex.org/) 因故无限期关闭，我们在此建立临时论坛，通过 GitHub Issues 进行提问、回答与讨论。

此外，临时论坛的管理员会对在临时论坛上发生的讨论进行筛选，择其善者列在此 `README.md` 文件当中，以便后来者索引。这些问题在被充分讨论的基础之上，至少具有以下一个特征：

* 问题本身具有代表性；
* 问题本身不具有特别强的代表性，但是具有一定的技术深度；
* 问题本身不具有代表性，技术上也不会特别深入，但涉及某个宏包、工具等的特定 bug，在一定时期内可能引起大量同质讨论。

在此处提问、讨论请遵循 [GitHub 社区规范](https://help.github.com/en/articles/github-community-guidelines)。

## 善问目录

### 文档版式

- [在 LaTeX 中如何实现「页尾注」？](https://github.com/CTeX-org/forum/issues/2)
- [latex 中文多级标题如何改为：第一章，1.1 这种格式](https://github.com/CTeX-org/forum/issues/11)
- [怎么把每段的首字符大写强调?](https://github.com/CTeX-org/forum/issues/56)
  - 即「首字下沉」功能
- [\item 对齐的问题](https://github.com/CTeX-org/forum/issues/55)
- [脚注之间的间距与脚注样式](https://github.com/CTeX-org/forum/issues/50)

### 中文支持

- [siunitx 宏包无法自动在两侧插入空白](https://github.com/CTeX-org/forum/issues/19)
  - 此问题其实与 `siunitx` 宏包并无直接关联，而是由于 `xeCJK` 的原因，无法在技术上很好地解决。具体参考 [CTeX-org/ctex-kit#392](https://github.com/CTeX-org/ctex-kit/issues/392)
- [如何在宏两侧自动插入 CJKecglue](https://github.com/CTeX-org/forum/issues/23)
- [如何优雅地修改 xeCJK 在边缘处的标点挤压规则？](https://github.com/CTeX-org/forum/issues/28)
- [有办法使 xCJKecglue 随着字体而变化吗？](https://github.com/CTeX-org/forum/issues/31)
- [中文版心设计的疑难与最佳实践？](https://github.com/CTeX-org/forum/issues/47)
  - 这是一场很长的讨论……

### 字体

- [Roboto 字体在 xdvipdfmx 中调用时出现 null character 的警告信息](https://github.com/CTeX-org/forum/issues/13)
  - 此问题来源于 xdvipdfmx 的一个 bug
- [如何在 XeTeX 中使用 CID 调用字符](https://github.com/CTeX-org/forum/issues/20)
- [xetex 中 fandol 字体 script 的问题](https://github.com/CTeX-org/forum/issues/34)

### 参考文献

- [如何使得参考文献中的标题大写](https://github.com/CTeX-org/forum/issues/8)
- [如何在每一章节后面单独显示本章引用文献？](https://github.com/CTeX-org/forum/issues/15)

### 图片

- [有关插入 eps 文件的问题](https://github.com/CTeX-org/forum/issues/9)
  - [这里](https://github.com/CTeX-org/forum/issues/9#issuecomment-462811150) 还探讨了 TeX 中插入图片的底层机制
- [插入图片时出现 Dimension too large 错误](https://github.com/CTeX-org/forum/issues/12)
- [无法加载 eps 格式图片](https://github.com/CTeX-org/forum/issues/58)

### 浮动体

- [有关浮动体过多产生的不良后果](https://github.com/CTeX-org/forum/issues/10)
- [怎么自动控制浮动体图片，表格不会跨越它所在的节?](https://github.com/CTeX-org/forum/issues/59)
- [包含浮动体和 longtable 环境的页面，内容从底部溢出](https://github.com/CTeX-org/forum/issues/40)
  - 涉及 `longtable` 的 bug，还与 Pandoc 的配置有关

### 宏包使用

#### `algorithm`

- [算法的行距太小，如何调整算法中的行距](https://github.com/CTeX-org/forum/issues/16)

#### `beamer`

- [beamer 与 wrapfig 合用的问题](https://github.com/CTeX-org/forum/issues/6)

#### `listings`

- [使用 listings 宏包，如何设置代码的字体](https://github.com/CTeX-org/forum/issues/7)

#### `PGF`/`TikZ`

- [TikZ-Feynman package didn't complied properly](https://github.com/CTeX-org/forum/issues/4)
  - 此问题来源于 PGF 的一个 bug

### 宏编程

- [参数中用换行符进行换行](https://github.com/CTeX-org/forum/issues/35)
- [obeylines 实现在参数中换行，导致 tabular 环境中 \hline 出错](https://github.com/CTeX-org/forum/issues/44)
- [`\RenewDocumentCommand` 修改计数器会导致相对引用出错](https://github.com/CTeX-org/forum/issues/110)
  - 该问题是因为 `\NewDocumentCommand` 等一组命令默认定义出的函数是 robust 的，从而导致 `\thefigure` 没有在恰当的地方展开。

### 格式转换

- [ctex + lwarp 生成的 html 出现文字顺序颠倒](https://github.com/CTeX-org/forum/issues/18)
- [日经问题：LaTeX 如何转为 Word？](https://github.com/CTeX-org/forum/issues/22)

### 编辑器

#### TeXStudio

- [TeXStudio 无法启动 build](https://github.com/CTeX-org/forum/issues/5)

#### Sublime Text

- [Sublime3 无法实时显示公式](https://github.com/CTeX-org/forum/issues/21)

### 杂项

- [\pdfmarkupcomment 不支持中文](https://github.com/CTeX-org/forum/issues/14)
- [TeX Live 2019 中 xdvipdfmx 出现 typecheck: Invalid object type 问题](https://github.com/CTeX-org/forum/issues/29)
