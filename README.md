工欲善其事，必先利其器！你好，我是[阿汤](https://github.com/tsq)，欢迎来到课程《VS Code入门教程2020》！在这门课程中，我将与你分享VS Code这款代码编辑器的使用方法，希望能够为你的学习或者工作带来一定的帮助。

这门课程是我从2020年2月份开始，在网上投稿的一门学习VS Code的视频教程，而之所以创建你现在正在看的这篇文档，是因为在下方的[课程详情](#课程详情)部分，你可以看到，我将每一节课的内容也以文字版的形式做了简单的介绍。这样做，一是，你可以通过搜索关键词来快速找到自己感兴趣的话题(搜索，你可以利用浏览器自带的搜索快捷键比如：mac是`command+f`；windows是`ctrl+f`)；二是，我将视频中涉及到的一些重要链接、命令、代码等信息在这里进行了记录，方便你在学习过程中查看和复制；三是，在已发布的视频当中，会有一些知识点的遗漏，对于遗漏的部分，我会在这里通过文字进行补充。

在阅读这篇文档的过程中，如果发现一些错误，欢迎在Github上提出[pr](https://github.com/tsq/vscode-course/pulls)或者[issue](https://github.com/tsq/vscode-course/issues)。

另外，我将视频分别上传到了[Youtube](https://www.youtube.com/watch?v=HfHsX2yxfNg&list=PLNEp_Xli9W_lUQTtRYG7883bGah63UkNB)、[Bilibili](https://space.bilibili.com/30677217/channel/detail?cid=105022)、[Toutiao](http://www.ixigua.com/pseries/6856506428144747012)这三个平台，你可以点击它们并查看视频内容。


**截止到目前，整个课程还没有制作完成，不过我会加油的！**

## 课程详情

整个课程被分成了八个章节：

**第一章**至**第五章**是VS Code基础知识的学习，这些基础知识与具体的编程语言无关但却十分重要，建议你**先依次完成一到五章的学习**，打好基础。

有了前面的知识，在**第六章**我们会结合具体的编程语言来学习这门编程语言在VS Code中的使用方式，比如，这门编程语言与VS Code结合时该如何搭建开发环境，以及这门编程语言在VS Code中又是如何做调试的等等。因为我会介绍很多门编程语言，所以你可以只挑选自己感兴趣的部分进行学习。同时，我们也会学习在开发过程中经常会遇到一些话题，例如：WSL，远程开发，Docker，云服务等等。

在**第七章**里我会推荐一些好用的扩展，这些扩展以工具的形式集成在VS Code当中。比如说支持远程协作的Live Share，丰富Git管理的Gitlens等等。这些推荐的扩展，你也可以只选择自己喜欢的部分进行学习。

至于最后一章**第八章**，我们会学习如何去开发一个扩展。如果你对扩展的开发很感兴趣并且也有[typescript](https://www.typescriptlang.org/)和[nodejs](https://nodejs.org/)的基础，你可以选择学习这一部分内容。

在上面介绍的八个章节中，每个章节都会由多个小节组合而成，而每个小节将围绕VS Code的一个知识点进行详细讲解。为了更好的去理解这些知识点，建议你在跟着视频学习的同时，打开自己的VS Code，将视频中涉及到的操作都亲手做一遍。

好的，下面我们就来开始一起学习吧！

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

这一章首先会对《VS Code入门教程2020》这门课程做简单的介绍，以及给出学习过程中遇到疑问时获取帮助的三种方式。之后会进入VS Code的正式学习：首先会介绍VS Code的一些基本知识，比如其官网地址、开源地址、受欢迎的原因等等；接着会进入VS Code的安装学习，我们会分别学习在Mac、Windows以及Linux上安装VS Code；最后会学习VS Code第一个最基础的操作：如何用VS Code去打开一个项目，其中会介绍非常重要的`code`命令。

**小节目录**

- [01 课程介绍](#01-课程介绍)
- [02 如何获取帮助](#02-如何获取帮助)
- [03 介绍 Visual Studio Code](#03-介绍-visual-studio-code)
- [04 在macOS上安装VS Code](#04-在macos上安装vs-code)
- [05 在Windows上安装VS Code](#05-在windows上安装vs-code)
- [06 在Linux上安装VS Code](#06-在linux上安装vs-code)
- [07 如何用VS Code打开一个项目](#07-如何用vs-code打开一个项目)

#### 01 课程介绍

这一节课会对《VS Code入门教程2020》这门课程是如何被规划的做一个大致的介绍。整个课程会被分成八个章节进行讲解，你将了解到这八个章节分别会学习到什么内容。

#### 02 如何获取帮助

当你在学习这门课程中遇到一些疑问，而自己又无法解决时，如果需要我的帮助，你可以通过三种方式与我取得联系。

1. 在视频下方留言，我看到了会尽快给予回复。
2. 发邮件给我，我的联系邮箱是：`tangshiqiangcn@gmail.com`.
3. 在Github上新建一个issue，地址是：[https://github.com/tsq/vscode-course](https://github.com/tsq/vscode-course)

#### 03 介绍 Visual Studio Code

这一节课会对VS Code这款代码编辑器做一个大致介绍，你将了解到VS Code相关的一些背景知识，以及最近几年它为什么如此受欢迎。

VS Code是由微软推出的一款**免费**、**开源**且**跨平台**的代码编辑器，我们可以通过它的官网：[https://code.visualstudio.com](https://code.visualstudio.com) 进行安装包的下载，以及阅读大量相关的帮助文档。因为VS Code是开源的，所以我们可以自由的访问它在Github上的开源地址：[https://github.com/microsoft/vscode](https://github.com/microsoft/vscode) 。通过查看源代码根目录下的`package.json`文件，我们可以发现，VS Code其实是基于[Electron](https://www.electronjs.org/)这样一个专门制作跨平台桌面软件的框架而搭建的。VS Code这款软件的组成，其实是里面嵌入了一个Chrome浏览器外加一个Node.js运行时，整个VS Code我们能够看到的界面，其实都是由HTML、CSS和Javascript编写而成并使用Chrome来渲染出页面，如果你不相信，你可以点击VS Code顶部菜单栏的最后一项`Help`，然后选择倒数第二项：`Toggle Developer Tools`，就可以看到弹出的Chrome开发者工具了。

VS Code近些年来越来越受开发者欢迎，是因为它的身上存在这么几个亮点：第一是**打开速度快**，用VS Code来打开一个项目，基本上可以说是秒开，即使是很大的项目，也可以非常快的被打开。

第二是**支持的编程语言非常多**，VS Code在初始状态（*即不按装任何的扩展的情况*）下对Web前端开发、Node.js开发以及PHP等语言的开发都有很好的支持，至于其它的一些编程语言，比如说：Java、Python、Go、Ruby、C#、C/C++等等，只要安装相应的扩展就能很好的完成开发环境的搭建。

第三是**拥有丰富的扩展**，VS Code的扩展十分丰富，首先从**量**上来看，VS Code的扩展数量已经上万，涵盖了方方面面，你能想到的它都有，比如说你想使用Mysql的GUI工具，那么你可以直接下载一个叫`MySQL`的扩展，这样就可以在VS Code中一边写代码，一边完成数据库查询等工作，其次是你想不到的它也有，比如说一款名叫`daily-anime`的扩展，如果你是个动漫爱好者，用了它你就可以边上班边摸鱼了（*不鼓励摸鱼哈，还是安安心心写代码吧，哈哈*）。再一个就是从**质**上来看，VS Code很多重要的扩展都是由微软、谷歌等这样的大公司在维护，这些扩展的安装量有很多都超过百万甚至是千万，所以用起来十分的放心，也很少出错误。除了拥有非常丰富的扩展，VS Code的扩展还有另外两大优势，一是，我们在大陆地区也能够以很快的网速完成扩展的安装；二是，除了一些特殊的扩展，绝大多数扩展安装完就生效，不需要重启VS Code。

第四是**涵盖应用程序的整个生命周期**，一款代码编辑器一般只涵盖应用程序的开发阶段，而对于一些程序，比如说Web应用，常常还会有部署阶段。在VS Code中我们可以利用一些扩展，比如说微软公司提供的azure相关扩展，或者亚马逊公司提供的aws相关扩展，利用它们，我们就可以很方便的通过VS Code完成应用的一键部署，所以从开发到部署全程用VS Code这一个工具就够了！

接下来，我们来看两个可能会遇到的并且有点令人迷惑的英文词汇：`Visual Studio Code`和`Visual Studio`。其实VS Code的全称叫做 `Visual Studio Code`，作为微软于2015年推出的一款代码编辑器，他还有一位老大哥，叫做[Visual Studio](https://visualstudio.microsoft.com/)。所以，`Visual Studio Code`和`Visual Studio`是两款不同的代码编辑器。Visual Studio是微软很早很早以前(*查了下[wikipedia](https://en.wikipedia.org/wiki/Microsoft_Visual_Studio)，第一个版本发布于1997年*)就推出的一款功能强大的IDE，但他主要用于微软自家的一些技术开发，比如说.NET开发和最近比较火的.NET Core开发。VS Code作为一款新产品，在创建之初，就从他大哥身上借鉴了很多好的地方，比如说后面课程会学习的`workspace`概念，如果你用过Visual Studio，你会发现这和Visual Studio上的`solution`很类似，同时VS Code也摒弃了他大哥身上一些不太好的地方，最大改善就是让整个软件变得更加轻量。VS Code安装过后大概占用不到300M的硬盘空间，而Visual Studio呢？哈哈，没有个两三个G你是搞不定他的！我记得在读大学的时候，那时候还在用Visual Studio 2008，为了卸载Visual Studio，我每次都是转而选择重装系统！

除了有老大哥Visual Studio，VS Code他还有一位双胞胎兄弟，叫做`Insiders Edition`，他的下载地址是：[https://code.visualstudio.com/insiders/](https://code.visualstudio.com/insiders/)。他俩无论是相貌还是才能，几乎都一模一样，但是，微软会将一些新的bug修复或者一些新的功能更新，首先发布到`Insiders Edition`，等相应的功能稳定过后，才会将这部分更新发布到VS Code当中。如果你喜欢尝鲜的话，对于平时个人编程学习或者是开发自己的一些小项目，不妨试着用一用`Insiders Edition`。我自己就一直都在用`Insiders Edition`，给我的整体感受是：他俩在使用的是时候，基本上没什么区别。不过最近自己突然发现，`Insiders Edition`推出了[设置同步](https://code.visualstudio.com/docs/editor/settings-sync)功能（*界面左下角，包含人物图标的那个按钮就是*），我们可以使用自己的微软账户或者Github账户在`Insiders Edition`上进行登录，登录过后，我们安装的一些插件，设置过的一些偏好等信息都能够被同步到云端，如果我们以后换了台电脑，只要在新电脑上安装`Insiders Edition`并登录账户，云端保存的信息就会同步到本地，之前的设置就都恢复了。而这个设置同步功能，目前在VS Code中还没有，不过我估计很快就会有的。最后，为了从外貌上区分这对双胞胎，最简单的方法就是看他们的logo图标，`Insiders Edition`的是<span style="padding: 2px 8px;color: #fff;background-color: #20baa0;">绿色的</span>，而VS Code是<span style="padding: 2px 8px;color: #fff;background-color: #0066B8;">蓝色的</span>。


#### 04 在macOS上安装VS Code

这一节课我们会学习如何在macOS上安装VS Code，其中会讲解一个可能会遇到的问题：安装完毕后，却无法打开VS Code。

为了在macOS上安装VS Code，我们首先前往官网首页：[https://code.visualstudio.com](https://code.visualstudio.com)进行安装包的下载，下载完毕后会是个zip文件，将解压后的文件直接拖入Applications里就可以完成安装。

但是我们在打开VS Code的时候可能会遇到无法打开的情况，这是因为你的macOS操作系统版本可能是Catalina，而Catalina在安全方面做了一些增强，对于从非Apple Store下载的应用可能就会遇到这种情况。为了解决这个问题，我们需要打开`System Preferences`，然后点击`Security & Privacy`，在里面就能解锁被阻止的VS Code了。

#### 05 在Windows上安装VS Code

这一节课我们会学习如何在Windows上一步步安装VS Code。

在Windows上安装VS Code，我们首先前往官网首页：[https://code.visualstudio.com](https://code.visualstudio.com)进行安装包的下载，下载完毕后直接双击下载后的exe，在安装的第一步，我们首先选择“我接受协议”，之后全部点击“下一步”按钮直到安装完成。可以说，相较于Mac和Linux上的安装，Windows上的安装是最简单的了。

*P.S. 如果你仔细观察安装的过程，你会发现在安装时，默认勾选住了“添加到PATH”这个选项，正是因为有了这个选项，安装完毕后，我们就可以在cmd或者Powershell中直接使用`code`这个命令了。*


#### 06 在Linux上安装VS Code

这一节课我们会学习如何在Linux上一步步安装VS Code，我会以Ubuntu发行版做演示。

为了在Linux上安装VS Code，我们首先前往官网首页：[https://code.visualstudio.com](https://code.visualstudio.com)进行安装包的下载。在Linux上使用浏览器访问VS Code官网时，我们会发现有两个下载按钮，一个是`deb`，一个是`rpm`，这是因为Linux有很多发行版，不同的发行版我们需要下载不同的安装包，对于Debian、Ubuntu我们需要下载deb安装包，而对于Red Hat、Fedora我们需要下载rpm安装包，因为这一节课我是使用Ubuntu来做演示，所以我下载的是deb。

下载完deb文件，接下来就是安装操作。为了安装VS Code，你可以直接双击deb文件，这样会自动弹出安装引导窗口，这种方式我自己试过几次，但有时会出现一些问题，所以在视频中我选择的是另外一种安装方法：采用Ubuntu自带的`dpkg`命令来完成安装。为了使用dpkg，我们首先打开`Terminal`，然后在`Terminal`中直接输入以下命令:

```shell
sudo dpkg -i [deb的路径]
```

对于`[deb的路径]`我们可以手动输入它在系统中的绝对路径，为了简单，我们也可以直接将deb文件拖入到`sudo dpkg -i `的后面。


#### 07 如何用VS Code打开一个项目

这一节课，我们会学习VS Code第一个最基础的操作：如何用VS Code去打开一个项目，其中会介绍非常重要的`code`命令。

在前面的三节课中，我们分别学习了在Mac，Windows以及Linux上安装VS Code，但是因为我平常用Mac比较多，所以在后面的课程中，我将主要以Mac上的VS Code来做演示。三个平台上的VS Code在功能上完成一致，但是在快捷键、菜单项等一些地方也存在一些使用差别，在后面的课程中，当遇到这些差别时，我会给予一定的提示。还有就是，VS Code安装完毕后，默认显示的语言是英文，虽然可以更换语言包，但在后面的课程中，我还是会采用英文版的VS Code来做演示，最主要的原因是，当有一天你自己去阅读VS Code官方英文文档时，你会很容易将文档中描述的内容与你摆在你面前的VS Code对得上。当然，更换语言包这个操作本身，我们还是需要学会如何去操作的，我将在后面第五章加以介绍。

好的，既然VS Code已经安装完毕，接下来，我们来学习使用VS Code的第一个最基础的操作：如何使用VS Code去打开一个项目。为了打开一个项目，VS Code提供了三种方式，它们分别是：

第一，采用**拖拽**，我们可以将一个项目目录直接拖拽入VS Code，就能让VS Code直接打开这个项目。

第二，使用**菜单栏选项**, 在Mac上是：`File > Open`；而在Windows上是：`File > Open Folder`。

第三，是使用`code`命令，这也是我认为我们必须要学会的一个操作技巧，我们可以通过code命令直接从命令行中打开一个项目。code这个命令其实是VS Code自带的一个命令，在Windows和Linux上安装VS Code的时候，就默认帮我们安装好了code这个命令，所以我们可以直接在Linux的Terminal或者Windows中的cmd中使用code命令。而在Mac上，我们需要手动安装，安装步骤是：

1. 打开菜单栏中的`View > Command Palette`
2. 在`Command Palette`的顶部输入框中输入：`path` 并点击结果列表中的`Shell Command: Install 'code' command in PATH`
3. 新打开一个`terminal`窗口并输入`code -h`来校验一下code命令是否安装成功

最后，我们来看一下code命令的**三个常用用法**：

```shell
code -h             # 用于显示帮助文档
code .              # 用于打开当前目录
code [文件夹路径]     #用于打开指定路径下的文件夹
```

*P.S. 除了可以打开一个项目目录，VS Code也可以用来直接打开单个文件，我自己就经常用 `code ~/.zshrc`来修改本地zsh的配置文件。*

[回到顶部](#课程详情)

### 第二章 界面布局与功能介绍

在第一章我们完成了VS Code的安装并且学习了如何使用VS Code去打开一个项目，我们将在这个的基础上，开始VS Code用户界面的学习。VS Code的用户界面其实是由五大部分组成，每一个部分都有特定的功能，这些功能从不同的角度协助我们更好的利用VS Code来完成项目的开发工作，所以在正式使用VS Code开发项目之前，我们一定要先学好这五大部分。

这五大部分的内容会比较多，也有点杂，建议你多点耐心，一个一个的学好，我想，其中一些看似很小的知识点或者技巧，如果你掌握了，一定会帮助你在实际的项目开发过程中节省很多时间，提升开发效率。

好的，下面我们就来一个一个的学习吧！

**小节目录**

- [08 用户界面概览](#08-用户界面概览)
- [09 资源管理器](#09-资源管理器)
- [10 搜索工具](#10-搜索工具)
- [11 源代码管理](#11-源代码管理)
- [12 在macOS上搭建Git环境](#12-在macos上搭建git环境)
- [13 在Windows上搭建Git环境](#13-在windows上搭建git环境)
- [14 在Linux上搭建Git环境](#14-在linux上搭建git环境)
- [15 在VS Code中使用Git - Part1](#15-在vs-code中使用git---part1)
- [16 在VS Code中使用Git - Part2](#16-在vs-code中使用git---part2)
- [17 介绍调试工具](#17-介绍调试工具)
- [18 在macOS上搭建Node.js开发环境](#18-在macos上搭建nodejs开发环境)
- [19 在Windows上搭建Node.js开发环境](#19-在windows上搭建nodejs开发环境)
- [20 在Linux上搭建Node.js开发环境](#20-在linux上搭建nodejs开发环境)
- [21 调试界面概览](#21-调试界面概览)
- [22 Debug sidebar的使用方式](#22-debug-sidebar的使用方式)
- [23 Debug toolbar的使用方式](#23-debug-toolbar的使用方式)
- [24 介绍launch.json](#24-介绍launchjson)
- [25 调试技巧1 搜索本地变量](#25-调试技巧1-搜索本地变量)
- [26 调试技巧2 logpoints](#26-调试技巧2-logpoints)
- [27 调试技巧3 conditional breakpoint](#27-调试技巧3-conditional-breakpoint)
- [28 调试技巧4 inline breakpoint](#28-调试技巧4-inline-breakpoint)
- [29 调试技巧5 multi-target debugging](#29-调试技巧5-multi-target-debugging)
- [30 管理扩展](#30-管理扩展)
- [31 介绍Command Palette](#31-介绍command-palette)
- [32 介绍Settings](#32-介绍settings)
- [33 介绍User Snippets](#33-介绍user-snippets)
- [34 隐藏Side Bar](#34-隐藏side-bar)
- [35 介绍Editor区域](#35-介绍editor区域)
- [36 Zen Mode](#36-zen-mode)
- [37 介绍Panels](#37-介绍panels)
- [38 Terminal的使用方式与技巧](#38-terminal的使用方式与技巧)
- [39 Status bar的使用技巧](#39-status-bar的使用技巧)
- [40 用户界面知识快速复习](#40-用户界面知识快速复习)

#### 08 用户界面概览

这一节课，我们会对VS Code的用户界面做一个大致的概览。

VS Code的用户界面一共由五大部分组成，分别是：

1. 底部的Status Bar（状态栏），用于显示当前被打开文件的一些信息。
2. 最左侧的Activity Bar（活动栏），它里面包含了VS Code五个重要功能的入口点。
3. Activity Bar旁边的Side Bar（侧边栏），它里面包含了Activity Bar五个功能点的详细内容。
4. 右侧，占据空间最多的Editor（编辑器），用于编写代码。
5. 编辑器下方的Panels（面板），它包含了4个不同的面板，其中的Terminal面板我们会经常用到。



#### 09 资源管理器

从这一节课开始，我们将具体学习VS Code用户界面的每一块内容，首先我们将学习最左侧的Activity Bar。这一节课，我们会学习Activity Bar的第一个功能点：Explorer（资源管理器）。

**Explorer**它的功能主要是用于显示我们项目所包含的所有文件以及文件夹。在Side Bar中，我们可以看到，整个功能区被分成了三个部分，从上到下分别是：OPEN EDITORS、项目本身、OUTLINE。位于中间的项目本身，我们可以看到自己的项目名，以及项目里包含的文件及文件夹，如果我们将鼠标放在在项目名的右侧区域，我们可以看到四个功能键，它们分别用于在当前项目里新建一个文件、新建一个文件夹、刷新当前目录、折叠某个目录。

接着我们来看上方的OPEN EDITORS，在OPEN EDITORS里面，它以列表的形式列出了当前所有被打开的文件，这里面包含了一个非常好用的功能,我们可以将鼠标移动到OPEN EDITORS的右侧，这时会出现三个功能键，通过点击最右侧那个带有叉叉图标的按键，我们就可以**一键关闭所有当前被打开的文件**。在实际的项目开发过程中，随着时间推移，我们打开的文件经常是越来越多，这时候我们常常希望关闭所有被打开的文件，来让整个编辑器看起来更加清爽，而利用刚刚说的那个带有叉叉图标的按键，我们就可以很方便的完成这种操作。

最后，我们来看一下最下方的OUTLINE，OUTLINE我用自己的话总结它的作用就是：**换个角度看代码**。对于一份源代码，OUTLINE中列出的视图常常会以另外一个角度来看待，比如当前源代码是HTML，OUTLINE中视图就会以DOM树的角度来看待，再比如当前源代码是面向对象编程语言，它就会从类、类的成员变量、类的成员函数等角度来看待。那，这种从不同角度来看待源代码会带来什么好处呢？好处有两点：第一，当代码过长时，通过OUTLINE中列出的视图信息，我们可以**很容易理解代码的组织结构**；第二，当代码过长时，通过点击OUTLINE视图中的选项，我们可以**很容易跳转到指定的代码块**。


#### 10 搜索工具

这一节课，我们会学习Activity Bar的第二个功能点，用于搜索和替换的：Search。

点击Search，我们可以在Side Bar顶部看到两个输入框，第一个输入框是用于文本的搜索，而第二个输入框则用于文本的替换。相较于替换，我感觉在平时的工作中使用“搜索”会更多些。通过搜索，我们可以很方便的找到某个单词或者某个句子在整个项目中出现过的地方，通过查看搜索词在其它文件中是如何被使用，如果是跟踪一个bug，那么就能通过这种方式来快速追踪bug的来源，而如果我们是刚接手一个项目，就很有可能对其中的一些函数、类或者组件的用法不太熟悉，那么就能通过这种方式来找到这些函数、类或者组件出现过的地方，并参考它们是如何被写的。

搜索和替换的使用方法很简单，直接在输入框里输入相应的单词就可以，但是VS Code还针对搜索和替换提供了一些高级选项，通过这些高级选项，我们可以进一步缩小查询结果的范围，当遇到比较大的项目时，开启这些选项还是很有用的，可以帮助我节省查看搜索结果所花费的时间，在这一节课的视频中，你可以看到这些高级选项具体是如何工作的。

#### 11 源代码管理

这一节课，我们会学习Activity Bar的第三个功能点，用于Git版本控制的：Source Control。

通过Source Control，我们可以很方便在VS Code里完成对Git的相关操作。不过，为了使用Source Control，我们需要满足以下两个条件：

1. 我们需要在本地电脑先搭建好Git环境
2. 项目自身要使用Git

虽然这门课程是用于学习VS Code，但是呢，Git在实际的工作中真的非常重要，所以在学习Source Control之前，我将先带领大家一步步完成Git环境的搭建。

在搭建Git环境之前，我们先来看一下Git命令的分类。用过Git的都知道，一部分Git命令可以在本地电脑直接使用，比如说命令log、add、commit、branch等，还有一部分命令就必须和远程仓库做交互了，比如push、pull等。在实际的工作中，你会发现，我们几乎每天都要与远程Git仓库打交道，比如说，早上上班后，会首先拉取远程仓库的更新到本地，晚上下班前，将自己本地尚未提交的代码提交到远程等等。所以，学习Git，我们一定也要学好涉及远程仓库的一些知识，而提到远程仓库，就不得不提到存放远程远程仓库的**代码托管平台**了。市面上代码托管平台有很多很多，比如说可以是自建的Gitlab，也可以是利用几乎免费的Github等等，在后面的学习中，我将使用Github来做演示。

为了安全、快捷的完成与远程仓库的通讯，我们常常采用ssh，而为了使用ssh，我们就必须完成ssh的配置工作，所以整个Git环境的搭建有很大一部分精力是花在ssh的配置上的。接下来，我们来看一下Git环境搭建的具体步骤：

**第一步：安装Git**

首先需要前往Git官网下载Git的安装包，地址是：[https://git-scm.com/downloads](https://git-scm.com/downloads)

**第二步：完成Git的基础配置**

安装完Git后，我们需要完成Git的两个基础配置：`user.name`和`user.email`，这样我们就能知道每次commit的作者是谁，他的联系邮箱又是什么。为了配置这两项，需要输入以下命令：

```shell
git config --global user.name "your name" 
git config --global user.email your@example.com
```

*P.S. 将`your name`替换成你自己的Github用户名，将`your@example.com`替换成注册Github时填写的邮箱。*

**第三步：生成ssh公钥私钥**

从这一步开始，就进入ssh的相关配置了。我们首先需要在本地电脑通过一些命令生成ssh的公钥和私钥，这里我们可以参考Github所提供的一篇文档，它里面详细记录了各种操作系统生成ssh公钥和私钥的步骤，链接地址是：[https://help.github.com/en/github/authenticating-to-github/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent](https://help.github.com/en/github/authenticating-to-github/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)。

**第四步：将公钥添加到Github**

因为后面我们会使用Github来作为远程代码的托管平台，所以我们需要完成本地电脑与Github之间的ssh配置。完成这个配置很简单，我们首先将上一步生成的公钥内容复制，然后进入自己Github账户的设置页，然后点击侧边栏中的`SSH and GPG keys`并点击`New SSH key`，将复制的公钥在这里粘贴就可以。这样，以后我们本地电脑与Github进行ssh通讯时，本地电脑上的私钥就与存放在Github上公钥完成匹配，ssh通讯就能成功建立连接。对于这一步的操作，Github也提供了一份详细的文档，地址是：[https://help.github.com/en/github/authenticating-to-github/adding-a-new-ssh-key-to-your-github-account](https://help.github.com/en/github/authenticating-to-github/adding-a-new-ssh-key-to-your-github-account)

**第五步：测试ssh连接**

为了验证本地电脑与Github之间的ssh通讯是否正常，我们可以使用如下命令：

```sh
ssh -T git@github.com
```

如果显示的结果中出现了你的Github账户名，那就说明ssh通讯正常，也说明我们已经成功完成了Git环境的搭建工作。关于这一步详细的文档，可以参阅：[https://help.github.com/en/github/authenticating-to-github/testing-your-ssh-connection](https://help.github.com/en/github/authenticating-to-github/testing-your-ssh-connection)。

在后面的三节课，我将上面按照这五步，分别完成在macOS、Windows以及Linux上的Git环境搭建。

#### 12 在macOS上搭建Git环境

这一节课，我们将学习如何在macOS上搭建Git环境，为我们后面学习Source Control做好准备。

为了安装Git，我们将按照[第11课](#11-源代码管理)中提到的五个步骤来操作：

**第一步：安装Git**

首先需要前往Git官网下载Git的安装包，地址是：[https://git-scm.com/downloads](https://git-scm.com/downloads)

**第二步：完成Git的基础配置**

```shell
git config --global user.name "your name" 
git config --global user.email your@example.com
```
*P.S. 将`your name`替换成你自己的Github用户名，将`your@example.com`替换成注册Github时填写的邮箱。*

**第三步：生成ssh公钥私钥**

```shell
ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
eval "$(ssh-agent -s)"
ssh-add -K ~/.ssh/id_rsa
```

*P.S 将`your_email@example.com`替换成你自己的任意邮箱*

**第四步：将公钥添加到Github**

首先通过mac自带的`pbcopy`命令复制公钥内容，再将公钥粘贴到Github中。

```shell
pbcopy < ~/.ssh/id_rsa.pub
```


**第五步：测试ssh连接**

```sh
ssh -T git@github.com
```

#### 13 在Windows上搭建Git环境

这一节课，我们将学习如何在Windows上搭建Git环境，为我们后面学习Source Control做好准备。


为了安装Git，我们将按照[第11课](#11-源代码管理)中提到的五个步骤来操作：

**第一步：安装Git**

首先前往Git官网下载Git的安装包，地址是：[https://git-scm.com/downloads](https://git-scm.com/downloads)
这一步需要注意的是，在安装Git的时候，其实这个安装包也会默认帮我们安装一个叫`Git Bash`的工具。在Windows上做Git相关操作，相较于cmd或者Powershell，我推荐使用Git Bash。它有很多优点，比如，它可以在命令行中直接显示当前Git的分支名，所以在后面的几个步骤中，我将使用Git Bash来完成相关操作。

**第二步：完成Git的基础配置**

```shell
git config --global user.name "your name" 
git config --global user.email your@example.com
```

*P.S. 将`your name`替换成你自己的Github用户名，将`your@example.com`替换成注册Github时填写的邮箱。*

**第三步：生成ssh公钥私钥**

```shell
ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
eval $(ssh-agent -s)
ssh-add ~/.ssh/id_rsa
```

*P.S 将`your_email@example.com`替换成你自己的任意邮箱*

**第四步：将公钥添加到Github**

首先通过Windows自带的`clip`命令复制公钥内容，再将公钥粘贴到Github中。

```shell
clip < ~/.ssh/id_rsa.pub
```

*如果你的windows系统不存在clip命令，你可以先用记事本打开公钥文件，再手动复制公钥内容*


**第五步：测试ssh连接**

```sh
ssh -T git@github.com
```

#### 14 在Linux上搭建Git环境

这一节课，我们将学习如何在Linux上搭建Git环境，为我们后面学习Source Control做好准备，我将以Ubuntu桌面版做演示。

为了安装Git，我们将按照[第11课](#11-源代码管理)中提到的五个步骤来操作：

**第一步：安装Git**

在Linux安装Git，我们可以通过下面这条命令：

```shell
sudo apt update && sudo apt install git -y
```

**第二步：完成Git的基础配置**

```shell
git config --global user.name "your name" 
git config --global user.email your@example.com
```

*P.S. 将`your name`替换成你自己的Github用户名，将`your@example.com`替换成注册Github时填写的邮箱。*

**第三步：生成ssh公钥私钥**

```shell
ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
eval "$(ssh-agent -s)"
ssh-add ~/.ssh/id_rsa
```

*P.S 将`your_email@example.com`替换成你自己的任意邮箱*

**第四步：将公钥添加到Github**

首先通过Linux的`cat`命令打印出公钥内容，再通过鼠标选中内容并手动复制，最后将公钥粘贴到Github中。

```shell
cat ~/.ssh/id_rsa.pub
```


**第五步：测试ssh连接**

```sh
ssh -T git@github.com
```

#### 15 在VS Code中使用Git - Part1

这一节课，我们将学习使用Source Control来完成一些Git常用操作。

在前面的三节课里，我们完成了Git环境的搭建工作，所以这一节课开始，我们就来正式学习VS Code的Source Control。为了更好的学习Source Control，对于接下来的每一个演示项目，我都会准备两份。这两份其实它们的内容完全一致，不同的只是项目名而已。其中的一份，我会使用git命令加vim的方式进行操作，而另一份，我会使用VS Code来操作。之所以采用这种方式，第一，可以帮助你复习Git的常用命令。说真的，使用命令来操作Git是非常重要的，因为有些时候我们只能通过命令来完成Git操作，比如说在远程的Linux服务器上进行Git操作时，我们就只能通过Git命令。所以我个人的建议是：我们可以使用Git的GUI工具（*比如 SourceTree、Github Desktop、Gitkraken以及我们即将学习的Source Control*），但是一定要先学会如何使用命令来完成一些Git常用操作！第二，采用这种方式可以带来另外一个好处，那就是我们可以更好的理解在使用Source Control的过程中，它的底层到底做了什么操作，理解了这些底层操作，有时候反而可以帮助我们更加灵活的利用Source Control。第三，采用这种方式后，我们可以很好的进行比较：哪些操作使用Source Control真的很有优势，而哪些操作其实使用命令也很方便。

Git的操作有很多，在这一节课里，我们会学习利用本地环境就能完成操作的Git命令，它们分别是：

1. git init：用于初始化一个Git仓库
2. git status：用于查看当前Git状态
3. git add：它的使用场景有三个：1、将一个尚未被Git跟踪的文件纳入Git跟踪；2、将一个已经被Git跟踪的文件且这个文件处于修改状态，通过add，可以将它纳入暂存区；3、将merge或者rebase后产生的冲突文件标记为冲突已解决。
4. git commit：将暂存区内容纳入Git提交记录
5. git restore：取消对某个文件的修改
6. git diff：查看文件修改详情
7. git checkout：切换分支
8. git branch：新建分支
9. git merge：合并分支
10. git stash：临时保存当前分支的工作状态，方便切换到其它分支。

在这一节课的视频中，你可以看到上面提到的所有操作。

#### 16 在VS Code中使用Git - Part2

这一节课，我们将学习使用Source Control完成与远程仓库相关的Git操作。

与远程仓库相关的Git操作中，常用的有三个，它们分别是：

1. git clone：用于克隆一个远程仓库
2. git pull：用于拉取远程仓库的更新并将更新合并到本地分支，它等于git fetch 加 git merge
3. git push：将本地的修改提交到远程分支

在这一节课的视频中，你可以看到如何利用Git命令以及Source Control来完成上面三个操作。

#### 17 介绍调试工具

这一节课，我们会学习Activity Bar的第四个功能点：Debug。

Debug也就是调试，在软件项目开发过程中，调试扮演着非常重要的角色。当我们的程序遇到问题是，我们可以利用调试来快速定位问题发生的原因；当我们对一段代码逻辑不是很清楚时，我们也可以利用调试来帮助我们理解代码内部的逻辑，可以看到调试功能对我们开发人员来说是多么的重要，自然VS Code也少不了对调试功能的支持，而且支持度还不是一般的好，是非常的好！

VS Code中涉及调试的知识非常的多，我将这些知识分成了两类，一类叫“通用知识”，这些通用知识，无论我们使用VS Code来调试什么项目，它都可以用的上，甚至是即使我们不用VS Code转而使用其它编辑器，你会发现学到的这些知识在其它的编辑器中基本上也能适用。对于这部分通用知识，我会在这一章接下来的课程中一一进行介绍。还有一类，叫“和具体编程语言相关的调试知识”，我们知道，VS Code支持很多编程语言的调试，而不同的编程语言在调试时，需要使用不同的调试配置，对于这部分知识我会在后面第六章结合具体的编程语言进行逐一介绍。所以，接下来我们首先来学习VS Code中用于调试的“通用知识”。不过，为了学习调试的“通用知识”，我们还是必须要选择一门编程语言来写调试的演示项目，这里，我选择的编程语言是：**基于Node.js运行时的Javascript**，为了后面方便称呼，我将它简称为“Node.js”（*P.S. 需要注意的是：Node.js并不是一门编程语言，而是一个专门运行Javascript代码的运行时*），为什么会是它呢？回答这个问题之前，我们先来看一下，如果要想在VS Code进行调试，我们需要满足的三个条件：

1. **搭建相应编程语言的开发环境** ：比如说，我们想调试Java程序，那我们就必须先要在本地搭建好Java的开发环境，保证可以在命令行中调用`java`和`javac`命令。
2. **安装相应编程语言用于调试的扩展**：不同的编程语言在调试时，还需要借助专门的扩展。比如说，我们想调试PHP程序，那我们就必须要安装一个叫`PHP Debug`的扩展。
3. **配置launch.json**：`launch.json`是VS Code中专门用于调试的配置文件，只有将这个文件配好了，我们才能开启调试。

可以看到，如果我们想要在VS Code中学习调试，要准备的东西还是挺多的，不过，如果我们使用的是Node.js的话，我们可以省略其中的条件2和条件3，这是因为VS Code默认只支持Node.js调试（*P.S. 在第三课中，我们有提到VS Code的内部其实是嵌入了一个Chrome浏览器外加一个Node.js运行时，这或许就是VS Code和Node.js这么亲近的原因吧*）。所以，对于调试的“通用知识”学习，我将使用Node.js来做演示。

为了使用Node.js，我们就必须要先在本地搭建好Node.js的开发环境，所以在接下来的三节课，我将分别介绍如何在macOS、Windows以及Linux上搭建Node.js开发环境。

#### 18 在macOS上搭建Node.js开发环境

这一节课，我们将学习在macOS上搭建Node.js开发环境，为后面利用Node.js来学习调试的通用知识做好准备。

在macOS上搭建Node.js开发环境很简单，一共两步：

1. 下载Node.js安装包并安装：下载地址是：[https://nodejs.org](https://nodejs.org)
2. 校验安装是否成功：在Terminal中输入`node -v`

#### 19 在Windows上搭建Node.js开发环境

这一节课，我们将学习在Windows上搭建Node.js开发环境，为后面利用Node.js来学习调试的通用知识做好准备。

在Windows上搭建Node.js开发环境也很简单，一共两步：

1. 下载Node.js安装包并安装：下载地址是：[https://nodejs.org](https://nodejs.org)
2. 校验安装是否成功：在cmd中输入`node -v`

#### 20 在Linux上搭建Node.js开发环境

这一节课，我们将学习在Linux上搭建Node.js开发环境，为后面利用Node.js来学习调试的通用知识做好准备，我将使用Ubuntu桌面版做演示。

在Linux上搭建Node.js开发环境的方法有很多，我推荐如下方法：

1. 安装nvm：文档地址是：[http://nvm.sh](http://nvm.sh)
2. 安装Node.js：直接在Terminal中输入`nvm install 12.16.1`来安装指定版本的Node.js，这里我选择的版本是：12.16.1
3. 校验安装是否成功：在Terminal中输入`node -v`

#### 21 调试界面概览

这一节课，我们将对VS Code的调试界面做一个大致的概览。

VS Code的调试界面，我将它分成了四个部分，分别是：

1. 位于顶部的Debug toolbar，在调试时，用它来控制程序的执行流程
2. 位于行号左侧的Breakpoint，也就是断点。为了做调试，我们至少需要打上一个断点
3. 位于底部的Debug console panel，它有两个功能，一是可以输出调试日志，二是可以利用当前函数的本地变量输出表达式的值
4. 位于Side Bar中的Debug sidebar，它由多个部分组成，用于显示本地变量、计算表达式、显示函数调用栈、断点管理等功能

#### 22 Debug sidebar的使用方式

这一节课，我们会学习Debug sidebar的使用方式，它由五个部分组成，在调试过程中，其中的每个部分都会从不同的角度来帮助我们完成调试工作。

Debug sidebar一共由五个部分组成，从上到下分别是：VARIABLES、WATCH、CALL stack、LOADED SCRIPTS、BREAKPOINTS。这里面我个人觉得：学会VARIABLES、WATCH和CALL stack的用法非常的重要，利用VARIABLES，我们可以分析当前函数的本地变量；利用WATCH，我们可以使用本地变量组成我们想要的表达式并输出结果；利用CALL stack，我们可以理清函数的调用关系。

Tip: 课程中会使用以下代码片段：

```js
class Person {
    constructor(firstName, lastName, age) {
        this.firstName = firstName;
        this.lastName = lastName;
        this.age = age;
    }

    getName() {
        const name = this.lastName + this.firstName;
        return name;
    }

    say() {
        const name = this.getName();
        const text = name + ":" + this.age;
        return text;
    }
}

const person = new Person("三", "张", 20);
const text = person.say();
console.log(text);
```

#### 23 Debug toolbar的使用方式

这一节课，我们会学习Debug toolbar的使用方式，它里面包含里用于控制程序执行流程的六个小工具。

首先我想强调的是：学会使用Debug Toolbar**非常的重要**，它将直接关系到我们能否顺利完成调试任务，所以建议你一定要牢牢掌握这一节课的内容。

当我们在调试时，我们就必须要借助Debug Toolbar上的六个工具，来控制程序的执行流程，这六个工具从左到右分别叫做：continue、step over、step into、step out、restart、stop。

**continue**，它的作用是**立即跳到下个断点**，如果后面没有断点了，那么程序就会运行到最后一行代码，在Web后端开发中，为了调试一个请求处理函数，我们常常会利用continue来释放被阻塞的请求。

**stop**，它的作用很简单，用于**立即中断调试**，当我们想要放弃调试时，就可以使用它。

**restart**，它的作用也很简单，用于**立即重启调试**，当我们在调试过程中修改了源代码，为了让修改生效，我们就可以使用它来重启调试。

接下来，是有点让人迷惑的**step over**和**step into**了，之所以让人迷惑，是因为他俩既有相似点也有不同点，关键在于**当前行是否存在函数调用**，如果存在，那他俩的作用一样：都是**单步执行**，如果不存在，**step over**会直接拿到函数的返回结果并运行至下一行，而**step into**则会进入当前行函数并运行至该函数的第一行。所以，如果当前行存在函数调用，选择**step over**还是**step into**，就要看我们对这个函数内部实现细节感不感兴趣了，感兴趣的话就用**step into**，不感兴趣的话就用**step over**。

最后一个是**step out**，它和**step into**刚好相反，**step into**是跳入函数，而**step out**则是跳出函数。它的使用场景常常是：当我们身处某个函数内部，同时这个函数的代码行数又很多，我们可能利用单步调试，运行了前面几行代码过后，就达到了自己的调试目的，这时候为了避免再单步执行后面大段我们不感兴趣的代码，我就可以使用它来快速跳出当前函数，节省时间。

#### 24 介绍launch.json

这一节课，我们会学习VS Code调试时，非常重要的launch.json。

除了Node.js以外，其它场景的调试，我们都需要配置launch.json这个文件，所以学习和理解launch.json就显得格外重要。

launch.json是用于调试的配置文件，这个配置文件里会指定一些非常重要的信息，比如说，当前调试的程序是什么语言编写的，是Java？是C#？还是C？等等。这个关键的信息必须要在launch.json中指定，为了指定这个信息，我们需要借助配置项`type`。

除了`type`，还有一个配置项也很重要，叫做`request`，它有两个值可供选择，一个叫`launch`，一个叫`attach`。使用`launch`我们可以让VS Code去启动我们的程序，同时启动后的程序还支持调试。而`attach`的方式有点不一样，它并不会帮我们启动程序，而是通过为一个**已经在运行且还不支持调试**的程序**注入一个调试器**，让这个程序从不支持调试变成支持调试。

Tip: 课程中会使用以下代码片段：

```js
const http = require("http");

const server = http.createServer((req, res) => {
    res.end("hello world");
});

server.listen(3000, () => {
    console.log("Server is listening on 3000");
});
```

#### 25 调试技巧1 搜索本地变量

这一节课，我们会学习**搜索本地变量**这个调试小技巧，利用它我们可以从大量的信息中快速寻找到自己想要的结果。

在调试过程中，VARIABLES里会显示当前函数的所有本地变量，有些情况下，这些本地变量的数量会非常对多，这种情况下，为了从中快速找到自己想要的值，我们就可以将光标定位到VARIABLES区域，然后直接输入搜索关键词，这样VS Code会自动定位到符合搜索词的变量并高亮其内容。在这一节课的视频中，我们将学习它的具体使用用法。

#### 26 调试技巧2 logpoints

这一节课，我们会学习一种特殊的断点：**logpoints**，使用它我们可以以非阻塞、打日志的方式来调试程序

对于一个处于生产环境的Web项目，如果我们想要对其进行调试，为了**降低普通断点造成请求被阻塞的风险**，我们就可以使用logpoints断点，它以非阻塞、打日志的方式来调试程序。在这一节课的视频中，我们将学习它的具体使用用法。

#### 27 调试技巧3 conditional breakpoint

这一节课，我们会学习一种特殊的断点：**conditional breakpoint**，使用它我们可以为一个断点添加条件判断语句，条件判断语句返回真时，断点才会生效。在这一节课的视频中，我们将学习它的具体使用用法。

在上一节课我们有提到，对于一个处于生产环境的Web项目，如果我们想要对其进行调试，我们可以使用logpoints断点。虽然logpoints断点不会阻塞程序的运行，但它毕竟只是通过输出日志的方式进行调试，对于一些复杂的场景，这种做法的效率就会比较低。为了更快的利用调试来定位问题，使用普通断点是最好的方式，所以，对于这种**既想要使用普通断点又不想要请求被阻塞**的情况，我们就可以使用conditional breakpoint，使用它之后，我们可以为一个普通断点加上一个条件，只有当条件满足时，断点才会生效，通过这种方式来最小化调试带来的请求阻塞风险。

#### 28 调试技巧4 inline breakpoint

这一节课，我们会学习VS Code支持的另外一种特殊断点：**inline breakpoint**，当一行代码存在多个函数调用时，使用它，我们就可以在任意一个函数前面添加一个断点。在这一节课的视频中，我们将学习它的具体使用用法。

Tip1: 课程中会用到以下代码片段：

```js
class Demo {
    static getFoo() {
        return "foo";
    }

    static getBoo() {
        return "boo";
    }

    static getCoo() {
        return "coo";
    }
}

const info = Demo.getFoo();
console.log(info);
```

Tip2: 课程中用到的serve命令，可以通过下面的命令来安装：

```shell
npm i -g serve
```

Tip3: 课程中用于模拟第三方库的链接是：

[https://tsqcdn.oss-cn-shanghai.aliyuncs.com/lib.js](https://tsqcdn.oss-cn-shanghai.aliyuncs.com/lib.js)


#### 29 调试技巧5 multi-target debugging

这一节课，我们会学习：**multi-target debugging**，使用它，我们可以在VS Code中同时发起多个调试。

当面对**前后端分离**等场景时，我们的项目可能会被拆分成多个子项目，每个子项目可以是不同的编程语言编写，为了能够对这些子项目同时进行联调，我们就可以使用VS Code提供的multi-target debugging功能，同时开启多个调试。

multi-target debugging的使用方式有两种，一种是通过依次启动单个调试配置项，另一种我认为更加方便，我们可以在launch.json中添加一个`compounds`配置项，通过它我们就能一键快速启动多个调试项。在这一节课的视频中，你将学到它们的具体用法。

Tip1: 课程中要到的create-react-app命令可以通过下面的方式来安装：

```shell
npm i -g create-react-app
```

Tip2: 课程中介绍了一个前后端分离项目，我将它上传到了Github，地址是：

[https://github.com/tsq-vscode/multi-target-debugging](https://github.com/tsq-vscode/multi-target-debugging)

#### 30 管理扩展

这一节课，我们会学习Activity Bar的第五个功能点，用于管理扩展的：Extensions。

首先，对于这一块内容，有些人喜欢把它称为“插件”，有些人则喜欢把它称为“扩展”，在这门课程中，我会把它称作“扩展”。

VS Code的扩展非常的丰富，我将它大致分成了以下三类：

- **写代码相关**： 这一类的扩展最多，比如格式化代码的 "Prettier"、调试PHP代码的 "PHP Debug"等
- **工具**：这些扩展以工具的形式集成在了VS Code当中，比如用于远程开发的 "Remote SSH"
- **自定义相关**：比如用于更换主题、语言包、快捷键的扩展

接着，我们来看一下Extensions的具体用法。Extensions这个工具主要用于扩展的管理，而扩展的管理常用的操作有：扩展的搜索、安装、禁用、删除等。在这一节课的视频中，我将以`DotENV`这个扩展为例，演示这些操作。


#### 31 介绍Command Palette

Activity Bar的底部有一个按钮，名叫：Manager，Manager里面包含了一些VS Code的功能选项，其中有三个我认为比较重要，分别是Command Palette、Settings、User Snippets。这一节课，我们会先学习：Command Palette。

因为Command Palette会被经常使用，所以我们需要记住打开它的快捷键。这个快捷键，在Mac上是：` shift + ⌘ + p`，在Windows上是：`shift + ctrl + p`。

接着，我们来了解下它的作用，它的作用是：**通过命令来执行一些操作**。VS Code中的一些操作，可以有多种方式来实现，以放大VS Code界面为例，我们可以通过菜单栏选项，也可以通过快捷键，还有就是通过Command Palette了。我们可以打开Command Palette，然后直接输入`zi`就能找到放大VS Code的命令。但是需要注意的是：有一些操作，我们只能通过Command Palette来实现，比如说更改VS Code语言包。正因为有些重要的操作只能在Command Palette里实现，所以它非常的重要。这一节课的视频中，你将看到它的具体使用方法。

#### 32 介绍Settings

这一节课，我们会学习“Settings”这个功能选项，并理解其中的“User”和“Workspace”这两个重要的概念。

“Settings”也就是我们常说的“设置”，不过和普通的桌面软件不一样，VS Code的设置有两种，一种是“User”范围下的设置，还有一种是“Workspace”范围下的设置。

对于User设置，一旦我们对其中的设置项进行了修改，那么这些修改会作用于**所有的项目**，而Workspace设置却不一样，在它里面的修改只能作用于**当前这一个项目**。在实际的使用过程中，我们会通过修改User设置，来满足我们的一些个性化的使用需求，而通过修改Workspace设置，在团队协作时，就可以实现代码风格的统一。

User设置和Workspace设置，其实它们的背后都有一个叫做“Settings.json”的配置文件，VS Code设置中出现的界面，其实就是对这份配置文件的可视化展现。利用它，我们不仅可以快速**将某个设置项快速恢复到默认值**，而且我们也可以通过直接编辑这个文件，**快速修改设置项**。

Tip: 所有设置项的默认值，如果使用settings.json来表示，可以参考下面的官方文档：

[https://code.visualstudio.com/docs/getstarted/settings#_default-settings](https://code.visualstudio.com/docs/getstarted/settings#_default-settings)

#### 33 介绍User Snippets

通过VS Code提供的User Snippets功能，我们可以创建属于自己的代码片段，以此来帮助我们快速编写代码，提升开发效率。

User Snippets的配置文件中有两个关键的配置项，一个叫`prefix`，它用于指定**关键词**，在写代码的时候，我们输入完关键词，紧接着按`tab`键，就能立刻生成相应的代码片段，而另一个关键的配置项`body`就是用于配置代码片段的内容，它是一个数组类型，数组的每一项就代表代码片段的一行。

我们在编写代码片段的内容时候，需要注意两件事：第一，如果一行代码中存在代码缩进，我们可以使用空格来代替或者使用`\t`；第二，如果该行代码存在`"`，我们需要使用反斜杠来对它进行转义，也就是：`\"`。

在编写代码片段的时候，我们可以使用以$开头的特殊变量：$0、$1、$2、$3...。$0用于代码片段生成后，光标最后所处的位置，$1、$2、$3...等用于指定光标移动的位置，当我们按tab键时，光标会依次切换到$1、$2、$3所在的位置。

除了$开头的特殊变量，VS Code还支持很多其它特殊变量，比如代表当前年的`$CURRENT_YEAR`，代表当前月的`$CURRENT_MONTH`等等，利用它们，我们可以创建内容丰富的注释。

Tip1: 文本提到的代码片段生成工具，链接如下：

[https://github.com/pawelgrzybek/snippet-generator](https://github.com/pawelgrzybek/snippet-generator)

Tip2: 可以通过下面的文档，查看VS Code代码片段中支持的所有特殊变量：

[https://code.visualstudio.com/docs/editor/userdefinedsnippets#_variables](https://code.visualstudio.com/docs/editor/userdefinedsnippets#_variables)

Tip3: 本节视频中用到的代码片段: `c.json`

```
{
	"using stdio": {
		"prefix": "io",
		"body": [
			"#include <stdio.h>"
		]
	},
	"main function": {
		"prefix": "m",
		"body": [
			"int main() {",
			"\t$0",
			"\treturn 0;",
			"}"
		]
	},
	"print": {
		"prefix": "p",
		"body": [
			"printf(\"%$1\", $2);"
		]
	},
	"print1": {
		"prefix": "p1",
		"body": [
			"printf(\"%${1:you can use: i,s,c,f}\", $2);"
		]
	},
	"print2": {
		"prefix": "p2",
		"body": [
			"printf(\"%${1|i,s,c,f|}\", $2);"
		]
	},
	"my main": {
		"prefix": "mm",
		"body": [
			"#include <stdio.h>",
			"",
			"int main() {",
			"    printf(\"%$1\", $2);",
			"    return 0;",
			"}"
		],
		"description": "my main"
	},
	"header comment": {
		"prefix": "hc",
		"body": [
			"$BLOCK_COMMENT_START",
			" * Author: tsq",
			" * Date: $CURRENT_YEAR-$CURRENT_MONTH-$CURRENT_DATE",
			"$BLOCK_COMMENT_END"
		]
	}
}
```

这一节课是Activity Bar相关知识的最后一节课，下一节课，我们将学习它旁边的：Side Bar。

#### 34 隐藏Side Bar

在使用VS Code的过程中，我们常常希望为代码编辑区域留出更多的空间，这时我们可以选择隐藏Side Bar，而隐藏Side Bar最方便的操作是使用快捷键。

隐藏Side Bar的快捷键如下：

- Mac: <kbd>command + B</kbd>
- Win: <kbd>ctrl + B</kbd>

#### 35 介绍Editor区域

这一节课将对 VS Code 的 Editor 区域做一个简单的介绍，你将学习到 minimap 以及 breadcrumbs 相关的知识。

minimap 位于编辑器的右侧，它有两个作用，一是通过它我们可以对源文件的内容做一个大致的概览，二是可以通过拖动它来快速移动到指定对代码区域。VS Code 默认会显示 minimap，如果你觉得 minimap 对你并没有什么作用，或者是觉得它占用了过多的编辑器空间，我们就可以选择将 minimap 隐藏，隐藏对方式是：点击顶部`View`菜单栏并点击里面的`Show Minimap`菜单项。

breadcrumbs 位于编辑器顶部，它其实是由两部分组成，以文件名为分割线，文件名左侧显示的是文件在项目中的相对路径，文件名右侧显示的是 Symbol 信息。Symbol 是对文件内容的一种展现方式，不同的文件类型有不同的展现方式，比如对于面向对象编程语言而言，常常是以类，类的属性，类的方法等方式来展现光标所处行的信息，而对于 html 文件，它则会以 Dom 树的结构来进行展现。Symbol 这个词在阅读 VS Code 官方文档时偶尔会遇到，我们只需要知道它所代表的意思就可以了。

#### 36 Zen Mode

Zen Mode是VS Code提供的一种非常有趣的编辑模式，在这种模式下，我们可以更加专注的编写代码。

为了开启Zen Mode，有三种方式可以选择，分别是：

1. 使用菜单栏选项：View > Appearance > Zen Mode
2. 通过Command Palette，输入关键词: zm
3. 使用快捷键，Mac是： `Cmd + K + Z`；Win是 `Ctrl + K + Z`

如果你喜欢在Zen Mode下进行工作，推荐你记住下面七个快捷键：

| 功能                | Mac 上的快捷键              | Win 上的快捷键                      |
| ------------------- | --------------------------- | ----------------------------------- |
| 打开 Explorer       | `Cmd + Shift + E`           | `Ctrl + Shift + E`                  |
| 打开 Search         | `Cmd + Shift + F`           | `Ctrl + Shift + F`                  |
| 打开 Source Control | `Ctrl + Shift + G`          | `Ctrl + Shift + G`                  |
| 打开 Debug          | `Cmd + Shift + D`           | `Ctrl + Shift + D`                  |
| 打开 Extensions     | `Cmd + Shift + X`           | `Ctrl + Shift + X`                  |
| 打开 Terminal       | `Ctrl + 数字键1左侧的那个键`   | `Ctrl + 数字键1左侧的那个键` |
| 隐藏 Sidebar        | `Cmd + B`                   | `Ctrl + B`                          |

通过这七个快捷键，我们可以在Zen Mode下，很方便的完成一些常用操作。

#### 37 介绍Panels

Panels由四个面板组合而成，这一节课，我们会分别学习PROBLEMS, OUTPUT以及DEBUG CONSOLE的使用方式。TERMINAL的学习会放在下一节课。

PROBLEMS, OUTPUT以及DEBUG CONSOLE这三个面板，基本上都是往外输出一些信息，在平时的项目开发过程中，在合适的时候，如果我们能够利用
这些信息，就能够为项目开发带来一定的帮助。这三个面板它们的具体功能如下：

- PROBLEMS：它会列出项目中存在问题的代码，而问题可以分成两种，一种是Warning，代表我们的代码写得并没有错，但是写得不够好，另一种是Error，代表我们的代码写得有错误。
- OUTPUT：它会显示出VS Code自身以及第三方扩展的一些日志信息。
- DEBUG CONSOLE：它有三个功能，第一，会显示调试器自身的日志信息，第二，会显示项目本身包含的控制台输出，第三，在调试过程中，可以输出本地变量，以及利用本地变量组成的表达式的值。

#### 38 Terminal的使用方式与技巧

Terminal是VS Code自带的一个工具，在这个工具中我们可以使用命令来操作计算机以及切换不同的shell，在这一节课你将学习什么是Terminal以及和Terminal相关的计算机基础知识，同时也会了解众多shell的具体使用方式。

对于软件开发者或者计算机系统管理员，常常需要使用命令的方式来操作计算机，而命令的执行需要一个环境，这个环境负责提供命令的输入、输出以及切换不同的shell。VS Code所自带的Terminal其实就是为提供这样的环境而生。

因为一个操作系统通常会提供多种shell，所以在Terminal中执行命令的时候，我需要指定一种shell，Windows中，我们常常使用cmd或者powershell，如果安装了Git，那么我们也可以使用一个叫做“Git Bash”的shell，它支持众多linux命令，同时也会在命令行提示符中显示Git分支名，所以选择“Git Bash”也是一个不错的选择！在MacOS或者Linux中，我们通常使用bash和zsh，这里，我推荐大家使用zsh并且配上“oh my zsh”这个工具：https://github.com/ohmyzsh/ohmyzsh 。因为MacOS默认已经安装zsh，所以在MacOS上只需要再单独安装“oh my zsh”即可，而在Linux中，因为默认没有安装zsh，我们首先需要安装好zsh，下面列出了zsh的安装方法：

```shell
dnf install zsh	# for centos
apt install zsh # for ubuntu
```

因为Terminal很重要，推荐大家记住打开或隐藏Terminal的快捷键:

```shell
ctrl + `(数字键1左侧的那个键)
```

#### 39 Status bar的使用技巧

Status bar位于VS Code用户界面的最底部，它主要会显示当前项目和当前被编辑文件的一些信息。在这一节课，你将学习到Status bar里面包含的众多小技巧，学会这些小技巧，有时候就会带来很大的帮助。

#### 40 用户界面知识快速复习
VS Code的用户界面由5个部分组成，每一个部分里面都包含了很多小功能，这些小功能其实是从不同的角度来协助我们更好的完成一个项目的开发。这一节课，我们就来对这些知识点做一个快速的复习。

[回到顶部](#课程详情)

### 第三章 文件及文件夹的使用

这一章节主要会介绍在VS Code中文件及文件夹的使用方式与使用技巧，还有就是，这一章节的最后我们也会学习，使用VS Code提供的workspace功能来更好的管理多个项目文件夹。

**小节目录**

- [41 文件及文件夹的三个特点](#41-文件及文件夹的三个特点)
- [42 管理文件及文件夹](#42-管理文件及文件夹)
- [43 Dirty Write](#43-dirty-write)
- [44 Preview Mode](#44-preview-mode)
- [45 文件使用技巧1: 寻找文件的三种方式](#45-文件使用技巧1-寻找文件的三种方式)
- [46 文件使用技巧2: 文件快速导航](#46-文件使用技巧2-文件快速导航)
- [47 文件使用技巧3: Pin Tab](#47-文件使用技巧3-pin-tab)
- [48 文件使用技巧4: 单个文件内的搜索和替换](#48-文件使用技巧4-单个文件内的搜索和替换)
- [49 文件使用技巧5: 文件的自动保存与自动格式化](#49-文件使用技巧5-文件的自动保存与自动格式化)
- [50 文件使用技巧6: 文件比较](#50-文件使用技巧6-文件比较)
- [51 文件使用技巧7: Timeline](#51-文件使用技巧7-timeline)
- [52 文件使用技巧8: 快速创建文件或文件夹](#52-文件使用技巧8-快速创建文件或文件夹)
- [53 文件使用技巧9: 快速撤销修改](#53-文件使用技巧9-快速撤销修改)
- [54 文件使用技巧10: 配置项-File Associations](#54-文件使用技巧10-配置项-file-associations)
- [55 文件使用技巧11: 查看源文件的健康状况](#55-文件使用技巧11-查看源文件的健康状况)
- [56 文件使用技巧12: 文件的拖入与拖出](#56-文件使用技巧12-文件的拖入与拖出)
- [57 文件使用技巧13: 文件内容的自由缩放](#57-文件使用技巧13-文件内容的自由缩放)
- [58 文件使用技巧14: 配置项-Compact Folders](#58-文件使用技巧14-配置项-compact-folders)
- [59 文件使用技巧15: Screencast Mode](#59-文件使用技巧15-screencast-mode)
- [60 文件使用技巧16: Save All](#60-文件使用技巧16-save-all)
- [61 文件使用技巧17: 在Source Control中打开文件](#61-文件使用技巧17-在source-control中打开文件)
- [62 文件使用技巧18: 在Source Control中调整文件的排序规则](#62-文件使用技巧18-在source-control中调整文件的排序规则)
- [63 文件使用技巧19: 配置项-Wrap tab](#63-文件使用技巧19-配置项-wrap-tab)
- [64 文件使用技巧20: 配置项-Files exclude](#64-文件使用技巧20-配置项-files-exclude)
- [65 文件使用技巧21: Open in editor](#65-文件使用技巧21-open-in-editor)
- [66 文件使用技巧22: Search editor context](#66-文件使用技巧22-search-editor-context)
- [67 文件使用技巧23: 保存Search Editor](#67-文件使用技巧23-保存search-editor)
- [68 文件使用技巧24: 使用搜索历史记录](#68-文件使用技巧24-使用搜索历史记录)
- [69 文件使用技巧25: 在Explorer中搜索文件](#69-文件使用技巧25-在explorer中搜索文件)
- [70 文件使用技巧26: Find in selection](#70-文件使用技巧26-find-in-selection)

#### 41 文件及文件夹的三个特点

相较于常见的代码编辑器，比如Visual Studio、Xcode、Intellig IDEA，VS Code在文件及文件夹的使用方式上存在3个特点，这一节课，我们就来探讨一些这些不同之处，以此来更好的认识VS Code。

第一个特点是：**VS Code不支持新建模版项目**， 我们在新建一个项目时，常常希望使用一个模板项目，之后再在这个模板项目的基础上做二次开发，但是VS Code本身并没有像其它编辑器那样提供一个叫做“New Project”的选项来新建一个模板项目，虽然不支持，但是，我们可以使用下面两种方式来创建模板项目，第一种方式是使用命令行工具，我们可以安装一些能够创建项目模板的命令，比如开发vuejs的“vue”命令，开发dotnet core的“dotnet”命令等等；第二种使用方式是使用扩展，VS Code中一些扩展可以用于快速新建一个模板项目，比如“Web Template Studio”和“Spring Initializr Java Support”。

第二个特点是：**VS Code不支持新建模板文件**，VS Code的“New File”功能键并不提供“选择一个模板文件”的功能。所以，在VS Code新建文件时，我需要手动输入文件名称以及文件后缀名。一个新文件被创建之后，默认是空的内容，而常常呢，我们希望创建完文件之后，文件可以包含一些内容，比如当前文件创建的日期、作者姓名等信息，面对这种情况，我们可以利用 User Snippets来创建属于自己的代码片段，新建文件后，这样就可以快速生成一些默认内容。

第三个特点是：**VS Code不会对文件及文件夹的显示做重构**。当VS Code去加载一个项目时，它不会对项目里的文件及文件夹做重构显示，所以文件及文件夹在磁盘上看上去是什么样，那在VS Code中显示就是什么样。但是需要注意的是，VS Code的Settings里的Exclude选项里的一些配置，会使得VS Code隐藏项目下的一些特殊文件或文件夹，比如用于git的".git"文件夹就不会显示在VS Code中。

#### 42 管理文件及文件夹

这一节课，我们将学习如何在VS Code中对文件或文件夹进行增、删、改、查等常见操作。

新增文件或文件夹，第一种方式，我们可以使用项目名称右侧的“新增功能键”；第二种方式是使用上下文菜单中等“New File”和“New Folder”；第三种方式是使用复制粘贴来快速生成一个文件或文件夹。

删除文件或文件夹，可以使用上下文菜单中的“Delete”选项，或者使用快捷键，Mac是“Cmd + Delete”；Win是“Delete”。

对文件或文件夹重命名，可以使用上下文菜单中“Rename”选项，或者使用快捷键，Mac是“Enter”；Win是“F2”。

对文件或文件夹按名称进行搜索，我们可以先将鼠标在文件列表的空白处做一次点击，当四周出现一个蓝色当框时，我们就可以在键盘上输入搜索词，VS Code会高亮搜索结果。

另外，上下文菜单中还有几个比较常用的选项，第一个是将文件或文件夹在磁盘中进行打开，这个选项在Mac上叫“Reveal in Finder”，在Win上叫“Reveal in File Explorer”，在Linux上叫“Open Containing Folder”；第二个常用选项是“Open in Integrated Terminal”，使用它，我们可以快速打开Terminal且Terminal的当前工作目录为该文件所在目录；第三个常用选项是“Copy Path”用于获取文件或文件夹的绝对路径；第四个常用选项是“Copy Relative Path”用于获取文件或文件夹的相对路径。

#### 43 Dirty Write

当我们在VS Code对某个文件进行修改并保存时，可能会出现文件无法保存的现象，这种现场发生的原因常常是因为触发了Dirty Write，这一节课，我们就来详细了解一下Dirty Write。

Dirty Write的发生是因为经历了如下三个步骤：

第一步：我们在VS Code中对某个文件进行了编辑，且文件尚未保存。

第二步：除VS Code之外的其它进程对这个文件进行了修改并将修改保存到了磁盘中。

第三步：我们在VS Code中对这个文件做保存操作。

由于上面的第二步（别人的版本）和第三步（我们的版本），会对同一个文件的内容产生了两个不同版本，所以就会导致文件在保存时发生错误，这种错误就叫做“Dirty Write”。

为了解决Dirty Write，让文件能够顺利保存，VS Code提供了两个选项，一个叫做“Override”，一个叫做“Compare”，Override选项会直接使用我们的版本，别人的版本会被移除，而选择“Compare”时，VS Code会打开差异视图，来让我们选择到底使用哪个版本，在选择的时候，如果最终版本的内容，在两方中都有，我们还需要先做merge操作，再来选择使用哪个版本。

在实际的工作中，编程语言的包管理工具的配置文件常常会发生dirty write现象，在使用的时候，我们需要注意下：对包管理工具的配置文件进行修改后，要及时进行保存，以免触发Dirty Write。

#### 44 Preview Mode

当我们在VS Code中打开一个文件的时候，VS Code默认会以Preview mode的方式对文件进行显示，这会导致新打开的文件并不会独自占用一个Tab，有时候这并不是我们希望的结果。

当一个文件处于Preview mode的时候，VS Code会在文件的Tab区域对文件名采用斜体进行暗示，如果不是Preview mode，那么字体就不会是斜体而是正常的进行显示。为了能够让新开的文件独自占用一个Tab，我们就需要首先取消当前文件的Preview mode，取消方式有三种，分别是：**双击当前文件名**、**双击当前文件的Tab**和**对当前文件进行编辑**。

#### 45 文件使用技巧1: 寻找文件的三种方式

一个真实的项目通常包含很多源代码文件，在项目开发过程中，能否从这么多文件中快速找到自己想要的文件将是非常重要。这一节课，我们就来学习一下在VS Code中寻找文件的三种方式以及它们的具体使用场景。

**使用场景一： 知道文件名**

当我们知道要找文件的名称时，我们可以使用VS Code提供一个快捷键叫做`Quick Open`，这个快捷键在Windows上`Ctrl+P`，在macOS上`Cmd+P`。这个快捷键是寻找文件最方便的方式，平时用的也最多，我们应该牢记这个快捷键。

**使用场景二： 不记得文件名，但是记得文件里包含一定的内容且该文件处于某个文件夹下**

当我们不记得文件名时，我们就不能用第一种方法了。软件项目的源代码通常会根据功能或者模块需求被分配到不同的文件夹下，此时如果我们记得要找文件里包含一定的内容，且该文件处于某个特定的文件夹下，我们可以将鼠标移动到该文件夹上方，鼠标右键打开上下文菜单，并选择`Find in Folder`，这样VS Code会打开Search功能且这时候Search功能的搜索范围会被自动限定到刚刚选择的文件夹上，这时候，因为搜索范围被缩小，搜索结果将会变少，这有助于我们更快的找到想要的文件。

**使用场景三： 不记得文件名，不记得文件内容，但记得它有个“邻居”**

不记得文件名，也不记得文件内容，我们就不能用前两种方法了，这时候如果我们记得要找的文件有个“邻居”（这里的邻居，指的是两个文件处于同一目录或相近目录），我们就可以通过找邻居的方式找到想要的文件。这样做，其实是利用了VS Code`打开一个文件的同时，该文件在Explorer中所在的目录会被自动展开`的特性。这样，通过先找邻居，就可以帮助我们间接的找到想要的文件。

#### 46 文件使用技巧2: 文件快速导航

这一节课，我们将学习和文件导航的相关技巧，学习了这些技巧后，我们就可以在多个已打开文件之间做快速切换，以及我们可以在单个文件内快速回到上个编辑点。

**多个文件之间**

在项目开发过程中，我们经常会打开多个文件，随着已打开文件的不断增多，我们就需要一种方法能够在这些文件之间做快速切换。

在VS Code中，做文件切换最方便的方式是使用快捷键<kbd>Ctrl</kbd>+<kbd>Tab</kbd>，它的具体使用方法是：

1. 按住<kbd>Ctrl</kbd>+<kbd>Tab</kbd>
2. 不松<kbd>Ctrl</kbd>，依靠单击<kbd>Tab</kbd>选择文件
3. 释放<kbd>Ctrl</kbd>打开被选文件。

**单个文件内部**

文件内的每一次编辑都会产生一个编辑点，英文叫`Edit Location`，我们常常需要能够快速回到上个编辑点。

在VS Code中，做编辑点切换，我们可以使用快捷键

- Windows: <kbd>Alt</kbd>+<kbd>Left</kbd> 和 <kbd>Alt</kbd>+<kbd>Right</kbd>
- macOS: <kbd>Ctrl</kbd>+<kbd>-</kbd>(`-`是键盘上的减号键)

#### 47 文件使用技巧3: Pin Tab

在使用VS Code过程中，随着时间推移，我们会打开越来越多的文件，在这么多已打开文件当中，我们可以将一些我们认为重要的文件的Tab设定为Pin（固定），被Pin的Tab，会带来很多好处，这一节课我们就来学习下这里面的使用技巧。

Pin Tab这个选项有三种设置，我个人推荐使用`compact`而不是默认的`normal`，相应的设定方法是

1. 打开`Settings`
2. 输入关键词`pin tab`进行搜索
3. 找到设置项`Pinned Tab Sizing`并选择`compact`设置项

使用Pin Tab，可以带来以下几点好处：

1. 被Pin的Tab总是会固定在Tab区域的开始，方便随时进行切换
2. 滚动Tab区域时，被Pin的Tab不会发生滚动，方便随时进行切换
3. 使用"Close All"时，被Pin的Tab不会被关闭，方便保留住重要的文件

#### 48 文件使用技巧4: 单个文件内的搜索和替换

在Activity Bar中，VS Code提供了Search这个工具来进行全局的搜索或替换，但在实际的工作中，你会发现，我们也经常需要能够在单个文件的内部进行搜索或替换。这一节课，我们就来学习下相关的使用技巧。

为了在单个文件的内使用搜索或替换功能，我需要使用快捷键：macOS是 <kbd>Cmd</kbd> + <kbd>F</kbd>；Windows是 <kbd>Ctrl</kbd> + <kbd>F</kbd>。之后我们就能看到文件顶部浮现出的搜索以及替换输入框了。这里面的使用方法和我们之前在第10节课中学习到的内容几乎一样。在这一节课，我想着重复习下搜索输入框右侧的两个功能: `Aa`和`Ab|`，灵活的使用它们，可以更好的缩小搜索范围，帮助我们更精确的找到想要的值或者进行更精确的文本替换。它们俩的具体用法如下：

- `Aa`: 代表是否开启**大小写匹配**功能，一旦开启这个功能，文本的匹配就变得大小写敏感了（VS Code默认使用的是大小写不敏感）。
- `Ab|`: 代表是否开启**全单词匹配**功能，一旦开启这个功能，文本的匹配必须作用于一个完整的单词，比如文件中有个单词叫`username`, 如果这时候我们搜索`user`，那么，这时候我们是搜不到结果的，因为文件里只有一个叫`username`的单词，而没有一个叫`user`的单词。

我自己的体会是，在工作过程中，这个两个工具的使用常常会带来出其不意的效果，特别是在单个文件内容很长的情况下。推荐你多多使用！

#### 49 文件使用技巧5: 文件的自动保存与自动格式化

VS Code支持文件的自动保存与自动格式化功能，这一节课，我们就来学习下相关的使用技巧。

**自动保存** 功能设置方法如下：

1. 打开Settings
2. 搜索`auto save`
3. 找到`Files: Auto Save`选项并进行设置

**自动格式化** 功能设置方法如下：

1. 打开Settings
2. 搜索`format`
3. 找到`Editor: Format On Save`选项并进行设置

对于自动保存功能，我个人推荐不使用自动保存功能，养成手动保存的好习惯；对于自动格式化功能，需要提醒的是，VS Code默认只支持部分文件类型的格式化，比如：HTML，CSS，JS，JSON等，为了支持其它文件类型的格式化，需要安装相应的扩展。

#### 50 文件使用技巧6: 文件比较

在工作或者学习的过程中，我们有时候需要对两个文件进行比较，以此来查看它们在内容上的不同之处。利用VS Code，我们可以很容易实现这个功能。

为了对两个文件进行比较，我们可以这样做：

1. 鼠标点击第一个文件名
2. 按住<kbd>Shift</kbd>键，鼠标单击另一个文件的文件名
3. 鼠标右键，选择“Compare Selected”

这样，VS Code就会打开差异视图，高亮这两个文件在内容上的不同之处。

#### 51 文件使用技巧7: Timeline

在VS Code的Explorer中，新版的VS Code新增了一个叫做“Timeline”的功能，通过这个功能，我们可以很方便的查看每一个源代码文件在Git中的提交记录。

如果我们的项目是使用Git管理的，那么，当我们打开某一个源代码文件，然后展开Timeline，就可以看到这个文件的Git提交记录列表，列表按照提交时间由近及远自上而下排列，每一列分别标注有commit message，提交人，提交日期等信息。单击这一列，VS Code会打开差异视图，高亮这次提交所修改的地方。

#### 52 文件使用技巧8: 快速创建文件或文件夹

VS Code中创建文件或文件夹有多种方式，当我们希望一次连续创建多个文件夹，或者是希望创建某个文件的同时附带创建文件所属的文件夹，我们可以使用`/`字符来快速完成这种操作。

具体的操作方法是：在Explorer中点击项目名右侧的`New File`或者`New Folder`时，在弹出的输入框中，借助`/`就可以完成这样的任务。


#### 53 文件使用技巧9: 快速撤销修改

VS Code内建了一个命令叫做“Revert File”，使用它，我们可以快速撤销对某个文件的修改。

需要注意的是，撤销的范围是：从当前点到上一次保存点之间的所有修改。

#### 54 文件使用技巧10: 配置项-File Associations

通过修改配置项中的"File Associations"，我们可以自定义文件关联，将某种文件关联到某个VS Code支持的文件类型中，以便支持语法高亮，格式化等功能。

首先我需要在VS Code的Settings里通过输入关键词"File Associations"，找到这个配置项，然后点击“Add Item”，这时候会出现key，value输入框，关于key，有两种输入模式：

1. 输入文件后缀名，例如，在key的地方输入“*.styl”，在value的地方输入“css”，styl后缀名的文件就会被关联到css文件类型。
2. 输入文件名，例如，在key的地方输入“README”，在value的地方输入“markdown”，我们就可以将一个名为“README”的文件关联到markdown文件类型。

#### 55 文件使用技巧11: 查看源文件的健康状况

我们在编写代码的时候，VS Code会在后台时刻分析我们的源文件，当它发现我们的代码有问题的时候，VS Code会从多个方面来提醒我们。

具体来说，VS Code会从在几个方面做出提醒：

1. Problems Panel： 这里会列出项目中所有的Problems，以及每一个Problem所在的源文件及行号。
2. Status bar左侧：这里会分别列出项目Problems中Error和Warning的个数。
3. Minimap：当一个源文件某一行出现Error时，minimap中会以红色来提醒，当出现Warning时，会以黄色来提醒。
4. 文件名右侧显示的数字：如果一个源文件有多个error，那么数字就代表error的个数并以红色字体来显示，warning也类似。

#### 56 文件使用技巧12: 文件的拖入与拖出

VS Code在打开的状态下，支持对单个文件的拖入与拖出，当我们想要将某个文件复制到VS Code中，或者从VS Code中将某个文件复制到别的地方，这种方式将显得非常简单。

对于文件的拖入，有两种不同的效果：第一，如果我们是将某个文件拖入Editor区域，那么仅仅是在VS Code中打开这个文件；第二，如果我们是将这个文件拖入Explorer的文件列表区域，那么这个文件将会被复制到VS Code中。

对于文件的拖出，我们可以在文件列表中选择某个文件，或者是在Editor的Tab区域选择某个文件，然后将这个文件拖入其它的地方，比如桌面，那么一旦释放鼠标，这个文件就会被复制一份到指定的地方。

#### 57 文件使用技巧13: 文件内容的自由缩放

VS Code的Editor的区域支持文件内容的自由缩放，我们可以利用这个功能，快速调整代码的字体大小。

为了开启这个功能，我们需要配置一个设置项，在Setting里搜索“mouse wheel zoom”，找到这一项并将它打为勾，这样我们就开启了这个功能。

使用的时候，我们首先需要打开项目里的某个文件，将鼠标定位到其中某一行，按住Ctrl键同时滚动鼠标滚轮，这时候就能看到文件的内容被自由的缩放了。
如果你没有使用鼠标而是在使用触控板，那么只需要使用缩放手势（大部分触控板使用两个手指做开合的动作）就可以完成同样的操作。

#### 58 文件使用技巧14: 配置项-Compact Folders

如果一个文件夹下面只有一个文件夹，这时候VS Code默认采用横向的方式在文件列表中显示这个文件夹，有时候我们可能希望改变这种显示方式，采用一般的竖向显示。

为了改变这种默认的显示方式，我们可以在Settings里面搜索“Compact Folders”，找到配置项“Explorer：Compact Folders”，将默认的勾取消掉即可。

#### 59 文件使用技巧15: Screencast Mode

VS Code里有一个特殊的功能叫做“Screencast Mode”，一旦我们将它开启，当我们的鼠标在源文件中移动时，VS Code会以一个红色的圆圈来提醒，当我们在键盘上输入任何一个字符时，它也会在屏幕中即时显示出当前按键字符。当我们参加一个代码review会议或者是制作一些代码编辑技巧的视频教程时，这个功能将会显得格外有用，它可以让观众更好的接受我们想要表达的信息。

为了开启这个功能，首先我们需要打开“Command Palette”，接着在输入框中输入“screencast mode”，找到命令“Toggle Screencast Mode”然后执行，这样我们就开启了这个功能。为了关闭这个功能，我们只需要将这条命令再执行一遍就可以了。

#### 60 文件使用技巧16: Save All

有时候我们想一次性保存所有的文件，为此，VS Code提供了多种实现方式。

- 方式一：通过菜单栏选项。File -> Save All。
- 方式二：通过快捷键。macOS是“Option + Mac + S”， Windows是“Ctrl + Shift + S”。
- 方式三：通过命令。打开Command Palette，输入“saveall”，找到命令“Save All”。

#### 61 文件使用技巧17: 在Source Control中打开文件

在Source Control中，当我们点击某个文件，VS Code这时会打开差异视图，我们在对文件内容做对比的时候，如果发现需要对文件做继续修改，这时我们可以利用Source Control的“Open File”功能。

“Open File”这个功能键存在于两个地方，一个是顶部右上角第一个图标，还有一个是在文件名右侧第一个图标，点击它，我们就可以快速将这个文件打开。

#### 62 文件使用技巧18: 在Source Control中调整文件的排序规则

Source Control中的文件显示顺序可以被调整，在修改文件过多的情况下，通过调整显示顺序，有时候会帮助我们更好的查看被修改的文件。

调整的方法是，在Source Control中点击右上角的三个点，之后点击“View & Sort”，就可以看到三个排序选项：

- Sort by Name: 按照文件名进行排序，也就是a字母开头的文件名会在最前面，z字母开头的会在最后面。
- Sort by Path：按照文件路径进行排序，也就是位于相同文件夹的文件会排在一起。
- Sort by Status：按照Git状态进行排序，也就是相同的Git状态的文件会排在一起。

#### 63 文件使用技巧19: 配置项-Wrap tab

当我们在VS Code中打开很多文件时，编辑器顶部的tab区域会被很快占满，占满之后就会出现滚动条，我需要移动滚动条才能查看其它已打开的文件。VS Code中有个配置项，一旦我们将它打开，将会采用换行而非滚动条的方式对tab区域进行展示，如果你是在一个比较大屏幕的外接显示器上使用VS Code，推荐打开这个配置项。

为了打开这个配置项，我们需要在`Settings`里面搜索`wrap tab`找到`Editor: Wrap Tabs`这个选项，将它勾选即可。

#### 64 文件使用技巧20: 配置项-Files exclude

项目当中常常会存在一些我们在开发过程中无需关注的文件或文件夹，比如说包文件夹，构建产生的文件夹等等，这时，我们可以通过更改一个配置项将这些文件或文件夹通通隐藏，这样项目的文件列表就会显得更加干净整洁。

为了配置，我们需要在`Settings`里面搜索`files exclude`找到`Files: Exclude`这个选项，接着点击`Add Pattern`按钮新增一个隐藏配置项。

为了减少影响范围，建议在`Workspace`范围下修改这个配置项。

#### 65 文件使用技巧21: Open in editor

在VS Code中做搜索时，搜索结果会出现在sidebar中，我们可以通过点击sidebar列出的每一项来查看搜索结果详情。这是VS Code提供的默认方式，需要我们对每一个搜索结果项先手动点击再查看详情。除了这种方式，查看搜索结果时，VS Code还提供了另外一种较为简便的方式，叫做“Open in editor”。

在sidebar的搜索结果列表的最上方，我们可以看见一个按钮叫做“Open in editor”，点击它就可以将当前搜索结果在一个新的editor中显示，这时所有的搜索结果就会在这一个editor中显示，方便我们更快的查看所有的搜索结果。

#### 66 文件使用技巧22: Search editor context

在上一节课，我们学习了利用“Open in editor”就可以新打开一个editor，在这个editor中，VS Code会一次性显示所有的匹配项，这一节课，我们来进一步学习下这个editor顶部的几个功能项，它可以帮助我们快速调整匹配项的参考上下文。

有时候，为了判断匹配项是否真的是我们想要找的结果，我们需要利用匹配项周围的一些代码来协助我们做判断，VS Code默认会显示匹配项的上一行和下一行，如果我们希望VS Code能够提供更多的上下文，我们就可以利用顶部右侧倒数第二个选项，点击它或者直接输入数字就可以调整上下文了。

在有些情况下，我们可能不希望有匹配项上方或下方代码的干扰，我们就可以点击顶部最右侧的选项，这样就可以只显示匹配项这一行。

#### 67 文件使用技巧23: 保存Search Editor

在前面两节课中，我们学习了利用Search中的“Open in editor”选项，它可以打开一个新的Editor，在这个Editor中，可以一次性显示所有的匹配结果，这个Editor其实是有名字的叫做“Search Editor”。“Search Editor”有个非常特殊的功能，就是可以被单独保存，这一节课我们就来学习一下它的使用方法以及使用场景。

为了保存“Search Editor”，我们只需要按保存快捷键（Mac是cmd+s, Windows是ctrl+s），这样VS Code会提示我们新建一个“.code-search”后缀名的文件，这种后缀名的文件可以被VS Code直接打开。

在以下两种场景下，我们可以选择保存“Search Editor”：

1. 频繁的搜索相同的词。
2. 搜索词或搜索条件较为复杂。

#### 68 文件使用技巧24: 使用搜索历史记录

当我们在VS Code中做搜索时，VS Code其实会记录我们的每一次搜索词，因此当我们在做搜索的时候，如果想利用曾经输入过的搜索词，而不想再次手动输入一遍，我们就可以直接使用VS Code所记录下的搜索历史记录。

使用方法很简单，只需要在搜索输入框中按“向上箭头键”。

另外，类似的功能，VS Code的Source Control的Message输入框也支持。

#### 69 文件使用技巧25: 在Explorer中搜索文件

在VS Code中，当我们想要搜索某个文件的时候，在知道文件名的情况下，我们有多种方式可以实现，前面第45课我们有介绍一些方法，这一节课我们来学习另一种方法，它可以让我们直接在VS Code的Explorer中的文件列表中进行文件搜索，帮助我们从文件列表的众多文件中，过滤出那些自己想要的文件。

使用方法很简单，首先我们需要确保文件列表处于**激活状态**，这个**激活状态**我们有两种方法可以实现，一是随便点击文件列表中的某个文件，二是在文件列表的空白处单击一下。

处于**激活状态**下，我们就可以直接输入文件名的关键词，这时候就可以在Explorer的右上方看到自己输入的关键词，同时VS Code会将匹配到结果（文件或文件夹）进行高亮。

将鼠标hover在右上角的关键词上时，这时候会显示出两个功能键，右侧的“叉”，点击后用于清除此次搜索，而左侧的“三条横杠”，点击后会过滤出匹配到的结果，这个功能非常有用，当我们的文件过多的时候，匹配到的文件可能有多个且分布的比较散，即使VS Code对它们进行了高亮，我们也很难一次性看清所有的匹配结果，使用这个功能后，就可以让Explorer中只显示匹配结果，帮助我们快速找到想要的文件。

#### 70 文件使用技巧26: Find in selection

当我们在一个大文件中做搜索或替换时，可能会发现匹配结果有很多，而过多的匹配结果会有碍我们找到真正的匹配项。面对这种情况，如果我们确定想要搜索或替换的内容存在某一片代码区域，我们就可以利用“Find in selection”选项来缩小匹配范围，帮助我们更快的找到想要的匹配项，这一节课我们就来看下如何使用这个功能。

使用方法很简单：

1. 打开单个文件搜索功能（Win：Ctrl+F；Mac：Cmd+F）
2. 用鼠标选择一片想要搜索的区域
3. 单击搜索工具栏右数第二个功能键


### 第四章 自定义VS Code
### 第五章 代码编辑技巧
### 第六章 开发中的具体使用
### 第七章 通用扩展推荐
### 第八章 扩展的开发与发布
