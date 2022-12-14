# 如何将黑客踢出你的戒指账户

> 原文：<https://lifehacker.com/how-to-kick-hackers-out-of-your-ring-account-1840507643>

关于亚马逊环形摄像头的安全性，已经有很多报道了。我仍然坚持认为，人们发现的大多数公司安全问题都需要攻击者知道你的用户名和密码——这可以通过为你的帐户使用一个强有力的、唯一的密码来帮助防止。但是不要止步于此。



Vice 的主板在其最新调查文章 中对该公司松懈的安全做法进行了批评，该文章讨论了当有人试图(或已经成功)登录你的账户时，Ring 如何不通知你。例如，当有人使用以前从未用于登录您的帐户的 IP 地址登录您的帐户时，您不会收到任何警告，反过来，此人也不会被要求提供额外的方法来验证他们是您。也没有办法看到在任何时候有多少人登录到你的帐户，也没有一个列表显示所有*已经*成功登录到你的帐户的 IP 地址。

事实上，Ring 似乎并没有做太多的事情来阻止黑客用来侵入 Ring 账户的暴力攻击(使用之前泄露的凭证)。正如主板所描述的:

> *“Ring hackers”软件的工作原理是快速检查 Ring web 登录门户上的电子邮件地址和密码是否有效；黑客通常会使用来自其他服务的已经妥协的组合列表。如果有人提出太多不正确的登录请求，许多在线服务会暂时阻止他们这样做，将他们的 IP 地址标记为可疑，或者提供验证码来检查试图登录的用户是人而不是自动程序。不过，Ring 似乎对此采取了最低限度的保护措施。Motherboard 故意在登录门户网站上输入错误的密码，同时连续几十次从 Tor 匿名网络连接。Ring 从未试图限制我们的登录尝试或出示验证码。"*

好消息是什么？你仍然可以保护你的戒指账户，但是你需要采取额外的措施来阻止任何已经登录并且正在看你读这篇文章的人。

### 保护你的戒指账户很简单，但是很微妙

正如 Mozilla [写的](https://foundation.mozilla.org/en/blog/how-to-secure-your-ring-security-camera/) 所说，阻止攻击者进入你的 Ring 账户的最好方法是启用双因素认证。而这样做 [就容易](https://support.ring.com/hc/en-us/articles/360024818291) 。你只需要在你的 iOS、iPadOS 或 Android 设备上打开 Ring 应用程序，通过左上角的图标(三线图)调出你的账户设置，然后在“增强安全性”下查找“双因素认证”

打开它，输入您的密码，提供一个手机号码，它可以用来发送给您一个验证码，并在提示时输入该代码。

由于只要您或其他人试图从新设备访问您的环形摄像机，Ring 就会向您发送代码，因此这种“两步”认证技术的安全性略低于适当的“双因素”认证设置。(对于普通用户来说，这是 [和](https://lifehacker.com/two-factor-authentication-isnt-enough-to-keep-your-acco-1827867557) 的细微区别，但了解这一点很重要。)

不过，关键在于:开启 Ring 的双因素认证(用它的术语来说)并不会让任何已经*登录*的人退出你的账户。这是一个奇怪但重要的区别:你将使你的账户在*未来*更加安全，但不是现在。

在我们写这篇文章的时候，注销所有可以访问你的帐户的人的唯一方法是修改你的密码。在您设置了双因素身份验证后再这样做，您的 Ring 帐户将会尽可能地安全。

因为如果有人拥有你的登录凭证并试图以你的身份登录，但两步认证失败，你将不会收到任何通知，所以你必须相信所述攻击者*也*没有找到拦截你的消息的方法。

这就是 Vice 的报告击中要害的地方:由于 Ring 向其用户提供最少的信息，你真的无法知道有人是否设法获得了你的账户凭证*和*绕过了你的双重认证。虽然随机攻击者能够做到这一点的几率低得令人难以置信，但几率*应该*为零。当有人试图以您的身份登录时，Ring 没有理由不能告诉您，这样您就可以更改您的密码或保护您的鉴定方法。