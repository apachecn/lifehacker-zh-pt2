# 了解 Nvidia 的“G-Sync”和 AMD 的“FreeSync”显示器技术的基础知识

> 原文：<https://lifehacker.com/learn-the-basics-of-nvidias-g-sync-and-amds-freesync-mo-1831578473>

Nvidia 是 PC 显卡和所有与游戏好看相关的东西的主要供应商，最近宣布计划开放其专有的显示渲染技术，“”用于支持*其他*可变刷新率技术的少数显示器，AMD 的 FreeSync。



如果这些都没有意义，那也没关系。大多数游戏玩家和极客可能不会记住显示技术的细微差别来给朋友和爱人留下深刻印象。然而，如果你想让你的电脑游戏更上一层楼，完全忽略 G-Sync 和 FreeSync 是不明智的。如果你能得到这些好处，它们会让你的游戏更流畅，输入延迟更少，从而真正丰富你的游戏体验。

如果你还在挠头，不要担心。为了让你免于陷入研究的兔子洞，让我们快速浏览一下自适应显示技术背后的基础知识，以便你更好地理解 G-Sync 和 free Sync——以及为什么你在购买下一台 [大型游戏显示器](https://gizmodo.com/hps-65-inch-hdr-gaming-monitor-with-g-sync-looks-specta-1831489823) 时会需要它们。

## G-Sync 和 FreeSync 能为我的游戏做些什么？

G-Sync 和 FreeSync 是它们的通用名称，但 Nvidia 和 AMD 实施的基础技术通常被称为“自适应同步”，或简称为“自适应同步”。启用后，G-Sync 和 FreeSync 会将您的显卡输出与显示器输出相匹配，以确保前者生成的每一帧都显示在您的显示器上——不多也不少。这可以最大限度地减少延迟，并防止当您的显卡发送的帧数多于(或少于)显示器的本机刷新率时出现令人讨厌的图像毛刺。

 [https://lifehacker.com/embed/inset/iframe?id=youtube-video-ZSgHqImxQpE&start=0](https://lifehacker.com/embed/inset/iframe?id=youtube-video-ZSgHqImxQpE&start=0) 

让我们把这个再打开一点。在运行视频游戏时，你的电脑每秒钟会计算和重绘你需要知道的一切——游戏中每个潜在活动部分的状态，例如，包括玩家、敌人和环境——数十次。就像卡通是由许多相似的图画经过微小的变化组成的一样，你的电脑将这些“帧”中的每一个发送到你的显示器上，从而产生你所感知的运动和动画。一个游戏发送信息的次数被称为它的“帧速率”

另一方面，每台显示器都有显示动画帧数的限制——刷新率，或每秒钟更新画面的次数。当计算机发送的动画帧数超过显示器的处理能力时，会导致“屏幕撕裂”，即同时显示两帧动画。相反，一台不能输出足够多动画帧的电脑会在你的输入和屏幕上显示的内容之间产生延迟——恼人的延迟。

 [https://lifehacker.com/embed/inset/iframe?id=youtube-video-iFLDpqIT6MY&start=0](https://lifehacker.com/embed/inset/iframe?id=youtube-video-iFLDpqIT6MY&start=0)

<figcaption class="sc-1ptbguh-0 hxeMec caption">This video shows does a good job demonstrating screen-tearing and how FreeSync helps prevent it.</figcaption> 

大多数游戏通过提供一种称为垂直同步或“V-Sync”的功能来解决这个问题，这是一种软件解决方案，可以防止您的 PC 发送超过显示器处理能力的帧。这在某些情况下解决了屏幕撕裂问题，但不是理想的解决方案。

游戏通常不会以一致的帧速率运行:根据游戏和计算机的能力，你的游戏可以随时以每秒几十帧的速度跳跃。如果你很难输出一个匹配或超过显示器刷新率的帧速率，由于缺乏更好的表达方式， [你可能会陷入更差的帧速率](https://www.reddit.com/r/DestinyTechSupport/comments/7deehm/dropping_to_30_fps_when_vsync_is_set_to_60/) 。那只是技术。

自适应同步通过为您提供更多的灵活性来防止除最极端情况之外的所有问题:锁定帧速率，使其不超过您的显示器所能做到的，但当您的每秒帧数达不到显示器的刷新率时，让您尽可能以最高的帧速率运行。

## G-Sync 和 FreeSync 有什么区别？

最简单的答案是，G-Sync 是 Nvidia 及其显示器制造合作伙伴专有的动态缩放器。FreeSync 是 AMD 创建的开源标准，任何显示器厂商都可以支持。

然而，事情远不止如此。在 CES 2019 之前，G-Sync 在技术上是一种硬件标准:支持 G-Sync 的显示器中有一个处理器芯片，可以直接与英伟达显卡通信以调整帧率。除非你有 Nvidia 显卡，否则没有 G-Sync 适合你。

FreeSync 显示器不需要任何特殊的显示器缩放器来工作，理论上也应该可以与任何显卡一起工作，但直到现在，你只能在使用兼容的 AMD 显卡时才能利用 FreeSync。

正如我们前面提到的，Nvidia 本周宣布，1 月 15 日推出的纯软件版本的 G-Sync 将为少量预先批准的“G-Sync 兼容”显示器启用自适应同步技术，这些显示器没有内置 Nvidia 缩放器。那些拥有其他 FreeSync 显示器(和 Nvidia 显卡)的人最终也应该能够打开自适应同步，但细节仍不清楚。此外，我们现在还不能说新的基于软件的 G-Sync 将如何与 FreeSync 或原始的基于芯片的版本相抗衡。

## 如何知道显示器支持 G-Sync 还是 FreeSync？

如果你要买一台新显示器，大多数公司都会明确表示显示器支持 G-Sync、FreeSync 或(现在)两者都支持。无论你在哪个网上商店购物，它都会是商品描述中的一个要点，而且盒子上应该有一个标志。(大部分时候 [就在那个该死的名字](https://www.bestbuy.com/site/promo/g-sync-monitors) 里)。

如果你想检查你已经拥有的显示器，或者只是想完全确定，这里有每个 [G-Sync 显示器](https://www.nvidia.com/en-us/geforce/products/g-sync-monitors/specs/) 和 [FreeSync 显示器](https://www.amd.com/en/products/freesync-monitors) 的链接。Nvidia 也做了一个小婴儿床表与显示器将成为 G-Sync 兼容下周

## 我如何使用它们？

如果您使用兼容的 GPU 和显示器，默认情况下会打开 G-Sync 和 FreeSync。你可以通过访问 G-Sync 的 Nvidia 控制面板应用程序或 FreeSync 的 AMD Catalyst 控制面板应用程序来检查以确保你的工具已打开。

虽然大多数人不会介意让 G-Sync 或 FreeSync 打开并忘记它，但特定的游戏玩家可能会发现某些游戏在没有 G-Sync 或 FreeSync 的情况下运行得更好——例如，那些寻求尽可能最小输入延迟的第一人称射击游戏 的。关于如何优化 G-Sync 的更长、更详细的纲要，包括如何在个别游戏中关闭 G-Sync，请查看本指南。对于如何在 [FreeSync 显示器](https://www.amd.com/en/support/kb/faq/dh-013#faq-Adjusting-Radeon-FreeSync-Within-Individual-Application-Profiles) 上做到这一点，AMD 也有类似的指导。

## 哪种自适应同步技术最好？

除非你同时购买一个新的显卡和显示器，否则在 G-Sync 和 FreeSync 之间进行选择可能会归结为选择最适合你现有设备的设备。例如，如果你有 AMD 显卡，那么购买 G-Sync 显示器是没有意义的，我也不会建议你去购买 FreeSync 显示器来与你的 Nvidia GPU 配对——至少，在我们看到 Nvidia 支持的 FreeSync 显示器与 G-Sync 配合的表现有多好之前。

购买新显示器时，您还需要考虑许多其他因素:显示器的面板类型(TN？IPS？);其最大刷新率，以及支持 G-Sync 和 FreeSync 的刷新率；它的分辨率，以及你的显卡能否输出高质量的游戏；、以及显示器的可调程度等等。

显示器支持 G-Sync 或 FreeSync 这一简单事实是您在购买新游戏显示器时应该问自己的第一个问题。即使这样，你也可能想暂时不买任何新东西。更新的“ [FreeSync 2](https://www.pcgamer.com/asus-launches-32-inch-43-inch-and-49-inch-freesync-2-hdr-monitors/) ”和“ [G-Sync Ultimate](https://www.engadget.com/2019/01/07/nvidia-rebrands-g-sync-hdr-as-g-sync-ultimate/) ”显示器仍处于初级阶段，但它们有可能比今天最好的显示器看起来更好——虽然现在价格高昂，但过一段时间后应该会冷却下来。