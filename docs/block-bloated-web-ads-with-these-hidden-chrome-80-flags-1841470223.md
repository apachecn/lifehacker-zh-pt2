# 用这些隐藏的 Chrome 80 标志阻止臃肿的网络广告

> 原文：<https://lifehacker.com/block-bloated-web-ads-with-these-hidden-chrome-80-flags-1841470223>

Chrome 80 昨天下架了，通常的建议也适用。如果你的桌面浏览器还没有更新，或者你不确定，可以点击 Windows 浏览器右上角的三点图标或者 Mac 浏览器的“Chrome”菜单，访问它的“关于谷歌 Chrome”页面。



Chrome 80 有很多新功能，包括一个很大的变化，可以防止网站向你发送垃圾通知请求——默认情况下，这些都可以隐藏在 omnibar 的一个按钮下。要启用它，你必须首先在你的 omnibar 中输入 *chrome://flags* ，然后搜索**“更安静的通知权限提示”**启用那个标志，重启浏览器，然后访问访问**设置>站点设置** *(在“隐私与安全”下)* **>通知**。打开**“使用更安静的消息”**以停止被烦人的通知提示骚扰。

谷歌也在慢慢努力，通过在可能的情况下自动将音频和视频内容升级到 HTTPS，来消除混合的 HTTPS 内容。换句话说，网站将无法加载安全的 HTTPS 和不太安全的 HTTP 内容的混合体；如果音频和视频不能通过 HTTPS 加载，Chrome 会默认屏蔽它。你不需要为这个设置一个标志；仅供参考。

* * *

### 阻止使用太多系统资源的劣质广告

不过，我觉得最有趣的是另外两个 Chrome 特性，你也必须在 *chrome://flags* 中直接启用。第一个是**重度广告干预**，可以让你自动屏蔽任何占用你太多处理器或内存的恼人的网络广告。至于有用的隐藏功能，我会把这个放在我的列表的首位——假设你还没有使用广告拦截器。

* * *

### 开始对第三方浏览器 cookies 更加严格

 [https://lifehacker.com/embed/inset/iframe?id=youtube-video-GPz7onXjP_4&start=0](https://lifehacker.com/embed/inset/iframe?id=youtube-video-GPz7onXjP_4&start=0) 

谷歌还对 cookies 实施了一个新的分类系统，如果跨站点 cookies 没有将它们的 [相同站点属性](https://web.dev/samesite-cookies-explained/) 设置为“无”并使它们可以通过 HTTPS 访问，就会被屏蔽。所有未标记的 cookie 都被视为“lax”，因为它们只有在您浏览的域与 cookie 的域匹配时才有效。这些是 [的技术部分](https://9to5google.com/2019/04/26/google-chrome-cookies-secure-samesite/) ，至少。至于为什么这很重要，谷歌的改变可以帮助抵御有问题的跨站点攻击，正如 [CookiePro](https://www.cookiepro.com/blog/google-samesite-cookies/) 所详述的:

> *“让我们假设你通过他们的在线门户登录了你的银行账户。你有没有注意到有些网站会让你一直保持登录状态？那是因为一个会话 cookie——在你认证之后，网站已经在你的浏览器上设置了一个 cookie，允许你保持登录。当你在浏览一个不同的网站时，你点击了一条推文中的链接，看到了一个有趣的视频。不幸的是，该链接可能是跨站点请求伪造攻击(XSRF ),它会欺骗您的浏览器在您的银行登录会话中执行不需要的操作。*
> 
> 在 SameSite 之前，点击 XSRF 链接将执行交易，并附带到从您的银行生成的会话 cookie 上(这使您保持登录)。
> 
> 在 SameSite 之后，如果链接来自外部网站，浏览器将不允许将 cookie 添加到已经认证的网站。"

谷歌 [将在未来几周推出](https://www.chromium.org/updates/same-site) 对第三方 cookie 的新处理方式，但你可以在你的 Chrome 80 浏览器中抢先一步，拉起 *chrome://flags* 并启用**“默认相同网站 cookie”、**以及**没有相同网站的 cookie 必须是安全的。”**

虽然这种变化 [可能会破坏](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/AknSSyQTGYs/U4RVwbF2DwAJ) 你经常访问的几个网站，但不管怎样，这是一种即将到来的变化——你只是比其他人更早看到而已。

* * *

### 整理溢出的标签

这里有一个额外的功能，我害怕开始使用，因为我仍然有太多的打开标签。调出 *chrome://flags* 并搜索**标签组**打开它，重新启动你的浏览器，现在你可以右击你的任何标签，开始将它们组织成组。选择“添加到新组”，然后右键单击为您自动创建的彩色选项卡(组)，为其命名或更改颜色。