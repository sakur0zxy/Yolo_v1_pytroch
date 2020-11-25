# Yolo_v1_pytroch
基于pytorch框架使用python编程实现Yolo_v1

* 我的学习日记（1）

当然，这次主要是参考网上大佬的代码做的，主要代码基本一样，希望大家能去顶一下大佬，[这里这里](https://blog.csdn.net/weixin_41424926/article/details/105383064)<br>

好了，下面正式开始：

## 1. 简单介绍
  Yolo，全称“You Only Look Once”，是一种用于检测图片中目标的深度学习网络。<br>
  以往的分类网络输出是类别，如 x = 0，1，2，3...而Yolo是将类别（Class）、检测框（Bounding Box）及置信度（Confidence）一起训练输出的。
  > 因为神经网络可以看成是一种映射（类似输入x，输出y），所以只要能正确的设计损失函数（Loss），便可得到我们需要的映射训练结果？（存疑，不是很确定）
  

