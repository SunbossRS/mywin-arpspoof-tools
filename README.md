# windows-cn-arpspoofproj

Now you can do the Arpspoof things via Windows! Here are the files that are using.

**TIPS: The interface language may not your local language.**

***此文档亦提供[简体中文](#cn)***

### Contents

- About this project
- The files we are using
- How to use
- Statement

### About this project

This project can let people to *Arpspoof* others via Windows.

We can often see the software like `Nmap` and `Arpspoof` on Kali Linux. However, due to the particularity of Kali Linux, it might be a little hard to find these two ones for some people. Now, I integrate them into one stuff and you can take them conveniently.

There are some executable files that we're going the use in this project. The `nmap.exe` only supports the command line, so you need to *cd* to the directory of this project, then type `nmap` to use it. Note that **DO NOT** delete the files that look like `nmap-*`, they can prettify the results' look like.

The next one is `Arpspoof.exe`. It is an MFC(Microsoft Foundation Classes) application and it supports the graphical interface. So you can just double-click it to open it.

And there's also a file named `WinPcap_4_1_3.exe`. If you want, you can use Npcap instead of WinPcap. But WinPcap is good enough, so you can use it directly. This is an installer.

### The files we are using

- [Nmap](https://nmap.org/)
- arpspoof.exe
- [WinPcap](https://www.winpcap.org/)

### How to use

1. First, open `WinPcap_4_1_3.exe` and install.
2. Open a command line(cmd) in this project's directory.
3. Type things like `nmap 192.168.*.*` in cmd. This is flexible, you can replace `192.168.*.*` to the *IP segment* you want to spoof.
4. Find the IP you want to spoof in the result, then open `arpspoof.exe`.
5. Type the IP address in the input box *Spoof address*.

6. And that's it! You can by clicking the button `stop attacking` to stop the attack.

### Statement

This project doesn't include any licenses. You can copy and transfer it at any time.

But this project only can be used for studying. I have no responsibility to help you If you have any trouble when you're using.

---

<div id="cn"></div>

# windows-cn-arpspoofproj

在Windows上进行Arpspoof攻击！你也可以的！

### 内容

- 关于
- 这个项目中用到的东西
- 使用方法
- 注意事项

### 关于

该项目可以使我们通过Windows系统与其他人进行*Arpspoof*攻击。  
我们经常可以在Kali系统上看到`nmap`和`Arpspoof`软件。 但有时我们可能很难找到这两个软件。 现在，我将它们整合在一起，你就可以方便地使用它们了;-)  
该项目中有一些主要的`.exe`可执行文件。`nmap.exe`是仅支持命令行的应用程序所以需要*cd*到该项目的目录，然后输入`nmap`来使用它。记住不要删除像`nmap- *`这样的文件！它们是为了更好显示结果！  
接下来是`Arpspoof.exe`文件。 它是MFC应用程序，它支持图形界面。 因此，你就可以直接双击它并打开。  
随后就是`WinPcap_4_1_3.exe`。 该文件可以改用*Npcap*，但是，使用这个也挺好的。这是一个安装程序。

### 这个项目中用到的东西
- [Nmap](https://nmap.org/)
- arpspoof.exe
- [WinPcap](https://www.winpcap.org/)

### 使用方法
1. 首先安装`WinPcap_4_1_3.exe`
2. 在该项目目录中打开一个*cmd*
3. 在*cmd*中输入`nmap 192.168.*.*`（将`192.168.*.*`替换为要欺骗的IP域段）
4. 找到您要欺骗的IP地址，然后打开`arpspoof.exe`
5. 在*欺骗IP*的框框中输入你要欺骗的IP地址
6. 弄好了！当你不想再欺骗时，请按下“停止攻击”按钮

### 注意事项
该项目没有任何许可证。你可以随时复制或传输该项目。  
但是，该项目仅用于学习。如果你在使用时遇到任何问题，本人不负责。
