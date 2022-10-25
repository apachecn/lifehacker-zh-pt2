# 注意 Lastpass 新的注销错误

> 原文:[https://life hacker . com/watch-out-for-lastpass-new-log-off-bug-1841519478](https://lifehacker.com/watch-out-for-lastpass-new-log-off-bug-1841519478)

许多 LastPass 用户正在该公司的论坛上抱怨一个非常不幸的错误，该错误影响了其扩展的自动注销功能——这是一种你总是想启用的备份安全措施。

Watch

据报道，这个漏洞似乎不是特定于平台的:Windows 和 macOS 上的 Firefox、Chrome 和 Brave 用户都加入了描述 LastPass 的“x 分钟不活动后注销”如何停止工作的线程。他们对这个问题不满意。正如 [一位用户写的](https://forums.lastpass.com/viewtopic.php?f=12&t=361995&start=20#p1203415) :

> “我上周注意到了这一点，并在两台不同的电脑上证实了这一点。对我来说，这是一个巨大的安全问题。chrome 和 safari 上的 lastpass 扩展都明确声明它应该在 10 分钟后让我注销，但它没有。直到上周的某个时候。请 lastpass 解决这个问题，否则我会尝试另一个密码管理器。

LastPass 的代表在主要评论激增大约一周后加入了这个帖子，表明该公司正在通过更新 来修补这个问题。当我们发表这篇文章时，还没有可用的修复 ETA。

也不清楚到底是什么引发了这个 bug。我试图在我的 MacBook 上使用 Chrome 80 中的 LastPass 扩展来重现这个问题，但发现 LastPass 的自动注销设置工作得非常好。在我的 MacBook 上无所事事一分钟后，我打开设置让自己注销。然后我等了一分钟，LastPass 的图标从红色变成了灰色——我被注销了。

当我检查另一个设置“当所有浏览器关闭时注销”时，也发生了同样的情况。当我退出并重新打开 Chrome 时，我必须重新登录 LastPass。

然而，如果你使用 LastPass 的自动注销设置，你会想在你自己的系统上测试它们。如果他们不为你工作，你需要记住在你使用完 LastPass 后手动注销它。

虽然你应该*也*使用一些更强的认证机制(比如一个很好的密码或指纹)来防止入侵者在你离开时进入你的台式机或笔记本电脑，但确保你的密码管理器不会向坐在你键盘前的任何人放弃*你使用的每一次登录*可能是一件好事。事实上，这是最重要的。