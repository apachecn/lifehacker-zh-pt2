# 更新这个 WordPress 插件来防止站点被接管

> 原文：<https://lifehacker.com/update-this-wordpress-plugin-to-prevent-a-site-takeover-1841429640>

安全研究人员发现了流行的 WordPress 插件 [代码片段](https://wordpress.org/plugins/code-snippets/) 的旧版本中存在的一个严重漏洞，该漏洞可能允许攻击者远程接管一个人的网站。该插件的开发者发布了一个补丁来修复这个漏洞，但仍有超过 20 万个网站面临风险。



代码片段允许 WordPress 站点运行少量的 PHP 代码来添加额外的功能，而不需要额外的插件，你甚至可以使用预先编写的代码来简化这个过程。对于那些可能没有编程技能来自己编写插件的人来说，这是一个有用的工具，但正如 [Threat Post 在其漏洞报告中解释的](https://threatpost.com/200k-wordpress-sites-vulnerable-to-plugin-flaw/152415/) ，代码片段的导入工具未能首先检查代码的源代码和安全性，这意味着用户可能会无意中导入并运行恶意代码。这可能会使他们的网站遭受各种攻击，包括允许黑客在没有管理员访问的情况下执行命令。

 [https://lifehacker.com/embed/inset/iframe?id=youtube-video-tuGog329Ayg&start=0](https://lifehacker.com/embed/inset/iframe?id=youtube-video-tuGog329Ayg&start=0) 

这是一个可怕的错误，但它是可以修复的。如果你的 WordPress 页面使用了代码片段，你应该马上更新插件——尤其是在添加或运行任何新代码到你的站点之前。你可以通过登录你的网站后台，然后从 WordPress 仪表盘进入“更新”部分来获取更新。你也可以从 [代码片段的 WordPress 插件](https://wordpress.org/plugins/code-snippets/) 页面下载并安装最新版本。