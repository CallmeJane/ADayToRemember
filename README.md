# 参考智源大会每日资讯
记录每天有用的ai技术
# 2021.1
## 2021.1.18
(1)给AI从业者的重要年终参考——**谷歌两万字博客总结自身2020人工智能进展**(https://mp.weixin.qq.com/s/gcR8_61A6gP1fkDDnUvr_Q)  
(2)谷歌最新发布数据集：Open Images V6 来了！新增局部叙事标注形式(https://storage.googleapis.com/openimages/web/index.html)  
(3)谷歌在**MediaPipe**中开源了新的感知推理功能和解决方案，例如设备上的面部、手和姿势预测，实时身体姿势跟踪，实时虹膜跟踪和深度估计以及实时3D对象检(https://github.com/google/mediapipe)     (4)AWS机器学习服务的概况与发展(https://mp.weixin.qq.com/s/NLKjAYuw-y_KhgXMyGs-Dw)    
(5)综述 | GAN逆映射(inversion)技术：全面调研（2016-2020） (https://hub.baai.ac.cn/view/5882)    
(6)第一个对**整个人体进行人工标注的基准**，包括133个密集的地标，其中68个在脸上，42个在手上，23个在身体和脚上（https://github.com/jin-s13/COCO-WholeBody）    
(7)**HRnet**目前比较好的模型，利用**多尺度**提高heatmap准确度(https://www.aiuai.cn/aifarm927.html)  
(8)一个值得深思的问题？**为什么验证集的loss会小于训练集的loss**（https://zhuanlan.zhihu.com/p/89623222）  
## 2021.1.20
(1)【机器学习】Cross-Validation（交叉验证）详解 https://zhuanlan.zhihu.com/p/24825503?refer=rdatamining  
(2)【思考】 mask标签数据如何训练？是全局部还是全局的数据参加训练?模型生成掩码可以提高其他任务的准确度(eg:分类，回归，maskrcnn)?
(3)【比赛方案流程】思路的构建（模型的选择），epoch的选择，数据集分布，数据增强（加噪，将噪），交叉验证，学习率的设置，多任务loss的均衡，模型训练结果的可视化（可视化可帮助分析）  
(4)【数据增强库】OpenCV，PIL，Skimage你pick谁（https://www.jianshu.com/p/bda23f8cfd84）  
Python下PIL, OpenCV, SKImage图像的相互转换（https://blog.csdn.net/u013832707/article/details/90293585）
## 2021.1.21
(1)2021/01/19 必读 |谷歌提出「元伪标签」半监督学习方法，将ImageNet的top-1提升到90.2% https://hub.baai.ac.cn/view/5947  
(2)UIUC韩家炜团队发文：文本分类只需标签名称，不需要任何标注数据 | EMNLP 2020 https://hub.baai.ac.cn/view/5972  
(3)共享单车站点规划 | 基于门控图神经网络对共享单车停放进行动态管理 https://hub.baai.ac.cn/view/5976  
(4)2021/01/20 必读 | CVPR 2021评审出炉，评审员奇葩意见遭热议 https://hub.baai.ac.cn/view/5968  
## 2021.1.24
(1)T-PAMI 2021 | **换个损失函数就能实现数据扩增**(语义层面的数据增强)？https://hub.baai.ac.cn/view/6013  
(2)trian img size必须和test img size**一致**  
(3)AI跳舞哪家强？**谷歌**3D舞者闻**歌**起**舞**，挑战**DanceNet**(多模态训练) https://mp.weixin.qq.com/s/duxL22Gohnj9SfSU3YmQfw  
论文地址：https://arxiv.org/pdf/2101.08779v1.pdf  
项目地址：https://google.github.io/aichoreographer/  
(4)AIST++数据集， AIST++ 是一个大规模 3D 舞蹈动作数据集，包含大量伴随音乐的3D舞蹈动作。其中每一帧都具备以下额外标注：  
9 种视角，包括摄像机的内外参数；  
17 种 COCO 格式的人类关节位置，包含 2D 和 3D 形式；  
24 个 SMPL 姿势参数，以及全局扩展和平移。  
数据集地址：https://google.github.io/aistplusplus_dataset/  
(5)**目标检测Anchor**是什么？怎么科学设置？人人都能彻底搞懂的Anchor深度解析 https://mp.weixin.qq.com/s/Qvjk7mz8d9lxeyIMND1mPA  
**anchor只有跟你要检测的物体的大小和长宽比更贴近**，才能让模型的效果更好。YOLOv2版本开始使用**kmeans方法聚类**得到**合适的anchor**  
## 2021.1.25
(1)动手学习深度学习 **mxnet** https://zh.d2l.ai/  
(2)了解mxnet的fine tune https://zhuanlan.zhihu.com/p/42441251,  
Fine-tuning a pre-trained model: 33 output nodes vs 17 https://github.com/MVIG-SJTU/AlphaPose/issues/187  
(3)创建新的HDF5数据集 https://github.com/MVIG-SJTU/AlphaPose/issues/193，https://github.com/MVIG-SJTU/AlphaPose/issues/238  
(4)alphapose的输出格式 https://github.com/MVIG-SJTU/AlphaPose/blob/pytorch/doc/output.md  
因为前17个输出是COCO关键点（COCO有17个关键点），而其他16个是MPII关键点（MPII有16个关键点），所以有33个输出  
## 2021.1.26
(1)**My Neural Network isn't working! What should I do?(经典)** http://theorangeduck.com/page/neural-network-not-working  
(2)3d人体姿态检测 https://github.com/facebookresearch/VideoPose3D  
(3)PIL(Python Imaging Library)教程 https://blog.csdn.net/yjwx0018/article/details/52852067  
(4)每个任务的损失函数中学习另一个**噪声参数（noise parameter）** https://github.com/yaringal/multi-task-learning-example/blob/master/multi-task-learning-example-pytorch.ipynb  
(5)如何利用深度学习模型实现**多任务学习**？这里有三点经验(loss,学习率)  https://zhuanlan.zhihu.com/p/56900939?utm_source=ZHShareTargetIDMore  
## 2021.1.27 
(1)目标检测｜综述：**通用**目标检测中的**遮挡**问题处理 https://hub.baai.ac.cn/view/6081  
(2)Learning Deep Features for Discriminative Localization CAM 探究我们的CNN在学习图像的时候到底重点关注在哪个部分  
(3)图像动态化｜ 用于视频会议的单样本自由视角动态人脸合成方法 https://hub.baai.ac.cn/view/6110  
(4)开源项目｜**基于YOLO-V5**实现行人社交距离风险提示(附完整源码) https://mp.weixin.qq.com/s/uCb8EaoL0EXzUahXyC18vQ  
## 2021.1.28
(1)对于新项目，首先重要的是**参数设置，参数设置，参数设置**（先看各个参数的作用，没弄明白不要加）  
(2)对于模型的调参，重要的是**先列好对比试验，再调整参数**（严格保证修改过的版本和未修改过版本的记录，做到不反复修改）  
(3)argparse学习
```python
#coding=utf-8
import argparse

parser=argparse.ArgumentParser(description='This is a arg')
parser.add_argument("--verbose", help="increase output verbosity",
                    action="store_true")
parser.add_argument('--detector', dest='detector',
                    help='detector name', default="yolo")
parser.add_argument('--save_img', default=False, action='store_true',
                    help='save result as image')
parser.add_argument('--conf', dest='confidence', type=float, default=0.1,
                    help='bounding box confidence threshold')

#'--*' '-*':使用的名称
#dest:字典中的名称
#type:输入类型需正确
#default:默认值
#action
#help:描述

args=parser.parse_args()
print(args.save_img)
print(args.confidence)    #字典中存储的名称
```

##2021.1.29
(1)CNN与Transformer的强强联合！谷歌最新开源BoTNet，ImageNet达84.7%准确率 https://mp.weixin.qq.com/s/BlFlJsX65Jp4i0-5s_pkKA  
(2)机器学习应用设计阶段的 10 个陷阱和 11 个最佳实践 https://mp.weixin.qq.com/s/PdsxhMfHjql9gkWKSD0olA  
(3)深入理解renset https://blog.csdn.net/chenyuping333/article/details/82344334  
**resnet34和resnet50区别** 基础block不同（目的是**减少参数**），前者是两个3*3，后者是1*1（降低通道）,3*3,1*1,且输出通道是前者的4倍      
**resnetv1和rensetv2区别** **conv,bn,relu的顺序不同**，前者是conv->bn->relu,后者是bn->relu->conv,并且下采样的位置不同，详见mxnet实现  
(4)深度学习参数量的计算(**各个通道公用卷积核**) https://www.cnblogs.com/lllcccddd/p/10671879.html    
(5)Darknet53网络结构图及代码实现(主要由卷积和残差1*1,3*3实现) https://blog.csdn.net/leiduifan6944/article/details/104857968  
