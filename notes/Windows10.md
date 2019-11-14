Windows 10 LTSC 2019系统已经出了有一段时间了，今天本着好奇的心理，进行了安装尝试。总的来说用户体验还是挺好的，没有LTSB小娜那烦人的语音，没有应用商店乱七八糟的东西。给我的感觉简单就完事了。但是跟网上说的一样确实有卡顿现象。

接下来说下如何激活吧，

>首先在开始菜单旁边的搜索中输入CMD，右键以管理员身份运行。按顺序输入下面的字符

    slmgr -ipk M7XTQ-FN8P6-TTKYV-9D4CC-J462D
    slmgr -skms kms.03k.org
    slmgr -ato
    slmgr -dlv

>每当出现弹出窗体，点击确定即可。如下图所示——最后的结果

![tupian](http://ww1.sinaimg.cn/large/0080moZxgy1g8ro7hdh2wj311y0lctht.jpg)

>此时电脑右下角的未激活状态就消失了。