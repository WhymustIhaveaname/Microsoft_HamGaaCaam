# Microsoft_HamGaaCaan
我草windows也太没素质了，就跟流氓一样

### Windows 启动就覆盖 grub
电脑上自带一个 Windows，我又装了一个 Ubuntu，一直用的 Ubuntu 很久都没动过 Windows。今天启动到 Windows 结果再重启发现 grub 被覆盖了？！开机就直接进入 Windows。我草这也太没素质了，直接覆盖竞争对手的启动？

解决方法是，插入一个 Ubuntu 启动盘，
```
sudo add-apt-repository ppa:yannubuntu/boot-repair
sudo apt-get update
sudo apt-get install boot-repair
```
这是一个GUI软件，找到它的图标，点击启动，选 recommand repair, 最后有一个报错不用管， 等一会儿就好了。

今天又进入 Windows 果不其然又碰到了这个毛病， 但这次修复完头没了！不知道为什么，至今还是无头的呢。

最后，祝 Windows 和 整个Microsoft 公司冚家富贵。

参考文献：[Ubuntu与Windows10双系统引导问题](https://www.jianshu.com/p/b1255856423b)

