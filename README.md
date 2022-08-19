# 求解各向异性椭圆界面问题的物理信息引导并行神经网络   
范晓鸿1，易华明1，张建平1，冯聿杰1，杨银1   
(1.湘潭大学 数学与计算科学学院，湖南 湘潭 411105)   
摘要：本文中，我们提出了一个物理信息引导的求解各向异性椭圆界面问题的并行神经网络，在界面附近和界面处都能获得较精确的解。通过引入辅助变量把二阶系统改写为一阶系统，降低了解的正则性要求。使用不同的子网络预测不同的子域中的解，并且用界面跳跃条件损失函数项把各个子网络耦合在一起。此外，我们使用L1范数和L2范数结合的分段损失函数，加强了对异常值的鲁棒性。数值实验验证了所提方法在求解各向异性椭圆界面问题时的准确性和有效性。
关键词：各向异性，椭圆界面，神经网路，一阶系统


# Physics-informed-Parallel-Neural-Network-for-Solving-Anisotropic-Elliptic-Interface-Problems   
Xiaohong Fan1, Huaming Yi1, Jianping Zhang1, Yujie Feng1, Yin Yang1,   
（1.School of Mathematics and Computational Science, Xiangtan University, Xiangtan 411105)   
Abstract: In this study, we propose a physics-informed parallel neural network for solving anisotropic elliptic interface problems, which can obtain accurate solutions both near and at the interface. We rewrite the original second-order system into a first-order system to reduce the regularity requirement of solutions by an auxiliary variable. We use different sub-networks to predict solutions in different subdomains and couple them together by loss function terms designed by the interface jump conditions. In addition, we use a piecewise loss function combining L1 norm and L2 norm to enhance the robustness of outliers. Numerical experiment verifies the accuracy and effectiveness of proposed method for solving anisotropic elliptic interface problems.    
Key Words: anisotropic, elliptic interface, neural network, first-order system

湖南省第十四届研究生创新论坛优秀论文二等奖.   
![image](https://user-images.githubusercontent.com/48355877/185525824-6041722d-26c8-405f-aeb7-957a402ec4d2.png)   
图 1  提出的物理信息引导的求解各向异性椭圆界面问题的并行神经网络流程图   
![image](https://user-images.githubusercontent.com/48355877/185525887-49977ddf-dcd2-4e26-8367-275806ebe8f1.png)   
图 2  数值实验结果. (a) 训练采样点；(b) 测试采样点；(c) 未降低解的正则性要求且以均方差为损失的方法的误差图；(d) 本文方法的误差图。
