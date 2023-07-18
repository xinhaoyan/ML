<img width="532" alt="image" src="https://github.com/xinhaoyan/ML/assets/111496997/3007e67b-068d-41a3-886b-921e1b6c3ff0"><img width="532" alt="image" src="https://github.com/xinhaoyan/ML/assets/111496997/5718438d-916d-406d-9e22-e86254f79b11"># Overview
## Supervised Learning 

X -> Y
input -> output Label

Learns from being given "right answers"

Regression  is that predicting a number from infinitely many possible outputs


Classification  is that predicting categories from small number  of possible outputs

## Unsupervise Learning
find some interesting structures
Example : Clustering - Google news / DNA microarray -DNA微阵列 / Grouping customers

Data only comes with inputs x, but not output labels y.
Algorithm has to find structure in the data

1.Clustering
Group similar data points together.

2.Anomaly detection
Find unusual data points 

3.Dimensionality reduction
Compress data using fewer numbers.


recommend tool: Jupyter Notebook 

# Supervised Learning 
the widest use 
## Linear Regression with one Variable 

Notation 
X = "input" variable 
      feature
Y = "output" variable
      "target" variable 
m = number of training examples
(x,y) = single tarining example 

<img width="262" alt="image" src="https://github.com/xinhaoyan/ML/assets/111496997/184d0400-5d73-494b-8727-84b3c84fe0d2">

<img width="636" alt="image" src="https://github.com/xinhaoyan/ML/assets/111496997/e2d37c8e-a339-417a-bed7-90633801f2cb">

## Cost Fuction-- 代价函数

Model fw,b(X) =  wx + b
w: weight
b: bias 

<img width="637" alt="image" src="https://github.com/xinhaoyan/ML/assets/111496997/ed7c969b-1103-4af3-8322-0866f2d7e69b">

<img width="319" alt="image" src="https://github.com/xinhaoyan/ML/assets/111496997/f7ee6aae-07e8-426d-9759-6c7cc3da13a2">

<img width="333" alt="image" src="https://github.com/xinhaoyan/ML/assets/111496997/5168b5dc-f489-46fb-afde-00984bf44c4c">

<img width="621" alt="image" src="https://github.com/xinhaoyan/ML/assets/111496997/8bdd832b-1ddd-4368-bd3c-18225052cb61">

<img width="447" alt="image" src="https://github.com/xinhaoyan/ML/assets/111496997/cc8ce493-028b-422c-b131-645342ecd3e4">


## Visualization Examples

<img width="618" alt="image" src="https://github.com/xinhaoyan/ML/assets/111496997/3e9ded79-6814-4a19-99e1-5866916b78f6">

## Gradient Descent  -- 梯度下降

所有的AI模型都会用到 

<img width="645" alt="image" src="https://github.com/xinhaoyan/ML/assets/111496997/580675ff-5fbc-4fcc-bd4d-a85b0106346b">

“Local mimima”

<img width="532" alt="image" src="https://github.com/xinhaoyan/ML/assets/111496997/14fd161d-8e65-415f-b208-d3072015ce4b">   

<img width="771" alt="image" src="https://github.com/xinhaoyan/ML/assets/111496997/f6b3f8d6-bf38-4684-b8f2-b94b435753f8">

<img width="698" alt="image" src="https://github.com/xinhaoyan/ML/assets/111496997/4806eaa7-4944-477b-9fcd-f79c005fd025">

## Learning Rate
 
<img width="763" alt="image" src="https://github.com/xinhaoyan/ML/assets/111496997/48e0f22e-3406-4d92-9b1a-913fdf0634a5">

<img width="783" alt="image" src="https://github.com/xinhaoyan/ML/assets/111496997/e9323997-b1f5-40f6-aca3-e0312875babb">

## Gradient Descent for linear Regression

<img width="711" alt="image" src="https://github.com/xinhaoyan/ML/assets/111496997/f50f7d1a-1ebe-42a2-b8d2-eb81f7424ce6">

<img width="769" alt="image" src="https://github.com/xinhaoyan/ML/assets/111496997/87735357-08e5-4457-accb-ac914d368649">

<img width="764" alt="image" src="https://github.com/xinhaoyan/ML/assets/111496997/e06ffed4-bb2d-4589-8cfb-0f50b8b7a3bf">

<img width="768" alt="image" src="https://github.com/xinhaoyan/ML/assets/111496997/b1a87c71-d77a-41d1-8cc4-73a6e6751b54">

<img width="766" alt="image" src="https://github.com/xinhaoyan/ML/assets/111496997/46259322-5b0f-4926-84b9-eb6f4d9a1b6e">

<img width="748" alt="image" src="https://github.com/xinhaoyan/ML/assets/111496997/efa98e8a-451c-4cac-98da-05651f6653d0">

<img width="742" alt="image" src="https://github.com/xinhaoyan/ML/assets/111496997/f2a92e3a-ff86-43d4-9f1d-114d40ecb87c">

## Vectorization 

<img width="638" alt="image" src="https://github.com/xinhaoyan/ML/assets/111496997/38ad560d-0204-497a-ac45-ee4bfe9c0187">

<img width="636" alt="image" src="https://github.com/xinhaoyan/ML/assets/111496997/70cc0811-fb91-459a-aa8c-afdfed9ab90f">

<img width="642" alt="image" src="https://github.com/xinhaoyan/ML/assets/111496997/cfae2323-48a1-40a4-9057-f89b1f5151ff">

<img width="632" alt="image" src="https://github.com/xinhaoyan/ML/assets/111496997/ead375f7-9120-4bbf-8d84-8c86061ecc74">

<img width="630" alt="image" src="https://github.com/xinhaoyan/ML/assets/111496997/77990672-3255-454d-ac53-5f5eb9b42d5e">

<img width="595" alt="image" src="https://github.com/xinhaoyan/ML/assets/111496997/44a4a61a-7b02-46f9-b5e5-2ae69b090124">

### 关于梯度下降算法我还是不太懂，看其他视频
最小二乘法  
<img width="413" alt="image" src="https://github.com/xinhaoyan/ML/assets/111496997/5e3d0f0a-901c-4e91-9b19-f0f6e63a6ee5">

最小二乘法是解决线性回归问题的常用方法 

<img width="583" alt="image" src="https://github.com/xinhaoyan/ML/assets/111496997/1ef59d7c-29e7-4965-b6ec-6889b0a14e80">

要确定这个W 所以引出线性回归的代价函数
代价函数值越大，越说明 W 与 B  不合适
因此要求出 当代价函数最小时， W 和 B 的值

<img width="522" alt="image" src="https://github.com/xinhaoyan/ML/assets/111496997/372bd437-6c7a-4f79-ad18-a2cb08c890e7">

## Feature Scaling 特征缩放
 <img width="1056" alt="image" src="https://github.com/xinhaoyan/ML/assets/111496997/aa0f7d66-48bc-4a85-abbb-477a7c01841c">

最大法 
<img width="1008" alt="image" src="https://github.com/xinhaoyan/ML/assets/111496997/f2b3708c-8b02-40a1-8378-f3380c30a513">

Mean Normalization --平均值标准化 
<img width="1018" alt="image" src="https://github.com/xinhaoyan/ML/assets/111496997/89b1f604-b802-474c-b7c6-8697e82e89fa">

Z-score normalization
<img width="1020" alt="image" src="https://github.com/xinhaoyan/ML/assets/111496997/2b279a37-08dd-45df-8122-9e3724a0da9c">


<img width="1139" alt="image" src="https://github.com/xinhaoyan/ML/assets/111496997/4c20004d-6def-49d4-b299-6b25d679e961">


##  判断梯度下降是否收敛
 

