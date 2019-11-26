## 批量给文件添加编号

```
批量给歌曲添加编号，如果数量比较少，我们可以通过手工的方式一个一个的添加编号，但是如果数量很大，一个一个的添加就很麻烦，这个我们用办公软件的excel实现，当然，你也可以用第三方软件实现。
```

## Step 1 

### 我们要给下面的这些歌曲加编号,如下图

![01.png](http://ww1.sinaimg.cn/large/00810L9aly1g9bvdplhfoj30s20gjn0r.jpg)

## Step 2 

### 我们用window+r打开“运行”对话框，输入cmd，进入cmd后，用cd进入到歌曲所在的目录，这里歌曲所在的目录是D盘下面的test目录，如下图

![02.png](http://ww1.sinaimg.cn/large/00810L9aly1g9bvdxv2f6j30it0cawf9.jpg)

## step 3 

### 进入到歌曲所在的目录后，我们敲入：dir /b ###  music.xls，如下图

![03.png](http://ww1.sinaimg.cn/large/00810L9aly1g9bveb6synj30it07uaao.jpg)

## step 4 

### 回车后，歌曲所在的目录里生成了一个music.xls文件，我们打开它，如下图

![04.png](http://ww1.sinaimg.cn/large/00810L9aly1g9bvek48x1j30s20f1dje.jpg)

![05.png](http://ww1.sinaimg.cn/large/00810L9aly1g9bvek4n75j30kh03mwet.jpg)

![06.png](http://ww1.sinaimg.cn/large/00810L9aly1g9bvek6ebfj30g80eq0tj.jpg)
## step 5 

### 打开“music.xls”文件后，把music.xls这一行删除，因为这个不是歌曲，然后在B列通过自动填充拉出编号，如下图

![07.png](http://ww1.sinaimg.cn/large/00810L9aly1g9bvhrd3fcj30k20hpab2.jpg)

## step 6 

### 编号完成后，我们把编号与歌曲合并，用excel的&符合进行合并，如下图

![08.png](http://ww1.sinaimg.cn/large/00810L9aly1g9bvhr9eksj30jg05874c.jpg)


## step 7 

### 编号与歌曲合并后，我们用同样的方法给A列的内容和C列的内容连接上双引号，如下图

![09.png](http://ww1.sinaimg.cn/large/00810L9aly1g9bvhrcry1j30w709dab8.jpg)

## step 8  

### 接下来，我们用命令行的ren把原文件名更改为合并后的文件名，如下图

![10.png](http://ww1.sinaimg.cn/large/00810L9aly1g9bvhrbccqj31d60440t5.jpg)

## step 9 

### 最后把H列复制，在歌曲所在的目录那里新建一个txt文本文档，把复制的内容粘贴在txt文本文档中，如下图

![11.png](http://ww1.sinaimg.cn/large/00810L9aly1g9bvhrdeb3j30k60cpwg4.jpg)

## step 10 

### 保存粘贴的内容，把文本文档的扩展名改为bat，双击这个bat文件即可，如下图

![12.png](http://ww1.sinaimg.cn/large/00810L9aly1g9bvhrf1ozj30b00cgt9m.jpg)

![13.png](http://ww1.sinaimg.cn/large/00810L9aly1g9bvhrine5j30kt0f1jtz.jpg)

### 批处理结束后，歌曲的文件名如图

![15.png](http://ww1.sinaimg.cn/large/00810L9aly1g9bvhrhxg9j30s20f10w9.jpg)

