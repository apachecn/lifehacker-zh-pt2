# 如何提高 Android 手机游戏性能和电池寿命

> 原文:[https://life hacker . com/how-to-boost-mobile-game-performance-and-battery-life-o-1833499397](https://lifehacker.com/how-to-boost-mobile-game-performance-and-battery-life-o-1833499397)

随着手机游戏变得越来越复杂，图形变得越来越好，智能手机需要更高的硬件规格才能让这些游戏看起来更棒。无论你的智能手机是全新的还是有点老化，你都可以获得更高的帧速率。调整手机或平板电脑的显示设置，你将能够在游戏和图形密集型应用程序中获得更好的性能，甚至可能节省一些电池寿命。

Watch

有几种方法可以做到这一点。最简单的方法是从您设备的设置菜单 [中更改分辨率设置，但是，此选项仅在部分 Android 设备上可用，](https://lifehacker.com/how-to-increase-the-galaxy-s9s-screen-resolution-1823635301#_ga=2.26522878.2110051260.1552929225-1864099547.1536779123) ，它仅允许您切换到预定义的屏幕分辨率。对于某些应用或游戏，你的调整甚至无关紧要。

对于那些想要将分辨率或 DPI 设置降低到超出系统设置允许的程度的人，或者那些一开始就无法从手机设置中选择这样做的人，谷歌 Play 商店 中有许多 [应用程序可以让你立即改变屏幕分辨率，尽管这些应用程序需要你为手机设置根目录才能这样做。这样做的问题是，许多较新的游戏(离线或在线)无法在根设备上加载，这使得像*口袋妖怪 Go* 、*堡垒之夜*或 *PUBG Mobile* 这样的游戏玩家无法选择这一选项。](https://play.google.com/store/apps/details?id=com.cpuid.cpu_z)

幸运的是，还有第三个选项可以让你改变设备的显示分辨率，而不需要 root 访问。

### **如何在没有 root 用户的情况下更改 Android 设备的显示分辨率**

首先，你需要在你的电脑上下载并安装 Android Debug bridge，如果你还没有这样做的话，我们正好有的快速指南

安装完成后，你需要将手机置于开发者模式。开发者模式允许你在手机上改变更深层次的系统设置，但是我们需要做的就是启用 USB 调试。就这么简单。

1.  进入**设置>关于**，然后向下滚动，连续轻按 Build 号大约 7-10 次。当你启用开发模式时，你会收到一个通知。
2.  现在进入 S **设置>系统>高级>开发者选项**。向下滚动到**“调试”**，打开**“USB 调试”**

快速提醒:如果你这样做是为了提高*堡垒之夜*的性能，请确保在编辑你的显示设置后禁用 USB 调试和开发者模式，因为如果打开这些设置，*堡垒之夜*(和许多其他在线游戏)将阻止你进入比赛。要关闭开发者模式，进入**设置>系统>高级>开发者选项**，然后点击顶部的横幅禁用。

#### 连接您的手机并更改其显示设置。

1.  将手机的 USB 充电线插入电脑
2.  在你的电脑上运行命令行。对于 Windows，按下 **Windows 键+ R** ，然后键入**“cmd”**并按下**回车。**在 Mac 上，按 **Command 键+空格键**，然后搜索**终端。**对于 Linux 用户，按 **Ctrl+Alt+T.**
3.  在命令行中键入**“ADB shell dump sys display”**，按**回车**
4.  找到手机显示屏的 DPI 值( **wm 密度**)和分辨率( **wm 大小、**或**显示宽度和显示高度**)。记下这些数字，以便将来可以恢复到原始显示。
5.  您现在可以开始编辑分辨率和 DPI。这些将因电话而异。 [使用这个图表](http://viziblr.com/news/2013/9/10/chart-of-display-resolutions-by-aspect-ratio.html) 找到你的手机的原始分辨率，并从那里放大或缩小(如果你使用的是 1920x1080 分辨率的设备，降低到 1280x720 也很好)。改变 DPI 并不简单，但是对于大多数手机来说，原始的 DPI 值通常应该在 120 到 640 之间。找到一个可读的 DPI 可能需要一些尝试和错误，但是只要你坚持在 120 到 640 的范围内，你就会找到一个
6.  在命令行中输入**“WM density[new DPI value]”**，按**回车**更改 DPI，按**“WM size[new resolution value]”**更改分辨率。您应该会看到这在您的设备上自动发生。
7.  完成后，键入**“ADB reboot”**重新启动您的 Android 设备，并将其与您的 PC 安全断开。

我在我最初的谷歌 Pixel XL 上测试了 Pokemon Go 的上述步骤，因为调整一个人的显示设置是一种 [通常推荐的方式](https://www.reddit.com/r/pokemongodev/comments/6554k1/tutorial_set_your_android_phone_to_a_lower/) 来提高游戏社区中的游戏性能。在改变分辨率之前，我在游戏中的表现不错，但在健身房加载和战斗或浏览游戏菜单屏幕时，流畅度有了明显的改善。我没有测量任何帧速率差异，但感觉还是更好——这种差异可能在老款(功能较弱)手机上更明显。