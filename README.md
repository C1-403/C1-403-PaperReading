# X-PaperReading

>by KingXHJ

## 目录
  - [深度学习论文](#深度学习论文)
    - [计算机视觉-CNN](#计算机视觉-CNN)
    - [计算机视觉-Transformer](#计算机视觉-Transformer)
    - [生成模型](#生成模型)
    - [计算机视觉-ObjectDetection](#计算机视觉-ObjectDetection)
    - [计算机视觉-对比学习](#计算机视觉-对比学习)
    - [自然语言处理-Transformer](#自然语言处理-Transformer)
    - [图神经网络](#图神经网络)
    - [优化算法](#优化算法)
    - [新领域应用](#新领域应用)
  - [系统](#系统)
## 深度学习论文

### 计算机视觉-CNN


| 笔记 | 年份 | 名字                                                         | 简介                 | 引用 |
| ------ | ---- | ------------------------------------------------------------ | -------------------- | ------------------------------------------------------------ |
| [✅](https://github.com/KingXHJ/X-PaperReading/blob/main/DeepLearning/CV%20CNN/ImageNet%20Classification%20with%20Deep%20Convolutional%20Neural%20Networks.md)      | 2012 | [AlexNet](https://papers.nips.cc/paper/2012/file/c399862d3b9d6b76c8436e924a68c45b-Paper.pdf) | 深度学习热潮的奠基作                   | [![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fabd1c342495432171beb7ca8fd9551ef13cbd0ff%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/ImageNet-classification-with-deep-convolutional-Krizhevsky-Sutskever/abd1c342495432171beb7ca8fd9551ef13cbd0ff) |
| [✅](https://github.com/KingXHJ/X-PaperReading/blob/main/DeepLearning/CV%20CNN/Going%20deeper%20with%20convolutions.md)| 2014 | [GoogleNet](https://arxiv.org/pdf/1409.4842.pdf) | 使用并行架构构造更深的网络                   | [![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fe15cf50aa89fee8535703b9f9512fca5bfc43327%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Going-deeper-with-convolutions-Szegedy-Liu/e15cf50aa89fee8535703b9f9512fca5bfc43327) |
| [✅](https://github.com/KingXHJ/X-PaperReading/blob/main/DeepLearning/CV%20CNN/VERY%20DEEP%20CONVOLUTIONAL%20NETWORKS%20FOR%20LARGE-SCALE%20IMAGE%20RECOGNITION.md) | 2015 | [VGG](https://arxiv.org/pdf/1409.1556.pdf) | 使用 3x3 卷积构造更深的网络                   | [![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Feb42cf88027de515750f230b23b1a057dc782108%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Very-Deep-Convolutional-Networks-for-Large-Scale-Simonyan-Zisserman/eb42cf88027de515750f230b23b1a057dc782108) |
| [✅](https://github.com/KingXHJ/X-PaperReading/blob/main/DeepLearning/CV%20CNN/Deep%20Residual%20Learning%20for%20Image%20Recognition.md)  | 2015 |  [ResNet](https://arxiv.org/pdf/1512.03385.pdf) | 构建深层网络都要有的残差连接。               |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F2c03df8b48bf3fa39054345bafabfeff15bfd11d%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Deep-Residual-Learning-for-Image-Recognition-He-Zhang/2c03df8b48bf3fa39054345bafabfeff15bfd11d)  |
| [✅](https://github.com/KingXHJ/X-PaperReading/blob/main/DeepLearning/CV%20CNN/MobileNets%20Efficient%20Convolutional%20Neural%20Networks%20for%20Mobile%20Vision%20Applications.md) | 2017 | [MobileNet](https://arxiv.org/pdf/1704.04861.pdf) | 适合终端设备的小CNN                   |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F3647d6d0f151dc05626449ee09cc7bce55be497e%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/MobileNets%3A-Efficient-Convolutional-Neural-Networks-Howard-Zhu/3647d6d0f151dc05626449ee09cc7bce55be497e)  |
| [✅](https://github.com/KingXHJ/X-PaperReading/blob/main/DeepLearning/CV%20CNN/EfficientNet%20Rethinking%20Model%20Scaling%20for%20Convolutional%20Neural%20Networks.md)| 2020 | [EfficientNet](https://arxiv.org/pdf/1905.11946.pdf) | 通过架构搜索得到的CNN                   |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F4f2eda8077dc7a69bb2b4e0a1a086cf054adb3f9%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/EfficientNet%3A-Rethinking-Model-Scaling-for-Neural-Tan-Le/4f2eda8077dc7a69bb2b4e0a1a086cf054adb3f9)  |
| [✅](https://github.com/KingXHJ/X-PaperReading/blob/main/DeepLearning/CV%20CNN/NON-DEEP%20NETWORKS.md)| 2021 |  [Non-deep networks](https://arxiv.org/pdf/2110.07641.pdf) | 让不深的网络也能在ImageNet刷到SOTA                   | [![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F0d7f6086772079bc3e243b7b375a9ca1a517ba8b%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Non-deep-Networks-Goyal-Bochkovskiy/0d7f6086772079bc3e243b7b375a9ca1a517ba8b) |

### 计算机视觉-Transformer

| 笔记 | 年份 | 名字                                                         | 简介                 | 引用 |
| ------ | ---- | ------------------------------------------------------------ | -------------------- | ------------------------------------------------------------ |
| [✅](https://github.com/KingXHJ/X-PaperReading/blob/main/DeepLearning/CV%20Transformer/AN%20IMAGE%20IS%20WORTH%2016X16%20WORDS%20TRANSFORMERS%20FOR%20IMAGE%20RECOGNITION%20AT%20SCALE.md) | 2021 | [ViT](https://arxiv.org/pdf/2010.11929.pdf) | Transformer杀入CV界                   |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F7b15fa1b8d413fbe14ef7a97f651f47f5aff3903%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/An-Image-is-Worth-16x16-Words%3A-Transformers-for-at-Dosovitskiy-Beyer/7b15fa1b8d413fbe14ef7a97f651f47f5aff3903)  |
| [✅](https://github.com/KingXHJ/X-PaperReading/blob/main/DeepLearning/CV%20Transformer/Learning%20Transferable%20Visual%20Models%20From%20Natural%20Language%20Supervision.md) | 2021 |  [CLIP](https://openai.com/blog/clip/) | 图片和文本之间的对比学习                   |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F6f870f7f02a8c59c3e23f407f3ef00dd1dcf8fc4%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Learning-Transferable-Visual-Models-From-Natural-Radford-Kim/6f870f7f02a8c59c3e23f407f3ef00dd1dcf8fc4)  |
| [✅](https://github.com/KingXHJ/X-PaperReading/blob/main/DeepLearning/CV%20Transformer/Swin%20Transformer%20Hierarchical%20Vision%20Transformer%20using%20Shifted%20Windows.md) | 2021 | [Swin Transformer](https://arxiv.org/pdf/2103.14030.pdf) | 多层次的Vision Transformer                   | [![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fc8b25fab5608c3e033d34b4483ec47e68ba109b7%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Swin-Transformer%3A-Hierarchical-Vision-Transformer-Liu-Lin/c8b25fab5608c3e033d34b4483ec47e68ba109b7) |
| | 2021 | [MLP-Mixer](https://arxiv.org/pdf/2105.01601.pdf) | 使用MLP替换self-attention            |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F2def61f556f9a5576ace08911496b7c7e4f970a4%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/MLP-Mixer%3A-An-all-MLP-Architecture-for-Vision-Tolstikhin-Houlsby/2def61f556f9a5576ace08911496b7c7e4f970a4)  |
| [✅](https://github.com/KingXHJ/X-PaperReading/blob/main/DeepLearning/CV%20Transformer/Masked%20Autoencoders%20Are%20Scalable%20Vision%20Learners.md) | 2021 | [MAE](https://arxiv.org/pdf/2111.06377.pdf) | BERT的CV版             |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fc1962a8cf364595ed2838a097e9aa7cd159d3118%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Masked-Autoencoders-Are-Scalable-Vision-Learners-He-Chen/c1962a8cf364595ed2838a097e9aa7cd159d3118)  |

### 生成模型

| 笔记 | 年份 | 名字                                              | 简介         | 引用 |
| ------ | ---- | ------------------------------------------------- | ------------ | ------------------------------------------------------------ |
| [✅](https://github.com/KingXHJ/X-PaperReading/blob/main/DeepLearning/Generative%20model/Generative%20Adversarial%20Nets.md)  | 2014 | [GAN](https://papers.nips.cc/paper/2014/file/5ca3e9b122f61f8f06494c97b1afccf3-Paper.pdf) | 生成模型的开创工作                   |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F54e325aee6b2d476bbbb88615ac15e251c6e8214%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Generative-Adversarial-Nets-Goodfellow-Pouget-Abadie/54e325aee6b2d476bbbb88615ac15e251c6e8214)  |
|  | 2015 | [DCGAN](https://arxiv.org/pdf/1511.06434.pdf) | 使用CNN的GAN          |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F8388f1be26329fa45e5807e968a641ce170ea078%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Unsupervised-Representation-Learning-with-Deep-Radford-Metz/8388f1be26329fa45e5807e968a641ce170ea078)  |
|  | 2016 | [pix2pix](https://arxiv.org/pdf/1611.07004.pdf) |           |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F8acbe90d5b852dadea7810345451a99608ee54c7%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Image-to-Image-Translation-with-Conditional-Isola-Zhu/8acbe90d5b852dadea7810345451a99608ee54c7)  |
|  | 2016 | [SRGAN](https://arxiv.org/pdf/1609.04802.pdf) | 图片超分辨率          |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fdf0c54fe61f0ffb9f0e36a17c2038d9a1964cba3%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Photo-Realistic-Single-Image-Super-Resolution-Using-Ledig-Theis/df0c54fe61f0ffb9f0e36a17c2038d9a1964cba3)  |
|  | 2017 | [WGAN](https://arxiv.org/abs/1701.07875) | 训练更加容易          |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F2f85b7376769473d2bed56f855f115e23d727094%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Wasserstein-GAN-Arjovsky-Chintala/2f85b7376769473d2bed56f855f115e23d727094)  |
|  | 2017 | [CycleGAN](https://arxiv.org/abs/1703.10593) |           |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fc43d954cf8133e6254499f3d68e45218067e4941%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Unpaired-Image-to-Image-Translation-Using-Networks-Zhu-Park/c43d954cf8133e6254499f3d68e45218067e4941)  |
|  | 2018 | [StyleGAN](https://arxiv.org/abs/1812.04948) |           |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fceb2ebef0b41e31c1a21b28c2734123900c005e2%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/A-Style-Based-Generator-Architecture-for-Generative-Karras-Laine/ceb2ebef0b41e31c1a21b28c2734123900c005e2)  |
| | 2019 | [StyleGAN2](https://arxiv.org/pdf/1912.04958.pdf) |        |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Ff3e3d1f86a534a3654d0ee263142e44f4e2c61e9%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Analyzing-and-Improving-the-Image-Quality-of-Karras-Laine/f3e3d1f86a534a3654d0ee263142e44f4e2c61e9)  |
| | 2020 | [DDPM](https://arxiv.org/pdf/2006.11239.pdf) | Diffusion Models   |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F289db3be7bf77e06e75541ba93269de3d604ac72%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Denoising-Diffusion-Probabilistic-Models-Ho-Jain/289db3be7bf77e06e75541ba93269de3d604ac72)  |
| | 2021 | [Improved DDPM](https://arxiv.org/pdf/2102.09672.pdf) | 改进的 DDPM   |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fde18baa4964804cf471d85a5a090498242d2e79f%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Improved-Denoising-Diffusion-Probabilistic-Models-Nichol-Dhariwal/de18baa4964804cf471d85a5a090498242d2e79f)  |
| | 2021 | [Guided Diffusion Models](https://arxiv.org/pdf/2105.05233.pdf) | 号称超越 GAN  |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F64ea8f180d0682e6c18d1eb688afdb2027c02794%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Diffusion-Models-Beat-GANs-on-Image-Synthesis-Dhariwal-Nichol/64ea8f180d0682e6c18d1eb688afdb2027c02794)  |
| | 2021 | [StyleGAN3](https://arxiv.org/pdf/2106.12423.pdf) |        |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fc1ff08b59f00c44f34dfdde55cd53370733a2c19%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Alias-Free-Generative-Adversarial-Networks-Karras-Aittala/c1ff08b59f00c44f34dfdde55cd53370733a2c19)  |

### 计算机视觉-ObjectDetection

| 笔记 | 年份 | 名字                                              | 简介         | 引用 |
| ------ | ---- | ------------------------------------------------- | ------------ | ------------------------------------------------------------ |
|        | 2014 | [R-CNN](https://arxiv.org/pdf/1311.2524v5.pdf)    | Two-stage             |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F2f4df08d9072fc2ac181b7fced6a245315ce05c8%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/2f4df08d9072fc2ac181b7fced6a245315ce05c8)  |
|        | 2015 | [Fast R-CNN](http://arxiv.org/abs/1504.08083v2)   |                       |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F7ffdbc358b63378f07311e883dddacc9faeeaf4b%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/7ffdbc358b63378f07311e883dddacc9faeeaf4b)  |
|        | 2015 | [Faster R-CNN](http://arxiv.org/abs/1506.01497v3) |                       |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F424561d8585ff8ebce7d5d07de8dbf7aae5e7270%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/424561d8585ff8ebce7d5d07de8dbf7aae5e7270)  |
|        | 2016 | [SSD](http://arxiv.org/abs/1512.02325v5)          | Single stage          |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F4d7a9197433acbfb24ef0e9d0f33ed1699e4a5b0%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/4d7a9197433acbfb24ef0e9d0f33ed1699e4a5b0)  |
|        | 2016 | [YOLO](http://arxiv.org/abs/1506.02640v5)         |                       |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Ff8e79ac0ea341056ef20f2616628b3e964764cfd%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/f8e79ac0ea341056ef20f2616628b3e964764cfd)  |
|        | 2017 | [Mask R-CNN](http://arxiv.org/abs/1703.06870v3)   |                       |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fea99a5535388196d0d44be5b4d7dd02029a43bb2%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/ea99a5535388196d0d44be5b4d7dd02029a43bb2)  |
|        | 2017 | [YOLOv2](http://arxiv.org/abs/1612.08242v1)       |                       |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F7d39d69b23424446f0400ef603b2e3e22d0309d6%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/7d39d69b23424446f0400ef603b2e3e22d0309d6)  |
|        | 2018 | [YOLOv3](http://arxiv.org/abs/1804.02767v1)       |                       |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fe4845fb1e624965d4f036d7fd32e8dcdd2408148%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/e4845fb1e624965d4f036d7fd32e8dcdd2408148)  |
|        | 2019 | [CenterNet](https://arxiv.org/pdf/1904.07850.pdf) | Anchor free           |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F6a2e2fd1b5bb11224daef98b3fb6d029f68a73f2%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Objects-as-Points-Zhou-Wang/6a2e2fd1b5bb11224daef98b3fb6d029f68a73f2)  |
| [✅](https://github.com/KingXHJ/X-PaperReading/blob/main/DeepLearning/CV%20Object%20Detection/End-to-End%20Object%20Detection%20with%20Transformers.md)       | 2020 | [DETR](https://arxiv.org/pdf/2005.12872.pdf)      | Transformer           |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F962dc29fdc3fbdc5930a10aba114050b82fe5a3e%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/End-to-End-Object-Detection-with-Transformers-Carion-Massa/962dc29fdc3fbdc5930a10aba114050b82fe5a3e)  |

<a name="contrastive_learning"></a>

### 计算机视觉-对比学习


| 笔记 | 年份 | 名字                                                         | 简介                 | 引用 |
| ------ | ---- | ------------------------------------------------------------ | -------------------- | ------------------------------------------------------------ |
| [✅](https://github.com/KingXHJ/X-PaperReading/blob/main/DeepLearning/CV%20Contrastive%20Learning/Overview%20of%20Comparative%20Learning.md)    | 2018 | [InstDisc](https://arxiv.org/pdf/1805.01978.pdf) | 提出实例判别和memory bank做对比学习                  |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F155b7782dbd713982a4133df3aee7adfd0b6b304%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Unsupervised-Feature-Learning-via-Non-parametric-Wu-Xiong/155b7782dbd713982a4133df3aee7adfd0b6b304)  |
| [✅](https://github.com/KingXHJ/X-PaperReading/blob/main/DeepLearning/CV%20Contrastive%20Learning/Overview%20of%20Comparative%20Learning.md)      | 2018 | [CPC](https://arxiv.org/pdf/1807.03748.pdf) | 对比预测编码，图像语音文本强化学习全都能做                   | [![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fb227f3e4c0dc96e5ac5426b85485a70f2175a205%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Representation-Learning-with-Contrastive-Predictive-Oord-Li/b227f3e4c0dc96e5ac5426b85485a70f2175a205) |
| [✅](https://github.com/KingXHJ/X-PaperReading/blob/main/DeepLearning/CV%20Contrastive%20Learning/Overview%20of%20Comparative%20Learning.md)      | 2019 | [InvaSpread](https://arxiv.org/pdf/1904.03436.pdf) | 一个编码器的端到端对比学习                   |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fe4bde6fe33b6c2cf9d1647ac0b041f7d1ba29c5b%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Unsupervised-Embedding-Learning-via-Invariant-and-Ye-Zhang/e4bde6fe33b6c2cf9d1647ac0b041f7d1ba29c5b)  |
| [✅](https://github.com/KingXHJ/X-PaperReading/blob/main/DeepLearning/CV%20Contrastive%20Learning/Overview%20of%20Comparative%20Learning.md)  | 2019 |  [CMC](https://arxiv.org/pdf/1906.05849.pdf) | 多视角下的对比学习               |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F97f4d09175705be4677d675fa27e55defac44800%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Contrastive-Multiview-Coding-Tian-Krishnan/97f4d09175705be4677d675fa27e55defac44800)  |
| [✅](https://github.com/KingXHJ/X-PaperReading/blob/main/DeepLearning/CV%20Contrastive%20Learning/Momentum%20Contrast%20for%20Unsupervised%20Visual%20Representation%20Learning.md) | 2019 | [MoCov1](https://arxiv.org/pdf/1911.05722.pdf) | 无监督训练效果也很好                   | [![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fec46830a4b275fd01d4de82bffcabe6da086128f%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Momentum-Contrast-for-Unsupervised-Visual-Learning-He-Fan/ec46830a4b275fd01d4de82bffcabe6da086128f) |
| [✅](https://github.com/KingXHJ/X-PaperReading/blob/main/DeepLearning/CV%20Contrastive%20Learning/Overview%20of%20Comparative%20Learning.md) | 2020 |  [SimCLRv1](https://arxiv.org/pdf/2002.05709.pdf) |  简单的对比学习 (数据增强 + MLP head + 大batch训练久)                  |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F34733eaf66007516347a40ad5d9bbe1cc9dacb6b%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/A-Simple-Framework-for-Contrastive-Learning-of-Chen-Kornblith/34733eaf66007516347a40ad5d9bbe1cc9dacb6b)  |
| [✅](https://github.com/KingXHJ/X-PaperReading/blob/main/DeepLearning/CV%20Contrastive%20Learning/Overview%20of%20Comparative%20Learning.md)  | 2020 | [MoCov2](https://arxiv.org/pdf/2003.04297.pdf) | MoCov1 + improvements from SimCLRv1                   |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fa1b8a8df281bbaec148a897927a49ea47ea31515%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Improved-Baselines-with-Momentum-Contrastive-Chen-Fan/a1b8a8df281bbaec148a897927a49ea47ea31515)  |
| [✅](https://github.com/KingXHJ/X-PaperReading/blob/main/DeepLearning/CV%20Contrastive%20Learning/Overview%20of%20Comparative%20Learning.md)  | 2020 |  [SimCLRv2](https://arxiv.org/pdf/2006.10029.pdf) | 大的自监督预训练模型很适合做半监督学习                   |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F3e7f5f4382ac6f9c4fef6197dd21abf74456acd1%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Big-Self-Supervised-Models-are-Strong-Learners-Chen-Kornblith/3e7f5f4382ac6f9c4fef6197dd21abf74456acd1)  |
| [✅](https://github.com/KingXHJ/X-PaperReading/blob/main/DeepLearning/CV%20Contrastive%20Learning/Overview%20of%20Comparative%20Learning.md)  | 2020 |  [BYOL](https://arxiv.org/pdf/2006.07733.pdf) | 不需要负样本的对比学习                   | [![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F38f93092ece8eee9771e61c1edaf11b1293cae1b%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Bootstrap-Your-Own-Latent%3A-A-New-Approach-to-Grill-Strub/38f93092ece8eee9771e61c1edaf11b1293cae1b) |
| [✅](https://github.com/KingXHJ/X-PaperReading/blob/main/DeepLearning/CV%20Contrastive%20Learning/Overview%20of%20Comparative%20Learning.md)  | 2020 |  [SWaV](https://arxiv.org/pdf/2006.09882.pdf) | 聚类对比学习                   | [![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F10161d83d29fc968c4612c9e9e2b61a2fc25842e%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Unsupervised-Learning-of-Visual-Features-by-Cluster-Caron-Misra/10161d83d29fc968c4612c9e9e2b61a2fc25842e) |
| [✅](https://github.com/KingXHJ/X-PaperReading/blob/main/DeepLearning/CV%20Contrastive%20Learning/Overview%20of%20Comparative%20Learning.md)  | 2020 |  [SimSiam](https://arxiv.org/pdf/2011.10566.pdf) | 化繁为简的孪生表征学习                   |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F0e23d2f14e7e56e81538f4a63e11689d8ac1eb9d%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Exploring-Simple-Siamese-Representation-Learning-Chen-He/0e23d2f14e7e56e81538f4a63e11689d8ac1eb9d)  |
| [✅](https://github.com/KingXHJ/X-PaperReading/blob/main/DeepLearning/CV%20Contrastive%20Learning/Overview%20of%20Comparative%20Learning.md) | 2021 | [MoCov3](https://arxiv.org/pdf/2104.02057.pdf) | 如何更稳定的自监督训练ViT                   |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F739ceacfafb1c4eaa17509351b647c773270b3ae%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/An-Empirical-Study-of-Training-Self-Supervised-Chen-Xie/739ceacfafb1c4eaa17509351b647c773270b3ae)  |
| [✅](https://github.com/KingXHJ/X-PaperReading/blob/main/DeepLearning/CV%20Contrastive%20Learning/Overview%20of%20Comparative%20Learning.md)  | 2021 |  [DINO](https://arxiv.org/pdf/2104.14294.pdf) | transformer加自监督在视觉也很香                   |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fad4a0938c48e61b7827869e4ac3baffd0aefab35%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Emerging-Properties-in-Self-Supervised-Vision-Caron-Touvron/ad4a0938c48e61b7827869e4ac3baffd0aefab35)  |


### 自然语言处理-Transformer

| 笔记 | 年份 | 名字                                                         | 简介                 | 引用 |
| ------ | ---- | ------------------------------------------------------------ | -------------------- | ------------------------------------------------------------ |
| [✅](https://github.com/KingXHJ/X-PaperReading/blob/main/DeepLearning/NLP%20Transformer/Attention%20Is%20All%20You%20Need.md) | 2017 | [Transformer](https://arxiv.org/abs/1706.03762) | 继MLP、CNN、RNN后的第四大类架构                   |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F204e3073870fae3d05bcbc2f6a8e263d9b72e776%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Attention-is-All-you-Need-Vaswani-Shazeer/204e3073870fae3d05bcbc2f6a8e263d9b72e776)  |
| [✅](https://github.com/KingXHJ/X-PaperReading/blob/main/DeepLearning/NLP%20Transformer/Generative%20Pre-Training%201%202%203.md) | 2018 | [GPT](https://s3-us-west-2.amazonaws.com/openai-assets/research-covers/language-unsupervised/language_understanding_paper.pdf) | 使用 Transformer 解码器来做预训练               |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fcd18800a0fe0b668a1cc19f2ec95b5003d0a5035%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Improving-Language-Understanding-by-Generative-Radford-Narasimhan/cd18800a0fe0b668a1cc19f2ec95b5003d0a5035)  |
| [✅](https://github.com/KingXHJ/X-PaperReading/blob/main/DeepLearning/NLP%20Transformer/BERT%20Pre-training%20of%20Deep%20Bidirectional%20Transformers%20for%20Language%20Understanding.md) | 2018 | [BERT](https://arxiv.org/abs/1810.04805) | Transformer一统NLP的开始                  |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fdf2b0e26d0599ce3e70df8a9da02e51594e0e992%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/BERT%3A-Pre-training-of-Deep-Bidirectional-for-Devlin-Chang/df2b0e26d0599ce3e70df8a9da02e51594e0e992)  |
| [✅](https://github.com/KingXHJ/X-PaperReading/blob/main/DeepLearning/NLP%20Transformer/Generative%20Pre-Training%201%202%203.md) | 2019 | [GPT-2](https://d4mucfpksywv.cloudfront.net/better-language-models/language_models_are_unsupervised_multitask_learners.pdf)  |  更大的 GPT 模型，朝着zero-shot learning迈了一大步             |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F9405cc0d6169988371b2755e573cc28650d14dfe%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Language-Models-are-Unsupervised-Multitask-Learners-Radford-Wu/9405cc0d6169988371b2755e573cc28650d14dfe)  |
| [✅](https://github.com/KingXHJ/X-PaperReading/blob/main/DeepLearning/NLP%20Transformer/Generative%20Pre-Training%201%202%203.md) | 2020 |  [GPT-3](https://arxiv.org/abs/2005.14165) | 100倍更大的 GPT-2，few-shot learning效果显著                  |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F6b85b63579a916f705a8e10a49bd8d849d91b1fc%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Language-Models-are-Few-Shot-Learners-Brown-Mann/6b85b63579a916f705a8e10a49bd8d849d91b1fc)  |


### 图神经网络

| 笔记 | 年份 | 名字                                                         | 简介                 | 引用 |
| ------ | ---- | ------------------------------------------------------------ | -------------------- | ------------------------------------------------------------ |
| [✅](https://github.com/KingXHJ/X-PaperReading/blob/main/DeepLearning/Graph%20Neural%20Network/A%20Gentle%20Introduction%20to%20Graph%20Neural%20Networks.md)  |  2021 | [图神经网络介绍](https://distill.pub/2021/gnn-intro/) | GNN的可视化介绍                  |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F2c0e0440882a42be752268d0b64243243d752a74%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/A-Gentle-Introduction-to-Graph-Neural-Networks-S%C3%A1nchez-Lengeling-Reif/2c0e0440882a42be752268d0b64243243d752a74)  |

### 优化算法

| 笔记 | 年份 | 名字                                                         | 简介                 | 引用 |
| ------ | ---- | ------------------------------------------------------------ | -------------------- | ------------------------------------------------------------ |
| | 2014 | [Adam](https://arxiv.org/abs/1412.6980) | 深度学习里最常用的优化算法之一                   |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fa6cb366736791bcccc5c8639de5a8f9636bf87e8%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Adam%3A-A-Method-for-Stochastic-Optimization-Kingma-Ba/a6cb366736791bcccc5c8639de5a8f9636bf87e8)  |
| | 2016 |  [为什么超大的模型泛化性不错](https://arxiv.org/abs/1611.03530)   |               |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F54ddb00fa691728944fd8becea90a373d21597cf%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Understanding-deep-learning-requires-rethinking-Zhang-Bengio/54ddb00fa691728944fd8becea90a373d21597cf)  |
| | 2017 | [为什么Momentum有效](https://distill.pub/2017/momentum/) | Distill的可视化介绍            |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F3e8ccf9d3d843c9855c5d76ab66d3e775384da72%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Why-Momentum-Really-Works-Goh/3e8ccf9d3d843c9855c5d76ab66d3e775384da72)  |


### 新领域应用


| 笔记 | 年份 | 名字                                                         | 简介                 | 引用 |
| ------ | ---- | ------------------------------------------------------------ | -------------------- | ------------------------------------------------------------ |
| | 2016 | [AlphaGo](https://storage.googleapis.com/deepmind-media/alphago/AlphaGoNaturePaper.pdf) | 强化学习出圈                 |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F846aedd869a00c09b40f1f1f35673cb22bc87490%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Mastering-the-game-of-Go-with-deep-neural-networks-Silver-Huang/846aedd869a00c09b40f1f1f35673cb22bc87490)  |
| | 2020 | [AlphaFold](https://discovery.ucl.ac.uk/id/eprint/10089234/1/343019_3_art_0_py4t4l_convrt.pdf) | 赢得比赛的的蛋白质3D结构预测 |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F3a083d843f891b3574494c385699c21766ce8b7a%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Improved-protein-structure-prediction-using-from-Senior-Evans/3a083d843f891b3574494c385699c21766ce8b7a)  |
|  | 2021 | [AlphaFold 2](https://www.nature.com/articles/s41586-021-03819-2.pdf) | 原子级别精度的蛋白质3D结构预测       |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fdc32a984b651256a8ec282be52310e6bd33d9815%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Highly-accurate-protein-structure-prediction-with-Jumper-Evans/dc32a984b651256a8ec282be52310e6bd33d9815)  |
|  | 2021 | [Codex](https://arxiv.org/pdf/2107.03374.pdf) | 使用注释生成代码       |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Facbdbf49f9bc3f151b93d9ca9a06009f4f6eb269%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Evaluating-Large-Language-Models-Trained-on-Code-Chen-Tworek/acbdbf49f9bc3f151b93d9ca9a06009f4f6eb269)  |
|  | 2021 | [指导数学直觉](https://www.nature.com/articles/s41586-021-04086-x.pdf) | 分析不同数学物体之前的联系来帮助发现新定理         |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Ff672b8fb430606fee0bb368f16603531ce1e90c4%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Advancing-mathematics-by-guiding-human-intuition-AI-Davies-Velickovic/f672b8fb430606fee0bb368f16603531ce1e90c4)  |
|  | 2022 | [AlphaCode](https://storage.googleapis.com/deepmind-media/AlphaCode/competition_level_code_generation_with_alphacode.pdf) | 媲美一般程序员的编程解题水平       |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F5cbe278b65a81602a864184bbca37de91448a5f5%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Competition-Level-Code-Generation-with-AlphaCode-Li-Choi/5cbe278b65a81602a864184bbca37de91448a5f5)  |

## 系统

| 笔记 | 年份 | 名字                                                         | 简介                 | 引用 |
| ------ | ---- | ------------------------------------------------------------ | -------------------- | ------------------------------------------------------------ |
| [✅](https://github.com/KingXHJ/X-PaperReading/blob/main/System/Scaling%20Distributed%20Machine%20Learning%20with%20the%20Parameter%20Server.md)  |  2014 | [参数服务器](https://www.usenix.org/system/files/conference/osdi14/osdi14-paper-li_mu.pdf) | 支持千亿参数的传统机器学习模型       |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F0de0c3240bda7972bd0a3c8369ebc4b4f2e4f9c2%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Scaling-Distributed-Machine-Learning-with-the-Li-Andersen/0de0c3240bda7972bd0a3c8369ebc4b4f2e4f9c2)  |
|   | 2018 | [GPipe](https://proceedings.neurips.cc/paper/2019/file/093f65e080a295f8076b1c5722a46aa2-Paper.pdf) | 流水线（Pipeline）并行      |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fc18663fea10c8a303d045fd2c1f33cacf9b73ca3%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/GPipe%3A-Efficient-Training-of-Giant-Neural-Networks-Huang-Cheng/c18663fea10c8a303d045fd2c1f33cacf9b73ca3)  |
|  | 2019 | [Megatron-LM](https://arxiv.org/pdf/1909.08053.pdf) | 张量（Tensor）并行      |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F8323c591e119eb09b28b29fd6c7bc76bd889df7a%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Megatron-LM%3A-Training-Multi-Billion-Parameter-Using-Shoeybi-Patwary/8323c591e119eb09b28b29fd6c7bc76bd889df7a) |
|  | 2019 | [Zero](https://arxiv.org/pdf/1910.02054.pdf) | 参数分片      |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F00c957711b12468cb38424caccdf5291bb354033%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/ZeRO%3A-Memory-optimizations-Toward-Training-Trillion-Rajbhandari-Rasley/00c957711b12468cb38424caccdf5291bb354033)  |
|  |  2022 | [Pathways](https://arxiv.org/pdf/2203.12533.pdf) |  将Jax拓展到上千TPU核上       |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F512e9aa873a1cd7eb61ce1f25ca7df6acb7e2352%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Pathways%3A-Asynchronous-Distributed-Dataflow-for-ML-Barham-Chowdhery/512e9aa873a1cd7eb61ce1f25ca7df6acb7e2352)  |


#### 1. [斯坦福100+作者的200+页综述](https://arxiv.org/abs/2108.07258)
#### 2. [对LayerNorm的新研究](https://arxiv.org/pdf/1911.07013.pdf)
#### 3. [对Attention在Transformer里面作用的研究](https://arxiv.org/abs/2103.03404)
