# 从头重新安装 Windows 的终极指南

> 原文:[https://life hacker . com/the-ultimate-guide-to-重装 windows-从头开始-1832897572](https://lifehacker.com/the-ultimate-guide-to-reinstalling-windows-from-scratch-1832897572)

在每个 Windows 用户的生活中，都会有一段时间感觉速度变慢。也许你一直在安装和卸载大量的应用程序，或者你一直在摆弄模糊的 Windows 设置(或者更糟，注册表)。也许你甚至像我一样决定过狂野的生活，并注册了微软的 Windows Insider 程序，该程序最近导致我的桌面系统嘎然而止。*呜呜。*

Watch

不管是什么原因，对 Windows 10 进行一次彻底的更新都不会有什么坏处——也就是说，对操作系统进行全新的、干净的安装。是的，你必须重新安装你的应用并重新设置你的帐户，但这并不像你想象的那样需要太多时间。有很多方法可以让这个过程尽可能的无痛。

### 如果你健忘，列出你安装的程序

我每年(或任何时候)的 Windows 10 重装都是大扫除的好时机。在清除并重新安装之前，我倾向于避免写下或生成我已经安装在系统上的程序列表。为什么？如果当我盯着一个新的 Windows 10 时，我不记得安装了一个应用程序，我可能并不那么需要它——或者忘记了它的存在。

如果你知道你经常安装了一些你不需要的*那些*的晦涩程序，但你宁愿永远不跟它们说再见，那也没关系。很容易生成一个列表，列出您之前在 PC 上存放的所有内容。点击开始按钮，打开 **Powershell** 并输入，然后复制并粘贴到提示中:

`Get-ItemProperty HKLM:\Software\Wow6432Node\Microsoft\Windows\CurrentVersion\Uninstall\* | Select-Object DisplayName, DisplayVersion, Publisher, InstallDate | Format-Table –AutoSize`

您可以将结果复制并粘贴到一个文本文件中，也可以通过以下命令让 Powershell 自己生成一个文本文件:

`Get-ItemProperty HKLM:\Software\Wow6432Node\Microsoft\Windows\CurrentVersion\Uninstall\* | Select-Object DisplayName, DisplayVersion, Publisher, InstallDate | Format-Table –AutoSize > *****`

您可能希望用文本文件的位置来替换*****，比如:`c:\Users\David\Desktop\Stuff.txt`

您还可以通过**命令提示符**导出已安装应用程序的列表。把它拉出来，就像你加载 Powershell 一样，输入“wmic ”,然后按回车键。然后，输入以下字符串:

```
output:C:\Users\Davem\Desktop\InstalledProgramsWMIC.txt product get name,version
```

显然，你会想用你的位置替换我的位置。如果你复制并粘贴那行代码(除非你碰巧也用“davem”作为你的文件夹名)，你会得到一个提示，说你搞砸了。

### 备份你的东西

我不是你，所以在重新安装 Windows 10 之前，我无法给你准确的指示，让你*做*需要在你的系统上保存什么。如果你担心任何类型的数据丢失，你可以走硬核路线，在删除任何东西之前， [克隆(或制作)](https://lifehacker.com/back-up-and-clone-your-hard-drive-with-macrium-reflect-1825289970) 你的主驱动器。然后，您可以花所有需要的时间来分析旧驱动器的内容，并在删除该克隆或映像之前复制您想要保留的所有内容。

然而，大多数人可能不需要走那么远。当我不得不重新安装 Windows 10 时，我通常会将系统用户文件夹(通常位于 C:\Users\)的全部内容复制到一个单独的驱动器中。这通常会处理我所关心的一切，尽管我会快速浏览 C:\上的任何主要文件夹，以确保我没有意外地将数据存储在其他地方，比如我的虚拟机硬盘或其他什么地方。

如果你没有备用硬盘，甚至没有便携式硬盘，我真的建议你现在就投资。无论您是购买另一个硬盘、固态硬盘、便携式硬盘还是 NAS 盒，它都会对这些*和*有用，您将有另一个地方来存储数据备份——当然，假设您已经通过 [将数据发送到云，无论您喜欢什么服务](https://lifehacker.com/how-to-back-up-your-files-now-that-crashplan-isnt-an-op-1798320345) 。备份越多越好。或者，至少，当您的单一备份解决方案失败时，您会这么想。

如果你只有一个硬盘，但这是一个大问题，你也可以廉价地将它的一部分分区，以保存主分区内容的克隆或镜像。这是一个不雅的解决方案，但它的工作。

### 取消你的应用授权

如果你有几个应用程序需要授权，并且只能在有限的系统上使用，比如 CalMAN calibration 软件，Office 365，当然还有 iTunes，你应该确保在清除系统并重新安装 Windows 10 之前取消授权。(你其实不需要提前 [做这个](https://support.office.com/en-us/article/deactivate-office-365-if-you-see-a-limit-reached-error-767e3560-96ed-4b1c-806d-2fe01c529b1b) 对于 Office 365，我只是想提一下作为授权和使用限制的例子。)

就我而言，iTunes 是我唯一不得不使用的应用程序，只是因为如果可以避免的话，我宁愿不使用这个选项来取消我所有系统的授权。你 [毕竟每年只能得到一个](https://support.apple.com/en-us/HT204385) 的那些“核弹”。

你可能还知道你系统上的其他有限的应用程序，但是滚动开始菜单来刷新你的记忆是值得的。

### 保留以后不想下载的内容

我很幸运，因为我可以将我的大部分关键文件(我的游戏)转储到我台式机上的几个辅助硬盘驱动器和固态硬盘上。我这样做并不是为了提高速度或容量(我的主驱动器，一个 500GB 的 SSD，会被我收集的 Steam 淹没，而我的辅助 2TB 驱动器非常适合我的一堆游戏)。我这么做也是因为重新安装 Windows 10 要容易得多，因为我不必担心重新安装数百 GB 的游戏。

如果可以的话，我建议尽可能把你的游戏放在主硬盘之外。就我而言，我把所有可以轻松下载的东西都转储到不同的驱动器上。其中包括 Steam、Battle.net、Origin、Epic Games、GoG 等游戏。

正因为如此，我在重装 Windows 10 之前，不需要备份任何与游戏相关的东西(除非某个游戏愚蠢地在我的文档里转储了一个保存的游戏，我不常发现这种情况)。都在那里，就在我的其他硬盘上。当面对一个没有我的任何游戏服务的新的、干净的 Windows 10 版本时，我会下载并安装它们。

如果一切顺利，我就不用重新下载或安装任何游戏了。虽然我通常不得不为每个游戏服务的应用程序重置我的设置，有时不得不轻轻地让应用程序知道之前下载的游戏在哪里(*咳咳 Battle.net 咳咳*)，但这只是找到并重新下载我之前安装的所有程序所需时间的一小部分——或者说，是所有已经安装的程序和等待我玩的。

### 保存打开的浏览器选项卡

如果你不想在清空硬盘和重新安装 Windows 10 之前对所有打开的浏览器标签添加书签，有一种更简单的方法来保存你一直在查看的所有内容(或者发誓你会看到的)。抓取 [Chrome](https://chrome.google.com/webstore/detail/onetab/chphlpgkkbolifaimnlloiipkdnihall?hl=en) 或 [Firefox](https://addons.mozilla.org/en-US/firefox/addon/onetab/) 的 OneTab 扩展，你将能够导出所有打开的内容或将其保存为更容易点击的链接网页。

这一步在安装前的混乱中很容易被忘记，但是如果你不这样做，你将不得不仔细检查你的(基于云的)浏览器历史来找到你丢失的所有东西。这并不是最困难的任务，尤其是因为你的浏览器可能会在你的历史中的某个时间点向你显示所有你以前关闭的标签页*和*，但是处理起来有点烦人。

### 将 Windows 10 ISO 安装到 USB 闪存驱动器上

碟片？Pffft。你的台式机或笔记本电脑还有光驱吗？重新安装 Windows 10 最快最简单的方法是从 u 盘安装。(如果你身边没有至少 4GB 的硬盘，现在是买一台的好时机。)

下载微软的 [媒体创作工具](https://www.microsoft.com/en-us/software-download/windows10) ，然后用那个直接从微软抓取最新的 Windows 10 ISO。当你下载的时候，也可以下载一个名为“[【Rufus](https://rufus.ie/)”的工具。您将使用它将您的 ISO 文件 [刻录到 USB 闪存驱动器](https://lifehacker.com/windows-app-of-the-week-rufus-1824077593) 而不是光盘，因为缺少更好的方式来描述这个过程。

一旦你下载了你的 ISO，启动 Rufus 并点击一个光盘的小图像，它看起来像这样:

选择窗户。ISO 文件，然后单击“开始”按钮开始创建您的可启动 USB 驱动器。完成后，您可以通过在文件资源管理器中拉出驱动器并双击“setup.exe”来开始重新安装 Windows(当您准备好时)，否则，您也可以重新启动系统并粘贴从辅助源(您的 USB 闪存驱动器)启动所需的任何关键配置。您可能还需要进入系统的 BIOS，从 USB 闪存驱动器启动，或者，除此之外，更改启动顺序，将闪存驱动器置于硬盘驱动器之上。

### 保存以后不想查找的任何其他设置

这是一个快速的总括，但不要忘记复制和粘贴任何其他应用程序设置，你不想处理弄清楚以后。就我而言，我总是至少导出我的 VPN 配置文件或记下它们的设置，以便在我重新安装 Windows 10 后，我可以快速启动它们并再次工作。我还确保在校准显示器时找到我以前创建的颜色配置文件。(这也确保了我不会忘记在新版本的 Windows 上设置它，我心不在焉的自己有时肯定会错过它。)

### 考虑使用 Microsoft 帐户

虽然大多数人可能会设置一个微软帐户来使用 Windows 10(这使得认证你的操作系统副本变得非常容易，等等)，但你们中的一些人可能出于任何原因仍然在运行本地帐户。在 Windows 10 本身的 中，从本地帐户切换到微软帐户 [很容易，你可能希望在重新安装操作系统之前这样做，这样你就可以快速地将你的设置从旧版本的 Windows 同步到新版本。](https://answers.microsoft.com/en-us/windows/forum/windows_10-other_settings/how-to-change-local-account-to-microsoft-account/edc4cf39-cef0-4b31-93b2-a37d63726dc2)

如果没有，在 Windows 10 的安装过程中，系统会提示您使用一个登录到您的系统。如果有必要，您仍然可以使用本地帐户，但是使用 Microsoft 帐户进行身份验证非常方便。(别忘了，如果你不想在每次电脑启动时都输入大量复杂的内容，你也可以使用 PIN 码登录 windows，而不是你的 Microsoft 帐户密码。)

### 将应用程序重新加载到全新的 Windows 10 中

安装新版本的 Windows 10 后，我首先求助的网站之一是[Ninite](https://ninite.com/)——检查你电脑上想要的所有应用程序，你将能够下载一个可执行文件，自动安装你选择的所有程序。除此之外，还有我已经提到的各种游戏服务，这些服务通常可以满足我系统中大多数关键应用的需求。

然而，我确实想给微软商店一个快速的大喊。是的，*那个* app。虽然我很少使用它，但在一些情况下，你可能会考虑微软商店版本的应用程序，而不是从另一家公司的网站下载的东西。以 [iTunes](https://www.microsoft.com/en-us/p/itunes/9pb2mz1zmb1s) 为例——微软商店版本 [可以保持更新](https://lifehacker.com/if-youre-an-iphone-loving-windows-user-youll-want-itun-1825606649) 而不需要额外的苹果软件更新实用程序。

虽然一些应用程序的“普通”版本和微软商店版本非常相似(例如 Spotify)，但我通常发现通过后者安装和卸载应用程序更容易。如果没有别的，万一你有点健忘，你会有一个你在应用程序的“我的图书馆”部分使用过的所有东西的快速列表。

### 完成基本工作后，做一个备份

一旦你有了一个你喜欢的通用版本的 Windows 10——你所有的偏好都设置好了，你使用的所有常规程序都安装好了——我认为在你开始从网上或诸如此类的地方下载一堆垃圾之前对你的整个安装进行镜像是一个很好的主意。

去抓取 [Macrium Reflect](https://lifehacker.com/back-up-and-clone-your-hard-drive-with-macrium-reflect-1825289970) 并创建你的整个 C:\驱动器的备份镜像，假设那是你安装 Windows 和你的程序的地方。这样，您将拥有一个非常棒的“操作系统+我喜欢的一切”版本的 Windows，下次您想将系统恢复到“干净”的操作系统版本时，可以使用它。

当然，与使用微软的系统相比，你可能需要下载更多的 Windows 10 更新。ISO，但你也不必经历设置和安装操作系统以及应用程序的过程。