# Best PC App

这是为 [知乎-大学生的电脑有哪些必装软件？](https://www.zhihu.com/question/29287203/answer/105767450 'https://www.zhihu.com/question/29287203/answer/105767450') 整理的软件列表。

涵盖**Windows**、**MacOS**平台及**Chrome**浏览器插件。

### 平台

![MacOS][MacOS]   MacOS

![Windows][Windows]   Windows

### 分类

![Dictionary][Dictionary] 词典/百科 

![Edit][Edit] 文本编辑 

![Game][Game] 娱乐

![Media][Media] 音乐/视频

![Office][Office] 办公

![Safe][Safe] 安全/清理/维护

![Web][Web] 浏览器

### 安装
![Windows][Windows] Windows平台可在各软件的官网下载安装。

![MacOS][MacOS] MacOS平台可在各软件的官网与AppStore下载安装。推荐使用[Homebrew][Homebrew]进行安装。



## ![Dictionary][Dictionary] 词典/百科 

1. [Kiwix][Kiwix]-离线版百科全书

![Kiwix_ico][Kiwix_ico]

> We bring internet content to people without internet access。

![Kiwix][Kiwix_img]

**Kiwix** 的宗旨是：帮助那些无法访问互联网的人，方便地获取互联网内容。而他们的解决方案也很简单：下载，离线访问。

通过 **Kiwix**，你可以下载 **维基百科**、**TED**等内容，之后，你便可以在你自己的电脑中自由浏览它们。

![MacOS][MacOS] ![Windows][Windows]

```
brew cask install kiwix
```


2. [欧路词典][Eudic]-可扩展词库的优秀词典软件

![Eudic_ico][Eudic_ico]
![欧路词典][Eudic_img]

**欧路词典** 是一款优秀的词典软件，拥有**多语言翻译**、**海量词汇**、**百科**、**单词本**、**取词划词**等常用功能外，其最大的特色是支持多种词库。

除去软件本身提供的内置与在线词库外，你还可以使用它加载**MDict**、**灵格斯**、**Babylon**等多种词典格式。

![MacOS][MacOS] ![Windows][Windows]

```
brew cask install eudic
```

3. [有道词典][YoudaoDict]-简约、强大的词典软件

![YoudaoDict_ico][YoudaoDict_ico]

![有道词典][YoudaoDict_img]

**有道词典** 是网易出品的词典软件，其主要功能与 **欧路词典** 类似，但不支持加载第三方词库。

![MacOS][MacOS] ![Windows][Windows]



## ![Edit][Edit] 文本编辑
1. [Sublime-Text][SublimeText]-高颜值、高效率的文本编辑器

![Sublime-Text][SublimeText_ico]

>Sublime Text - A sophisticated text editor for code, markup and prose

![Sublime-Text][SublimeText_img]

**Sublime Text**是一款功能强大的文本编辑器，支持**自动保存**、**窗口分栏**、**多重编辑**、**任意跳转**、**代码折叠**、**语法高亮**、**片段**等众多功能。

**Sublime Text**还支持插件对其进行扩展，通过安装不同的插件，可以实现**自动对其**、**文件差异比较**、**代码检测**等众多功能。

如果你具备一定的技术知识，也可对**Sublime Text**进行更多个性化定制，或者编写你自己的插件。

![MacOS][MacOS] ![Windows][Windows]

![SublimeText-package_ico][SublimeText-package_ico]

你可以通过[Package Control][SublimeText-package]来**安装**、**卸载**、**启用**、**禁用**其他插件。


2. [Typora][Typora]-极简、强大的可视化MarkDown编辑器

> Typora — a minimal markdown editor, markdown reader.

![Typora_img][Typora_img]

使用**Typora**编辑**MarkDown**时，文本会被自动转换为可视化的内容。

你可以随意在**编辑**与**预览**模式之间无缝切换，也可将文档导出为**PDF**、**Doc**、**HTML**等格式。

![MacOS][MacOS] ![Windows][Windows]



## ![Safe][Safe] 安全/清理/维护
1. [Homebrew][Homebrew]-软件管家

>Homebrew — The missing package manager for macOS

![Homebrew_img][Homebrew_img]

**Homebrew** 是命令行版本的软件管家，通过几个简单的命令，你就可以轻松完成软件的**搜索**、**安装**、**升级**以及**卸载**。

![MacOS][MacOS]

安装**Homebrew**
```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

1. 搜索软件
```
brew search 软件名称
```

2. 安装软件
```
// 命令行应用
brew install 软件名称

// 桌面应用
brew cask install 软件名称
```

3. 升级软件
```
brew upgrade 软件名称
```

4. 卸载软件
```
brew uninstall 软件名称
```

5. 升级全部软件
```
brew update
brew upgarade
```

[MacOS]: ./icon/os/mac.png   "MacOs"
[Windows]: ./icon/os/windows.png   "Windows"

[Dictionary]: ./icon/type/dictionary.png "Dictionary"
[Edit]: ./icon/type/edit.png "Edit"
[Game]: ./icon/type/game.png "Game"
[Media]: ./icon/type/media.png "Media"
[Office]: ./icon/type/office.png "Office"
[Safe]: ./icon/type/safe.png "Safe"
[Web]: ./icon/type/web.png "Web"

[Kiwix]: http://www.kiwix.org/ "Kiwix:Read Wikipedia offline"
[Kiwix_ico]: ./icon/app/kiwix.png "Kiwix:Read Wikipedia offline"
[Kiwix_img]: ./img/app/kiwix/kiwix.jpg "Kiwix:Read Wikipedia offline"

[Eudic]: https://www.eudic.net "英语学习首选的词典软件"
[Eudic_ico]: ./icon/app/eudic.png "英语学习首选的词典软件"
[Eudic_img]: ./img/app/eudic/eudic.png "英语学习首选的词典软件"

[YoudaoDict]: http://cidian.youdao.com/ "有道词典"
[YoudaoDict_ico]: ./icon/app/youdaodict.png "有道词典"
[YoudaoDict_img]: ./img/app/youdaodict/youdaodict.png "有道词典"

[Homebrew]: https://brew.sh/ "Homebrew — The missing package manager for macOS"
[Homebrew_img]: ./img/app/homebrew/homebrew.png "有道词典"

[SublimeText]: https://www.sublimetext.com/ "Sublime Text - A sophisticated text editor for code, markup and prose"
[SublimeText_ico]: ./icon/app/sublimetext.svg
[SublimeText_img]: ./img/app/sublimetext/sublimetext.png
[SublimeText-package]: https://packagecontrol.io/ "Package Control - the Sublime Text package manager"
[SublimeText-package_ico]: ./icon/app/sublimetext_package.svg

[Typora]: https://typora.io/ "Typora — a minimal markdown editor, markdown reader."
[Typora_img]: ./img/app/typora/typora.png
