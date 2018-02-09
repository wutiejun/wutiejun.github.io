Emacs使用日志（2018-02-09）
----

断断继续使用emacs有一段时间了，但每次都没有入门。想想，主要原因只有一个：有其它的依赖，总是可以使用其它的widnows工具可以替代。因此，一二再，再二三的放下了。

今天又找了一些文档，看一下emacs入门的内容，有些还记得，有些也忘记了。
想重新从emacs的演练工程中再次学习使用，想想，也没必要了，emacs的大概框架也知道了，能做什么也知道了，简单的操作也清楚，就是没有实际的使用以及坚持下来。

前天Linux-4.1.18版本做为lontem版本发布了，下载过来看了一下。再次遇到纠结的问题：
如果在windows下看代码， 大小写敏感问题，SI同步问题再次感觉到麻烦。
再次让我想在Linux下直接使用emacs看内核代码。
想想也是的，整个内核代码本身大部份是只读的，也不需要大量的修改，而初始化一个SI工作，快也要半小时。
如果使用Linux服务器上放代码，再使用Samba映射过来加载代码，更是慢的不想弄了。

因此，今天，把emacs看内核代码的工程再次弄好了，主要参考：

1、基础工具的安装：

https://techtooltip.wordpress.com/2012/01/06/how-to-integrate-emacs-cscope-to-browse-linux-kernel-source-code/

2、环境搭建：

http://martinezjavier.blogspot.my/2011/07/emacs-configuration-for-linux-kernel.html

3、另外再推荐一个emacs美女用户的blog:

http://sachachua.com/blog/category/emacs/

Good Luck for my emacs!
