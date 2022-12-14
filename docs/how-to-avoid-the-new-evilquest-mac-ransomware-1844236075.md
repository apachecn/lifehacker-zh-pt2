# 如何避免新的“evil quest”Mac 勒索软件

> 原文：<https://lifehacker.com/how-to-avoid-the-new-evilquest-mac-ransomware-1844236075>

当你开始下载时，最新的 Mac 恶意软件之一是一种破坏性的勒索软件，称为“EvilQuest”。



好消息是什么？现在它主要是通过盗版的 Mac 软件传播，所以如果你不做偷窃程序的事情，你现在就不用担心了。 [Malwarebytes 说](https://blog.malwarebytes.com/mac/2020/06/new-mac-ransomware-spreading-through-piracy/) 该勒索病毒存在于至少两个不同 app 的假冒安装程序中: [小飞贼](https://obdev.at/products/littlesnitch/index.html) 和 [混在 Key 8](https://mixedinkey.com/) 。Malwarebytes 还发现了一个伪造的 [Ableton Live](https://www.ableton.com/en/) 安装程序的证据，并且其他人也可能存在。

与“小飞贼”和“Key 8 制造”的合法安装文件不同，这些文件有官方标志并经过适当包装，带有勒索软件的伪造者使用通用的安装包图标，并带有不相关的光盘映像。Malwarebytes 还在检查存放 EvilQuest 的安装程序的内容时发现了一个可疑的“补丁”文件，并发现安装程序没有正确的代码签名证书(验证文件来自可信来源的数字签名)。

与其他勒索软件一样，EvilQuest 会加密您设备上的文件(包括连接的硬盘和外部存储位置)，并将您锁定在外。重新访问你的文件的唯一方法是向黑客支付“赎金”，通常是通过比特币交易或匿名转账。支付赎金通常有一个最后期限，过了这个期限，你的文件就会被永久锁定甚至删除。EvilQuest 给被感染的用户三天时间付款，否则将被永久锁定。

### 如何保护您的 Mac 免受 EvilQuest 的攻击

勒索软件很可怕，但却是可以避免的。盗版是部署各种恶意软件的常见载体，因为盗版程序和媒体通常以改变的格式或非正统的文件出现，这使得不知情的用户很容易忽略相当明显的迹象，即他们下载了一些伪造的东西。

这就是为什么完全避免盗版是最安全的。你将避免恶意软件感染，也不会违反法律。另外，通过实际购买应用和媒体，你是在支持创作者，这样他们就可以继续工作。

然而，这并不是说恶意软件不能潜伏在你从网上下载的正常应用中。确保你在评论区或论坛上关注你听说的新应用，甚至在安装你在网上偶然发现的东西之前粗略地搜索一下 Twitter，以确保没有人报告任何问题。

跳过任何你不能得到明确答案的内容，彻底检查你下载的内容。最简单的解决办法是使用可靠的反恶意软件和反病毒应用程序，在你下载或安装它们之前捕获恶意文件。谈到 EvilQuest，Malwarebytes 表示，它会在勒索软件感染你的 Mac 之前识别并删除它，并且可以免费使用 [Malwarebytes 应用](https://www.malwarebytes.com/mac/) 运行基本扫描。

您还应该有一些系统备份，以防出现问题，您需要执行全新安装并恢复您的旧文件——无论是由于恶意软件还是其他问题，如错误、硬件故障或设备丢失/被盗。将多个备份保存在不同的位置是明智之举，包括云驱动器、设备上的存储设备(T2)和外部存储设备(T4)。只要确保在不执行备份时保持外部驱动器断开连接，以防止它们也被勒索软件加密。

### 如果你被感染了该怎么办

预防措施应该足以确保您的计算机安全，但如果您发现自己感染了 EvilQuest 勒索软件，请不要惊慌:只要您安全备份了您的文件，您就可以(很可能)恢复而无需支付。尝试使用 Malwarebytes 或其他反恶意软件删除勒索软件。如果你的设备已经被锁定*并且*你的反恶意软件程序无法工作，尝试执行工厂重置，然后使用干净的备份恢复你的旧文件。