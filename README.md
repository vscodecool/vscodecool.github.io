工欲善其事，必先利其器！你好，我是[阿汤](https://github.com/tsq)，欢迎来到课程《VS Code入门教程2020》！在这门课程中，我将与你分享VS Code这款代码编辑器的使用方法，希望能够为你的学习或者工作带来一定的帮助。

这门课程其实是我从2020年2月份开始，在[B站](https://space.bilibili.com/30677217/channel/detail?cid=105022)和[Youtube](https://www.youtube.com/playlist?list=PLNEp_Xli9W_lUQTtRYG7883bGah63UkNB)上投稿的一门学习VS Code的视频教程，而之所以创建你现在正在看的这篇文档，是因为在下方的[课程详情](#课程详情)部分，你可以看到，我将每一节课的内容也以文字版的形式做了简单的介绍。这样做，一是，你可以通过搜索关键词来快速找到自己感兴趣的话题(搜索，你可以利用浏览器自带的搜索快捷键比如：mac是`command+f`；windows是`ctrl+f`)；二是，我将视频中涉及到的一些重要链接、命令、代码等信息在这里进行了记录，方便你在学习过程中查看和复制；三是，在已发布的视频当中，会有一些知识点的遗漏，对于遗漏的部分，我会在这里通过文字进行补充。

在阅读这篇文档的过程中，如果你发现了一些错误，欢迎你在Github上提出[pr](https://github.com/tsq/vscode-course/pulls)或者[issue](https://github.com/tsq/vscode-course/issues)。

**截止到目前，整个课程还没有制作完成，不过我会加油的！**

## 课程详情

整个课程被分成了八个章节：

**第一章**至**第五章**是VS Code基础知识的学习，这些基础知识与具体的编程语言无关但却十分重要，如果你是一名VS Code的初学者，建议你**先依次完成一到五章的学习**。

有了前面的知识，在**第六章**我们会结合具体的编程语言来学习这门编程语言在VS Code中的使用方式，比如，这门编程语言与VS Code结合时该如何搭建开发环境，以及这门编程语言在VS Code中又是如何做调试的等等。因为我会介绍很多门编程语言，所以你可以只挑选自己感兴趣的部分进行学习。

在**第七章**里我会推荐一些好用的扩展，这些扩展以工具的形式集成在VS Code当中。通过这些扩展，我们可以实现一些特殊的功能，比如说远程开发、远程协作等等。这些推荐的扩展，你也可以只选择自己喜欢的部分进行学习。

至于最后一章**第八章**，我们会学习如何去开发一个扩展。如果你对扩展的开发很感兴趣并且也有[typescript](https://www.typescriptlang.org/)和[nodejs](https://nodejs.org/)的基础，你可以选择学习这一部分内容。

在上面介绍的八个章节中，每个章节都会由多个小节组合而成，而每个小节将围绕VS Code的一个知识点进行详细讲解。为了更好的去理解这些知识点，建议你在跟着视频学习的同时，打开自己的VS Code，将视频中涉及到的操作都亲手做一遍。

好的，下面我们就来一起学习吧！

**章节目录**

- [第一章 介绍与安装](#第一章-介绍与安装)
- [第二章 界面布局与功能介绍](#第二章-界面布局与功能介绍)
- [第三章 文件及文件夹的使用](#第三章-文件及文件夹的使用)
- [第四章 自定义VS Code](#第四章-自定义VS-Code)
- [第五章 代码编辑技巧](#第五章-代码编辑技巧)
- [第六章 开发中的具体使用](#第六章-开发中的具体使用)
- [第七章 通用扩展推荐](#第七章-通用扩展推荐)
- [第八章 扩展的开发与发布](#第八章-扩展的开发与发布)

### 第一章 介绍与安装

这一章首先会对《VS Code入门教程2020》这门课程做简单的介绍，以及给出学习过程中遇到疑问时获取帮助的三种方式。之后会进入VS Code的正式学习：首先会介绍VS Code的一些基本知识，比如其官网地址、开源地址、受欢迎的原因等等；接着会进入VS Code的安装学习，我们会分别学习在Mac、Windows以及Linux上安装VS Code；最后会学习VS Code第一个最基础的操作：`如何用VS Code去打开一个项目`，其中会介绍非常重要的`code`命令。

**小节目录**

- [01 课程介绍](#01-课程介绍)
- [02 如何获取帮助](#02-如何获取帮助)
- [03 介绍 Visual Studio Code](#03-介绍-visual-studio-code)
- [04 在macOS上安装VS Code](#04-在macos上安装vs-code)
- [05 在Windows上安装VS Code](#05-在windows上安装vs-code)
- [06 在Linux上安装VS Code](#06-在linux上安装vs-code)
- [07 如何用VS Code打开一个项目](#07-如何用vs-code打开一个项目)

#### 01 课程介绍

视频链接：| [B站](https://www.bilibili.com/video/BV1Y7411V7mU) | [Youtube](https://youtu.be/HfHsX2yxfNg)

这一节课会对《VS Code入门教程2020》这门课程是如何被规划的做一个大致的介绍。整个课程会被分成八个章节进行讲解，你将了解到这八个章节分别会学习到什么内容。

#### 02 如何获取帮助

视频链接：| [B站](https://www.bilibili.com/video/BV1f741137Uf) | [Youtube](https://youtu.be/dxcPeXRNc-o)

当你在学习这门课程中遇到一些疑问，而自己又无法解决时，如果需要我的帮助，你可以通过三种方式与我取得联系。

1. 在视频下方留言，我看到了会尽快给予回复。
2. 发邮件给我，我的联系邮箱是：`tangshiqiangcn@gmail.com`.
3. 在Github上新建一个issue，地址是：[https://github.com/tsq/vscode-course](https://github.com/tsq/vscode-course)

#### 03 介绍 Visual Studio Code

视频链接：| [B站](https://www.bilibili.com/video/BV1U7411g75V) | [Youtube](https://youtu.be/8YbkDVtKAEg)

这一节课会对VS Code这款代码编辑器做一个大致介绍，你将了解到VS Code相关的一些背景知识，以及最近几年它为什么如此受欢迎。

VS Code是由微软推出的一款**免费**、**开源**且**跨平台**的代码编辑器，我们可以通过它的官网：[https://code.visualstudio.com](https://code.visualstudio.com) 进行安装包的下载，以及阅读大量相关的帮助文档。因为VS Code是开源的，所以我们可以自由的访问它在Github上的开源地址：[https://github.com/microsoft/vscode](https://github.com/microsoft/vscode) 。通过查看源代码根目录下的`package.json`文件，我们可以发现，VS Code其实是基于[Electron](https://www.electronjs.org/)这样一个专门制作跨平台桌面软件的框架而搭建的。VS Code这款软件的组成，其实是里面嵌入了一个Chrome浏览器外加一个Node.js运行时，整个VS Code我们能够看到的界面，其实都是由HTML、CSS和Javascript编写而成并使用Chrome来渲染出页面，如果你不相信，你可以点击VS Code顶部菜单栏的最后一项`Help`，然后选择倒数第二项：`Toggle Developer Tools`，就可以看到弹出的Chrome开发者工具了。

VS Code近些年来越来越受开发者欢迎，是因为它的身上存在这么几个亮点：第一是**打开速度快**，用VS Code来打开一个项目，基本上可以说是秒开，即使是很大的项目，也可以非常快的被打开。

第二是**支持的编程语言非常多**，VS Code在初始状态（即不按装任何的扩展的情况）下对Web前端开发、Node.js开发以及PHP等语言的开发都有很好的支持，至于其它的一些编程语言，比如说：Java、Python、Go、Ruby、C#、C/C++等等，只要安装相应的扩展就能很好的完成开发环境的搭建。

第三是**拥有丰富的扩展**，VS Code的扩展十分丰富，首先从**量**上来看，VS Code的扩展数量已经上万，涵盖了方方面面，你能想到的它都有，比如说你想使用Mysql的GUI工具，那么你可以直接下载一个叫`MySQL`的扩展，这样就可以在VS Code中一边写代码，一边完成数据库查询等工作，其次是你想不到的它也有，比如说一款名叫`daily-anime`的扩展，如果你是个动漫爱好者，用了它你就可以边上班边摸鱼了（*不鼓励摸鱼哈，还是安安心心写代码吧，哈哈*）。再一个就是从**质**上来看，VS Code很多重要的扩展都是由微软、谷歌等这样的大公司在维护，这些扩展的安装量有很多都超过百万甚至是千万，所以用起来十分的放心，也很少出错误。除了拥有非常丰富的扩展，VS Code的扩展还有另外两大优势，一是，我们在大陆地区也能够以很快网速完成扩展的安装；二是，除了一些特殊的扩展，绝大多数扩展安装完就生效，不需要重启VS Code。

第四是**涵盖应用程序的整个生命周期**，一款代码编辑器一般只涵盖应用程序的开发阶段，而对于一些程序，比如说Web应用，常常还会有部署阶段。在VS Code中我们可以利用一些扩展，比如说微软公司提供的azure相关扩展，或者亚马逊公司提供的aws相关扩展，利用它们，我们就可以很方便的通过VS Code完成应用的一键部署，所以从开发到部署全程用VS Code这一个工具就够了！

接下来，我们来看两个可能会遇到的并且有点令人迷惑的英文词汇：`Visual Studio Code`和`Visual Studio`。其实VS Code的全称叫做 `Visual Studio Code`，作为微软于2015年推出的一款代码编辑器，他还有一位老大哥，叫做[Visual Studio](https://visualstudio.microsoft.com/)。所以，`Visual Studio Code`和`Visual Studio`是两款不同的代码编辑器。Visual Studio是微软很早很早以前(*查了下[wikipedia](https://en.wikipedia.org/wiki/Microsoft_Visual_Studio)，第一个版本发布于1997年*)就推出的一款功能强大的IDE，但他主要用于微软自家的一些技术开发，比如说.NET开发和最近比较火的.NET Core开发。VS Code作为一款新产品，在创建之初，就从他大哥身上借鉴了很多好的地方，比如说后面课程会学习的`workspace`概念，如果你用过Visual Studio，你会发现这和Visual Studio上的`solution`很类似，同时VS Code也摒弃了他大哥身上一些不太好的地方，最大改善就是让整个软件变得更加轻量。VS Code安装过后大概占用不到300M的硬盘空间，而Visual Studio呢？哈哈，我这么说吧，没有个两三个G你是搞不定他的！我记得在读大学的时候，那时候还在用Visual Studio 2008，为了卸载Visual Studio，我每次都是转而选择重装系统！

除了有老大哥Visual Studio，VS Code他还有一位双胞胎兄弟，叫做`Insiders Edition`，他的下载地址是：[https://code.visualstudio.com/insiders/](https://code.visualstudio.com/insiders/)。他俩无论是相貌还是才能，几乎都一模一样，但是，微软会将一些新的bug修复或者一些新的功能更新，首先发布到`Insiders Edition`，等相应的功能稳定过后，才会将这部分更新发布到VS Code当中。如果你喜欢尝鲜的话，对于平时个人编程学习或者是开发自己的一些小项目，不妨试着用一用`Insiders Edition`。我自己就一直都在用`Insiders Edition`，给我的整体感受是：他俩在使用的是时候，基本上没什么区别。不过最近自己突然发现，`Insiders Edition`推出了[设置同步](https://code.visualstudio.com/docs/editor/settings-sync)功能（*界面左下角，包含人物图标的那个按钮就是*），我们可以使用自己的微软账户或者Github账户在`Insiders Edition`上进行登录，登录过后，我们安装的一些插件，设置过的一些偏好等信息都能够被同步到云端，如果我们以后换了台电脑，只要在新电脑上安装`Insiders Edition`并登录账户，云端保存的信息就会同步到本地，之前的设置就都恢复了。而这个设置同步功能，目前在VS Code中还没有，不过我估计很快就会有的。最后，为了从外貌上区分这对双胞胎，最简单的方法就是看他们的logo图标，`Insiders Edition`的是<span style="padding: 2px 8px;color: #fff;background-color: #20baa0;">绿色的</span>，而VS Code是<span style="padding: 2px 8px;color: #fff;background-color: #0066B8;">蓝色的</span>。


#### 04 在macOS上安装VS Code

视频链接：| [B站](https://www.bilibili.com/video/BV1a7411J75b) | [Youtube](https://youtu.be/8QOxxs6XJoM)

这一节课我们会学习如何在macOS上安装VS Code，其中会讲解一个可能会遇到的问题：`安装完毕后，却无法打开VS Code`。

为了在macOS上安装VS Code，我们首先前往官网首页：[https://code.visualstudio.com](https://code.visualstudio.com)进行安装包的下载，下载完毕后会是个zip文件，将解压后的文件直接拖入Applications里就可以完成安装。

但是我们在打开VS Code的时候可能会遇到无法打开的情况，这是因为你的macOS操作系统版本可能是Catalina，而Catalina在安全方面做了一些增强，对于从非Apple Store下载的应用可能就会遇到这种情况。为了解决这个问题，我们需要打开`System Preferences`，然后点击`Security & Privacy`，在里面就能解锁被阻止的VS Code了。

#### 05 在Windows上安装VS Code

视频链接：| [B站](https://www.bilibili.com/video/BV1u7411n7Cb) | [Youtube](https://youtu.be/QcNgBX1sAdc)

这一节课我们会学习如何在Windows上一步步安装VS Code。

在Windows上安装VS Code，我们首先前往官网首页：[https://code.visualstudio.com](https://code.visualstudio.com)进行安装包的下载，下载完毕后直接双击下载后的exe，在安装的第一步，我们首先选择“我接受协议”，之后全部点击“下一步”按钮直到安装完成。可以说，相较于Mac和Linux上的安装，Windows上的安装是最简单的了。

*如果你仔细观察安装的过程，你会发现在安装时，默认勾选住了“添加到PATH”这个选项，正是因为有了这个选项，安装完毕后，我们就可以在cmd或者Powershell中直接使用`code`这个命令了。*


#### 06 在Linux上安装VS Code

视频链接：| [B站](https://www.bilibili.com/video/BV1r7411E7uC) | [Youtube](https://youtu.be/RsgPR8rcR_Q)

这一节课我们会学习如何在Linux上一步步安装VS Code，我会以Ubuntu发行版做演示。

#### 07 如何用VS Code打开一个项目

视频链接：| [B站](https://www.bilibili.com/video/BV1T741177ra) | [Youtube](https://youtu.be/THx4BsmPJ9U)


[回到顶部](#课程详情)

### 第二章 界面布局与功能介绍

**小节目录**

- [08 用户界面概览]()
- [09 资源管理器]()
- [10 搜索工具]()
- [11 源代码管理]()
- [12 在macOS上搭建Git环境]()
- [13 在Windows上搭建Git环境]()
- [14 在Linux上搭建Git环境]()
- [15 在VS Code中使用Git - Part1]()
- [16 在VS Code中使用Git - Part2]()
- [17 介绍调试工具]()
- [18 在macOS上搭建Node.js开发环境]()
- [19 在Windows上搭建Node.js开发环境]()
- [20 在Linux上搭建Node.js开发环境]()
- [21 调试界面概览]()
- [22 Debug sidebar的使用方式]()
- [23 Debug toolbar的使用方式]()
- [24 介绍launch.json]()
- [25 调试技巧1 搜索本地变量]()
- [26 调试技巧2 logpoints]()
- [27 调试技巧3 conditional breakpoint]()
- [28 调试技巧4 inline breakpoint]()
- [29 调试技巧5 multi-target debugging]()
- [30 管理扩展]()
- [31 介绍Command Palette]()

#### 08 用户界面概览

视频链接：| [B站]() | [Youtube]()

#### 09 资源管理器

视频链接：| [B站]() | [Youtube]()

#### 10 搜索工具

视频链接：| [B站]() | [Youtube]()

#### 11 源代码管理

视频链接：| [B站]() | [Youtube]()

#### 12 在macOS上搭建Git环境

视频链接：| [B站]() | [Youtube]()

#### 13 在Windows上搭建Git环境

视频链接：| [B站]() | [Youtube]()

#### 14 在Linux上搭建Git环境

视频链接：| [B站]() | [Youtube]()

#### 15 在VS Code中使用Git - Part1

视频链接：| [B站]() | [Youtube]()

#### 16 在VS Code中使用Git - Part2

视频链接：| [B站]() | [Youtube]()

#### 17 介绍调试工具

视频链接：| [B站]() | [Youtube]()

#### 18 在macOS上搭建Node.js开发环境

视频链接：| [B站]() | [Youtube]()

#### 19 在Windows上搭建Node.js开发环境

视频链接：| [B站]() | [Youtube]()

#### 20 在Linux上搭建Node.js开发环境

视频链接：| [B站]() | [Youtube]()

#### 21 调试界面概览

视频链接：| [B站]() | [Youtube]()

#### 22 Debug sidebar的使用方式

视频链接：| [B站]() | [Youtube]()

#### 23 Debug toolbar的使用方式

视频链接：| [B站]() | [Youtube]()

#### 24 介绍launch.json

视频链接：| [B站]() | [Youtube]()

#### 25 调试技巧1 搜索本地变量

视频链接：| [B站]() | [Youtube]()

#### 26 调试技巧2 logpoints

视频链接：| [B站]() | [Youtube]()

#### 27 调试技巧3 conditional breakpoint

视频链接：| [B站]() | [Youtube]()

#### 28 调试技巧4 inline breakpoint

视频链接：| [B站]() | [Youtube]()

#### 29 调试技巧5 multi-target debugging

视频链接：| [B站]() | [Youtube]()

#### 30 管理扩展

视频链接：| [B站]() | [Youtube]()

#### 31 介绍Command Palette

视频链接：| [B站]() | [Youtube]()


[回到顶部](#课程详情)


### 第三章 文件及文件夹的使用
### 第四章 自定义VS Code
### 第五章 代码编辑技巧
### 第六章 开发中的具体使用
### 第七章 通用扩展推荐
### 第八章 扩展的开发与发布存在这么几个亮点：第一是**打开速度快**，用VS Code来打开一个项目，基本上可以说是秒开，即使是很大的项目，也可以非常快的被打开。

第二是**支持的编程语言非常多**，VS Code在初始状态（即不按装任何的扩展的情况）下对Web前端开发、Node.js开发以及PHP等语言的开发都有很好的支持，至于其它的一些编程语言，比如说：Java、Python、Go、Ruby、C#、C/C++等等，只要安装相应的扩展就能很好的完成开发环境的搭建。

第三是**拥有丰富的扩展**，VS Code的扩展十分丰富，首先从**量**上来看，VS Code的扩展数量已经上万，涵盖了方方面面，你能想到的它都有，比如说你想使用Mysql的GUI工具，那么你可以直接下载一个叫`MySQL`的扩展，这样就可以在VS Code中一边写代码，一边完成数据库查询等工作，其次是你想不到的它也有，比如说一款名叫`daily-anime`的扩展，如果你是个动漫爱好者，用了它你就可以边上班边摸鱼了（*不鼓励摸鱼哈，还是安安心心写代码吧，哈哈*）。再一个就是从**质**上来看，VS Code很多重要的扩展都是由微软、谷歌等这样的大公司在维护，这些扩展的安装量有很多都超过百万甚至是千万，所以用起来十分的放心，也很少出错误。

第四是**涵盖应用程序的整个生命周期**，一款代码编辑器一般只涵盖应用程序的开发阶段，而对于一些程序，比如说Web应用，常常还会有部署阶段。在VS Code中我们可以利用一些扩展，比如说微软公司提供的azure相关扩展，或者亚马逊公司提供的aws相关扩展，利用它们，我们就可以很方便的通过VS Code完成应用的一键部署，所以从开发到部署全程用VS Code这一个工具就够了！

VS Code的全称叫做 `Visual Studio Code`，作为微软于2015年推出的一款代码编辑器，其实他还有一位老大哥，叫做[Visual Studio](https://visualstudio.microsoft.com/)。Visual Studio是微软很早很早以前(*查了下[wikipedia](https://en.wikipedia.org/wiki/Microsoft_Visual_Studio)，第一个版本发布于1997年*)就推出的一款功能强大的IDE，但他主要用于微软自家的一些技术开发，比如说.NET开发和最近比较火的.NET Core开发。VS Code作为一款新产品，在创建之初，就从他大哥身上借鉴了很多好的地方，比如说调试功能，如果你用过Visual Studio，你会发现他俩在调试功能上有很多相似之处，同时VS Code也摒弃了他大哥身上一些不太好的地方，最大改善就是让整个软件变得更加轻量。VS Code安装过后大概占用不到300M的硬盘空间，而Visual Studio呢？哈哈，我这么说吧，没有个两三个G你是搞不定他的！我记得在读大学的时候，那时候还在用Visual Studio 2008，为了卸载Visual Studio，我每次都是转而选择重装系统！

除了有老大哥Visual Studio，VS Code他还有一位双胞胎兄弟，叫做`Insiders Edition`，他的下载地址是：[https://code.visualstudio.com/insiders/](https://code.visualstudio.com/insiders/)。他俩无论是相貌还是才能，几乎都一模一样，但是，微软会将一些新的bug修复或者一些新的功能更新，首先发布到`Insiders Edition`，等相应的功能稳定过后，才会将这部分更新发布到VS Code当中。如果你喜欢尝鲜的话，对于平时个人编程学习或者是开发自己的一些小项目，不妨试着用一用`Insiders Edition`。我自己就一直都在用`Insiders Edition`，给我的整体感受是：他俩在使用的是时候，基本上没什么区别。不过最近自己突然发现，`Insiders Edition`推出了[设置同步](https://code.visualstudio.com/docs/editor/settings-sync)功能（*界面左下角，包含人物图标的那个按钮就是*），我们可以使用自己的微软账户或者Github账户在`Insiders Edition`上进行登录，登录过后，我们安装的一些插件，设置过的一些偏好等信息都能够被同步到云端，如果我们以后换了台电脑，只要在新电脑上安装`Insiders Edition`并登录账户，云端保存的信息就会同步到本地，之前的设置就都恢复了。而这个设置同步功能，目前在VS Code中还没有，不过我估计很快就会有的。最后，为了从外貌上区分这对双胞胎，最简单的方法就是看他们的logo图标，`Insiders Edition`的是<span style="padding: 2px 8px;color: #fff;background-color: #20baa0;">绿色的</span>，而VS Code是<span style="padding: 2px 8px;color: #fff;background-color: #0066B8;">蓝色的</span>。


#### 04 在macOS上安装VS Code

视频链接：| [B站](https://www.bilibili.com/video/BV1a7411J75b) | [Youtube](https://youtu.be/8QOxxs6XJoM)

这一节课我们会学习如何在macOS上安装VS Code，其中会讲解一个可能会遇到的问题：`安装完毕后，却无法打开VS Code`。

为了在macOS上安装VS Code，我们首先前往官网首页：[https://code.visualstudio.com](https://code.visualstudio.com)进行安装包的下载，下载完毕后会是个zip文件，将解压后的文件直接拖入Applications里就可以完成安装。

但是我们在打开VS Code的时候可能会遇到无法打开的情况，这是因为你的macOS操作系统版本可能是Catalina，而Catalina在安全方面做了一些增强，对于从非Apple Store下载的应用可能就会遇到这种情况。为了解决这个问题，我们需要打开`System Preferences`，然后点击`Security & Privacy`，在里面就能解锁被阻止的VS Code了。

#### 05 在Windows上安装VS Code

视频链接：| [B站](https://www.bilibili.com/video/BV1u7411n7Cb) | [Youtube](https://youtu.be/QcNgBX1sAdc)

这一节课我们会学习如何在Windows上一步步
