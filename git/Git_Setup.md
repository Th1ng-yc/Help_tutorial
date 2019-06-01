﻿# Git 中文安装教程

## Step 1 Information

**信息**

![](https://github.com/xiezongnan/Summarize/blob/master/git/images/setup/1.jpg)


*Please read the following important information before continuing*

***继续之前，请阅读以下重要信息***





## Step 2 Select Destination Location

**选择安装位置**

![](https://github.com/xiezongnan/Summarize/blob/master/git/images/setup/2.jpg)



## Step 3 Select Components

**选择组件**

![](https://github.com/xiezongnan/Summarize/blob/master/git/images/setup/3.jpg)



**Additional icons** 附加图标

​	**On the Desktop** 在桌面上



**Windows Explorer integration**  Windows资源管理器集成**==鼠标右键==**菜单

​	**Git Bash Here**

​	**Git GUI Here**



**Git LFS (Large File Support)** 

大文件支持



**Associate .git* configuration files with the default text editor** 

将 .git 配置文件与默认文本编辑器相关联



**Associate .sh files to be run with Bash**  

将.sh文件关联到Bash运行



**Use a TrueType font in all console windows** 

在所有控制台窗口中使用TrueType字体



**Check daily for Git for Windows updates** 

每天检查Git是否有Windows更新





## Step 4 Select Strat Menu Folder

**创建开始菜单目录**

![](https://github.com/xiezongnan/Summarize/blob/master/git/images/setup/4.jpg)





## Step 5 Choosing the default editor used by Git

**选择Git使用的默认编辑器**

![](https://github.com/xiezongnan/Summarize/blob/master/git/images/setup/5.jpg)



**Use the Nano editor by default**

默认使用 Nano 编辑器



**Use Vim (The ubiquitous text editor) as Git's default editor**

使用 Vim 作为 Git 的默认编辑器



**Use Notepad++ as Git's default editor**

使用 Notepad++ 作为 Git 的默认编辑器



**Use Visual Studio Code as Git's default editor**

使用 Visual Studio Code 作为 Git 的默认编辑器



## Step 6 Adjusting your PATH environment

![](https://github.com/xiezongnan/Summarize/blob/master/git/images/setup/6.jpg)



**配置PATH环境**

**Use Git from Git Bash only**

*This is the safest choice as your PATH will not be modified at all.You will only be able to use the Git command line tools form Git Bash.*

***这是最安全的选择，因为您的PATH根本不会被修改。您只能使用 Git Bash 的 Git 命令行工具。***



**Use Git from the Windows Command Prompt**

*This option is considered safe as it only adds some minimal Git wrappers to your PATH to avoid cluttering your environment with optional Unix tools . You will be able to use Git from both Git Bash and the Windows Command Prompt.*

***这个选项被认为是安全的，因为它只向PATH添加一些最小的 Git包，以避免使用可选的Unix工具混淆环境。 您将能够从 Git Bash 和 Windows 命令提示符中使用 Git。***



**Use Git and optional Unix tools from the Windows Command Prompt**

从Windows命令提示符使用Git和可选的Unix工具

*Both Git and the optional Unix tools will be added to you PATH*

***Git和可选的Unix工具都将添加到您计算机的 PATH 中***

*Warning:This will override Windows tools like "find and sort".Only use this option if you understand the implications.*

***警告：这将覆盖Windows工具，如 “ find 和 sort ”。只有在了解其含义后才使用此选项。***





## Step 7 Choosing HTTPS transport backend

**选择HTTPS传输后端**

![](https://github.com/xiezongnan/Summarize/blob/master/git/images/setup/7.jpg)



**Use the OpenSSL library**

使用 OpenSSL 库

*Server certificates will be validated using the ca-bundle.crt file.*

***服务器证书将使用ca-bundle.crt文件进行验证。***



**Use the native Windows Secure Channel library**

使用本地 Windows 安全通道库

*Server certificates will be validated using Windows Certificate Stores.This option also allows you to use your company's internal Root CA certificates distributed e.g. via Active Directory Domain Services.*

***服务器证书将使用Windows证书存储验证。此选项还允许您使用公司的内部根CA证书，例如， 通过Active Directory Domain Services 。***





## Step 8 Configuring the line ending conversions

**配置行结束转换**

![](https://github.com/xiezongnan/Summarize/blob/master/git/images/setup/8.jpg)



**Checkout Windows-style,commit Unix-style line endings**

*Git will convert LF to CRLF when checking out text files.When committing text files,CRLF will be converted to LF .For cross-pltform projects,this is the recommended setting on Windows ("core.autocrlf" is set to "true")*

***在检出文本文件时，Git会将LF转换为CRLF。当提交文本文件时，CRLF将转换为LF。 对于跨平台项目，这是Windows上推荐的设置（“core.autocrlf”设置为“true”）***



**Checkout as-is , commit Unix-style line endings**

*Git will not perform any conversion when checking out text files. When committing text files, CRLF will be converted to LF. For cross-platform projects,this is the recommended setting on Unix ("core.autocrlf" is set to "input")*

***在检出文本文件时，Git不会执行任何转换。 提交文本文件时，CRLF将转换为LF。 对于跨平台项目，这是Unix上的推荐设置 （“core.autocrlf”设置为“input”）***



**Checkout as-is,commit as-is**

*Git will not perform any conversions when checking out or committing text files.Choosing this option is not recommended for cross-platform projects ("core.autocrlf"is set to "false")*

***在检出或提交文本文件时，Git不会执行任何转换。对于跨平台项目，不推荐使用此选项（“core.autocrlf”设置为“false”）***





## Step 9 Configuring the terminal emulator to use with Git Bash

**配置终端模拟器以与 Git Bash 一起使用**

![](https://github.com/xiezongnan/Summarize/blob/master/git/images/setup/9.jpg)



**Use MinTTY (the default terminal of MSYS2)**

*Git Bash will use MinTTY as terminal emulator,which sports a resizable window,non-rectangular selections and a Unicode font. Windows console programs (such as interactive Python) must be launched via 'winpty' to work in MinTTY.*

***Git Bash将使用MinTTY作为终端模拟器，该模拟器具有可调整大小的窗口，非矩形选区和Unicode字体。 Windows控制台程序（如交互式Python）必须通过'winpty'启动才能在MinTTY中运行。***



**Use Windows' default console window**

*Git will use the default console window of Windows ("cmd.exe"),which works well with Win32 console programs such as interactive Python or node.js , but has a very limited default scroll-back,needs to be configured to use aUnicode font in order to display non-ASCII characters correctly,and prior to Windows 10 its windows was not freely resizable and it only allowed rectangular text selections.*

***Git将使用Windows的默认控制台窗口（“cmd.exe”），该窗口可以与Win32控制台程序（如交互式Python或node.js）一起使用，但默认的回滚非常有限，需要配置为使用unicode 字体以正确显示非ASCII字符，并且在Windows 10之前，其窗口不能自由调整大小，并且只允许矩形文本选择。***





## Step 10 Configuring extra options

**配置额外的选项**

![](https://github.com/xiezongnan/Summarize/blob/master/git/images/setup/10.jpg)



**Enable file system caching**

启用文件系统缓存

*File system data will be read in bulk and cached in memory for certain operations ("core.fscache" is set to "true"). This provides a significant performance boost.*

***文件系统数据将被批量读取并缓存在内存中用于某些操作（“core.fscache”设置为“true”）。 这提供了显着的性能提升。***



**Enable Git Credential Manager**

启用Git凭证管理器

*The Git Credential Manager for Windows provides secure Git credential storage for Windows,most notably multi-factor authentication support for Visual Studio Team Services and GitHub. (requires .NET framework v4.5.1 or or later).*

***Windows的Git凭证管理器为Windows提供安全的Git凭证存储，最显着的是对Visual Studio Team Services和GitHub的多因素身份验证支持。 （需要.NET Framework v4.5.1或更高版本）。***



**Enable symbolic links**

启用符号链接

*Enable symbolic links (requires the SeCreateSymbolicLink permission).Please note that existing repositories are unaffected by this setting.*

***启用符号链接（需要SeCreateSymbolicLink权限）。请注意，现有存储库不受此设置的影响。***





## Step 11 Installing

![](https://github.com/xiezongnan/Summarize/blob/master/git/images/setup/11.jpg)





## Step 12 Completing the Git Setup Wizard

![](https://github.com/xiezongnan/Summarize/blob/master/git/images/setup/12.jpg)


# Git 初次运行前的配置并通过SSH连接GitHub

每台计算机上只需配置一次，可在任何时候通过运行命令修改。

在 Windows 系统中，Git 会查找 $HOME 目录下（一般情况下是 C:\Users\$USER）的 .gitconfig 文件。
Git 同样也会寻找 /etc/gitconfig 文件，但只限于 MSys 的根目录下，即安装 Git 时所选的目标位置。



## Step 1 配置信息

`git config --list`

列出所有 Git 当时能找到的配置。



### 用户信息

`git config --global user.name "Tom"`

`git config --global user.name "tom@example.com"`

注：如果使用了 `--global` 选项，以后 Git 在该系统上都会使用这些信息。当你想针对特定项目使用不同的用户名称和邮件地址时，可在那个项目的目录运行没有 `--global` 的命令。



## Step 2 通过 SSH 连接 GitHub

### 生成SSH公钥

完成上述用户信息配置后，使用下面命令生成SSH公钥 (你的个人邮箱)

`ssh-keygen -t rsa -C tom@example.com`

`ssh-keygen` 会确认密钥的存储位置，默认 .ssh/id-rsa，要求你输入两次密钥口令。

如果你不想在使用密钥时输入口令，留空敲击回车即可。

切换到公钥生成的默认目录

`cd ~/.ssh`

目录下存在一对以 id_dsa 或 id_rsa 命名的文件，其中一个带有 .pub 扩展名。 .pub 文件是你的公钥，另一个则是私钥。

`cat ~/.ssh/id-rsa.pub`

复制公钥的==**全部**==内容。（包括开头的 ssh-rsa）= =!

看起来是这样的一串

```
ssh-rsa AAAAB3NzaC1yc2EAAAABIwAAAQEAklOUpkDHrfHY17SbrmTIpNLTGK9Tjom/BWDSUGPl+nafzlHDTYW7hdI4yZ5ew18JH4JW9jbhUFrviQzM7xlELEVf4h9lFX5QVkbPppSwg0cda3Pbv7kOdJ/MTyBlWXFCR+HAo3FXRitBqxiX1nKhXpHAZsMciLq8V6RjsNAQwdsdMFvSlVK/7XAt3FaoJoAsncM1Q9x5+3V0Ww68/eIFmb1zuUFljQJKprrX88XypNDvjYNby6vw/Pb0rwert/EnmZ+AW4OZPnTPI89ZPmVMLuayrD2cE86Z/il8b+gw3r3+1nKatmIkjn2so1d01QraTlMqVSsbxNrRFi9wrf+M7Q== schacon@mylaptop.local
```



登录到您的 GitHub 上，点击你右上角的头像，**Settings** 选项。

![](https://github.com/xiezongnan/Summarize/blob/master/git/images/configuration/1.jpg)

左栏 **SSH and GPG keys**  , **New SSH key**

![](https://github.com/xiezongnan/Summarize/blob/master/git/images/configuration/2.jpg)

**Title** 标题，能够区分你的设备

**Key** 将复制的公钥粘贴 

**Add SSH key**



成功后在 Git Bash 执行连接测试

`ssh -T git@github.com`

出现 **Hi somebody ! You've successfully authenticated...** 字样表示连接成功



### 失败了 ?

`cd ~`

删除 .ssh 文件夹

`rm -rf .ssh`

从生成公钥的环节重新开始吧 

