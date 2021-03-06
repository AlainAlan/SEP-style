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

[点击链接安装](https://cdn.jsdelivr.net/gh/AlainAlan/SEP-style/index.user.css)

[@main](https://cdn.jsdelivr.net/gh/AlainAlan/SEP-style@main/index.user.css)

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
- [x] 尝试更改打印时的URL颜色
- [x] 尝试改善打印时词条标题的缩进问题
- [ ] 進一步優化打印時換行效果
- [x] ~~調整圖片對齊方式~~（刪除了該圖片）
- [x] 調整文末附加信息的顯示效果（刪除了除作者信息外的附加信息）
- [x] 尋找更合適的字體，以避免三個dash之間`裂開`（2021-04-15改用了Garamond）

### 后记

在Windows下，默认的SEP词条正文是`serif`（等于什么都没说甚至于还不如不指定）。而默认的打印界面我记得是 sans serif，同样丑的不忍直视。于是乎，此前为了获得较为美观的SEP的pdf文档，一度安装了几个G的TeX套件，然后使用一个python2时代的爬虫工具（大佬写的：[mondain-dev/convert-sep](https://github.com/mondain-dev/convert-sep)）转为`.tex`然后转为pdf。虽然好看但是仍有些许瑕疵（左对齐导致的右侧参差、另页尾注导致的崩溃、图片支持度太差且大小需要手动调整，以及塔夫特式的排版的原生争议，以及xelatex本身的发际线不友好问题）。最近灵光一闪，在没有认真学习css的情况下使用“检查”-“Style”搭配[WhatFont Tool](http://www.chengyinliu.com/whatfont.html#whatfont-install-bookmarklet)几经尝试写了一个本地css。

希望以后可以老老实实读文献。


### 更新日志

- 2021-04-14：今天花費了一個晚上的時間，調整了導言的首行和首字母，並（主要）優化了虛擬列印的PDF頁面的效果
- ![網頁比較](https://user-images.githubusercontent.com/67500714/114729580-b1d08f00-9d72-11eb-8b46-17c559191dbd.png)
- ![虛擬打印](https://user-images.githubusercontent.com/67500714/114729591-b39a5280-9d72-11eb-8cc9-c6d301580c36.png)

- 2021-04-15：今天做了以下更新：
  - 更改了一些對齊，進一步試圖解決打印時懸挂縮進的bug；
  - 將`li`改用了Garamond，使得`---`之間沒有縫隙，雖然意大利體過於優雅喧賓奪主；
  - 適配了華文哲學百科詞條頁面和打印頁面（登入后系統提供的pdf文件字體和排版質量頗差，而直接打印會有導航欄殘留）；但是沒有適配首頁，且中英混排時的效果非常差，有待後續更新。
- 2021-04-25：小更新：
  - 调整了CEP的域名（仅适用于词条页面，其他页面不修改，不免了0.0.3版本的问题）
  - 调整了CEP的打印字体大小（18px被用无处不在的style写定我也没有办法）
  - 调整了CEP的引用（华文仿宋） 
  - 效果预览
   - ![龙树2](https://user-images.githubusercontent.com/67500714/115986348-54460900-a5e2-11eb-91b7-27702cf74ea4.png)![龙树](https://user-images.githubusercontent.com/67500714/115986340-4ee8be80-a5e2-11eb-99c4-2f6cfa2020dc.png)
   - ![虚拟打印](https://user-images.githubusercontent.com/67500714/115986352-58722680-a5e2-11eb-9d7e-579243c73896.png)![虚拟列印](https://user-images.githubusercontent.com/67500714/115986368-645de880-a5e2-11eb-9faf-6ad8ce673c10.png)
 
- 2021-07-02
  - 调整了一些细节，但是仍然非常不稳定（打印时标题的缩进时有时无，字体大小也不稳定）
  - 在@page里指定了页边距
  - 加入了与Palatino搭配的华文中宋，和与Garamond搭配的华文宋体，以适配部分中国哲学相关词条中的中文字符
  - 修复了在导言区出现引用块也被视为首段文字的bug
  - 感觉目前审美上有些土，但是又懒得改，就这样吧，我知道我很土。

- 2021-07-03
  - 跑动了批量虚拟打印的代码，详见个人仓库（等我更新上传）
