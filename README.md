# 计图挑战热身赛

## 简述

本项目使用 Jittor 深度学习框架，在数字图片数据集 MNIST 上训练一个将随机噪声和类别标签映射为数字图片的 Conditional GAN 模型，生成指定数字序列对应的图片。

## Jittor安装

Jittor 框架目前支持 Linux 或 Windows(包括 WSL)，mac 系统请安装虚拟机解决。需要使用 Python 及 C++ 编译器（g++ 或 clang）。Jittor 提供了三种安装方法：docker，pip 和手动安装，具体安装教程请参考：

https://cg.cs.tsinghua.edu.cn/jittor/download/

## 如何使用

在根目录下，使用命令行运行，结果图片保存至result.png中：

```
python3 CGAN.py
```
