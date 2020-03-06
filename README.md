# windows-chinese-arpspoofproj
Now Chinese can using Arpspoof to spoof others via Windows! Here's the using files.

### Contents
- About
- Using's projects
- Use
- Attention

[中文版](#cn)


### About
This project can let Chinese people to *Arpspoof* others via Windows system.  
We can often see the `nmap` and `arpspoof` softwares on kali system, debian linux. And we might a little hard to find these two softwares. Now, I intergration them and you can just take them conviniently ;-)  
There are some main `.exe` executable files in this project. The `nmap.exe` is the application that only support command line . You need to *cd* to this project's directory and use it with typing `nmap`. Remember don't delete the files like `nmap-*`! They are for results' display!  
The next is the `arpspoof.exe` file. It is the MFC application and it support graphical interface. So you can just double click it and open.  
And there's the `WinPcap_4_1_3.exe`, too. The file can using *Npcap* instead, but, using this file is good, too. This is an installer. You need to install it soon.  

### Using's projects
- [Nmap](https://nmap.org/)
- arpspoof.exe
- [WinPcap](https://www.winpcap.org/)

### Use
1. Install `WinPcap_4_1_3.exe` first.
2. You can open a *cmd* in this project directory.
3. Type `nmap 192.168.*.*` in *cmd*. (Change `192.168.*.*` to the ip that you want to check)
4. Find the ip address that you want to spoof, and open the `arpspoof.exe`
5. Type that ip address in the box of Spoof address.
6. That's is! And stop spoof by clicking the button *stop attacking*.

### Attention
This project doesn't have any licenses. You can copy or transfer this project anytime.  
But, this project is just only for learning. If you have any problems on using, I won't responsible.

---

<div id="cn"></div>

# windows-chinese-arpspoofproj
在Windows上进行Arpspoof攻击！你也可以的！

### 内容
- 关于
- 这个项目中用到的东西
- 使用方法
- 注意事项

### 关于
该项目可以使我们通过Windows系统与其他人进行*Arpspoof*攻击。  
我们经常可以在Kali系统上看到`nmap`和`arpspoof`软件。 但有时我们可能很难找到这两个软件。 现在，我将它们整合在一起，你就可以方便地使用它们了;-)  
该项目中有一些主要的`.exe`可执行文件。`nmap.exe`是仅支持命令行的应用程序所以需要*cd*到该项目的目录，然后输入`nmap`来使用它。记住不要删除像`nmap- *`这样的文件！它们是为了更好显示结果！  
接下来是`arpspoof.exe`文件。 它是MFC应用程序，它支持图形界面。 因此，你就可以直接双击它并打开。  
随后就是`WinPcap_4_1_3.exe`。 该文件可以改用*Npcap*，但是，使用这个也挺好的。这是一个安装程序。

### 这个项目中用到的东西
- [Nmap](https://nmap.org/)
- arpspoof.exe
- [WinPcap](https://www.winpcap.org/)

### 使用方法
1. 首先安装`WinPcap_4_1_3.exe`
2. 在该项目目录中打开一个*cmd*
3. 在*cmd*中输入`nmap 192.168.*.*`（将`192.168。*。*`替换为要欺骗的IP域段）
4. 找到您要欺骗的IP地址，然后打开`arpspoof.exe`
5. 在*欺骗IP*的框框中输入你要欺骗的IP地址
6. 弄好了！当你不想再欺骗时，请按下“停止攻击”按钮

### 注意事项
该项目没有任何许可证。你可以随时复制或传输该项目。  
但是，该项目仅用于学习。如果你在使用时遇到任何问题，本人不负责。
