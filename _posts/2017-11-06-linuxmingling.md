---
layout: post
title: Linux开源下有哪些好玩的命令？
date: 2017-11-06
categories: blog
tags: [Linux好玩命令]
description: Email:Jning@beamer.top
---



1. Star Wars (telnet)

telnet是基于Telnet协议的远程登录客户端程序,经常用来远程登录服务器.但现在我们要用它来观看星球大战:

telnet towel.blinkenlights.nl



2. sl

我们经常用ls来列出当前目录下的所有文件,ls反过来也是一个有趣的命令,会出现一个移动的小火车.如果输入后提示"没有该命令",那就需要安装它.

apt-get install sl                 (In Debian like OS)yum -y install sl                 (In Red Hat like OS)
sl


还可以给别人搞恶作剧: alias ls=sl
这样别人使用 ls 列出目录和文件的时候,却出现一个小火车,那滋味一定很酸爽哈哈哈哈!

3. fortune

这个命令会随机输出有趣的话,比如名言或笑话.同样需要先安装.
apt-get install fortune         (for aptitude based system)yum install fortune                 (for yum based system)
jh@linux:~$ fortuneThere is no distinctly native American criminal class except Congress.        -- Mark Twain

还有 fortune-zh , 输出的是中文内容,可能是一些诗词,也可能是一些有趣的句子.

4. Cowsay

这是一只可以说话的 ASCII Cow.


还可以把 cowsay 和 fortune 结合到一起使用:


jh@linux:~$ fortune -s | cowsay -f duck ___________________________________/ 《闺怨》 作者：王昌龄       \\ 闺中少妇不知愁，春日凝妆上翠楼。 忽见陌头杨柳色，悔教夫婿觅封侯。 / ----------------------------------- \  \   \ >()_      (__)__ _

这只cow不仅会说话,还会思考,不信你看:

jh@linux:~$ cowthink I am thinking! ________________( I am thinking! ) ----------------        o   ^__^         o  (oo)\_______            (__)\       )\/\                ||----w |                ||     ||


还可通过cowsay -l  查看其它动物的名字，然后-f跟上动物名，如

jh@linux:~$ cowsay -f ghostbusters Who you Gonna Call ____________________< Who you Gonna Call > --------------------          \           \            \          __---__                    _-       /--______               __--( /     \ )XXXXXXXXXXX\v.             .-XXX(   O   O  )XXXXXXXXXXXXXXX-            /XXX(       U     )        XXXXXXX\          /XXXXX(              )--_  XXXXXXXXXXX\         /XXXXX/ (      O     )   XXXXXX   \XXXXX\         XXXXX/   /            XXXXXX   \__ \XXXXX         XXXXXX__/          XXXXXX         \__----> ---___  XXX__/          XXXXXX      \__         /   \-  --__/   ___/\  XXXXXX            /  ___--/=    \-\    ___/    XXXXXX              '--- XXXXXX       \-\/XXX\ XXXXXX                      /XXXXX         \XXXXXXXXX   \                    /XXXXX/          \XXXXXX      >                 _/XXXXX/            \XXXXX--__/              __-- XXXX/             -XXXXXXXX---------------  XXXXXX-                \XXXXXXXXXXXXXXXXXXXXXXXXXX/                  ""VXXXXXXXXXXXXXXXXXXV""

还可以这样玩,每次图形和文字都不一样:

jh@linux:~$ cowsay -f "$(ls /usr/share/cowsay/cows | sort -R | head -1)" "$(fortune -s)" _______________________________________/ Q: What's the difference betweeen USL \| and the Graf Zeppelin? A: The Graf    || Zeppelin represented cutting edge     |\ technology for its time.              / ---------------------------------------      \                    / \  //\       \    |\___/|      /   \//  \\            /0  0  \__  /    //  | \ \               /     /  \/_/    //   |  \  \             @_^_@'/   \/_   //    |   \   \            //_^_/     \/_ //     |    \    \        ( //) |        \///      |     \     \      ( / /) _|_ /   )  //       |      \     _\    ( // /) '/,_ _ _/  ( ; -.    |    _ _\.-~        .-~~~^-.  (( / / )) ,-{        _      `-.|.-~-.           .~         `. (( // / ))  '/\      /                 ~-. _ .-~      .-~^-.  \ (( /// ))      `.   {            }                   /      \  \  (( / ))     .----~-.\        \-'                 .~         \  `. \^-.             ///.----..>        \             _ -~             `.  ^-`  ^-_               ///-._ _ _ _ _ _ _}^ - - - - ~                     ~-- ,.-~                                                                  /.-~jh@linux:~$ cowsay -f "$(ls /usr/share/cowsay/cows | sort -R | head -1)" "$(fortune -s)" _____________________________________/ You will be awarded the Nobel Peace \\ Prize... posthumously.              / -------------------------------------   \             \    \             \_     \             \\      \             \\/\       \            _\\/        \         /   -\         \      /  oo   -\          \   /           \             |    ---\    -\             \--/     \     \                       |      -\                        \       -\         -------------\    /-\                         \        \-------/              ---/    \                          \                                  |\   \                           |                                 / |  |                           \                                |  \  |                            |                              /    \ |                            |                             /     \ |                             \                             \     \|                              -              /--------\    |      o                               \+   +---------          \   |                                |   |                   |   \                                |   |                    \   |                                |   |                    |   \                                |   |                     \   |                                 \  |                     |   |                                 |  |                      \  \                                 |  |                      |   |                                 +--+                       ---+



4. xcowsay

如果你觉得 ASCII Cow 太单调了,这里还有一头图形化的Cow.


5.cmatrix
这是屏保,没错,就是屏保!从上往下输出无尽的字符串,类似<<黑客帝国>>中的矩阵效果.


6.yes

yes命令会一直重复输出字符串,用Ctrl+c终止.
jh@linux:~$ yes hello,worldhello,worldhello,worldhello,worldhello,worldhello,worldhello,worldhello,world

7.toilet

输出由ASCII码组成的艺术字.


如果觉得白色不好看,还可以通过参数设置字体和颜色.

8. figlet

另一款在终端将字符进行图形化输出的软件.
jh@linux:~$ figlet linux  _ _                  | (_)_ __  _   ___  __| | | '_ \| | | \ \/ /| | | | | | |_| |>  < |_|_|_| |_|\__,_/_/\_\jh@linux:~$ figlet linux -f script _                         | | o                      | |     _  _               |/  |  / |/ |  |   |  /\/  |__/|_/  |  |_/ \_/|_/ /\_/                                                      jh@linux:~$ figlet linux -f bubble  _   _   _   _   _   / \ / \ / \ / \ / \ ( l | i | n | u | x ) \_/ \_/ \_/ \_/ \_/ jh@linux:~$ figlet linux -f shadow |_)                    | | __ \  |   |\ \  /  | | |   | |   | `  <  _|_|_|  _|\__,_| _/\_\                        jh@linux:~$ figlet linux -f lean                                              _/  _/                                   _/      _/_/_/    _/    _/  _/    _/     _/  _/  _/    _/  _/    _/    _/_/       _/  _/  _/    _/  _/    _/  _/    _/     _/  _/  _/    _/    _/_/_/  _/    _/   


9. oneko

输入命令后会屏幕上会出现一直喵星人,鼠标移到哪它就跟到哪,鼠标不动的时候它就睡觉哈哈.


9. xeyes

输入它,屏幕上会出现一双眼睛,一直盯着你看,你的鼠标移到哪,它就盯到哪.


10. cal

打印日历.


11. factor

求一个数的所有因素.
jh@linux:~$ factor1212: 2 2 39998347823 9998347823: 193 2207 2347332412343241234: 2 1620617


12. espeak 
该命令可以阅读所输入的英语字符.

espeak 'hell, world'


13. aafire

该命令会输出由ASCII码组成的火焰状的字符,让屏幕燃烧起来.

apt-get install libaa-binaafire


14.bb

一款不一样的音乐播放器

sudo apg-get install bbbb


15.rev 

字符串翻转.
jh@linux:~$ revwhat ?? tahwthis is coollooc si siht


16.pi

输出pi后面任意长度小数位数.
jh@linux:~$ pi 503.1415926535897932384626433832795028841971693993751


17.rig

生成随机的正真的假冒的身份地址.
jh@linux:~$ rigKristin Schwartz243 Fairfield RdMentor, OH  44060(216) xxx-xxxx

18. 乘法口诀表

jh@linux:~$ for i in {1..9}; do for j in $(seq 1 $i); do echo -ne $i×$j=$((i*j))\\t;done; echo;done1×1=1        2×1=2        2×2=4        3×1=3        3×2=6        3×3=9        4×1=4        4×2=8        4×3=12        4×4=16        5×1=5        5×2=10        5×3=15        5×4=20        5×5=25        6×1=6        6×2=12        6×3=18        6×4=24        6×5=30        6×6=36        7×1=7        7×2=14        7×3=21        7×4=28        7×5=35        7×6=42        7×7=49        8×1=8        8×2=16        8×3=24        8×4=32        8×5=40        8×6=48        8×7=56        8×8=64        9×1=9        9×2=18        9×3=27        9×4=36        9×5=45        9×6=54        9×7=63        9×8=72        9×9=81        
jh@linux:~$ for i in {1..12}; do for j in $(seq 1 $i); do echo -ne $iÃ—$j=$((i*j))\\t;done; echo;done 1Ã—1=1    2Ã—1=2    2Ã—2=4    3Ã—1=3    3Ã—2=6    3Ã—3=9    4Ã—1=4    4Ã—2=8    4Ã—3=12    4Ã—4=16    5Ã—1=5    5Ã—2=10    5Ã—3=15    5Ã—4=20    5Ã—5=25    6Ã—1=6    6Ã—2=12    6Ã—3=18    6Ã—4=24    6Ã—5=30    6Ã—6=36    7Ã—1=7    7Ã—2=14    7Ã—3=21    7Ã—4=28    7Ã—5=35    7Ã—6=42    7Ã—7=49    8Ã—1=8    8Ã—2=16    8Ã—3=24    8Ã—4=32    8Ã—5=40    8Ã—6=48    8Ã—7=56    8Ã—8=64    9Ã—1=9    9Ã—2=18    9Ã—3=27    9Ã—4=36    9Ã—5=45    9Ã—6=54    9Ã—7=63    9Ã—8=72    9Ã—9=81    10Ã—1=10    10Ã—2=20    10Ã—3=30    10Ã—4=40    10Ã—5=50    10Ã—6=60    10Ã—7=70    10Ã—8=80    10Ã—9=90    10Ã—10=100    11Ã—1=11    11Ã—2=22    11Ã—3=33    11Ã—4=44    11Ã—5=55    11Ã—6=66    11Ã—7=77    11Ã—8=88    11Ã—9=99    11Ã—10=110    11Ã—11=121    12Ã—1=12    12Ã—2=24    12Ã—3=36    12Ã—4=48    12Ã—5=60    12Ã—6=72    12Ã—7=84    12Ã—8=96    12Ã—9=108    12Ã—10=120    12Ã—11=132    12Ã—12=144    

19. lolcat 

让字符变成彩色的.



20.screenfetch

经 @谷月轩 提醒,添加了screenfetch.

它可以在终端上生成漂亮的文本系统信息和ASCII艺术的发行版LOGO.

安装使用步骤如下:

#使用命令克隆screenFectch库:git clone git://github.com/KittyKatt/screenFetch.git screenfetch#复制文件到/usr/bin/目录，并设置执行权限:cp screenfetch/screenfetch-dev /usr/bin/screenfetchchmod +x /usr/bin/screenfetch#运行screenFectch:screenfetch



-----------------------------------
然后再补充一点实用的.那必然是  Vim 啊!

首先是vim插件,推荐使用 spf13/spf13-vim · GitHub  适合没时间折腾的懒人.

然后是浏览器的vim插件,firefox的Vimperator , chrome的Vimium  ,彻底解放鼠标!



21.tpp
好,文艺程序员终极装X杀器来了!!!这是一个在终端上演示PPT的程序,要是哪天演讲的时候用它来展示,那真是狂拽酷炫叼炸天,分分钟惊艳全场!

废话不多说,先上两张图:

那要怎么使用呢?
首先要安装: 
sudo apt-get install tpp
然后自己制作一个tpp演示文件,具体格式可在这里看到: Nico Golde's website

这里贴一段我上面的tpp文件代码吧,这是一个最简单的tpp文件了:
--author Jiang Hang--title A simple example--date 2015.06.25--bgcolor redThis is the abstract of this presentation.It may consist of zero or more lines, and may be as long as you want.--newpage agenda--heading Agenda  * Introduction  * Concept  * Implementation  * Comparison with other implementations  * Conclusions--newpage intro--heading IntroductionThis is the introduction. And below, that's source code.--beginoutput#include <stdio.h>int main(void) {  puts("Hello World!");  return 0;}--endoutput

然后保存为 test.tpp, 再 tpp test.pp 就可以播放 ppt 了.各种炫酷的效果,只有想不到没有做不到,代码的力量是无穷的!剩下的就自己去研究吧哈哈哈

22. slurm
这是一个查看网络流量的一个工具.安装后,先使用 iwconfig 查看网卡,然后 slurm -i wlan0
.  -i后面的参数是网卡,回车后会出现下面的样子:

23. iftop & iptraf

再推荐两个查看网络流量的工具,iftop 和 iptraf :


24.htop & iotop

htop 和 iotop 用来查看进程，内存和IO负载。



25.linuxlogo

这个大多数应该都知道吧

26.moo
昨天漏了这个命令,现在补上.


27. ~~lvoe~~ (拼错了，应该是 love =，=缺爱啊)


28.在终端上网

在终端上网需要安装一个 w3m .
sudo apt-get install w3m w3m-img  w3m www.zhihu.com

在Ubuntu的Terminal上无法显示图片,在xterm上可以.

29.script & scriptreplay

script 可以整个终端会话的所有操作和输出录制下来,并可以通过 scriptreplay 进行播放. 在你需要将你的在终端优雅的操作展示给别人看的时候,script就非常有用了!

录制命令: 
script -t 2>example.time -a example.txt
播放命令:
scriptreplay example.time example.txt

简单解释一下这行命令:
-t是把时间数据输出到标准错误(standard error), 所以这里使用2>example.time  把数据转向到example.time这个文件当中.


-a 选项则指定输出录制的文件.


在录制过程中,使用 exit 结束录制过程.


script命令没有图片不好截图因为它是动态的,这个这个最终效果也真的非常华丽,用过的人才会懂!




---

[关于我](http://beamer.top/about/)

这里有我的个人简介：[关于我](http://beamer.top/about/)

如果你想看到我最新的文章，可以关注我的另一个私人博客「lemaden520」[点此进入](https://liuning.vip/)。