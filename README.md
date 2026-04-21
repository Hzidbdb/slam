如何启动

1.启动gezabo仿真环境

在demo01下打开终端输入./devel/setup.bash

首先启动gezabo仿真环境终端输入 roslaunch urdf02 demo02_copy.launch

2.启动rviz可视化

在demo01下新开一个终端输入./devel/setup.bash

然后启动rviz可视化，终端输入 roslaunch nav_demo nav07.launch

3.在rviz中可以点add自行添加robot模型(robotmodel)，path，map，雷达信息（leiser）等

在rviz上可以用2D那个东西进行手点导航

4.地图保存

在demo01下新开一个终端输入./devel/setup.bash

使用roslaunch nav_demo nav02_mapserve.launch可以保存地图到map文件夹下

5.启动已经保存的地图

首先启动gezabo仿真环境终端输入 roslaunch urdf02 demo02_copy.launch

然后启动rviz可视化，终端输入 roslaunch nav_demo nav06.launch

即可加载已经保存的地图

踩坑点：文件名字一定要打对

依赖库版本一定要对

urdf不要打成ufdr
