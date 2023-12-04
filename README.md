# SSAO

本项目的Shader共有两个，SSAO负责采样，BilateralBlur负责对采样结果进行双边滤波，使用双边滤波的好处是可以清晰的保留阴影的轮廓边缘

#### AO采样结果

![](./pics/ao.png)

#### 双边滤波处理

![](./pics/filter.png)

#### 最终结果

![](./pics/final.png)

#### 原图

![](./pics/disable.png)

