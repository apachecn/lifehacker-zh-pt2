# 如何在 Mac 上拍摄更漂亮的截图

> 原文：<https://lifehacker.com/how-to-take-prettier-screenshots-on-a-mac-1828009545>

如果你是一名 Mac 用户，剪下一段文字的图像以发送推文或保存租车确认页面的信息，标准的 **Command-Shift-4** 快捷键可以让你在想要捕捉的内容周围画一个框，这已经足够了。但是你的电脑比这聪明得多:有很多其他方法可以截图，这些方法同样简单，但最终产品会漂亮得多，当你想在演示文稿中包括你公司网页的专业外观图像时，它们会产生很大的影响。



### **捕捉带有边框和阴影的窗口**

要捕捉带有白色边框和灰色阴影的窗口，提供三维效果，请按下 **Command-Shift-4** ，然后按下空格键。当你的光标变成一个小照相机时，选择你想要捕捉的窗口。一旦它以蓝色突出显示，单击以捕捉图像。

* * *

### **捕捉一个没有边框或阴影的窗口**

如果你在遵循以上步骤后感到优柔寡断，那么你就没有*和*去忍受那个花哨的边框了。要捕捉没有边框和阴影的窗口内容，按下 **Command-Shift-4** ，然后按空格键，如上所述。一旦你选择的窗口有了蓝色调，按住**选项**键，然后点击一个干净的二维捕捉。

### **通过终端**永远禁用投影

如果你永远都不想用投影来抓图，你可以永久禁用这个功能。拉起终端，键入以下内容(代码感谢 [安德鲁·奥尔](https://www.macobserver.com/tips/quick-tip/disable-mojave-screenshot-shadows/) ):

`defaults write com.apple.screencapture disable-shadow -bool true`

按 Enter 键，然后键入下面的命令，再按一次 Enter 键:

`killall SystemUIServer`

要恢复原状，只需再次键入第一个命令，将最终的“true”更改为“false”，按 Enter 键，然后再次运行“killall”命令。

* * *

与所有 macOS 屏幕截图一样，如果您想要拷贝您的选择而不是将其存储为图像，请将控制键添加到混音中。例如， **Command-Control-Shift-4** 让你在屏幕上的一个区域周围画一个方框，并将你的选择复制到剪贴板，而不是转储到你的桌面。按住这些键，松开，按空格键来选择一个特定的窗口——并使用我们前面提到的步骤来添加(或删除)您认为合适的边框。

如果所有这些键盘操作让你腕管，你可以在 macOS Mojave 或更高版本中使用[**Command-Shift-5**](https://lifehacker.com/customize-your-mac-screenshots-with-these-hotkeys-1841481397)打开一个简单的界面，允许你选择你想要的截图。你将无法选择你的截图是否有漂亮的投影——至少，除非你在拍摄窗口截图时按住 Option 键来移除它——但你可以从许多其他选项中进行选择，从指定你的图像将保存在哪里，到为你的截图设置计时器，到包括或排除鼠标光标，等等。

* * *

*本文最初由 Melissa Kirsch 于 2018 年发表，由 David Murphy 于 2020 年 4 月 8 日更新。我们的更新包括以下内容:添加相关信息的附加链接，更改特色图片，修改文章的部分内容以澄清作者的原始信息，以及添加截图和调整 macOS 设置的最新建议。*