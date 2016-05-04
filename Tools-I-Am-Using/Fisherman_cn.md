<p align="center">
    <br>
    <img width="700" src="https://rawgit.com/fisherman/logo/master/fisherman-blue-white.svg" alt="Fisherman">
    <br>
    <br>
</p>
#前言
在介绍 [fisherman] 之前, 有必要先介绍下 [fish-shell] 。
[fish-shell] 按照他官网的介绍，自称是现代化的命令行终结者：）。
>Finally, a command line shell for the 90s.

>fish is a smart and user-friendly command line
shell for OS X, Linux, and the rest of the family.


那么它的特色是什么呢，我想每一个工程师，曾经必然是折腾过不过软件，从下载到编译再到安装，再到配置文件，最后成功运行。只有被配置玩过的人才明白，开箱即用是多么的用户友好。正如 [fish-shell] 自我介绍一样， [fish-shell] 就是一款对用户友好、开箱即用的 shell。不过 [fish-shell] 唯一被人诟病的是它是不兼容 bash 的， 它的语法是更具现代化的。不过忍者见忍，智者见智。         
如果你跟我一样很**懒**，并且知道自己在干什么，我还是推荐你尝试下 [fish-shell] 。

#介绍
在用 [fisherman] 之前， 我用过 [oh-my-zsh] 管理 zsh 的插件和主题，也用过 [oh-my-fish] 管理 [fish-shell] 的插件和主题。不过我实在是太懒了，懒得配置 [oh-my-zsh] 和 [oh-my-fish], 所以我最后选择了 [fisherman] 来管理 [fish-shell] 的插件和主题，当然有一点原因是我本身比较熟悉 [fisherman] 的代码，也是 [fisherman] 的维护者。`Eating your own dog food` 也是一种互联网文化：）。
就我懒的水平， [fisherman] 已足够简单，实乃懒人必备。


#安装     

````bash
[root@localhost ~]# cat /etc/issue
CentOS release 6.5 (Final)
Kernel \r on an \m
root@localhost ~# curl -Lo ~/.config/fish/functions/fisher.fish --create-dirs git.io/fisherman
````

就这么简单一行命令搞定。
默认的主题比较简单，来装个更简单的主题，嘿嘿。
````bash
fisher simple
````

个人再推荐几个常用插件：

1. *fzf*       
	`fisher fzf`：bash 的 CTRL + R 搜索功能
	
2. *z*      
	`fisher z`: cd 的替代品

你要问我为什么这么短，我只能说本来这东西就基本不用配置，作者也是跟我一样懒出新境界了才开发了 [fisherman], 哈哈。

#最后
就我个人而言，[fish-shell] 的开箱即用再加上 [fisherman] 的几个插件已经满足我懒的大部分需求了。如果你像我一样懒，我建议你试试 [fish-shell] + [fisherman] 的组合。
如果你有什么疑问，尽可在仓库下提交 issue, 我们目前有十几个各个国家的工程师在维护（嘿嘿）。

[fish-shell]: https://github.com/fish-shell/fish-shell
[fisherman]: http://fisherman.sh
[oh-my-zsh]: https://github.com/robbyrussell/oh-my-zsh
[oh-my-fish]: https://github.com/oh-my-fish/oh-my-fish
