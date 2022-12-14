# 通过限制占用大量带宽的应用程序来加快互联网速度

> 原文：<https://lifehacker.com/speed-up-your-internet-by-limiting-bandwidth-hungry-app-1836308469>

你可能会为某个服务等级向你的 ISP 付费，但这并不意味着你能同时获得这两种速度——细则可能会指出你的上传速度比下载速度慢得多。



虽然你可能会花大部分时间在网上下载这下载那，但是最大限度的上传会影响你的整体表现。这是一个很容易检查你使用的所有高带宽应用的*和*限制的问题。

### 什么在吞噬你的背景带宽？

我最近爱上了[**glass wire**](https://lifehacker.com/glasswire-monitors-your-bandwidth-and-identifies-resour-1660960008)，这是一个免费增值工具，你可以用它来查看你在几分钟、几小时、几天、几周、几个月内到底下载了多少*和上传了多少*。这很重要，因为这是一个很好的方式来查看你是否上传了太多的内容——无论是 BitTorrent、计算机备份，还是将大量数据同步到云服务——这可能会影响你的下载速度。

如果你的上传干扰了你的下载，或者如果你想在这些问题变成一个问题之前抢先一步，很容易为那些可能占用你大部分带宽的应用程序设置速度限制。

### 如何限制应用程序的上传(和下载)速度

如果我注意到我有一个 BitTorrent 应用程序在后台运行，它正在向网络上的每个人传播文件——首先，我可能不应该让它 24/7 不受检查地运行。一旦我确保禁止这个应用程序在启动时启动(通过它的设置)，我还可以在它的设置屏幕中调出“速度”部分，并对它的上传带宽进行严格限制。优秀的应用程序甚至允许你*安排*这些限制，以防你想在不使用电脑的时候疯狂上传，但需要在工作或游戏时将它们拉回一点。

我用来将我桌面的不同部分同步到网络上不同服务的许多应用程序也是如此。不要笑；这是我的任务栏:

以防你不想玩猜谜游戏，那就是 [谷歌备份同步](https://www.google.com/drive/download/backup-and-sync/)[I cloud](https://support.apple.com/en-us/HT204283)[one drive](https://onedrive.live.com/about/en-us/)[Backblaze](https://www.backblaze.com/)，以及 [Dropbox](https://www.dropbox.com/) 。是的，可能有我可以用来管理其中大部分的一体化应用程序，但我喜欢我的图标自助餐。

如果你觉得你的一个(或多个)云主题应用消耗了你很多的上传带宽，你可以限制它们的速度。例如，在 **Dropbox** 中，这就像调出应用程序的首选项，导航到其带宽部分，并为其上传和下载速率设置一些限制一样简单:

对于像 **Backblaze** 这样的服务来说，将我个人电脑上的大部分内容转储到云中某个神奇的服务器上，限制应用程序在正常工作日的上传速度至关重要。您可以通过其性能选项卡上的滑块来完成此操作:

您还可以安排应用程序仅在一天中的特定时间备份您的系统:

一些应用程序，比如 iCloud，不允许你在应用程序本身内限制它们的带宽——这很烦人。相反，你需要使用一个单独的应用程序，如 [**TMeter**](http://www.tmeter.ru/en/) (免费)或一直流行的[**net limiter**](https://www.netlimiter.com/)。如果你想要一个 [专业版](https://www.netlimiter.com/products/nl4) 的许可证，后者将花费你 30 美元，但它有一个试用版，所以你可以在付钱之前检查它的功能。

虽然价格昂贵，但该应用程序可以非常容易地限制 PC 上任何应用程序的上传和下载速度:

别忘了。Windows 本身可能也有责任。尝试限制它的更新(或者禁用 [它的 P2P 共享机制](https://lifehacker.com/windows-10-uses-your-bandwidth-to-distribute-updates-d-1721091469) )，这可能有助于为你想做的其他事情释放一些带宽。