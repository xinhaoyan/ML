# Gradient descent

步骤 1 选择 预测函数 比如 y= wx

机器学习算法： 1. 学习算法 2.发现规律 3，改进模型 4.做出预测

步骤 2 找到代价函数 
      量化数据偏离程度--均方误差（误差平方和的平均值）  一般使用均方误差
<img width="1241" alt="image" src="https://github.com/xinhaoyan/ML/assets/111496997/71e963e4-a694-4f21-a511-3ec2e8e57b42">
<img width="1142" alt="image" src="https://github.com/xinhaoyan/ML/assets/111496997/32a014c6-2667-4ed3-857d-b3108b154c3e">

推导过后就是表示学习所需要的代价函数

<img width="484" alt="image" src="https://github.com/xinhaoyan/ML/assets/111496997/97003652-9ada-4812-8df1-e5ebc7a33e69">

3.明确搜索方向 --- 梯度计算
<img width="1201" alt="image" src="https://github.com/xinhaoyan/ML/assets/111496997/a2f83253-5ca7-4726-9c05-e34ba24f0b2f">
寻找代价函数最小值，即图像中最低点
只要向着陡峭方向最大的地方走，就是更快到达最低点。 这个陡峭程度就是梯度（Gradient）

4.确定方向就大胆往前走吗? -- 学习率
<img width="1049" alt="image" src="https://github.com/xinhaoyan/ML/assets/111496997/f54a1d81-1d91-493e-887f-e7aaa0d6a9e0">

5.不达目标不罢休 -- 循环迭代


总结：
梯度下降的算法 包括： 1.定义代价函数 2.选择起始点 3，计算梯度 4，按学习率前进 5，重复 步骤3，4  直至函数收敛，找到最低点

## 各种梯度下降算法
1.批量梯度下降 Batch Gradient Descent  BGD  -- 全部训练样本参与训练 （这是梯度下降最原始的形式）优点 非常精准 缺点 ：慢 
<img width="1059" alt="image" src="https://github.com/xinhaoyan/ML/assets/111496997/cc2d6ea0-e3d9-4bb3-9a86-93695bb4976b">

2. 随机梯度下降法 (Stochastic Gradient Descent ) SGD 牺牲准度 提升效率
<img width="1064" alt="image" src="https://github.com/xinhaoyan/ML/assets/111496997/6a974524-a069-4917-be92-5857ba4df954">

3. 小批量梯度下降算法  （Mini-Batch Graient Descent）MBGD 结合上面二者优点 比1快 比2精准
   <img width="1198" alt="image" src="https://github.com/xinhaoyan/ML/assets/111496997/38e6a0e5-d0f5-44d5-ad20-4688ec74efd7">

在梯度算法中，学习率很重要，如果学习率太大 反复横跳； 学习率太小 浪费计算量 
还有 除了BGD 很慢外，还有就是有可能找到局部最低点，而不是全局最低点

所以有更优的学习算法 比如： AdaGrad - 动态学习率  
                          RMSProp - 优化动态学习率  
                          AdaDelta - 无需设置学习率  
                          Adam - 融合AdaGrad 和 RMSProp
                          Momentum - 模拟动量
                          FTRL ...

