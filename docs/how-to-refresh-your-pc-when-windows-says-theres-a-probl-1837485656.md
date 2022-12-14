# 当 Windows 说有问题时，如何“刷新”你的电脑

> 原文：<https://lifehacker.com/how-to-refresh-your-pc-when-windows-says-theres-a-probl-1837485656>

Windows 有积累数字灰尘和污垢的倾向，这可能会使系统陷入困境，重新安装操作系统 是解决任何问题的灵丹妙药。



较新版本的 Windows 包括一个方便的 [刷新选项](https://support.microsoft.com/en-us/help/17085/windows-8-restore-refresh-reset-pc) ，让你保留你的个人文件，但删除你的应用程序并重新安装 Windows。这使你免于更长时间的备份和恢复，并减少了你重新安装操作系统后重新配置设备的次数——它并不总是有效。

具有讽刺意味的是，许多迫使用户尝试 Windows 刷新的问题也会阻止它的工作。我最近在尝试例行刷新我的桌面时遇到了这种情况，而且我似乎并不孤单。恼人的错误信息“有一个问题，重置你的电脑，没有任何改变”似乎是常见的许多论坛和 Reddit 线程。

在经历了一些尝试性的和错误后，我终于找到了适合我的解决方案，但这就是问题所在:对于“重置您的电脑时出现问题”错误消息背后的无数原因，有多种解决方案，但没有一个是灵丹妙药。你可能需要尝试多种方法，直到找到合适的方法。为了帮助你完成这个过程，我在网上梳理了各种可行的解决方案，并把它们收集在这里，希望能帮你简化这个过程。

不过，在我们开始之前，我强烈建议您在尝试以下恢复选项之前，先备份重要文件。尽管 Windows 刷新可以保存你的一些个人文件，但明智的做法是将你的文件备份到其他地方，以防出现问题，你需要求助于删除所有内容并从头安装 Windows 的选择。

## 使用命令提示符修复 Windows 刷新

实际上有多种方法可以使用命令提示符来修复“重置您的电脑的问题”的错误。从第一个方法开始，向下移动，直到你找到一个有效的方法。

对于下面列出的每组命令，首先打开开始菜单，在搜索栏中键入“命令提示符”。**右击**命令提示符图标，选择**“以管理员身份运行”**命令提示符打开后，尝试以下命令:

#### **方法一:**

在命令提示符下，键入:

1.  `sfc /scannow`
2.  按 Enter 键运行扫描。等待它完成，然后关闭命令提示符。
3.  重新启动你的电脑，然后再次尝试刷新过程。如果成功了，太好了！如果没有，继续下一组命令。

#### **方法二:**

一次输入一个命令，每次输入后按 enter 键:

1.  `cd %windir%\system32\config`
2.  `ren system system.001`
3.  `ren software software.001`
4.  重新启动设备，然后尝试重置/刷新 Windows。如果不起作用，请尝试下一组命令:

#### **方法三:**

同样，一次使用一个命令:

1.  `reagentc/disable`
2.  `reagentc/enable`
3.  重新启动您的设备，然后再次尝试重置/刷新 Windows。如果它仍然不起作用，在转向其他解决方案之前，我们还有一组命令要尝试。

#### **方法四:**

*   类型`wmic logicaldisk get deviceid,volumename,description`
*   您将会看到您的电脑的各种驱动器的列表。输入 Windows 在您电脑上的安装盘符(如果您不知道，运行命令`dir [letter]` (例如，dir C，如果您有 c 盘)来查看该盘符的目录。你应该看到“窗口”列在其中之一；将驱动器用于下一个命令)。
*   `sfc /scannow /offbootdir=[letter]:\ /offwindir=[letter]:\Windows`(例如:sfc/scannow/offbootdir = C:\/offwindir = C:\ Windows)
*   最后一次重启你的设备，最后一次尝试重置/刷新。

## 使用系统还原或您的 Windows 安装媒体

如果您已经尝试了所有的系统命令(或者不想走那条路，跳过前面)，下一组解决方案应该可以做到这一点。

### 系统还原

如果您之前已经创建了还原点或 Windows 备份，您可以 [使用系统还原将回滚到那个旧的系统映像](https://lifehacker.com/the-complete-guide-to-windows-system-restore-its-bette-5466794) ，然后尝试 Windows 刷新。进入**控制面板>系统和安全>系统>系统保护**。如果“系统恢复”是可点击的，那么有一个可行的还原点。单击它并按照屏幕上的说明完成还原；如果呈灰色，则该选项不可用。请注意，这并不适用于所有版本的 Windows。

### 使用安装介质(USB/DVD)

使用此 [指南创建 Windows 安装盘或 USB 驱动器](https://lifehacker.com/the-ultimate-guide-to-reinstalling-windows-from-scratch-1832897572) 。按照说明进行操作，直到您可以选择重置/刷新或全新安装。首先尝试重置/刷新选项。

值得一提的是，上面的选项没有一个适合我的问题，所以这是我解决问题的方法。我仍然建议首先尝试上述方法，因为它们需要的时间更少。然而，如果重置/刷新选项*仍然*不工作，即使这最后一步，那么唯一的选择是使用安装介质做一个干净的 Windows 安装，并从头开始，按照上面链接的指南。