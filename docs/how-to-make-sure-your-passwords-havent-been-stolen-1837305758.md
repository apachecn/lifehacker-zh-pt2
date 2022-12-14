# 如何确保你的密码没有被盗

> 原文：<https://lifehacker.com/how-to-make-sure-your-passwords-havent-been-stolen-1837305758>

拥有一个可靠的密码的最大好处之一就是 [你不必更改它](https://lifehacker.com/instead-of-changing-your-passwords-upgrade-them-1836182279) 。如果它是强大的、独一无二的，并且没有被攻击者破坏，那么根据某个任意的时间表对它进行修改不会带来任何安全好处。就这样吧。



你*应该*跟踪的是你的密码是否在你最近可能经历过的或者曾经经历过的数据泄露事件中被泄露。显然，当这种情况发生时，更改受影响的密码应该是当务之急。但是很多人不这么做。根据谷歌 的最新研究 [:](https://ai.google/research/pubs/pub48399)

> *...我们实现了一个云服务，它可以协调对 40 多亿个违规凭证的访问，还有一个 Chrome 扩展作为初始客户端。根据来自近 670，000 名用户和 2，100 万次登录的匿名遥测数据，我们发现 1.5%的 web 登录涉及凭据泄露。通过提醒用户此违规状态，我们的警告中有 26%%会导致用户迁移到新密码，至少与原始密码一样强。”*

我不确定为什么一个人*在发现密码被泄露后不*更改密码，但也许这个信息不够清楚。更糟糕的是，想象一下人们*没有检查的所有被泄露的密码——毕竟，你不会改变那些你认为没有被破解的密码。*

虽然这一段的第一部分完全取决于你，但我们可以帮助你完成后半部分。有很多工具(免费或付费的)可以提醒你是时候修改密码了。这里有一些我们最喜欢的——请选择一个或多个，马上使用。

### [谷歌的密码审查扩展](https://chrome.google.com/webstore/detail/password-checkup-extensio/pncabnpcffmalkkjpajodfhijclecjno)

如果你是 Chrome 粉丝— [大多数人都是](https://gs.statcounter.com/browser-market-share)—可以考虑安装谷歌的 [**密码检查**](https://chrome.google.com/webstore/detail/password-checkup-extensio/pncabnpcffmalkkjpajodfhijclecjno) 扩展。它会呆在你浏览器的后台，不做任何重要的事情，直到你登录一个网站。当你这样做的时候，它会检查你的帐户凭证是否已经被泄露。如果是这样，它会让你知道是时候修改你的密码了，你绝对应该接受它的建议。

而且，不，这个扩展不会通过检查*泄露*你的密码。正如谷歌的[所写的](https://security.googleblog.com/2019/02/protect-your-accounts-from-data.html)的:

> *“我们设计了带有隐私保护技术的密码检查，绝不会向谷歌透露这些个人信息。我们还设计了密码检查，以防止攻击者滥用密码检查来揭示不安全的用户名和密码。最后，扩展报告的所有统计数据都是匿名的。这些指标包括发现不安全凭据的查找次数、警报是否会导致密码更改，以及提高站点兼容性所涉及的 web 域。”*

* * *

### [我被 pwn 了](https://haveibeenpwned.com/)

这个更简单。将您的电子邮件地址发送到 [**我已经通过该网站的“通知我”功能得到了**](https://haveibeenpwned.com) ，每当您的电子邮件地址(以及与之相关的任何内容)出现漏洞时，您都会收到警告。没有理由不使用这项免费服务，除非你很神秘，使用 [不同的电子邮件地址](https://lifehacker.com/make-a-joint-email-address-with-a-gmail-filter-1836702340) 获得多项服务。如果是这样，可以考虑使用类似[**Badrap**](https://badrap.io)的第三方服务，对照我是否被 Pwned 的数据库查询多个账户。

我们几乎不需要说出来，但我们要说出来:当你收到一封电子邮件，说你的帐户被入侵，请去更改你的服务密码。使其成为唯一的密码；请设置一个强密码。如果你很懒，什么都用同一个密码，那就修改其他服务的密码。

* * *

### [火狐监视器](https://monitor.firefox.com)

这里有一个不太大的秘密:[**Firefox Monitor**](https://monitor.firefox.com)提供了与我被 pwn 时相同的“如果我的电子邮件涉及数据泄露，请通知我”服务。事实上，它也使用了我被 Pwned 的数据库。

尽管 Firefox Monitor 基本上是“我被 Pwned 了吗”的翻版，但它仍然值得了解。如果你是火狐的超级粉丝，并且这是说服你注册这项有用服务的唯一原因，那就更好了。

* * *

### [1 密码](https://1password.com)

如果你为 1Password 付费——你应该这样做，因为它是一个很棒的密码管理器——你可以使用它的 [**瞭望塔**](https://support.1password.com/watchtower/) 功能。没有理由*不*关注这项关键服务，因为它会提醒你，只要你用过的密码出现在，你猜对了，我被 Pwned 的数据库中。这与仅仅查看您的电子邮件地址是否涉及违规有点不同(也更有用)。

你还可以很快看到你使用的任何服务本身是否涉及数据泄露，这是一个很好的鼓励，即使你没有受到攻击的直接影响，也要修改你的密码。

* * *

### [哈索·普拉特纳研究所的身份泄密者](https://sec.hpi.de/ilc/)

像类似的工具一样，德国哈索·普拉特纳研究所的这个工具只需要你输入你的电子邮件地址。如果该电子邮件与任何类型的数据泄露有关，您将会收到一份通过电子邮件发送的 [报告](https://sec.hpi.de/ilc/publickeys) 让您知道。

这个工具*不是*主动监控解决方案，但它有助于查看您的帐户信息先前在哪里被泄露。因为它只需要一秒钟就可以运行，所以当您试图全面了解您可能需要更改的帐户密码时，这不会是一个很大的负担。

* * *

### [信用因缘](https://www.creditkarma.com/id-monitoring/)

你可能知道其金融相关服务的信用因果，如免费信用评分和 [信用监控](https://www.creditkarma.com/credit-monitoring/) 。然而，它*也*有一个免费的 [**身份监控服务**](https://www.creditkarma.com/id-monitoring/) ，当你的电子邮件地址出现数据泄露时，它会提醒你。当这种情况发生时，您通常会想要更改您的关联密码。