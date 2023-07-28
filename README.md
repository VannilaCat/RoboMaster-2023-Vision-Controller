# Vision group training

## 1. 打符参考
1.  https://github.com/jssyzsfzy/robomaster_big_homework  
2.  https://www.robomaster.com/zh-CN/resource/pages/activities/1015  

## 2. 卡尔曼滤波
1.卡尔曼滤波器如果不看K(卡尔曼增益），P（协方差矩阵），剩下的部分就是一个状态观测器，所以要理解卡尔曼滤波器的滤波作用可以尝试观察这个观测器的极点变化曲线。这些极点最后都会收敛到一个很小的范围内，所以卡尔曼滤波器可以简化成极点固定的状态观测器。


## 3. 坐标系转化知识
参考：https://www.fdxlabs.com/calculate-x-y-z-real-world-coordinates-from-a-single-camera-using-opencv/


## 4. 关于串口
Linux c++ 串口操作参考文档如下：

https://blog.mbedded.ninja/programming/operating-systems/linux/linux-serial-ports-using-c-cpp/#:~:text=Linux%20Serial%20Ports%20Using%20C%2FC%2B%2B%201%20Everything%20Is,...%208%20VMIN%20and%20VTIME%20%28c_cc%29%20...%20%E6%9B%B4%E5%A4%9A%E9%A1%B9%E7%9B%AE

对于使用ROS的成员， 关于ros_serial_driver包的使用请参考 vision_advanced.md 文档，里边有较简单易懂的介绍。
