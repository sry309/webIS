-------
* 特性：H5新推出节点元素标签有section,article,aside
* 属性与方法：<article> 标签定义外部的内容。<br>
     article元素代表网站制作中的文档、页面或应用程序中独立的、完整的、可以独自被外部引用的内容。它可以是一篇博客或者报刊中的文章、一片论坛帖子、一段用户评论，或其它任何独立的内容。<br>
     除了内容部分，一个article元素通常用作它自己的标题，有时还有它自己脚注。<br>
     例如：<br>
     `<article>`<br>
      `<header>`<br>
        `<h1>标题</h1>`<br>
        `<p>发表日期：<time pubdate="pubdate">2011年7月10号</time></p>`<br>
      `</header>`<br>
     ` <footer>`<br>
       ` <p>w3cmm 版权所有</p>`<br>
      `</footer>`<br>
    ` </article>`<br>
  <section>元素描绘的是一个文档或者程序里的普通的section节。<br>
     section可以表示成一个小节，或者tab页面里的一个tab下的box块。<br>
     一个页面里可以拆分成多个section，分别代表introduction, news items和contact information。<br>
     例如：<br>
     `<section>`<br>
          `<h1>Ceremony</h1>`<br>
          `<p>Opening Procession</p>`<br>
          `<p>Speech by Validactorian</p>`<br>
          `<p>Speech by Class President</p>`<br>
          `<p>Presentation of Diplomas</p>`<br>
         `<p>Closing Speech by Headmaster</p>`<br>
     `</section>`<br>
  `<aside>`元素标签用来表示当前页面或文章的附属信息部分。<br>
     可以包含与当前页面或主要内容相关的引用、侧边栏、广告、nav元素组，以及其他类似的有别与主要内容的部分。<br>
     根据目前的规范，`<aside>`元素有两种使用方法：<br>
     被包含在`<article>`中作为主要内容的附属信息部分，其中的内容可以是与当前文章有关的引用、词汇列表等。<br>
     在`<article>`之外使用，作为页面或站点全局的附属信息部分；最典型的形式是侧边栏(sidebar)，其中的内容可以是友情链接、附属导航或广告单元等。
     
------
安全性：暂时只是发现是一个独立性的div父层，拥有资深独自的引用模式，相当于之前的有标志性的div。
    不过正因为新DOM具有强烈的独立性，在DOM文档中上下文显得十分具有逻辑性，和明显的关系性，让攻击者更加直接。 
    
------

