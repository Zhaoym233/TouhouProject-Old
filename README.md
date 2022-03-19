# TouhouProject-Old
PC-98××弹幕射击游戏  
由ZUN Soft制作（现已改名上海爱丽丝幻乐团）
由Zhaoym233整理
整理后版本在[CreativeCommons Attribution-NonCommercial-ShareAlike 3.0 Unported (CC BY-NC-SA 3.0)](https://creativecommons.org/licenses/by-nc-sa/3.0/)协议下公布
---
你或许想问:
> 为什么做这个整合包? 现在不是已经有现成的了吗?
好问题

现在大部分的旧作整合包使用的都是 Anex86
然而 Anex86 的声音效果不是很理想
对于东方 Project 这种音游 (暴论) 来说这简直是噩梦
并且在 Linux 上似乎并没有任何的教程 / 整合 (至少我看到的)
我估计其他类 Unix 系统也是如此
正好群友在问「为什么我的 Anex86 黑屏」
然后就做出了这个整合包

——————————

路径下有以下文件：
> dosbox-x.exe		(DOSBox-X 主程序)
> dosbox-x.conf		(DOSBox-X 配置文件)
> FREECG98.bmp		(NEC PC-98xx 的字形表)
> readme.txt		(说明文档)
> run.bat		(用来运行 DOSBox-X 的批处理文件)
> run.sh		(用来运行 DOSBox-X 的 shell 脚本)
> zun.hdi		(旧作磁盘镜像文件)
> zun_zh_TW.hdi		(旧作繁体中文汉化版镜像文件)

如果你是Windows系统：
> 请执行 run.bat (多半是双击 run.bat) 来运行 DOSBox-X (这样可以保证载入了配置文件)
如果你是类 Unix 系统：
> 请安装 flatpak 的 com.dosbox_x.DOSBox-X 软件包
> 执行 run.sh 来运行 DOSBox-X (这样可以保证载入了配置文件)

原版和繁体中文汉化版被分别挂载在了 A 和 B 驱动器上
你需要通过 <驱动器编号>: 来切换到对应的驱动器
通过 cd <游戏目录> 切换到你想玩的作品的目录
通过 game.bat 来执行游戏 (.bat 后缀可以缺省)

注意，DOSBox-X 下 autoexec.bat 不可用，所以你可能需要记住：
> REIIDEN 是 东方灵异伝 (这一作不是弹幕 STG)
> HUMAROKU 是 东方封魔录
> YUMEZIKU 是 东方梦时空
> GENSO	是 东方幻想乡
> KAIKI	是 东方怪绮谈

祝你玩得愉快 :D
