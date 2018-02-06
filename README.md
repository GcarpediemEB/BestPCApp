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

![Develop][Develop] 开发工具


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

```
brew cask install sublime-text
```

![SublimeText-package_ico][SublimeText-package_ico]

你可以通过[Package Control][SublimeText-package]来**安装**、**卸载**、**启用**、**禁用**其他插件。


2. [Typora][Typora]-极简、强大的可视化MarkDown编辑器

> Typora — a minimal markdown editor, markdown reader.

![Typora_img][Typora_img]

使用**Typora**编辑**MarkDown**时，文本会被自动转换为可视化的内容。

你可以随意在**编辑**与**预览**模式之间无缝切换，也可将文档导出为**PDF**、**Doc**、**HTML**等格式。

![MacOS][MacOS] ![Windows][Windows]

```
brew cask install typora
```

## ![Media][Media] 音乐/视频
1. [Vox][Vox]-简约、高颜值的音乐播放器

![Vox][Vox_ico]

> VOX Music Player for Mac & iPhone: Unlimited Solution for Music Lovers

![Vox][Vox_img]

**Vox**是一款简约的音乐播放器，支持高分辨率的无损音乐。

**Vox**可以播放**本地**、**Vox Clound**、**Last.fm**或者**iTunes**中的音乐，此外还支持网络广播。

![MacOS][MacOS] ![Windows][Windows]
```
brew cask install vox
```
你可以通过**MacOS顶部**的**Vox**菜单栏来**播放**、**暂停**、**切换**音乐，或者在软件的**设置**中，配置你喜爱的全局热键。

![Vox-Menu][Vox-menu_img]

![Vox-Setup][Vox-setup_img]

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

搜索软件
```
brew search 软件名称
```

安装软件
```
// 命令行应用
brew install 软件名称

// 桌面应用
brew cask install 软件名称
```

升级软件
```
brew upgrade 软件名称
```

卸载软件
```
brew uninstall 软件名称
```

升级全部软件
```
brew update
brew upgarade
```

2. [LastPass][LastPass]-云端密码管理器

![LastPass][LastPass_ico]

>LastPass密码管理器、自动填表、随机密码生成器和安全数字钱包应用程序

![LastPass][LastPass_img]

**LastPass**是一款密码管理器，当你在网站注册时，你可以通过**LastPss**生成高强度的密码，之后这些密码将会自动保存在**LastPass**的云端。

其支持**Windows**、**MacOS**、**Linux**等PC平台与**Android**、**iOS**等移动平台，并且提供**Chrome**、**FireFox**、**Safari**、**Opera**等浏览器的插件应用。

![MacOS][MacOS] ![Windows][Windows]

```
brew cask install lastpass
```

**LastPass**默认使用**用户名+主密码**的方式来作为你登录及管理其他密码的凭证，但更为安全的做法是：

将**LastPass**配合[Google 身份验证器][Google-Authenticator]一同使用，每次登录**LastPass**账户时，都需要输入发送到[Google 身份验证器][Google-Authenticator]的上的验证码。

3. [1Password][[1Password]-高颜值且功能强大的密码管理器

![1Password][1Password_ico]

>Go ahead. Forget your passwords.

![1Password][1Password_img]

**1Password**的功能同**LastPass**，但相比后者，**1Password**的历史更为悠久。

在**1Password**中，你既可以将密码保存在**1Password**的云端，也可以将其保存在**iCloud**、**Dropbox**或者**本地**。

其支持**Windows**、**MacOS**等PC平台与**Android**、**iOS**等移动平台，亦提供**Chrome**、**FireFox**、**Safari**、**Opera**等浏览器的插件应用。

![MacOS][MacOS] ![Windows][Windows]

```
brew cask install 1password
```


## ![Develop][Develop] 开发工具
1.[Postman][Postman]-API开发测试工具

![Postman][Postman_ico]

> Postman - API Development Environment

![Postman][Postman_img]

在**Http**请求方法中，**Post**方法被用于向服务器提交数据。而名称中带有**Post**的**Postman**，则是一款功能强大的用于测试**Http**请求的API开发工具。

通过**Postman**，你可以方便地对**Restfull api**进行测试，并且可以快速地生成有关的API文档分享给你的同伴。

![MacOS][MacOS] ![Windows][Windows]

```
brew cask install postman
```

通过在**Postman**中设置不同的环境，你可以快速地对**开发**、**生产**等各种环境中的API进行测试。

你的API将会被自动保存在**Postman**云端，你可以随意将它同步到其他设备上。

[MacOS]: ./icon/os/mac.png   "MacOs"
[Windows]: ./icon/os/windows.png   "Windows"

[Develop]: ./icon/type/develop.png "Develop"
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
[Typora_img]: ./img/app/typora/Typora.png

[LastPass]: https://www.lastpass.com "LastPass密码管理器、自动填表、随机密码生成器和安全数字钱包应用程序"
[LastPass_ico]: ./icon/app/lastpass.png
[LastPass_img]: ./img/app/lastpass/lastpass.png

[Google-Authenticator]: https://play.google.com/store/apps/details?id=com.google.android.apps.authenticator2 "Google 身份验证器"

[1Password]: https://1password.com/ "Go ahead. Forget your passwords."
[1Password_ico]: ./icon/app/1password.svg
[1Password_img]: ./img/app/1password/1password.jpg

[Vox]: https://vox.rocks/ "VOX Music Player for Mac & iPhone: Unlimited Solution for Music Lovers"
[Vox_ico]: ./icon/app/vox.png
[Vox_img]: ./img/app/vox/vox.png
[Vox-setup_img]: ./img/app/vox/vox_setup.png
[Vox-menu_img]: ./img/app/vox/vox_menu.png

[Postman]: https://www.getpostman.com/ "Postman - API Development Environment"
[Postman_ico]: ./icon/app/postman.svg
[Postman_img]: ./img/app/postman/postman.png