# 为什么我的工作笔记本电脑的 Wifi 速度比其他设备慢？

> 原文:[https://life hacker . com/why-my-work-laptop-with-my-other-1842489912](https://lifehacker.com/why-does-my-work-laptop-have-slower-wifi-than-my-other-1842489912)

日 Three of[**Tech 911**](https://lifehacker.com/c/tech-911)来这里答疑周，我正在快速浏览 [读者评论](https://lifehacker.com/tell-us-your-working-from-home-tech-issues-1842428782) 仿佛这是我的工作。事实就是如此。这是我的工作，我喜欢尽我所能帮助别人。请记住，如果你对在家工作的技术有疑问，因为你有一些不可靠的电脑或智能手机问题不能完全解决，例如，留下评论或给我发电子邮件。让我帮你做。

Watch

本周早些时候，我们已经讨论了如何修复你的家庭网络 ，但是对于那些现在被困在新的家庭办公室的人来说，糟糕的无线连接仍然是*的一个大问题。但是如果问题不在于你的无线网络呢？如果是你的设备呢？*

### 这个问题

Lifehacker 读者**阪神**T3】写道 T5:

> “我可以在我的手机、我妻子的手机和其他连接设备上获得不错的 WiFi 速度，但我的笔记本电脑的测试速度似乎非常有限。它是高规格的(一款像样的游戏笔记本电脑)——有什么原因吗？”

### 改变人生的答案

我很高兴您已经完成了主要的故障诊断，这也是我会花几段时间向大家介绍的。简而言之，你查看了你的 wifi 情况，并使用多种设备和/或服务进行了分析，如[【fast.com】](https://fast.com/)[【speedtest.net】](https://www.speedtest.net/)，或任何其他你喜欢的设备和/或服务。你发现了一个关键事实:你的 wifi 一般都很快，只有一个设备例外，你很难获得稳定的速度。

这使我们能够将重点放在您的游戏笔记本电脑上。而且，既然你这么说，我的假设是，它运行的是“游戏”制造商的某种奇特的网卡——比如黑仔的 wifi 卡。我最初的怀疑，或者说直觉，是你的无线网卡出了问题。

不过，对于新手来说，我建议你先看看这是哪种卡(根据你购买笔记本电脑时的发票或规格表)。如果你找不到，你也可以在**设备管理器>网络适配器**中查找。用谷歌快速搜索一下，确认一下，是的，它支持你的网络运行速度。

不管出于什么原因，如果你的“体面的”游戏笔记本电脑实际上在无线配置上让步了，有可能你的 wireless-n 非常慢(尽管我对此表示怀疑)。如果你有 wireless-ac，我假设你有，那么你*应该*能够看到一些很好的测试速度，因为你的游戏笔记本电脑无疑至少有一个 2x2 卡——换句话说，它支持至少 AC1200 的速度，或者在你的 5GHz 网络上的最大理论速度为 867Mbps(因为 5GHz 上的 867 Mbps+2.4 GHz 上的 300 Mbps = ~ 1200 Mbps)。

不要让数学绊倒你。简而言之，你要确保你的游戏笔记本电脑正在使用你家的 5Ghz 无线网络进行速度测试。你没有提到你有什么样的互联网计划，但如果它很强大——比如说，300Mbps 或更高——你只会看到快速连接，如果你使用 5Ghz(和无线交流，如上所述，如果你的笔记本电脑和路由器支持它)。

此外，我应该提到一件事:如果你的路由器使用一个 SSID 用于 2.4GHz 和 5GHz，并允许你的设备连接到他们选择连接的任何设备，那么*可能*你的游戏笔记本电脑愚蠢地连接到你较慢的 2.4GHz 无线网络，而不是你较快的 5GHz 无线网络。你可能想在你的路由器设置中把两者分开:比如“[你的 wifi]_2GHz”和“[你的 wifi]_5GHz”。

为了便于讨论，我将假设你已经做了所有这些事情，并且你的智能手机仍然比你的游戏笔记本速度快得多。在这种情况下，我的下一个倾向将是检查，以确保没有任何更新的驱动程序为您的笔记本电脑的无线卡。去联系你的笔记本电脑制造商和你的无线网卡制造商看看；更新(甚至重新安装)你的网卡驱动程序可能会给你你想要的速度。

如果你仍然不能从你的游戏笔记本电脑获得很高的无线速度，你可能不得不(或者想要)完全绕过你的网卡。虽然它们可能很挑剔，但至少支持 AC1200 的第三方 wifi 加密狗可能是最佳选择。这将花费你一点额外的现金，我绝对讨厌不得不购买硬件来取代笔记本电脑中已经可以正常工作的硬件，但这是一个选择。

这也可能值得检查一下，看看你是否可以在另一个连接上获得更快的 wifi 速度——一个开放的无线网络，或者朋友的房子，等等——以帮助排除你的家庭网络是一个问题。我不相信会是这样，但是如果你突然发现朋友的 wifi 网络比你自己的速度快 5 倍，也许将你的路由器重置为出厂默认设置可能会解决任何问题(并安装最新的固件，等等)。

不过，这些是我的想法。我错过了什么吗，生活黑客的读者们？除了更换路由器(这*可能*不是罪魁祸首)或从头重新安装 Windows(唉)，我不知道其他可能的解决方案。我认为电子狗是答案，谢天谢地， [它们很便宜](https://smile.amazon.com/NETGEAR-AC1200-Adapter-A6210-100PAS-Renewed/dp/B07TDLVX9N/ref=sr_1_4?asc_campaign=InlineText&asc_refurl=https://lifehacker.com/why-does-my-work-laptop-have-slower-wifi-than-my-other-1842489912&asc_source=&dchild=1&keywords=ac1200 adapter&qid=1585159438&s=electronics&sr=1-4&tag=kinjalifehackerlink-20) ？

* * *

*<small>你是否有一个让你夜不能寐的技术问题？厌倦了对您的 Windows 或 Mac 进行故障诊断？寻找关于应用程序、浏览器扩展或实用程序的建议来完成特定任务？让我们知道！在下面的评论或者邮件中告诉我们</small>*[*<small></small>*](mailto:david.murphy@lifehacker.com?subject=Tech%20911)<small>*<small>。</small>*</small> 

<small></small>