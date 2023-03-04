# Image

## 介绍

这是一个使用gitee自建的简单图床。

## 使用

- 使用PigGo来上传（最好还是不用了，PigGo不能管理图片，也可能是我不太会用）
- 在本地文件中使用Git来管理（可以来熟悉Git的命令）

>Tip：
>
>在仓库中查看图片 例子：https://gitee.com/charon-33/image/blob/master/git%E5%91%BD%E4%BB%A4.jpg
>
>真正引用图片 例子：https://gitee.com/charon-33/image/raw/master/git%E5%91%BD%E4%BB%A4.jpg
>
>（就是把链接中的`blob`改为`raw`）
>
>Markdown中插入网络图片的例子 `![网页引用](https://gitee.com/charon-33/image/raw/master/git%E5%91%BD%E4%BB%A4.jpg)`

> <font color='orange'>有一个问题：当文件被人修改且提交后，另一个人也同时用原来的数据作更改，但晚提交了，这时如何解决冲突？</font>

> **VM编辑器（Linux）**
>
> 1. 进入编辑器后，我们先按“i”，即切换到“插入”状态。就可以通过上下左右移动光标或空格、退格及回车等进行编辑内容，和Windows是一样的了。
>
> 2、退出 vim 编辑器的方法及区别
>
> 当文本编辑结束之后，通常需要退出编辑器，退出编辑器又分为4种情况：保存退出、正常退出、不保存退出及强制退出。
>
> ① 保存退出
>
> 当我们编辑或修改好了文件内容，我们当然要保存并退出然后下一步了。这时，<font color='orange'>我们要按键盘左上角的“ESC”</font>，留意到了没有？左下角的插入状态不见了，此时进入了命令模式
>
> 然后这时，我们<font color='orange'>输入“:wq”</font>，意思如下：
>
> w：write，写入
>
> q：quit，退出
>
> 再回车，就保存退出了。
>
> 其实，保存退出还有二个方法：
>
> A：<font color='orange'>在最后输入命令时，直接输入“x”</font>，也是一样的，即：x=wq。
>
> B：最快捷的方法：<font color='orange'>按了ESC后，直接按 shift+zz</font> 或者切换到大写模式按 ZZ ，就可以保存退出了，即是按两下大写的Z。
>
> 我们可以用查看命令 cat 查看其内容：cat /usr/local/con.cfg。
>
> ② 正常退出
>
> 正常退出有个前提条件是：打开的文本文件在内容上<font color='orange'>没有被改动过</font>。按了ESC后再输入“冒号”，在输入命令时，直接输入“q”。
>
> ③ 不保存退出
>
> 很多时候打开了文件或者修改了一些地方，才发现错了，需要不保存退出。先按ESC，再输入“:q!”。
>
> ④ 强制退出
>
> 不太常用的操作，先按ESC，再按“冒号”，在输入命令时，直接输入“!”，退出后，会有提示！
>
> 注意：Linux 命令都要小写！

## 特技

1.  使用 Readme\_XXX.md 来支持不同的语言，例如 Readme\_en.md, Readme\_zh.md
2.  Gitee 官方博客 [blog.gitee.com](https://blog.gitee.com)
3.  你可以 [https://gitee.com/explore](https://gitee.com/explore) 这个地址来了解 Gitee 上的优秀开源项目
4.  [GVP](https://gitee.com/gvp) 全称是 Gitee 最有价值开源项目，是综合评定出的优秀开源项目
5.  Gitee 官方提供的使用手册 [https://gitee.com/help](https://gitee.com/help)
6.  Gitee 封面人物是一档用来展示 Gitee 会员风采的栏目 [https://gitee.com/gitee-stars/](https://gitee.com/gitee-stars/)
