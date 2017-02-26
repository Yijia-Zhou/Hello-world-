# 文献检索，learning by doing

本文针对英文文献检索，先简要介绍基本检索技巧，然后介绍几大常用检索网站，并有一些简单的实际检索操作引导。



## 通用检索技巧

- AND

  和（逻辑运算符），用和连接的关键词必须同时出现才会被检索到。

- OR

  或（逻辑运算符），用或连接的关键词只要出现一个即可被检索到。

- 括号

  改变逻辑运算顺序，同四则运算中括号的使用。

- 减号 / NOT 

  - 减号在谷歌中使用，代表搜索不包含后面的词的页面。使用这个指令时减号前面必须是空格，减号后面没有空格，紧跟着需要排除的词。
  - NOT（逻辑运算符）, 在 pubmed, Web of Science 等中使用，同样代表搜索不包含后面的词的页面。使用这个指令时 NOT 后面空格，接着是需要排除的词。

  ![img](http://mmbiz.qpic.cn/mmbiz_jpg/vxzG21TibxNPrpyXicUIMQ5kthmfQbGRicQVRJwjuJeQevvC4BtHbuuBcf6zXNBLtDYrh9yDFypZM6awb8vgsInSA/640?wx_fmt=jpeg&tp=webp&wxfrom=5&wx_lazy=1)

- 双引号

  双引号中的内容会作为一个整体关键词，必须整个原样出现才会被检索到。

  一图流：

  ![通用检索技巧.png](https://github.com/Yijia-Zhou/Hello-world-/blob/c8e9d64ac252faca27cbd78db270e05818209718/%E9%80%9A%E7%94%A8%E6%A3%80%E7%B4%A2%E6%8A%80%E5%B7%A7.png?raw=true)

- 星号
  星号\*是常用的通配符，可代表任何文字。

- **关键词选取**

  从英文文本看到东西想查自不必说，直接拿着看到的查就是；想查一些东西又只知道中文的情况下，推荐使用[知网翻译助手](http://dict.cnki.net/)翻成英文进行初步检索，然后快速查看一下检索结果，尝试从结果中寻找更加精确的英文词汇继续检索。



## 各种检索工具上手操练

### [Pubmed](https://www.ncbi.nlm.nih.gov/pubmed/)

美国国立卫生研究院(NIH)建立的生物医学数据库(ncbi)的论文搜索引擎，生物科学领域文献收录多，更新快，适合普通查找文献（与后两种的对比会说明原因）。拿眼下热度相当高的基因编辑作为例子，[在 pubmed 的搜索栏里敲上 gene editing 然后回车](https://www.ncbi.nlm.nih.gov/pubmed/?term=gene+editing)，把玩一下，改改排列方式(most recent / best match)和文章类型

![pubmed 修改.png](https://github.com/Yijia-Zhou/Hello-world-/blob/c8e9d64ac252faca27cbd78db270e05818209718/pubmed%20%E4%BF%AE%E6%94%B9.png?raw=true)

不过无论怎么改，搜出来的结果总是大多与 Crispr-Cas9 有关（毕竟大热），但如果想找找看除了 Crispr 还有啥基因编辑技术的话，就得[在检索式后面加上 NOT CRISPR*](https://www.ncbi.nlm.nih.gov/pubmed/?term=gene+editing+NOT+CRISPR*)（ Crispr 能配套的不止 Cas9, 有时候用 Crispr-Cas9 的研究也会偷懒少写，所以可以用上通配符\*），不少没怎么见过的基因编辑手段就都浮出水面啦（此处建议 Article types 选 Journal Article 以选出研究论文）。

于是我们看到了各种没怎么见过的基因编辑技术，比如 [single-stranded DNA oligonucleotides(ssODNs)](https://www.ncbi.nlm.nih.gov/pubmed/26402400), 如果感兴趣的话可以用这些作为关键词继续查下去。



#### [高级检索](https://www.ncbi.nlm.nih.gov/pubmed/advanced)

![pubmed advance search.png](https://github.com/Yijia-Zhou/Hello-world-/blob/c8e9d64ac252faca27cbd78db270e05818209718/pubmed%20advance%20search.png?raw=true)

pubmed 的高级搜索基本上就是字段搜索，通过 AND OR NOT 等逻辑运算将作者、期刊、出版时间等检索词生成一个较复杂精确的检索式，之后也可以手工编辑检索式。点开 All Fields 下拉菜单看看都有啥字段，然后试着创建个检索式玩玩吧O(∩_∩)O~



#### 彩蛋：各种各样的过滤器们

通过右上角的 [Sign in to NCBI ](https://www.ncbi.nlm.nih.gov/account/?back_url=https%3A%2F%2Fwww.ncbi.nlm.nih.gov%2Fpubmed%2F)注册/登录后，在 My NCBI 里可以创建自己的文献过滤规则，以后检索的时候可以一键过滤。具体做法参见[如何打造PubMed个人专属滤器？](http://mp.weixin.qq.com/s?__biz=MzA4MzU2NjUyNA==&mid=409746417&idx=1&sn=e3bde988cb80ea56384efbd8828f6c38&scene=21#wechat_redirect) 个人推荐 LinkOut 中的 F1000 Filter, 它所收录的是1000多位世界最好的生物学家所推荐的文章，当有一大堆相关文献不知道该读什么的时候通过 F1000 过滤一下往往有不错的效果。F1000 自己的数据库里还附有推荐人的评述，可以直接到其[官网](http://f1000.com/prime)查找。

![NCBI filters.png](https://github.com/Yijia-Zhou/Hello-world-/blob/c8e9d64ac252faca27cbd78db270e05818209718/NCBI%20filters.png?raw=true)

扩展：[PubMed检索小帮手：单篇文献匹配器（Single Citation Matcher）](http://mp.weixin.qq.com/s?__biz=MzA4MzU2NjUyNA==&mid=2693802748&idx=2&sn=16c4202d7d4481bb92b0945004e03701&scene=21#wechat_redirect)



### [Web of Science(WOS)](webofknowledge.com) & [Scope](https://www.scopus.com/home.uri)

基本的字段检索同 Pubmed 高级检索、高级检索则类似 Pubmed 高级检索生成的检索式，不多赘述。这俩的特点有 PubMed 不具备的引文检索，且检索结果可按学科分类。（由于检索结果无法直接通过网址进入，这俩就不放实例了）

![Paste_Image.png](http://upload-images.jianshu.io/upload_images/3072722-642e06a8900f4d46.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

可以查看并搜索文献的引用及被引用是这俩数据库最大的特点之一，除了本身的引文分析手段，WOS 的引用数据可导出到各种引用分析软件，如 [Hiscite](https://zhuanlan.zhihu.com/p/20902898), 对快速入门一个新领域很有帮助。

![WOS 精炼解锁结果.png](https://github.com/Yijia-Zhou/Hello-world-/blob/c8e9d64ac252faca27cbd78db270e05818209718/WOS%20%E7%B2%BE%E7%82%BC%E8%A7%A3%E9%94%81%E7%BB%93%E6%9E%9C.png?raw=true)

在检索结果中按学学科等筛选和进一步检索也是其较好用的功能。



### Google Scholar

谷歌学术是常用检索工具中收录范围最大、检索方式最全面的了，可进行基本检索、高级检索、可查看引用情况（但不能像 WOS & Scope 那样按引用数排列），而且是全文搜索（其它的基本都只搜索标题、作者等字段信息和摘要）。但由于一些原因，现在我们需要[使用一些手段](https://github.com/getlantern/lantern/blob/devel/README.md)才能使用了（或者通过[镜像](http://dir.scmor.com/google/)）。

为了方便和 Pubmed 对比，我们继续搜去掉 Crispr-Cas9 的基因编辑

 `gene editing -crispr*`(记得这里是用减号)

![Paste_Image.png](http://upload-images.jianshu.io/upload_images/3072722-4d5d71a9ee73f0b7.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

同是按相关性排序的话，个人比较喜欢谷歌学术的检索结果，把 Crispr 兴起之前的流行使用锌指蛋白编辑的技术和一些综述文章都搜出来了，对于新入行党还是很受用的。不过相对来说，左侧边栏里的筛选和排序选项就少很多了。至于每次检索的时候具体用哪个，就根据这仨各自的优点和个人偏好来定吧。



## 获取文献，不仅靠直接检索

除了直接搜索以外，在阅读文献的过程中（甚至在检索文献的过程中，利用几大检索网站的查看引文功能）往往会发现某篇被引用的文章非常适合自己阅读，这时不要犹豫赶紧保存到自己的阅读清单或者文献管理应用（学校买的 Note Express, 功能强大但收费的 [Endnote](http://cn.bing.com/search?q=endnote+-endnote.com), 免费好用的 [Mendeley](https://www.mendeley.com/) 等）。而如果想追踪某研究的最新进展，利用 WOS, Scope 或谷歌学术的功能查看引用了该研究的论文是最好使的办法了。

在各种检索网站中，各种 create alert, create RSS 或是邮件、RSS 图标总是会在页面某处出现，点击它们，一旦有符合你检索条件的最新文章出现，你就可以通过邮箱或者 [RSS 阅读器](http://blog.sciencenet.cn/blog-304685-371928.html)收到推送通知了（前面提到的追踪引用了某研究的论文也可以使用这种方法），十分惬意。此外，已经有一些专门的文献推送服务，[应对文献洪流有何秒招？ ](http://blog.sciencenet.cn/blog-41174-824993.html)这篇文章中有详细介绍。

#### 彩蛋

丁香园曾经办过一段时间["读文献谈心得"](http://cn.bing.com/search?q=%22%E8%AF%BB%E6%96%87%E7%8C%AE%E8%B0%88%E5%BF%83%E5%BE%97%22+site%3Adxy.cn)活动，质量颇高，可惜好像不久就无疾而终了。如果你也发现过这类高质量活动，请不吝于向周围同学们推荐哦~

