工欲善其事，必先利其器！你好，我是[阿汤](https://github.com/tsq)，欢迎来到课程《VS Code入门教程2020》！在这门课程中，我将与你分享VS Code这款代码编辑器的使用方法，希望能够为你的学习或者工作带来一定的帮助。

这门课程是我从2020年2月份开始，在[B站](https://space.bilibili.com/30677217/channel/detail?cid=105022)和[Youtube](https://www.youtube.com/playlist?list=PLNEp_Xli9W_lUQTtRYG7883bGah63UkNB)上投稿的一门学习VS Code的视频教程，而之所以创建你现在正在看的这篇文档，是因为在下方的[课程详情](#课程详情)部分，你可以看到，我将每一节课的内容也以文字版的形式做了简单的介绍。这样做，一是，你可以通过搜索关键词来快速找到自己感兴趣的话题(*搜索，你可以利用浏览器自带的搜索快捷键比如：mac是`command+f`；windows是`ctrl+f`*)；二是，我将视频中涉及到的一些重要链接、命令、代码等信息在这里进行了记录，方便你在学习过程中查看和复制；三是，在已发布的视频当中，会有一些知识点的遗漏，对于遗漏的部分，我会在这里通过文字进行补充。

在阅读这篇文档的过程中，如果你发现了一些错误，欢迎你在Github上提出[pr](https://github.com/tsq/vscode-course/pulls)或者[issue](https://github.com/tsq/vscode-course/issues)。

**截止到目前，整个课程还没有制作完成，不过我会加油的！**

## 课程详情

整个课程被分成了八个章节：

**第一章**至**第五章**是VS Code基础知识的学习，这些基础知识与具体的编程语言无关但却十分重要，建议你**先依次完成一到五章的学习**，打好基础。

有了前面的知识，在**第六章**我们会结合具体的编程语言来学习这门编程语言在VS Code中的使用方式，比如，这门编程语言与VS Code结合时该如何搭建开发环境，以及这门编程语言在VS Code中又是如何做调试的等等。因为我会介绍很多门编程语言，所以你可以只挑选自己感兴趣的部分进行学习。

在**第七章**里我会推荐一些好用的扩展，这些扩展以工具的形式集成在VS Code当中。通过这些扩展，我们可以实现一些特殊的功能，比如说远程开发、远程协作等等。这些推荐的扩展，你也可以只选择自己喜欢的部分进行学习。

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

第二是**支持的编程语言非常多**，VS Code在初始状态（*即不按装任何的扩展的情况*）下对Web前端开发、Node.js开发以及PHP等语言的开发都有很好的支持，至于其它的一些编程语言，比如说：Java、Python、Go、Ruby、C#、C/C++等等，只要安装相应的扩展就能很好的完成开发环境的搭建。

第三是**拥有丰富的扩展**，VS Code的扩展十分丰富，首先从**量**上来看，VS Code的扩展数量已经上万，涵盖了方方面面，你能想到的它都有，比如说你想使用Mysql的GUI工具，那么你可以直接下载一个叫`MySQL`的扩展，这样就可以在VS Code中一边写代码，一边完成数据库查询等工作，其次是你想不到的它也有，比如说一款名叫`daily-anime`的扩展，如果你是个动漫爱好者，用了它你就可以边上班边摸鱼了（*不鼓励摸鱼哈，还是安安心心写代码吧，哈哈*）。再一个就是从**质**上来看，VS Code很多重要的扩展都是由微软、谷歌等这样的大公司在维护，这些扩展的安装量有很多都超过百万甚至是千万，所以用起来十分的放心，也很少出错误。除了拥有非常丰富的扩展，VS Code的扩展还有另外两大优势，一是，我们在大陆地区也能够以很快的网速完成扩展的安装；二是，除了一些特殊的扩展，绝大多数扩展安装完就生效，不需要重启VS Code。

第四是**涵盖应用程序的整个生命周期**，一款代码编辑器一般只涵盖应用程序的开发阶段，而对于一些程序，比如说Web应用，常常还会有部署阶段。在VS Code中我们可以利用一些扩展，比如说微软公司提供的azure相关扩展，或者亚马逊公司提供的aws相关扩展，利用它们，我们就可以很方便的通过VS Code完成应用的一键部署，所以从开发到部署全程用VS Code这一个工具就够了！

接下来，我们来看两个可能会遇到的并且有点令人迷惑的英文词汇：`Visual Studio Code`和`Visual Studio`。其实VS Code的全称叫做 `Visual Studio Code`，作为微软于2015年推出的一款代码编辑器，他还有一位老大哥，叫做[Visual Studio](https://visualstudio.microsoft.com/)。所以，`Visual Studio Code`和`Visual Studio`是两款不同的代码编辑器。Visual Studio是微软很早很早以前(*查了下[wikipedia](https://en.wikipedia.org/wiki/Microsoft_Visual_Studio)，第一个版本发布于1997年*)就推出的一款功能强大的IDE，但他主要用于微软自家的一些技术开发，比如说.NET开发和最近比较火的.NET Core开发。VS Code作为一款新产品，在创建之初，就从他大哥身上借鉴了很多好的地方，比如说后面课程会学习的`workspace`概念，如果你用过Visual Studio，你会发现这和Visual Studio上的`solution`很类似，同时VS Code也摒弃了他大哥身上一些不太好的地方，最大改善就是让整个软件变得更加轻量。VS Code安装过后大概占用不到300M的硬盘空间，而Visual Studio呢？哈哈，没有个两三个G你是搞不定他的！我记得在读大学的时候，那时候还在用Visual Studio 2008，为了卸载Visual Studio，我每次都是转而选择重装系统！

除了有老大哥Visual Studio，VS Code他还有一位双胞胎兄弟，叫做`Insiders Edition`，他的下载地址是：[https://code.visualstudio.com/insiders/](https://code.visualstudio.com/insiders/)。他俩无论是相貌还是才能，几乎都一模一样，但是，微软会将一些新的bug修复或者一些新的功能更新，首先发布到`Insiders Edition`，等相应的功能稳定过后，才会将这部分更新发布到VS Code当中。如果你喜欢尝鲜的话，对于平时个人编程学习或者是开发自己的一些小项目，不妨试着用一用`Insiders Edition`。我自己就一直都在用`Insiders Edition`，给我的整体感受是：他俩在使用的是时候，基本上没什么区别。不过最近自己突然发现，`Insiders Edition`推出了[设置同步](https://code.visualstudio.com/docs/editor/settings-sync)功能（*界面左下角，包含人物图标的那个按钮就是*），我们可以使用自己的微软账户或者Github账户在`Insiders Edition`上进行登录，登录过后，我们安装的一些插件，设置过的一些偏好等信息都能够被同步到云端，如果我们以后换了台电脑，只要在新电脑上安装`Insiders Edition`并登录账户，云端保存的信息就会同步到本地，之前的设置就都恢复了。而这个设置同步功能，目前在VS Code中还没有，不过我估计很快就会有的。最后，为了从外貌上区分这对双胞胎，最简单的方法就是看他们的logo图标，`Insiders Edition`的是<span style="padding: 2px 8px;color: #fff;background-color: #20baa0;">绿色的</span>，而VS Code是<span style="padding: 2px 8px;color: #fff;background-color: #0066B8;">蓝色的</span>。


#### 04 在macOS上安装VS Code

视频链接：| [B站](https://www.bilibili.com/video/BV1a7411J75b) | [Youtube](https://youtu.be/8QOxxs6XJoM)

这一节课我们会学习如何在macOS上安装VS Code，其中会讲解一个可能会遇到的问题：安装完毕后，却无法打开VS Code。

为了在macOS上安装VS Code，我们首先前往官网首页：[https://code.visualstudio.com](https://code.visualstudio.com)进行安装包的下载，下载完毕后会是个zip文件，将解压后的文件直接拖入Applications里就可以完成安装。

但是我们在打开VS Code的时候可能会遇到无法打开的情况，这是因为你的macOS操作系统版本可能是Catalina，而Catalina在安全方面做了一些增强，对于从非Apple Store下载的应用可能就会遇到这种情况。为了解决这个问题，我们需要打开`System Preferences`，然后点击`Security & Privacy`，在里面就能解锁被阻止的VS Code了。

#### 05 在Windows上安装VS Code

视频链接：| [B站](https://www.bilibili.com/video/BV1u7411n7Cb) | [Youtube](https://youtu.be/QcNgBX1sAdc)

这一节课我们会学习如何在Windows上一步步安装VS Code。

在Windows上安装VS Code，我们首先前往官网首页：[https://code.visualstudio.com](https://code.visualstudio.com)进行安装包的下载，下载完毕后直接双击下载后的exe，在安装的第一步，我们首先选择“我接受协议”，之后全部点击“下一步”按钮直到安装完成。可以说，相较于Mac和Linux上的安装，Windows上的安装是最简单的了。

*P.S. 如果你仔细观察安装的过程，你会发现在安装时，默认勾选住了“添加到PATH”这个选项，正是因为有了这个选项，安装完毕后，我们就可以在cmd或者Powershell中直接使用`code`这个命令了。*


#### 06 在Linux上安装VS Code

视频链接：| [B站](https://www.bilibili.com/video/BV1r7411E7uC) | [Youtube](https://youtu.be/RsgPR8rcR_Q)

这一节课我们会学习如何在Linux上一步步安装VS Code，我会以Ubuntu发行版做演示。

为了在Linux上安装VS Code，我们首先前往官网首页：[https://code.visualstudio.com](https://code.visualstudio.com)进行安装包的下载。在Linux上使用浏览器访问VS Code官网时，我们会发现有两个下载按钮，一个是`deb`，一个是`rpm`，这是因为Linux有很多发行版，不同的发行版我们需要下载不同的安装包，对于Debian、Ubuntu我们需要下载deb安装包，而对于Red Hat、Fedora我们需要下载rpm安装包，因为这一节课我是使用Ubuntu来做演示，所以我下载的是deb。

下载完deb文件，接下来就是安装操作。为了安装VS Code，你可以直接双击deb文件，这样会自动弹出安装引导窗口，这种方式我自己试过几次，但有时会出现一些问题，所以在视频中我选择的是另外一种安装方法：采用Ubuntu自带的`dpkg`命令来完成安装。为了使用dpkg，我们首先打开`Terminal`，然后在`Terminal`中直接输入以下命令:

```shell
sudo dpkg -i [deb的路径]
```

对于`[deb的路径]`我们可以手动输入它在系统中的绝对路径，为了简单，我们也可以直接将deb文件拖入到`sudo dpkg -i `的后面。


#### 07 如何用VS Code打开一个项目

视频链接：| [B站](https://www.bilibili.com/video/BV1T741177ra) | [Youtube](https://youtu.be/THx4BsmPJ9U)

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
- [33 介绍User Snippets](#32-介绍user-snippets)

#### 08 用户界面概览

视频链接：| [B站](https://www.bilibili.com/video/BV167411L7SM) | [Youtube](https://youtu.be/Ys4mbfvk3M0)

这一节课，我们会对VS Code的用户界面做一个大致的概览。

VS Code的用户界面一共由五大部分组成，分别是：

1. 底部的Status Bar（状态栏），用于显示当前被打开文件的一些信息。
2. 最左侧的Activity Bar（活动栏），它里面包含了VS Code五个重要功能的入口点。
3. Activity Bar旁边的Side Bar（侧边栏），它里面包含了Activity Bar五个功能点的详细内容。
4. 右侧，占据空间最多的Editor（编辑器），用于编写代码。
5. 编辑器下方的Panels（面板），它包含了4个不同的面板，其中的Terminal面板我们会经常用到。



#### 09 资源管理器

视频链接：| [B站](https://www.bilibili.com/video/BV1E7411A7DZ) | [Youtube](https://youtu.be/q1ExNjkORAY)

从这一节课开始，我们将具体学习VS Code用户界面的每一块内容，首先我们将学习最左侧的Activity Bar。这一节课，我们会学习Activity Bar的第一个功能点：Explorer（资源管理器）。

**Explorer**它的功能主要是用于显示我们项目所包含的所有文件以及文件夹。在Side Bar中，我们可以看到，整个功能区被分成了三个部分，从上到下分别是：OPEN EDITORS、项目本身、OUTLINE。位于中间的项目本身，我们可以看到自己的项目名，以及项目里包含的文件及文件夹，如果我们将鼠标放在在项目名的右侧区域，我们可以看到四个功能键，它们分别用于在当前项目里新建一个文件、新建一个文件夹、刷新当前目录、折叠某个目录。

接着我们来看上方的OPEN EDITORS，在OPEN EDITORS里面，它以列表的形式列出了当前所有被打开的文件，这里面包含了一个非常好用的功能,我们可以将鼠标移动到OPEN EDITORS的右侧，这时会出现三个功能键，通过点击最右侧那个带有叉叉图标的按键，我们就可以**一键关闭所有当前被打开的文件**。在实际的项目开发过程中，随着时间推移，我们打开的文件经常是越来越多，这时候我们常常希望关闭所有被打开的文件，来让整个编辑器看起来更加清爽，而利用刚刚说的那个带有叉叉图标的按键，我们就可以很方便的完成这种操作。

最后，我们来看一下最下方的OUTLINE，OUTLINE我用自己的话总结它的作用就是：**换个角度看代码**。对于一份源代码，OUTLINE中列出的视图常常会以另外一个角度来看待，比如当前源代码是HTML，OUTLINE中视图就会以DOM树的角度来看待，再比如当前源代码是面向对象编程语言，它就会从类、类的成员变量、类的成员函数等角度来看待。那，这种从不同角度来看待源代码会带来什么好处呢？好处有两点：第一，当代码过长时，通过OUTLINE中列出的视图信息，我们可以**很容易理解代码的组织结构**；第二，当代码过长时，通过点击OUTLINE视图中的选项，我们可以**很容易跳转到指定的代码块**。


#### 10 搜索工具

视频链接：| [B站](https://www.bilibili.com/video/BV1K7411w7VE) | [Youtube](https://youtu.be/ahOPXnVEyNA)

这一节课，我们会学习Activity Bar的第二个功能点，用于搜索和替换的：Search。

点击Search，我们可以在Side Bar顶部看到两个输入框，第一个输入框是用于文本的搜索，而第二个输入框则用于文本的替换。相较于替换，我感觉在平时的工作中使用“搜索”会更多些。通过搜索，我们可以很方便的找到某个单词或者某个句子在整个项目中出现过的地方，通过查看搜索词在其它文件中是如何被使用，如果是跟踪一个bug，那么就能通过这种方式来快速追踪bug的来源，而如果我们是刚接手一个项目，就很有可能对其中的一些函数、类或者组件的用法不太熟悉，那么就能通过这种方式来找到这些函数、类或者组件出现过的地方，并参考它们是如何被写的。

搜索和替换的使用方法很简单，直接在输入框里输入相应的单词就可以，但是VS Code还针对搜索和替换提供了一些高级选项，通过这些高级选项，我们可以进一步缩小查询结果的范围，当遇到比较大的项目时，开启这些选项还是很有用的，可以帮助我节省查看搜索结果所花费的时间，在这一节课的视频中，你可以看到这些高级选项具体是如何工作的。

#### 11 源代码管理

视频链接：| [B站](https://www.bilibili.com/video/BV1A7411A7To) | [Youtube](https://youtu.be/XQVPHlAks-s)

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

视频链接：| [B站](https://www.bilibili.com/video/BV1xj411f7ur) | [Youtube](https://youtu.be/ybcoXlTrmmM)

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

视频链接：| [B站](https://www.bilibili.com/video/BV1x7411F7HV) | [Youtube](https://youtu.be/eft749KMZJM)

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

视频链接：| [B站](https://www.bilibili.com/video/BV1V7411u7iA) | [Youtube](https://youtu.be/GPCzDPVCQ6M)

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

视频链接：| [B站](https://www.bilibili.com/video/BV1f7411N7Dj) | [Youtube](https://youtu.be/bK7dr7eG6KM)

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

视频链接：| [B站](https://www.bilibili.com/video/BV1A7411T7VC) | [Youtube](https://youtu.be/okSG4I99XuY)

这一节课，我们将学习使用Source Control完成与远程仓库相关的Git操作。

与远程仓库相关的Git操作中，常用的有三个，它们分别是：

1. git clone：用于克隆一个远程仓库
2. git pull：用于拉取远程仓库的更新并将更新合并到本地分支，它等于git fetch 加 git merge
3. git push：将本地的修改提交到远程分支

在这一节课的视频中，你可以看到如何利用Git命令以及Source Control来完成上面三个操作。

#### 17 介绍调试工具

视频链接：| [B站](https://www.bilibili.com/video/BV1m7411N7aC/) | [Youtube](https://youtu.be/wpZ_jKxFLVw)

这一节课，我们会学习Activity Bar的第四个功能点：Debug。

Debug也就是调试，在软件项目开发过程中，调试扮演着非常重要的角色。当我们的程序遇到问题是，我们可以利用调试来快速定位问题发生的原因；当我们对一段代码逻辑不是很清楚时，我们也可以利用调试来帮助我们理解代码内部的逻辑，可以看到调试功能对我们开发人员来说是多么的重要，自然VS Code也少不了对调试功能的支持，而且支持度还不是一般的好，是非常的好！

VS Code中涉及调试的知识非常的多，我将这些知识分成了两类，一类叫“通用知识”，这些通用知识，无论我们使用VS Code来调试什么项目，它都可以用的上，甚至是即使我们不用VS Code转而使用其它编辑器，你会发现学到的这些知识在其它的编辑器中基本上也能适用。对于这部分通用知识，我会在这一章接下来的课程中一一进行介绍。还有一类，叫“和具体编程语言相关的调试知识”，我们知道，VS Code支持很多编程语言的调试，而不同的编程语言在调试时，需要使用不同的调试配置，对于这部分知识我会在后面第六章结合具体的编程语言进行逐一介绍。所以，接下来我们首先来学习VS Code中用于调试的“通用知识”。不过，为了学习调试的“通用知识”，我们还是必须要选择一门编程语言来写调试的演示项目，这里，我选择的编程语言是：**基于Node.js运行时的Javascript**，为了后面方便称呼，我将它简称为“Node.js”（*P.S. 需要注意的是：Node.js并不是一门编程语言，而是一个专门运行Javascript代码的运行时*），为什么会是它呢？回答这个问题之前，我们先来看一下，如果要想在VS Code进行调试，我们需要满足的三个条件：

1. **搭建相应编程语言的开发环境** ：比如说，我们想调试Java程序，那我们就必须先要在本地搭建好Java的开发环境，保证可以在命令行中调用`java`和`javac`命令。
2. **安装相应编程语言用于调试的扩展**：不同的编程语言在调试时，还需要借助专门的扩展。比如说，我们想调试PHP程序，那我们就必须要安装一个叫`PHP Debug`的扩展。
3. **配置launch.json**：`launch.json`是VS Code中专门用于调试的配置文件，只有将这个文件配好了，我们才能开启调试。

可以看到，如果我们想要在VS Code中学习调试，要准备的东西还是挺多的，不过，如果我们使用的是Node.js的话，我们可以省略其中的条件2和条件3，这是因为VS Code默认只支持Node.js调试（*P.S. 在第三课中，我们有提到VS Code的内部其实是嵌入了一个Chrome浏览器外加一个Node.js运行时，这或许就是VS Code和Node.js这么亲近的原因吧*）。所以，对于调试的“通用知识”学习，我将使用Node.js来做演示。

为了使用Node.js，我们就必须要先在本地搭建好Node.js的开发环境，所以在接下来的三节课，我将分别介绍如何在macOS、Windows以及Linux上搭建Node.js开发环境。

#### 18 在macOS上搭建Node.js开发环境

视频链接：| [B站](https://www.bilibili.com/video/BV1vE411H7wh) | [Youtube](https://youtu.be/vmii_pB44gs)

这一节课，我们将学习在macOS上搭建Node.js开发环境，为后面利用Node.js来学习调试的通用知识做好准备。

在macOS上搭建Node.js开发环境很简单，一共两步：

1. 下载Node.js安装包并安装：下载地址是：[https://nodejs.org](https://nodejs.org)
2. 校验安装是否成功：在Terminal中输入`node -v`

#### 19 在Windows上搭建Node.js开发环境

视频链接：| [B站](https://www.bilibili.com/video/BV1gE411n7Ej) | [Youtube](https://youtu.be/8azTl1KRZGg)

这一节课，我们将学习在Windows上搭建Node.js开发环境，为后面利用Node.js来学习调试的通用知识做好准备。

在Windows上搭建Node.js开发环境也很简单，一共两步：

1. 下载Node.js安装包并安装：下载地址是：[https://nodejs.org](https://nodejs.org)
2. 校验安装是否成功：在cmd中输入`node -v`

#### 20 在Linux上搭建Node.js开发环境

视频链接：| [B站](https://www.bilibili.com/video/BV1fE411E78d) | [Youtube](https://youtu.be/4Giit0CR9XE)

这一节课，我们将学习在Linux上搭建Node.js开发环境，为后面利用Node.js来学习调试的通用知识做好准备，我将使用Ubuntu桌面版做演示。

在Linux上搭建Node.js开发环境的方法有很多，我推荐如下方法：

1. 安装nvm：文档地址是：[http://nvm.sh](http://nvm.sh)
2. 安装Node.js：直接在Terminal中输入`nvm install 12.16.1`来安装指定版本的Node.js，这里我选择的版本是：12.16.1
3. 校验安装是否成功：在Terminal中输入`node -v`

#### 21 调试界面概览

视频链接：| [B站](https://www.bilibili.com/video/BV18E41147NM) | [Youtube](https://youtu.be/2Q_FeLtgXcI)

这一节课，我们将对VS Code的调试界面做一个大致的概览。

VS Code的调试界面，我将它分成了四个部分，分别是：

1. 位于顶部的Debug toolbar，在调试时，用它来控制程序的执行流程
2. 位于行号左侧的Breakpoint，也就是断点。为了做调试，我们至少需要打上一个断点
3. 位于底部的Debug console panel，它有两个功能，一是可以输出调试日志，二是可以利用当前函数的本地变量输出表达式的值
4. 位于Side Bar中的Debug sidebar，它由多个部分组成，用于显示本地变量、计算表达式、显示函数调用栈、断点管理等功能

#### 22 Debug sidebar的使用方式

视频链接：| [B站](https://www.bilibili.com/video/BV1HE411x7gi) | [Youtube](https://youtu.be/prO6u1AUHDo)

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

视频链接：| [B站](https://www.bilibili.com/video/BV1nA411b7QA) | [Youtube](https://youtu.be/0peiVKd37wI)

这一节课，我们会学习Debug toolbar的使用方式，它里面包含里用于控制程序执行流程的六个小工具。

首先我想强调的是：学会使用Debug Toolbar**非常的重要**，它将直接关系到我们能否顺利完成调试任务，所以建议你一定要牢牢掌握这一节课的内容。

当我们在调试时，我们就必须要借助Debug Toolbar上的六个工具，来控制程序的执行流程，这六个工具从左到右分别叫做：continue、step over、step into、step out、restart、stop。

**continue**，它的作用是**立即跳到下个断点**，如果后面没有断点了，那么程序就会运行到最后一行代码，在Web后端开发中，为了调试一个请求处理函数，我们常常会利用continue来释放被阻塞的请求。

**stop**，它的作用很简单，用于**立即中断调试**，当我们想要放弃调试时，就可以使用它。

**restart**，它的作用也很简单，用于**立即重启调试**，当我们在调试过程中修改了源代码，为了让修改生效，我们就可以使用它来重启调试。

接下来，是有点让人迷惑的**step over**和**step into**了，之所以让人迷惑，是因为他俩既有相似点也有不同点，关键在于**当前行是否存在函数调用**，如果存在，那他俩的作用一样：都是**单步执行**，如果不存在，**step over**会直接拿到函数的返回结果并运行至下一行，而**step into**则会进入当前行函数并运行至该函数的第一行。所以，如果当前行存在函数调用，选择**step over**还是**step into**，就要看我们对这个函数内部实现细节感不感兴趣了，感兴趣的话就用**step into**，不感兴趣的话就用**step over**。

最后一个是**step out**，它和**step into**刚好相反，**step into**是跳入函数，而**step out**则是跳出函数。它的使用场景常常是：当我们身处某个函数内部，同时这个函数的代码行数又很多，我们可能利用单步调试，运行了前面几行代码过后，就达到了自己的调试目的，这时候为了避免再单步执行后面大段我们不感兴趣的代码，我就可以使用它来快速跳出当前函数，节省时间。

#### 24 介绍launch.json

视频链接：| [B站](https://www.bilibili.com/video/BV1Jf4y1S7Bw) | [Youtube](https://youtu.be/4Jqnf-E9VSY)

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

视频链接：| [B站](https://www.bilibili.com/video/BV1Wi4y1t7VQ) | [Youtube](https://youtu.be/Fv_0UDflXbk)

这一节课，我们会学习**搜索本地变量**这个调试小技巧，利用它我们可以从大量的信息中快速寻找到自己想要的结果。

在调试过程中，VARIABLES里会显示当前函数的所有本地变量，有些情况下，这些本地变量的数量会非常对多，这种情况下，为了从中快速找到自己想要的值，我们就可以将光标定位到VARIABLES区域，然后直接输入搜索关键词，这样VS Code会自动定位到符合搜索词的变量并高亮其内容。在这一节课的视频中，我们将学习它的具体使用用法。

#### 26 调试技巧2 logpoints

视频链接：| [B站](https://www.bilibili.com/video/BV1wz411z7Z7) | [Youtube](https://youtu.be/gBpl4-1VsYU)

这一节课，我们会学习一种特殊的断点：**logpoints**，使用它我们可以以非阻塞、打日志的方式来调试程序

对于一个处于生产环境的Web项目，如果我们想要对其进行调试，为了**降低普通断点造成请求被阻塞的风险**，我们就可以使用logpoints断点，它以非阻塞、打日志的方式来调试程序。在这一节课的视频中，我们将学习它的具体使用用法。

#### 27 调试技巧3 conditional breakpoint

视频链接：| [B站](https://www.bilibili.com/video/BV11k4y1r7zY) | [Youtube](https://youtu.be/nyv7_cVTn0M)

这一节课，我们会学习一种特殊的断点：**conditional breakpoint**，使用它我们可以为一个断点添加条件判断语句，条件判断语句返回真时，断点才会生效。在这一节课的视频中，我们将学习它的具体使用用法。

在上一节课我们有提到，对于一个处于生产环境的Web项目，如果我们想要对其进行调试，我们可以使用logpoints断点。虽然logpoints断点不会阻塞程序的运行，但它毕竟只是通过输出日志的方式进行调试，对于一些复杂的场景，这种做法的效率就会比较低。为了更快的利用调试来定位问题，使用普通断点是最好的方式，所以，对于这种**既想要使用普通断点又不想要请求被阻塞**的情况，我们就可以使用conditional breakpoint，使用它之后，我们可以为一个普通断点加上一个条件，只有当条件满足时，断点才会生效，通过这种方式来最小化调试带来的请求阻塞风险。

#### 28 调试技巧4 inline breakpoint

视频链接：| [B站](https://www.bilibili.com/video/BV1MV411d76P) | [Youtube](https://youtu.be/neg3Qv71tQA)

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

视频链接：| [B站](https://www.bilibili.com/video/BV1ke411s7A8) | [Youtube](https://youtu.be/m5eoYbE2jPI)

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

视频链接：| [B站](https://www.bilibili.com/video/BV1PQ4y1P795) | [Youtube](https://youtu.be/MWjDx_bFsAI)

这一节课，我们会学习Activity Bar的第五个功能点，用于管理扩展的：Extensions。

首先，对于这一块内容，有些人喜欢把它称为“插件”，有些人则喜欢把它称为“扩展”，在这门课程中，我会把它称作“扩展”。

VS Code的扩展非常的丰富，我将它大致分成了以下三类：

- **写代码相关**： 这一类的扩展最多，比如格式化代码的 "Prettier"、调试PHP代码的 "PHP Debug"等
- **工具**：这些扩展以工具的形式集成在了VS Code当中，比如用于远程开发的 "Remote SSH"
- **自定义相关**：比如用于更换主题、语言包、快捷键的扩展

接着，我们来看一下Extensions的具体用法。Extensions这个工具主要用于扩展的管理，而扩展的管理常用的操作有：扩展的搜索、安装、禁用、删除等。在这一节课的视频中，我将以`DotENV`这个扩展为例，演示这些操作。


#### 31 介绍Command Palette

视频链接：| [B站](https://www.bilibili.com/video/BV1Dt4y1C7x1) | [Youtube](https://youtu.be/tkmHvPAK6Ik)

Activity Bar的底部有一个按钮，名叫：Manager，Manager里面包含了一些VS Code的功能选项，其中有三个我认为比较重要，分别是Command Palette、Settings、User Snippets。这一节课，我们会先学习：Command Palette。

因为Command Palette会被经常使用，所以我们需要记住打开它的快捷键。这个快捷键，在Mac上是：` shift + ⌘ + p`，在Windows上是：`shift + ctrl + p`。

接着，我们来了解下它的作用，它的作用是：**通过命令来执行一些操作**。VS Code中的一些操作，可以有多种方式来实现，以放大VS Code界面为例，我们可以通过菜单栏选项，也可以通过快捷键，还有就是通过Command Palette了。我们可以打开Command Palette，然后直接输入`zi`就能找到放大VS Code的命令。但是需要注意的是：有一些操作，我们只能通过Command Palette来实现，比如说更改VS Code语言包。正因为有些重要的操作只能在Command Palette里实现，所以它非常的重要。这一节课的视频中，你将看到它的具体使用方法。

#### 32 介绍Settings

视频链接：| [B站](https://www.bilibili.com/video/BV1fv411z7V1/) | [Youtube](https://youtu.be/j2u-quDMWWk)

这一节课，我们会学习“Settings”这个功能选项，并理解其中的“User”和“Workspace”这两个重要的概念。

“Settings”也就是我们常说的“设置”，不过和普通的桌面软件不一样，VS Code的设置有两种，一种是“User”范围下的设置，还有一种是“Workspace”范围下的设置。

对于User设置，一旦我们对其中的设置项进行了修改，那么这些修改会作用于**所有的项目**，而Workspace设置却不一样，在它里面的修改只能作用于**当前这一个项目**。在实际的使用过程中，我们会通过修改User设置，来满足我们的一些个性化的使用需求，而通过修改Workspace设置，在团队协作时，就可以实现代码风格的统一。

User设置和Workspace设置，其实它们的背后都有一个叫做“Settings.json”的配置文件，VS Code设置中出现的界面，其实就是对这份配置文件的可视化展现。利用它，我们不仅可以快速**将某个设置项快速恢复到默认值**，而且我们也可以通过直接编辑这个文件，**快速修改设置项**。

Tip: 所有设置项的默认值，如果使用settings.json来表示，可以参考下面的官方文档：

[https://code.visualstudio.com/docs/getstarted/settings#_default-settings](https://code.visualstudio.com/docs/getstarted/settings#_default-settings)

33 介绍User Snippets

视频链接：| [B站]() | [Youtube]()

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

### 第三章 文件及文件夹的使用
### 第四章 自定义VS Code
### 第五章 代码编辑技巧
### 第六章 开发中的具体使用
### 第七章 通用扩展推荐
### 第八章 扩展的开发与发布
