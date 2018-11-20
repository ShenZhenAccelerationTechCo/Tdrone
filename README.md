# Tdrone
Open source coaxial drone
-------------------------
![SHOUYE](https://github.com/ShenZhenAccelerationTechCo/Tdrone/blob/master/pictures/SHOUYE.png)
## Why Coaxial Tdrone?
共轴双桨气动布局的飞行器其飞行原理类似于我们常见的直升机。与直升机不同的是，共轴双桨气动布局取消了直升机上常见的尾桨，使用了两个直径相同共轴布置的螺旋
桨。与直升机相同的是，都使用了倾斜盘作为变距机构，来控制飞行器的俯仰和横滚自由度。下面的视频介绍了倾斜盘的工作原理：
* [直升机斜盘原理视频](https://www.youtube.com/watch?v=-kWhNi-MZAM)

对于小型共轴双桨气动布局的飞行器，通常采用单层变距的结构，就是说上下两层旋翼只有一个旋翼可以变距，而另一个旋翼则为定距。这样布局的好处是最大限度简化机
械结构，利于飞行器的制造和后期维护。 当然如果追求更好的性能也可以设计更为复杂的双层变距结构，来使飞行器获得更强的飞行性能。

共轴双桨相对于多旋翼飞行器的优点有：
* 1.在相同的工作尺寸下（飞行中） 共轴双桨飞行器拥有更大的旋翼面积进而拥有更高的飞行效率；
* 2.在相同的工作尺寸下（飞行中） 共轴双桨飞行器拥有更大的有效载荷；
* 3.在相同有效载荷下，其旋翼转速低于多旋翼，进而产生的噪音更小，拥有较好的静音性；
* 4.其产生俯仰和横滚控制力矩时不需要频繁使主旋翼加减速，减少了能量的损耗，尤其在飞行器尺寸较大的情况下，这种相对于多旋翼的优势就会更明显；
* 5.其螺旋桨可以方便的折叠收纳，没有多旋翼飞行器较为复杂的机臂折叠锁定机构，折叠起来机身更为规整，便于携带与运输；

共轴双桨相对于多旋翼飞行器的缺点有：
* 1.相较于多旋翼飞行器，共轴双桨飞行器的机械结构相对复杂，导致在制造成本与可维护性上不如多旋翼飞行器；
* 2.飞行模态相对多旋翼复杂一些，在飞控设计方面有一定的挑战；

任何飞行器都是面向于目标用途和使用环境设计的，各种气动布局之间没有绝对的好坏之分。不仅在地球上如此，在其他星球上我们的理论依然适用～

![RME1](https://github.com/ShenZhenAccelerationTechCo/Tdrone/blob/master/pictures/RME1.jpg)

* [NASA共轴飞行器](https://www.nasa.gov/press-release/mars-helicopter-to-fly-on-nasa-s-next-red-planet-rover-mission)

在莱特兄弟使用固定翼飞行器完成人类第一次载人飞行的100多年后，我们有望见证人类首次在除地球以外的星球上使用无人飞行器，而这个无人飞行器正是共轴双桨无人
机！

## Tdrone介绍

### 1.概况：
Tdrone无人机是从2015年10月开始研发的，到2016年4月第一代Tdrone具备了初步飞行能力，就如视频中展示的那样（连接）。Tdrone使用了两个经过改装的1806无刷电
机作为动力，两个舵机用来控制斜盘，偏航使用差速控制。飞控使用了CC3D飞控。其搭载了两轴稳定的云台和运动相机。续航时间在10分钟左右。

![RME2](https://github.com/ShenZhenAccelerationTechCo/Tdrone/blob/master/pictures/RME2.jpg)  ![3D结构正面](https://github.com/ShenZhenAccelerationTechCo/Tdrone/blob/master/pictures/3D结构正面.png)
![TU4](https://github.com/ShenZhenAccelerationTechCo/Tdrone/blob/master/pictures/TU4.png)

### 2.飞控部分：
   Tdrone使用了CC3D飞控。CC3D飞控原生即支持该种类型的飞行器，但需要一些特殊的设置。这是我使用的配置文件（连接）。 你可以直接使用该配置文件，但遥控器
的设置需要根据你使用的遥控器的情况进行重新设置。这一步与多旋翼是一致的，参考多旋翼的部分即可。 地面站固件版本为 15.02.02。
我们会在此不断完善飞控的设置教程，请关注后续的更新。

### 3.制造方式及材质：
   Tdrone整机采用3D打印技术制造，所有零件都进行了3D打印优化，可以直接打印，打印材料使用了普通的ABS塑料。中央核心部分使用了铝管。98%的零件都使用了螺丝固定，方便后期维修更换。
   
![3D结构侧面](https://github.com/ShenZhenAccelerationTechCo/Tdrone/blob/master/pictures/3D结构侧面.png)

### 4.DIY注意事项：
我十分理解大家想尽快制造出属于自己的飞行器的急迫心情。但在一切开始之前，你需要弄清楚以下几点：
* 1.所有的零件尺寸都是按照我的3D打印机公差精度优化的，可能它并不适合你所使用的3D打印机。你需要根据你自己的打印机适当的调整零件。你可以先打印出一些需要配合的零件来测试。
* 2.所使用的电机与舵机尽量使用与我们建议或相近似的型号，不要偏差过多。
* 3.该飞行器的制造需要一定的动手能力，虽然打印机完成了大部分的工作，但仍需要你手工处理一些金属零件布线及调整电机等。

### 更多了解
点击YouTube，bilibili视频链接来观看Tdrone的实际飞行视频.

* [YouTube飞行视频](https://www.youtube.com/watch?v=wCfMVMhZFWQ&t=2s)
* [bilibili飞行视频](https://www.bilibili.com/video/av36347739/?redirectFrom=h5)










