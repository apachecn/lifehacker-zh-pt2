# 密码限制如何给你一种虚假的安全感

> 原文：<https://lifehacker.com/how-password-constraints-give-you-a-false-sense-of-secu-1830564360>

下一次你被迫设置密码时——尤其是如果一个网站要求你使用大小写字母、数字或符号的疯狂组合——不要认为这些混淆视听的尝试自动意味着你的密码是不可思议的和安全的。



Webroot 的高级安全分析师 Randy Abrams， [运行了一些简单的测试](https://www.webroot.com/blog/2018/11/05/password-constraints-unintended-security-consequences/) 。他统计了在一个八字符密码中可以创建的所有潜在密码，包括数字、大小写字母和符号。(那是 95^8 可能的组合，得出 6，634，204，312，890，625，或 6.6 千万亿个数字。)

假设有人试图用 [破解你的密码，典型的暴力破解攻击](https://www.4armed.com/blog/perform-mask-attack-hashcat/) 。假设他们每秒钟可以测试大约[310 亿个密码](https://www.michalspacek.com/cracking-passwords-from-the-mall.cz-dump) 。破解相当复杂的八个字符的密码最多需要 212903 秒。那是 3548 分钟，或者大约两天半。

现在，让我们花一分钟来讨论约束。假设你正在使用的服务*要求*你有一个八个字符的密码。艾布拉姆斯注意到，从混合密码中去掉了 70.6 万亿个密码，因为从单个字符长度到七个字符长度的每个密码现在都是无效的。这为破解工具节省了 2277 秒，或者将近 38 分钟。那不*太*坏了。

如果以安全的名义，你使用八个字符的密码(用于记忆)，而一个服务强迫你使用大写和小写字母、以及符号，那该怎么办？这样更安全，对吧？这是一个更复杂的密码，这使得让更难被攻击者破解？不完全是。正如艾布拉姆斯指出的，你刚刚将潜在密码池削减了 18.5%，删除了全小写密码等项目，例如。在我们的场景中，最多两天，系统就会嗅出你的密码。

如果一个服务也要求你在这个密码中有一个数字——你接受了它的建议并照做了，保持你的“c 复杂的】密码只有八个字符——你已经将暴力工具需要猜测的潜在密码减少了大约 41%。在我们的场景中，这将最长时间缩短到 34 小时，或者不到一天半。

Abrams 建议，不要担心让你的短密码更难被猜出或破解的最佳方法，而是选择一个更长的密码，因为即使服务有密码限制，它们的影响也会小得多:

> *“您可能已经注意到，长密码几乎没有影响。通常，对长密码施加限制也没有什么价值。这是因为密码中每增加一个字符，密码池就会呈指数级增长。仅使用小写字母的 16 个字符密码的组合是使用所有四种字符集的八个字符密码的 650 万倍。这意味着“toodlesmypoodles”将比“I81B@gle”更难破解*

你可能不应该使用三个单词的密码，而是坚持使用一个使用很多单词的密码——任何长度都可以——如果你走这条路的话。

更好的是，为您的密码管理应用程序使用长密码短语(这不仅仅是一句名言或相当常见的短语)，通过 [双因素身份验证](https://lifehacker.com/two-factor-authentication-isnt-enough-to-keep-your-acco-1827867557) (您从应用程序或其他硬件设备生成的令牌，而不是通过短信接收的登录代码)添加第二层安全保护，然后使用您的密码管理器为您的所有其他服务生成 16 个以上字符的密码，其中包含大小写字母、数字和符号。狂野一点。

如果你试图注册一个只允许你有一个带限制的短密码的东西——特别是如果你只需要使用一个数字——就要紧张了。如果你幸运的话，也许你也可以在那里建立 2FA，来增加一点安全保障。