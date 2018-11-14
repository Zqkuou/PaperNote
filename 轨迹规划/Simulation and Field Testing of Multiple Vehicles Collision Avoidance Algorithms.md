# Simulation and Field Testing of Multiple Vehicles Collision Avoidance Algorithms 

> 祖超越学长论文

[TOC]

## Abstract

介绍了本文的相关工作，主要延续了之前史飞学长的论文成果，再次进行了验证，同时在真车上进行了实际测试。

`MVCA`算法，主要应用在多车分布式计算情况。在这又列举了其优势。

---

## I. INTRODUCTION

> 记录几个概念：
>
> `ETSI`: European Telecommunication Standards Institute(欧洲电信标准协会)
>
> `CAM`: Cooperative Awareness Message(协作感知信息)
>
> `DENM` : Decentralized Environmental Notification Message(分布式事件通知信息)

在这强调了CAM通信的重要性，即延迟会导致汽车的航向角以及速度距离发生不可接受的误差。

*the timing of generating a CAM message satisfies one of the following conditions: The maximum time interval*
*between CAM messages is $1s$; the minimum time between CAM messages is $0.1s$; the yaw angle of the vehicle varies by more than 4 degrees; the current position coordinate of the vehicle changes more than 5 m; the current speed of the vehicle changes by more than $1m/s$. It can be seen that CAM messages are very sensitive and accurate.*

在介绍本文工作中，提到一点关于MVCA算法的车辆间延迟以及丢包率的研究成果，指出：**在恒定丢包率的情况下，通过减少分组传输间隔，可以在一定程度上减轻分组丢失对轨迹规划的负面影响**。但并没有再具体描述。

*In the case of a constant packet loss rate, by reducing the packet transmission interval, the negative impact of packet loss on trajectory planning can be mitigated to some extent*

---

## II. RELATED WORK

> Introduces commonly used types of trajectory planning algorithms and their advantages and disadvantages. It then compares the differences between existing methods and the `MVCA`. 
>
> 可以联系之前的史飞学长的论文，基本类似(英文翻译版)

### A.Graph Search

> **图搜索**
>
> 参考文献：An algorithm for planning collision-free paths among polyhedral obstacles, 

### B.Grid Method

> **网格法**
>
> 参考文献：Perception and remembrance of the environment during real-time navigation of a mobile robot, 

### C.Artificial Potential Field

>**人工势场法**
>
>参考文献：
>
>- 理论的提出：Real-time obstacle avoidance for manipulators and mobile robots 

 同样，在这介绍了人工势场法的一些**限制和不足**

### D. Artificial Neural Network

> ANN算法，自己科普一下，目前应用较广

*The artificial neural network (ANN) is a technique based on a nonlinear mapping system.* 

### E. Genetic Algorithm

> 遗传算法

遗传算法（GA）是一种受自然选择和遗传启发的数值优化方法

*A genetic algorithm (GA) is a numerical optimization method inspired by natural selection and heredity* 

### F. Comparison Analysis(总结)



















