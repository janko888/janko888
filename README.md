简要说明：

1.本dtb经过测试魔百和盒子m302a\m304a部分型号,没有条件测试m301a;

2.以下测试以ubuntu 系统Jammy发行版最新为基准；其它发行版及debian各发行版未经测试;

3.hdmi显示功能在目前各版本安卓固件和M30xA机型确认工作不正常;

4.内置有线网卡功能在安卓4固件下部分工作正常(2022/10/11确认，内核5.19x下正常，内核5.15x下不正常)；在安卓9固件下工作正常；

5.关于写入Emmc内存问题：

    a)M302A测试了两款代工厂型号(零配置扫描\牌照融合(ZN))都可写入,正常使用。
    
    b)M304A测试了一款代工厂型号(牌照南传(ZN))不可写入,推测其为nand的缘故。
    
6.有一定概率(约1/10左右)系统在启动\重启时卡在检测emmc环节无法前进。

7.有少许概率系统在启动\重启时网卡初始化失败，建议使用静态ip配置和关闭ipv6功能以提高启动成功率。

8.重要数据请自行另行备份！！！

更新日志:

2022/10/11 	确认在安卓4固件下运行5.19.x内核版本，有线网卡正常;5.15.x内核版本有线网卡不正常;其余内核版本未知

2022/10/11 	增加/m30Xa/适配情况.md



感谢armbian社区的神奇创意，给我们打开新的世界！

感谢unifreq大以及众多在内核世界默默深耕，提供源源不断的动力！

感谢ophub大的坚持，使混乱无序的晶晨盒子还能保留希望！
