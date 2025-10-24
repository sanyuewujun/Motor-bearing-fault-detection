# 基于CWRU数据集的电机故障检测
## 一.Neural network 训练及实验环境如下：
### 硬件信息
CPU 型号:Inte164 Family 6 Model 183 Stepping 1, GenuineIntel
帧率(FPS):54.87841226130907
GPU 信息:
型号:NVIDIA GeForce RTX 4090
总显存:24564.0 MB
空闲显存:19315.0 MB
已用显存:4828.0 MB
RAM 大小:63.8177604675293 GB
### 软件信息
Python 版本:3.9.19 (main, May 6 2024, 20:12:36) [MSC v.1916 64 bit (AMD64)]
CUDA 版本:12.1
PyTorch 版本:2.3.0+cu121
Torchvision 版本:0.18.0+cu121
## 二.使用方法：
### 1.下载data_deal文件夹（该文件夹内为数据集）。
### 2.下载自己需要的模型和对应算法
### 3.代码运行需要的文件结构如下：
Motor-bearing-fault-fetection:
├─data_deal
│      105.mat
│      118.mat
│      130.mat
│      169.mat
│      185.mat
│      197.mat
│      209.mat
│      222.mat
│      234.mat
│      97.mat
│
└─mfd-stft-resnet50
        mfd-stft-resnet50.ipynb

#### 注：
1.生成的数据集以及生成的权重参数会存放在对应模型的文件夹内。
2.若神经网络模型无法运行，请优先检查代码中的路径是否正确。
3.详情请阅读DOCX文件“一维转二维报告”
