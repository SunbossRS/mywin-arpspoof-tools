# mywin-arpspoof-tools

在Windows上进行Arpspoof攻击有关的工具集合。

## 内容

- 关于
- 这个项目中用到的东西
- 使用方法
- 注意事项

## 关于

该项目可以使我们通过Windows系统与其他人进行*Arpspoof*攻击。

是一时兴起，想在Windows上实现arp欺骗而创建的仓库。该仓库的内容，并不是需要自己构建的源文件而是打包好的工具。

`nmap.exe`程序仅支持命令行，所以需要敲键盘。不要删除像`nmap-***`这样的文件，是为了格式化显示结果。

`Arpspoof.exe`是MFC图形界面应用程序。 可以直接双击它并打开。

`WinPcap_4_1_3.exe`是一个网卡捕捉的安装程序。另外，你也可以改用*Npcap*。

## 这个项目中用到的东西

- [Nmap](https://nmap.org/)
- arpspoof.exe
- [WinPcap](https://www.winpcap.org/)

## 使用方法

1. 安装`WinPcap_4_1_3.exe`
2. 在该仓库目录中打开cmd
3. 输入`nmap 192.168.*.*`（替换为要欺骗的IP域段）
4. 找到要欺骗的IP地址后，打开`arpspoof.exe`
5. 在*欺骗IP*的框框中输入你要欺骗的IP地址
6. 这样就完事了。按下“停止攻击”按钮就可以结束攻击。

### 注意事项

该项目仅用于学习。如果你在使用时遇到任何问题，创建者无法给出回答。
