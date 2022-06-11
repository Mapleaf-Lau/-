| 第二届计图挑战赛

# Jittor 计算热身手写图像生成 JNeRF

<img src='imgs/result.png'/>



## 简介

第二届计算热身赛——以GAN为框架的手写数字图像生成<br>
本赛道将在数字图片数据集 MNIST 上训练 Conditional GAN（Conditional generative adversarial nets）模型，通过输入一个随机向量 z 和额外的辅助信息 y (如类别标签)，生成特定数字的图像。<br>
本项目包含了第二届计图挑战赛计图 - 热身赛比赛的代码实现。本项目的特点是：采用了CGAN网络方法对MNIST数据集处理，取得了生成特点手写数字的的效果。

## 安装 

#### 运行环境
- ubuntu 20.04 LTS
- python >= 3.7
- jittor >= 1.3.0

#### 安装依赖
执行以下命令安装 python 依赖
```
pip install -r requirements.txt
```

## 训练

```
python CGAN.py
```




## 致谢

此项目基于论文 *A Style-Based Generator Architecture for Generative Adversarial Networks* 实现，部分代码参考了 [jittor-gan](https://github.com/Jittor/gan-jittor)。
