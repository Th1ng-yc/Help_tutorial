## 批量给文件添加编号

```
批量给歌曲添加编号，如果数量比较少，我们可以通过手工的方式一个一个的添加编号，但是如果数量很大，一个一个的添加就很麻烦，这个我们用办公软件的excel实现，当然，你也可以用第三方软件实现。
```

## Step 1 

### 我们要给下面的这些歌曲加编号,如下图

![Image text](https://github.com/xiongcandehuzi/Help_tutorial/blob/master/Batch/image/01.png)

## Step 2 

### 我们用window+r打开“运行”对话框，输入cmd，进入cmd后，用cd进入到歌曲所在的目录，这里歌曲所在的目录是D盘下面的test目录，如下图

![Image text](https://github.com/xiongcandehuzi/Help_tutorial/blob/master/Batch/image/02.png)

## step 3 

### 进入到歌曲所在的目录后，我们敲入：dir /b ###  music.xls，如下图

![Image text](https://github.com/xiongcandehuzi/Help_tutorial/blob/master/Batch/image/03.png)

## step 4 

### 回车后，歌曲所在的目录里生成了一个music.xls文件，我们打开它，如下图

![Image text](https://github.com/xiongcandehuzi/Help_tutorial/blob/master/Batch/image/04.png)

![Image text](https://github.com/xiongcandehuzi/Help_tutorial/blob/master/Batch/image/05.png)

![Image text](https://github.com/xiongcandehuzi/Help_tutorial/blob/master/Batch/image/06.png)
## step 5 

### 打开“music.xls”文件后，把music.xls这一行删除，因为这个不是歌曲，然后在B列通过自动填充拉出编号，如下图

![Image text](https://github.com/xiongcandehuzi/Help_tutorial/blob/master/Batch/image/07.png)

## step 6 

### 编号完成后，我们把编号与歌曲合并，用excel的&符合进行合并，如下图

![Image text](https://github.com/xiongcandehuzi/Help_tutorial/blob/master/Batch/image/08.png)


## step 7 

### 编号与歌曲合并后，我们用同样的方法给A列的内容和C列的内容连接上双引号，如下图

![Image text](https://github.com/xiongcandehuzi/Help_tutorial/blob/master/Batch/image/09.png)

## step 8  

### 接下来，我们用命令行的ren把原文件名更改为合并后的文件名，如下图

![Image text](https://github.com/xiongcandehuzi/Help_tutorial/blob/master/Batch/image/10.png)

## step 9 

### 最后把H列复制，在歌曲所在的目录那里新建一个txt文本文档，把复制的内容粘贴在txt文本文档中，如下图

![Image text](https://github.com/xiongcandehuzi/Help_tutorial/blob/master/Batch/image/11.png)

## step 10 

### 保存粘贴的内容，把文本文档的扩展名改为bat，双击这个bat文件即可，如下图

![Image text](https://github.com/xiongcandehuzi/Help_tutorial/blob/master/Batch/image/12.png)

![Image text](https://github.com/xiongcandehuzi/Help_tutorial/blob/master/Batch/image/13.png)

### 批处理结束后，歌曲的文件名如图

![Image text](https://github.com/xiongcandehuzi/Help_tutorial/blob/master/Batch/image/15.png)

