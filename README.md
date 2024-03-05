# aiops_study
智能运维是一项系统工程，算法只是其中一个环节，好的算法还需要高效的平台去支持投产和应用。    
本文主要整理aiops领域相关的方法，并进行持续学习。   

本页面的编写，学习参考markdown[语法](https://markdown.com.cn/basic-syntax/lists.html)   

## 异常检测

## 根因分析

## 故障预测
### 事件预测
### 时序预测

## 告警事件
### 告警收敛
1. 【2023IEEE】[Dynamic Graph Neural Networks-based Alert Link
Prediction for Online Service Systems](https://zhendong2050.github.io/res/ASE23.pdf)
    - 首先构建某个时刻的告警快照图，里面包含了告警、指标、以及初步得到的一些链接关系。这些关系包括指标相似关系、指标触发告警的关系。基于多个连续快照图，可以建模得到告警的时空表示，此所谓动态图神经网络建模。图中还结合了告警嵌入（语义信息）、指标嵌入（时序信息）的方法。最终为了预测告警之间的链接，还需要打标数据集，这是一大门槛。但也因为是有监督学习，可以实现端到端训练，充分利用深度学习的表达能力。最后有[源码](https://github.com/FudanSELab/DyAlert)开放，值得点个赞。

  
### 事件分类
### 告警优先级排序


