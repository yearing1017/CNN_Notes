# DL_Notes

## 📚 专栏目录

- [神经网络与深度学习](#NN_DL)
- [卷积神经网络原理与视觉实践](#CNN)
- [经典CNN网络模型](#C_CNN)
- [语义分割网络模型](#FCN)
- [实例分割](#I_seg)
- [计算机视觉中的注意力机制](#CV_attention)
- [目标检测](#OB_D)
- [论文](#Paper)

<a id="NN_DL"></a>
## 1.神经网络与深度学习

- [1-1 神经网络与深度学习（1）-深度学习概论](http://yearing1017.cn/2019/04/12/%E7%A5%9E%E7%BB%8F%E7%BD%91%E7%BB%9C%E4%B8%8E%E6%B7%B1%E5%BA%A6%E5%AD%A6%E4%B9%A0-1-%E6%B7%B1%E5%BA%A6%E5%AD%A6%E4%B9%A0%E6%A6%82%E8%AE%BA/)
- [1-2 神经网络与深度学习（2）-逻辑回归](http://yearing1017.cn/2019/04/27/%E7%A5%9E%E7%BB%8F%E7%BD%91%E7%BB%9C%E4%B8%8E%E6%B7%B1%E5%BA%A6%E5%AD%A6%E4%B9%A0-2-%E9%80%BB%E8%BE%91%E5%9B%9E%E5%BD%92/)
- [1-3 神经网络与深度学习（3）-Python与向量化](http://yearing1017.cn/2019/05/02/%E7%A5%9E%E7%BB%8F%E7%BD%91%E7%BB%9C%E4%B8%8E%E6%B7%B1%E5%BA%A6%E5%AD%A6%E4%B9%A0-3-Python%E4%B8%8E%E5%90%91%E9%87%8F%E5%8C%96/)
- [机器学习常见评价指标及分割指标MIoU](http://yearing1017.cn/2020/02/07/语义分割指标MIoU/)
- [MIoU基于PyTorch的计算](http://yearing1017.cn/2020/02/17/MIoU-PyTorch/)
- [深度可分离卷积](http://yearing1017.cn/2020/02/15/Depthwise-separable-convolution/)
- [Kappa系数基于PyTorch的计算](http://yearing1017.cn/2020/02/27/基于混淆矩阵的Kappa系数的计算/)
- [过拟合问题原因](https://www.cnblogs.com/eilearn/p/9203186.html)
- [k折交叉验证](https://zhuanlan.zhihu.com/p/67563863)
- [sklearn中k折交叉验证的实现](https://scikit-learn.org/stable/modules/cross_validation.html#cross-validation) 
- [离线数据增强与在线数据增强](https://zhuanlan.zhihu.com/p/56139575)
- [语义分割中的三种上采样方式：转置卷积、线性插值、Unpooling](https://zhuanlan.zhihu.com/p/92123010)
- [上采样-双线性插值的理解](https://www.zhihu.com/search?type=content&q=%E4%B8%8A%E9%87%87%E6%A0%B7%20%E5%8F%8C%E7%BA%BF%E6%80%A7%E6%8F%92%E5%80%BC)
- [上采样-最邻近插值](https://zhuanlan.zhihu.com/p/89421892)
- [某大佬对align_corners的理解](https://zhuanlan.zhihu.com/p/87572724)
- [深度学习的11个技巧](https://zhuanlan.zhihu.com/p/138024517)
- [Focal-Loss损失函数的理解](https://www.zhihu.com/search?q=focal%20loss%20pytorch&type=content)
- [labelme标注工具的安装及使用总结](http://yearing1017.cn/2020/05/30/labelme%E7%9A%84%E5%AE%89%E8%A3%85%E5%8F%8A%E4%BD%BF%E7%94%A8/)
- [一份很全的Pytorch数据增强的总结](https://segmentfault.com/a/1190000022784467)
- [Batch Normalization原理与实战](https://zhuanlan.zhihu.com/p/34879333)
- [@张航-SyncBN-跨卡同步BN](https://zhuanlan.zhihu.com/p/40496177)
- [对DO-Conv的基于deeplabv3的测试](https://github.com/yearing1017/DL_Notes/blob/master/DO_Conv_test.ipynb)

<a id="CNN"></a>
## 2.卷积神经网络原理与视觉实践

- [CNN学习笔记（1）-CNN基本结构简介](http://yearing1017.cn/2019/07/28/CNN%E5%9F%BA%E7%A1%80%E7%9F%A5%E8%AF%86/)
- [CNN学习笔记（2）-CNN基本流程](http://yearing1017.cn/2019/08/04/CNN%E5%9F%BA%E6%9C%AC%E6%B5%81%E7%A8%8B/)
- [CNN学习笔记（3）-CNN_卷积层](http://yearing1017.cn/2019/08/11/CNN基本部件-卷积层/)
- [CNN学习笔记（4）-CNN_池化层](http://yearing1017.cn/2019/08/13/CNN%E5%9F%BA%E6%9C%AC%E9%83%A8%E4%BB%B6-%E6%B1%87%E5%90%88%E5%B1%82/)
- [CNN学习笔记（5）-CNN_激活函数与全连接层](http://yearing1017.cn/2019/08/14/CNN-%E6%BF%80%E6%B4%BB%E5%87%BD%E6%95%B0%E4%B8%8E%E5%85%A8%E8%BF%9E%E6%8E%A5%E5%B1%82/)
- [CNN学习笔记（6）-CNN_填充和步幅](http://yearing1017.cn/2019/09/05/CNN-%E5%A1%AB%E5%85%85%E5%92%8C%E6%AD%A5%E5%B9%85/)
- [CNN学习笔记（7）-CNN_channels](http://yearing1017.cn/2019/09/07/CNN-channels/)
- [CNN学习笔记（8）-张量](http://yearing1017.cn/2019/11/12/%E7%A5%9E%E7%BB%8F%E7%BD%91%E7%BB%9C-%E5%BC%A0%E9%87%8F/)
- [DL-知识点随笔积累](http://yearing1017.cn/2019/11/14/DL-%E7%9F%A5%E8%AF%86%E7%82%B9%E9%9A%8F%E7%AC%94%E7%A7%AF%E7%B4%AF/)
  - 全连接层流程及softmax loss
  - 过拟合欠拟合问题
  - 权重衰减的推导
  - 归一化
  - 网络参数的几种初始化方式
  - 机器学习模型的三种评估方法
  - 感受野
  - 全局平均池化
  - 张量的维度判断技巧
  - Focal Loss
  - 有关PyTorch中nn.CrossEntropyLoss()加入权重的理解
  - Pseudo Labeling 训练策略
  - CNN计算力FLOPs
  - 评价指标ROC和AUC
  
<a id="C_CNN"></a>
## 3.经典CNN网络模型学习
- [1. LeNet-5](http://yearing1017.cn/2019/09/09/CNN-LeNet-5/)
- [2. AlexNet](http://yearing1017.cn/2019/09/10/CNN-AlexNet/)
- [3. VGGNet-16](http://yearing1017.cn/2019/09/13/CNN-VGGNet16/)
- [4. GoogLeNet_v1-v3](http://yearing1017.cn/2019/09/24/GoogLeNet-V1-V3/)
- [5. ResNet_DRN](http://yearing1017.cn/2019/09/26/ResNet-DRN/)
- [7. DenseNet](http://yearing1017.cn/2019/10/29/DenseNet-CVPR2017/)

<a id="FCN"></a>
## 4.语义分割网络学习
- [1. FCN](http://yearing1017.cn/2019/10/17/FCN-%E8%AF%AD%E4%B9%89%E5%88%86%E5%89%B2/)
- [2. UNet](http://yearing1017.cn/2019/11/21/U-Net-paper/)
- [3. Deeplabv3](https://github.com/yearing1017/Deeplabv3_Pytorch/blob/master/Deeplab_v3.md)
- [4. Deeplabv3+](https://github.com/yearing1017/Paper_Note/blob/master/论文Markdown笔记/deeplabv3%2B_paper.md)
- [5. DFN](http://yearing1017.cn/2020/03/19/DFN-paper/)
- [6. Non-local-Net](http://yearing1017.cn/2020/04/05/Non-local-paper/)
- [7. CCNet](http://yearing1017.cn/2020/03/26/CCNet-paper/)
- [8. DAN](http://yearing1017.cn/2020/04/06/DAN-paper/#more)
- [9. PANet](http://yearing1017.cn/2020/04/10/PAN-paper/)
- [10. ResNeSt](http://yearing1017.cn/2020/05/17/ResNeSt-Split-Attention-Networks/)
- [11. FarSeg](http://yearing1017.cn/2020/07/15/FarSeg-paper/)
- [12. G-SCNN](http://yearing1017.cn/2020/08/03/G-SCNN-paper/)
- [13. GFF]()

<a id="I_seg"></a>
## 5.实例分割

### 5.1 相关资料积累
- [实例分割全面综述：从Mask R-CNN到BlendMask](https://zhuanlan.zhihu.com/p/110132002)

### 5.2 R-CNN系列
- R-CNN:[Rich feature hierarchies for accurate object detection and semantic segmentation Tech report (v5)](http://cn.arxiv.org/pdf/1311.2524.pdf)
- [R-CNN学习笔记](http://yearing1017.cn/2020/04/26/R-CNN-paper/)
- Fast R-CNN:[Fast R-CNN](http://cn.arxiv.org/pdf/1504.08083v2)
- [Fast R-CNN学习笔记](http://yearing1017.cn/2020/04/27/Fast-R-CNN/)
- Faster R-CNN:[Faster R-CNN: Towards Real-Time Object Detection with Region Proposal Networks](http://cn.arxiv.org/pdf/1506.01497.pdf)
- [Faster R-CNN学习笔记](http://yearing1017.cn/2020/04/29/Faster-R-CNN/)
- Mask R-CNN:[Mask R-CNN](https://arxiv.org/pdf/1703.06870.pdf)
- [Mask R-CNN学习笔记](http://yearing1017.cn/2020/05/04/Mask-R-CNN/)

<a id="CV_attention"></a>
## 6.计算机视觉中的Attention机制
- [简单认识CV中的注意力机制](https://blog.csdn.net/paper_reader/article/details/81082351)
- [Attention机制的文章总结](https://blog.csdn.net/humanpose/article/details/85332392)
- [深入理解注意力机制](https://zhuanlan.zhihu.com/p/40197380)
- [CV中的Attention机制-SENet中的SE模块]( https://zhuanlan.zhihu.com/p/102035721)
- [视觉注意力机制 | Non-local模块与Self-attention的之间的关系与区别](https://zhuanlan.zhihu.com/p/110130098)
- SENet论文笔记：[博文地址](http://yearing1017.cn/2020/05/11/SENet-paper/)
- SKNet论文笔记：[博文地址](http://yearing1017.cn/2020/05/14/SKNet/)
- [融合SENet、SKNet、ResNeXt、ResNet的backbone网络：ResNeSt](http://yearing1017.cn/2020/05/17/ResNeSt-Split-Attention-Networks/)
- [x] CCNet论文：[论文地址](http://cn.arxiv.org/pdf/1811.11721.pdf)
- [x] CCNet论文的实现：[官方实现](https://github.com/speedinghzl/CCNet)、[非官方简单实现](https://github.com/Serge-weihao/CCNet-Pure-Pytorch)
- [x] Non-local-Net论文：[论文地址](https://arxiv.org/abs/1711.07971)
- [x] DAN论文：[Dual Attention Network for Scene Segmentation](https://arxiv.org/abs/1809.02983)
- [x] DAN代码实现：[代码地址1](https://github.com/yiskw713/DualAttention_for_Segmentation)、[代码地址2](https://github.com/junfu1115/DANet/)
- [x] PANet论文：[Pyramid Attention Network for Semantic Segmentation](http://cn.arxiv.org/pdf/1805.10180v1.pdf)
- [x] PAN的代码实现：[参考1](https://github.com/JaveyWang/Pyramid-Attention-Networks-pytorch/)、[参考2](https://github.com/Andy-zhujunwen/pytorch-Pyramid-Attention-Networks-PAN-/)，后者是前者的改进
- [x] DFN的实现：[参考](https://github.com/ycszen/TorchSeg/tree/master/model/dfn)
- [ ] EMANet论文：[ Expectation-Maximization Attention Networks for Semantic Segmentation](https://zhuanlan.zhihu.com/p/78018142)

<a id="OB_D"></a>
## 7. 目标检测

### 7.1 资料积累
- [理解目标检测当中的mAP](https://blog.csdn.net/hsqyc/article/details/81702437)
- [一文搞懂目标检测的常用指标（Pascal VOC与COCO）](http://activepony.com/shen-du-xue-xi/mu-biao-jian-ce/mu-biao-jian-ce-ping-jie-zhi-biao/)
- [转载：Yolov1-v5系列解读（上）](https://zhuanlan.zhihu.com/p/183261974)
- [转载：Yolov1-v5系列解读（中）](https://zhuanlan.zhihu.com/p/183781646)
- [转载：Yolov1-v5系列解读（下）](https://zhuanlan.zhihu.com/p/186014243)
- [转载：Yolov1详细解读](https://zhuanlan.zhihu.com/p/46691043)
- [转载：Yolov2深入解读](https://zhuanlan.zhihu.com/p/47575929)


### 7.2 two-stage 算法
- R-CNN:[Rich feature hierarchies for accurate object detection and semantic segmentation Tech report (v5)](http://cn.arxiv.org/pdf/1311.2524.pdf)
- [R-CNN学习笔记](http://yearing1017.cn/2020/04/26/R-CNN-paper/)
- Fast R-CNN:[Fast R-CNN](http://cn.arxiv.org/pdf/1504.08083v2)
- [Fast R-CNN学习笔记](http://yearing1017.cn/2020/04/27/Fast-R-CNN/)
- Faster R-CNN:[Faster R-CNN: Towards Real-Time Object Detection with Region Proposal Networks](http://cn.arxiv.org/pdf/1506.01497.pdf)
- [Faster R-CNN学习笔记](http://yearing1017.cn/2020/04/29/Faster-R-CNN/)

### 7.3 one-stage算法
- Yolov1论文：[You Only Look Once: Uniﬁed, Real-Time Object Detection](http://xxx.itp.ac.cn/pdf/1506.02640v5)
- [Yolov1学习笔记]()
- [转载：Yolov1详细解读](https://zhuanlan.zhihu.com/p/46691043)
- Yolov2论文：[YOLO9000: Better, Faster, Stronger](http://xxx.itp.ac.cn/pdf/1612.08242)
- [Yolov2学习笔记](http://yearing1017.cn/2020/07/22/Yolov2-paper/)
- [转载：Yolov2深入解读](https://zhuanlan.zhihu.com/p/47575929)

<a id="Paper"></a>
## 8.论文

###  8.1 论文下载tips：arxiv国内镜像的访问及PDF下载
- Cornel University提供支持的原访问地址：https://arxiv.org
- 国内中科院镜像的地址：cn.arxiv.org 或者：xxx.itp.ac.cn
- 在原网站找到文章后，可以把https://替换为cn. 或者：http://xxx.itp.ac.cn/
- 如：cn.arxiv.org/pdf/1710.06081v2 或者：http://xxx.itp.ac.cn/pdf/1506.02640v5

### 8.2 已读论文列表

| [AlexNet](https://papers.nips.cc/paper/4824-imagenet-classification-with-deep-convolutional-neural-networks.pdf) |          [VGG](https://arxiv.org/pdf/1409.1556.pdf)          |        [ResNet](https://arxiv.org/pdf/1512.03385.pdf)        |      [DenseNet](https://arxiv.org/abs/1608.06993)      |          [SENet](https://arxiv.org/abs/1709.01507)           |        [SKNet](https://arxiv.org/pdf/1903.06586.pdf)         |
| :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: |
|        **[DoConv](https://arxiv.org/abs/2006.12030)**        |        **[PyConv](https://arxiv.org/abs/2006.11538)**        | **[FCN](https://people.eecs.berkeley.edu/~jonlong/long_shelhamer_fcn.pdf)** |    **[UNet](https://arxiv.org/pdf/1505.04597.pdf)**    |   **[DilationConv](https://arxiv.org/pdf/1511.07122.pdf)**   |   **[Deeplabv3](https://arxiv.org/pdf/1706.05587v3.pdf)**    |
|    **[Deeplabv3+](https://arxiv.org/pdf/1802.02611.pdf)**    | **[DepthwiseConv](http://yearing1017.cn/2020/02/15/Depthwise-separable-convolution/)** |       **[Xception](https://arxiv.org/abs/1610.02357)**       |     **[SegNet](https://arxiv.org/abs/1505.07293)**     |         **[DFN](https://arxiv.org/abs/1804.09337)**          |     **[CCNet](http://cn.arxiv.org/pdf/1811.11721.pdf)**      |
|   **[Non-local](http://cn.arxiv.org/pdf/1711.07971.pdf)**    |         **[DAN](https://arxiv.org/abs/1809.02983)**          |        **[PAN](https://arxiv.org/abs/1805.10180v1)**         | **[ResNeSt](https://hangzhang.org/files/resnest.pdf)** | **[FarSeg](https://openaccess.thecvf.com/content_CVPR_2020/papers/Zheng_Foreground-Aware_Relation_Network_for_Geospatial_Object_Segmentation_in_High_Spatial_CVPR_2020_paper.pdf)** | **[OCRNet](https://link.zhihu.com/?target=https%3A//arxiv.org/pdf/1909.11065.pdf)** |
|        **[ACNet](https://arxiv.org/abs/1905.10089)**         |      **[R-CNN](http://cn.arxiv.org/pdf/1311.2524.pdf)**      |    [**Fast R-CNN**](http://cn.arxiv.org/pdf/1504.08083v2)    |  [**Faster R-CNN**](https://arxiv.org/abs/1506.01497)  |    [**Mask R-CNN**](https://arxiv.org/pdf/1703.06870.pdf)    |   **[EfﬁcientDet](https://arxiv.org/pdf/1911.09070.pdf)**    |

