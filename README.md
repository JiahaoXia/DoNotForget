# DoNotForget

## System
* [Dell Alienware Win10+Ubuntu双系统安装](https://www.dell.com/support/article/cn/zh/cnbsd1/sln308010/ubuntu-win10%E5%8F%8C%E7%B3%BB%E7%BB%9F%E5%AE%89%E8%A3%85%E6%95%99%E7%A8%8B?lang=zh)
* [Win10+Ubuntu双系统---Ubuntu卸载](https://www.cnblogs.com/xia-Autumn/p/6294055.html)
* Ubuntu
<br> .deb file installation: sudo  dpkg  -i  package.deb
<br> Ubuntu进入命令行模式 在boot时按【ctrl+alt+f1~f6】
<br> dev/sda6:clean错误 通常与显卡驱动相关
<br> nautilus --- file management
* [ubuntu 挂载硬盘](https://segmentfault.com/a/1190000022840767)


## Tools
* [Git installation](https://www.linuxidc.com/Linux/2018-05/152610.htm)
<br>sudo apt-get update -y
<br>sudo apt-get upgrade -y
<br>sudo apt install git
<br>/git setting/
<br>git config --global user.name "linuxidc"
<br>git config --global user.email "root@linuxidc.net"
<br>git --help
* [Visual Studio code](https://code.visualstudio.com/)
<br>launch.json
<br>delete "enter program name, for example"--->"program":"${workspaceRoot}/a.out"
<br>task.json
<br>"command": "g++"
* [PCL](https://blog.csdn.net/mush_room/article/details/78339578)
* [WIN10+VS2017, PCL安装及配置](https://blog.csdn.net/weixin_41991128/article/details/83864713)
* pycharm使用
<br>[设置pycharm运行时可以输出变量值](https://blog.csdn.net/qq_15969343/article/details/79895761)
* TerraPhoto
<br> 当软件中某些ToolBox被意外关闭，可以通过命令行的方式打开
<br> 在 右上角（Search Ribbon）中输入key-in调出 命令行
<br> 在对话框右下角 选择 TPhoto
<br> 依次 键入 对应命令调出所需工具
* Ubuntu on Win10
<br> [How to Access Your Ubuntu Bash Files in Windows (and Your Windows System Drive in Bash)](https://www.howtogeek.com/261383/how-to-access-your-ubuntu-bash-files-in-windows-and-your-windows-system-drive-in-bash/)

## Installation
* WIN10+VS2017 libLAS usage
<br> [compiled libLAS](https://blog.csdn.net/qq_22170875/article/details/89425358)
<br> for more details, please refer to the dir [libLAS](https://github.com/JiahaoXia/DoNotForget/tree/master/libLAS)
* 第三方库配置
<br> [VS添加第三方库](https://blog.csdn.net/i_chaoren/article/details/77893527)
* [Ubuntu tensorflow,keras installation by anaconda](https://blog.csdn.net/weixin_39954229/article/details/79961172)
* Ubuntu 18.04下安装NVIDIA驱动
<br> 需要disable security boot
<br> 在software & updates--->additional drivers中下载NVIDIA驱动
* [Ubuntu下 Tensorflow安装](https://www.tensorflow.org/install/gpu)

### Programming
* [python] plt.plot() 当使用x=x1,y=y1时绘制图像为空，直接使用x1，y1时绘制正确
* WIN10 下打开jupyter notebook访问无法访问其他盘符的解决方法
<br> WIN+R进入CMD模式 cd到指定盘符下，再由命令行打开jupyter notebook即可
* [python彩色映射](https://blog.csdn.net/guduruyu/article/details/60868501)
* python code: 
<br> b=a
<br> a[b>k] = a[b>k] + m
<br> the value of a and b will change at the same time
* [tensorflow](https://www.zhihu.com/question/57308628/answer/1353318151) Out of Memory in one GPU
* [ValueError: The passed save_path is not a valid checkpoint](https://blog.csdn.net/qq_37764129/article/details/93979561) use absolute directory
* [multi-GPU Training](https://wizardforcel.gitbooks.io/tensorflow-examples-aymericdamien/content/6.2_multigpu_cnn.html)

### Learning resources
* [CVPR 2020 论文大盘点-目标检测篇](https://mp.weixin.qq.com/s/Qg-ZoRKtIsq4NYNekS326g)
* [Essential and Fundamental Matrices](http://www.cse.psu.edu/~rtc12/CSE486/lecture19.pdf)
