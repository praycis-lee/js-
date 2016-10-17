js语法总结
原来Github上的README.md文件这么有意思——Markdown语言详解

转自

http://blog.csdn.NET/zhaokaiqiang1992/article/details/41349819

之前一直在使用github，也在上面分享了不少的项目和Demo，每次创建新项目的时候，使用的都是默认的README.md文件，也不曾对这个文件有过什么了解。但是在看到别人写的项目的README.md里面竟然有图片、链接什么的，就感到很好奇，这效果是什么加上去的？于是便查了一下资料，结果，竟迁出了一门从来没有了解过的语言— —Markdown！
    github上的README.md文件就是使用的Markdown语言编写的，我们先简单介绍下这门语言的来龙去脉，然后再介绍一些基本的语法和使用。

    1.来龙去脉和语法特点
    Markdown 是一种轻量级标记语言，创始人为约翰·格鲁伯（John Gruber）。它允许人们“使用易读易写的纯文本格式编写文档，然后转换成有效的XHTML(或者HTML)文档”。这种语言吸收了很多在电子邮件中已有的纯文本标记的特性。

   Markdown 的目标是实现「易读易写」。可读性，无论如何，都是最重要的。一份使用 Markdown 格式撰写的文件应该可以直接以纯文本发布，并且看起来不会像是由许多标签或是格式指令所构成。Markdown 语法受到一些既有 text-to-HTML 格式的影响，包括Setext、atx、Textile、reStructuredText、Grutatext 和 EtText，而最大灵感来源其实是纯文本电子邮件的格式。总之， Markdown 的语法全由一些符号所组成，这些符号经过精挑细选，其作用一目了然。比如：在文字两旁加上星号，看起来就像*强调*。Markdown 的列表看起来，嗯，就是列表。Markdown 的区块引用看起来就真的像是引用一段文字，就像你曾在电子邮件中见过的那样。

    Markdown 语法的目标是：成为一种适用于网络的书写语言。Markdown 不是想要取代 HTML，甚至也没有要和它相近，它的语法种类很少，只对应 HTML 标记的一小部分。Markdown 的构想不是要使得 HTML 文档更容易书写。在我看来， HTML 已经很容易写了。Markdown 的理念是，能让文档更容易读、写和随意改。HTML 是一种发布的格式，Markdown 是一种书写的格式。就这样，Markdown 的格式语法只涵盖纯文本可以涵盖的范围。

    正是因为Markdown的这些特点，而且功能比纯文本更强，因此有很多人用它写博客。世界上最流行的博客平台WordPress和大型CMS如joomla、drupal都能很好的支持Markdown。

          2.编辑软件
    如果我们要写Markdown代码的话，我们首先需要一个编辑器，因为我使用的是Mac，所以推荐使用Mou，非常的强大，非常的好用。
    下面是Mou的界面，左边是Markdown代码，右边是实时的展示效果，而且可以选择不同的主题色，非常的漂亮！



    当然，如果你使用的是其他的平台的话，你可以选择在线的编辑器，效果也非常棒。
    给出两个在线的Markdown编辑器
    http://mahua.jser.me/
    http://maxiang.info/