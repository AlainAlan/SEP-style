# SEP-style
Stanford Encyclopedia of Philosophy user css

# 效果预览 Preview

![微信截图_20210413014438](https://user-images.githubusercontent.com/67500714/114439034-1bc62880-9bfb-11eb-9384-7ffbf8fd1184.png)


![微信截图_20210413014456](https://user-images.githubusercontent.com/67500714/114439027-19fc6500-9bfb-11eb-88b2-440fa1b25bae.png)


## 如何使用 How to use

### 安装 Stylus

[Stylus :: add0n.com](https://add0n.com/stylus.html)

[openstyles/stylus: Stylus - Userstyles Manager](https://github.com/openstyles/stylus/)

[Chrome网上应用店](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne)

### 在浏览器中 Click the link below in your browser

[点击链接安装](https://cdn.jsdelivr.net/gh/AlainAlan/SEP-style@main/index.user.css)

### 打开SEP页面查看效果 Try an entry to see

[Social Epistemology (Stanford Encyclopedia of Philosophy)](https://plato.stanford.edu/entries/epistemology-social/)

或者
[Try a random one](https://plato.stanford.edu/cgi-bin/encyclopedia/random)

## 注意

**目前仅使用Windows 10测试**
> i.e. the `.css` only used several `font-family` currently available on my own PC
> 
> They are:
> 
> - Old English Text MT
> - Palatino Linotype
> - Copperplate Gothic
> - Georgia

> Though I know "Georgia", "Copperplate" and "Palatino" are available on MacOS, and I love "Bodoni"(especially Small Caps) and "Zapfino" a lot.
> 
> Maybe I did it subconsciously. (e.g. using "Palatino Linotype" in quotation marks instead of a plain Palatino.
> 
> Ok fine, I can't afford a mbp up to now.

## TO-DO

- [ ] 适配MacOS（重点在~~字体~~搞台mbp）
- [ ] 尝试更改打印时的URL颜色
- [ ] 尝试改善打印时词条标题的缩进问题

### 后记

在Windows下，默认的SEP词条正文是`serif`（等于什么都没说甚至于还不如不指定）。而默认的打印界面我记得是 sans serif，同样丑的不忍直视。于是乎，此前为了获得较为美观的SEP的pdf文档，一度安装了几个G的TeX套件，然后使用一个python2时代的爬虫工具（大佬写的：[mondain-dev/convert-sep](https://github.com/mondain-dev/convert-sep)）转为`.tex`然后转为pdf。虽然好看但是仍有些许瑕疵（左对齐导致的右侧参差、另页尾注导致的崩溃、图片支持度太差且大小需要手动调整，以及塔夫特式的排版的原生争议，以及xelatex本身的发际线不友好问题）。最近灵光一闪，在没有认真学习css的情况下使用“检查”-“Style”搭配[WhatFont Tool](http://www.chengyinliu.com/whatfont.html#whatfont-install-bookmarklet)几经尝试写了一个本地css。

希望以后可以老老实实读文献。
