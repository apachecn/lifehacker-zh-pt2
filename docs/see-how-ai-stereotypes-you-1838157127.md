# 看 AI 怎么给你定型

> 原文：<https://lifehacker.com/see-how-ai-stereotypes-you-1838157127>

电脑认为它们知道你是谁。人工智能算法可以从图像中识别物体，甚至是人脸。但我们很少能看到面部识别算法的内幕。现在，有了 [ImageNet 轮盘](https://imagenet-roulette.paglen.com) ，我们可以看着一个 AI 妄下结论。它的一些猜测很搞笑，其他的……种族歧视。



ImageNet Roulette 是作为艺术和技术博物馆展览*【训练人类】*的 [的一部分而设计的，旨在向我们展示面部识别算法的混乱内部，否则我们可能会认为这些算法是直截了当和不带偏见的。它使用人工智能研究中使用的大型标准数据库中的数据。上传一张照片，算法会显示它认为你是什么。我的第一张自拍被贴上了“不吸烟者”的标签另一个被贴上了“脸”的标签我们的主编被贴上了“心理语言学家”的标签我们的社会编辑被贴上了“勤奋、刻苦、书呆子、书呆子、呆子”的标签无害的乐趣，对不对？](https://www.fastcompany.com/90400613/who-does-ai-think-you-are-this-groundbreaking-new-exhibit-will-show-you)

但后来我试着在较暗的光线下照了一张自己的照片，结果显示“黑人，黑人，黑人，黑人，黑人”。事实上，这似乎是人工智能对任何深色皮肤的人的标签。更糟糕的是:在 twitter 上讨论这个工具的帖子中，有色人种总是被贴上“黑白混血儿”这样的标签，还有一些绝对不好玩的标签，比如“孤儿”和“强奸嫌疑人”。

 [https://lifehacker.com/embed/inset/iframe?id=twitter-1173595483186634752&autosize=1](https://lifehacker.com/embed/inset/iframe?id=twitter-1173595483186634752&autosize=1) 

这些类别在原始的 ImageNet/WordNet 数据库中，不是 ImageNet 轮盘赌工具的制作者添加的。下面是后者的说明:

> ImageNet Roulette 定期以可疑和残酷的方式对人进行分类。这是因为基础训练数据包含那些类别(以及被标记了那些类别的人的照片)。我们没有让基础训练数据负责这些分类。我们从一个名为 ImageNet 的流行数据集导入了类别和训练图像，该数据集由普林斯顿大学和斯坦福大学创建，是图像分类和对象检测中使用的标准基准。

> ImageNet Roulette 在一定程度上是为了展示各种各样的政治是如何通过技术系统传播的，而这些系统的创造者往往甚至没有意识到它们。

### 这些标签从何而来？

该工具基于 ImageNet，这是一个图像和标签数据库，过去是，现在仍然是图像识别算法最大和最容易访问的训练数据源之一。正如 Quartz报道的那样，它是从网上收集的图像组装而成的，并主要由土耳其机械工人标记——这些人为了几分钱而对图像进行集体分类。

 [https://lifehacker.com/embed/inset/iframe?id=twitter-1173668824329203712&autosize=1](https://lifehacker.com/embed/inset/iframe?id=twitter-1173668824329203712&autosize=1) 

因为 ImageNet 的制作者并不拥有他们收集的照片，他们不能就这么把照片给出去。但是如果你很好奇， [你可以查找这些照片的标签](http://image-net.org/explore.php?wnid=n10488656) ，得到这些照片原始来源的网址列表。比如“人，个体，某人，某人，某人，凡人，灵魂”>“科学家”>“语言学家，语言学家”>“心理语言学家”引出 [这一列照片](http://www.image-net.org/api/text/imagenet.synset.geturls?wnid=n10488656) ，很多好像都是来自大学教工网站。

 [https://lifehacker.com/embed/inset/iframe?id=twitter-1173548091754078208&autosize=1](https://lifehacker.com/embed/inset/iframe?id=twitter-1173548091754078208&autosize=1) 

浏览这些图片可以让我们一窥这里发生了什么。心理语言学家倾向于在那种教员头像照中的白人。如果你的照片看起来像他们的，你可能会被贴上心理语言学家的标签。同样，其他标签取决于您与带有这些标签的训练图像的相似程度。如果你是秃头，你可能会被贴上光头的标签。如果你皮肤黝黑，衣着花哨，你可能会被贴上穿着非洲礼仪服装的标签。

 [https://lifehacker.com/embed/inset/iframe?id=twitter-1173570307837386753&autosize=1](https://lifehacker.com/embed/inset/iframe?id=twitter-1173570307837386753&autosize=1) 

ImageNet 远远不是一个不带偏见的客观算法，它反映了其创作者收集的图像中的偏见，反映了产生这些图像的社会中的偏见，反映了 mTurk 工人的思想中的偏见，反映了为标签提供单词的字典中的偏见。很久以前，一些人或计算机将“blackamoor”放入在线词典，但从那时起，许多人肯定在他们的人工智能标签中看到过“blackamoor”(在 2019 年！)也没有说，哇，把这个去掉吧。是的， [算法可以是种族主义者和性别歧视者](https://lifehacker.com/what-makes-an-artificial-intelligence-racist-and-sexist-1796990621) ，因为它们是从观察我们中学到的，好吗？他们从观察我们中学到的。