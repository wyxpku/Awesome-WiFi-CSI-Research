# Awesome-WiFi-CSI-Research
置顶：

## 新增scripts文件夹，提供文件采集、实时可视化的脚本程序
- 自动每分钟采集，并以时间戳命名文件，自动以日期建立文件夹，配置简单
- 借助Realtime-processing-for-csitool使用Matlab远程服务，实时可视化csi

## [Opensource code: CSI_Generator and AoA-ToF Joint Estimation by MUSIC](https://github.com/wuzhiguocarter/Awesome-WiFi-CSI-Research)

- CSI_NonCoherent 非相干源CSI生成，与标准MUSIC算法实现（AoA ToF联合估计）
- CSI_Coherent 相干源CSI生成，与平滑MUSIC算法实现（AoA ToF联合估计）
- 下一步计划，考虑带PDD/CFO/STO/PLL Initial Offset误差项的CSI信号生成，考虑带PDD/CFO/STO/PLL Initial Offset误差项的CSI信号生成，验证Spotfi的spotfi_algorithm_1并测试CSI_Coherent里的算法
- 更下一步计划，在上一步误差项的基础上，考虑双向CSI观测的生成，实现并验证Chronos的N-DFFT算法
## [Related Blog: CSI Generator设计原理（非相干）](http://www.jianshu.com/c/6e0897ba0cec)

---
此项目服务于**QQ群（CSI信道状态信息交流：366102075）**
---

### 通过此项目，你可以获得什么？

- **快速跟进**
同样的问题，被别人解决了，通过学习别人的解决方案，可以快速跟进

- **合作解决难题**
别人提出的新问题，自己也遇到了，可以和提这个问题的人以及对这个问题同样感兴趣的人一起讨论，合作解决难题

### 你可以为这个项目作出什么贡献？

- **遇到了别人没遇到的问题，通过Github New Issue提出你的问题**

注意：在提问题之前，务必确保你的问题没有出现在[Linux 802.11n CSI Tool FAQ](http://dhalperi.github.io/linux-80211n-csitool/faq.html)、[Linux 802.11n CSI Tool Issues List](https://github.com/dhalperi/linux-80211n-csitool-supplementary/issues)、[本项目Issue List](https://github.com/wuzhiguocarter/WiFi-CSI-Research-Q-A/issues)

- **解决别人提出的问题，并贡献答案**
- **补充更多的相关资源链接，如包括并不限于开源项目/技术文档/高质量博客文章等等**
- **补充最新的已发表的国内外学术论文/专利**

### 资源链接

- Linux 802.11n CSI Tool项目相关

[Linux 802.11n CSI Tool项目主页](http://dhalperi.github.io/linux-80211n-csitool/) 

[Linux 802.11n CSI Tool项目源码](https://github.com/dhalperi/linux-80211n-csitool/)

[linux-80211n-csitool-supplementary CSI获取](https://github.com/dhalperi/linux-80211n-csitool-supplementary)

- CSI Tool的安装/使用/CSI数据的基本处理

[Linux 802.11n CSI Tool FAQ](http://dhalperi.github.io/linux-80211n-csitool/faq.html)

[Linux 802.11n CSI Tool Issues List](https://github.com/dhalperi/linux-80211n-csitool-supplementary/issues)

- 可视化

[CSI测量的实时可视化](https://github.com/lubingxian/Realtime-processing-for-csitool)

- 学术论文的开源实现

[SpotFi的开源实现：Looks Good to Me (LGTM)](https://github.com/egaebel/lgtm)

[DeepFi](https://github.com/mars920314/DeepFi)

- 开源项目

[WiFi-movement-identification](https://github.com/persistforever/WiFi-movement-identification)

- 博客文章


> **动作识别系列**

[文献阅读：手势识别 WiFinger: Leveraging Commodity WiFi for Fine-grained Finger Gesture Recognition （MobiHoc 2016）](http://blog.csdn.net/dfcaihg/article/details/52699561)

[文献阅读：手写识别 WiFinger: Talk to Your Smart Devices with Finger-grained Gesture （UbiComp 2016）](http://blog.csdn.net/dfcaihg/article/details/52763083)

[文献阅读：吸烟识别 Smokey: Ubiquitous Smoking Detection with Commercial WiFi Infrastructures（InfoCom 2016）](http://blog.csdn.net/dfcaihg/article/details/52708626)

[文献阅读：步态识别 Gait Recognition Using WiFi Signals（UbiComp 2016）](http://blog.csdn.net/dfcaihg/article/details/52803525)

> **室内定位系列** 

[文献阅读：Device-Free行走方向估计 WiDir: Walking Direction Estimation Using Wireless Signals（UbiComp 2016）](http://blog.csdn.net/dfcaihg/article/details/52846443)

[文献阅读：MUSIC算法在室内定位的应用 以SpotFi（SIGCOMM 2015）和Dynamic-MUSIC（UbiComp 2016）为例](http://blog.csdn.net/dfcaihg/article/details/52914414)

[文献阅读：AoA估计 Tuning by Turning: Enabling Phased Array Signal Precessing for WiFi with Inertial Sensors (InfoCom 2016)](http://blog.csdn.net/dfcaihg/article/details/52687570)

[基于WiFi CSI定位综述](http://www.jianshu.com/p/04c202f51b16)

[CSI的信号模型与测量模型](http://www.jianshu.com/p/d7590470fe32)

[研究笔记： 基于单接入点/单基站WiFi CSI的分米级定位（Chronos2016）](http://www.jianshu.com/p/4ef8b2cee7d4)

[室内定位研究国内外主要实验室、团队和学者（WiFi CSI）](http://www.jianshu.com/p/85399d050305)

