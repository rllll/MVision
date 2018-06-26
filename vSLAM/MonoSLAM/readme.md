# MonoSLAM  扩展卡尔曼滤波 更新 相机特征点法得到的位姿 
    Extended Kalman Filter based Monocular SLAM
![](http://vision.ia.ac.cn/Students/gzp/ekfslamflow.jpg)

[参考 EKF+ Monocular SLAM ](http://vision.ia.ac.cn/Students/gzp/monocularslam.html)

    Real-Time Single Camera SLAM  单目摄像头的3D运动轨迹的算法
    本文设计了一种可以实时复现在未知场景里随机运动的单目摄像头的3D运动轨迹的算法。
    我们叫这个系统为MonoSLAM,它是第一个成功地利用一个移动端的不可控制的摄像头获得“纯粹的视觉”的系统
    ，在用移动的方法无法预知接口的情况下可以达到实时且无漂亮的表现。
    这个方法的核心是在一个概率框架内实时在线地创建一些稀疏但持久的自然landmark。 
    关键贡献点包括一种映射和测量的积极的方式，一种为摄像头平滑运动设计的通用移动模型的使用，
    以及单目特征初始化和特征方向估计的解决方案。
    综合以上，我们设计了非常有效和鲁棒的算法，
    在普通PC和摄像头可以运行到30HZ。 这些工作扩展了robotic系统的范围，也开辟了SLAM在其中应用的大门。
    最后我们把MonoSLAM应用于高性能全自由度的仿人机器人和人手持摄像头的增强现实中。