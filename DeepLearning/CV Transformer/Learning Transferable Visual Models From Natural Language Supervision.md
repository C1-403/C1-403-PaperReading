# 论文信息
- 时间：2021
- 期刊：ICCV
- 网络名称： CLIP（Contrastive Language-Image Pre-training）
- 意义：图片和文本之间的对比学习
- 作者：Alec Radford * 1, Jong Wook Kim * 1, Chris Hallacy 1, Aditya Ramesh 1, Gabriel Goh 1, Sandhini Agarwal 1, Girish Sastry 1, Amanda Askell 1, Pamela Mishkin 1, Jack Clark 1, Gretchen Krueger 1, Ilya Sutskever 1；OpenAI
- 实验环境： V100 GPUs
- 数据集：WIT(WebImageTex)，400 million
# 一、解决的问题
- taskagnostic architectures -> zero-shot transfer -> downstream datasets removing the need for specialized output heads or dataset specific customization 发展历程
- 直接从网络文本中学习的可扩展预训练方法能否在计算机视觉领域取得类似的突破?
- 不需要ImageNet的训练集就可以和ResNet匹敌
- 利用自然语言处理，达到一个迁移性好的模型
- 设定好的类别让模型有局限性，要从文本里得到信号，可以拼凑出想要的结果
- 模型和数据都不庞大
- 训练速度太慢了，不选择GPT，选择对比学习
# 二、做出的创新
![CLIP summary](../pictures/CLIP%20summary.png)
- 输入图片和文本的配对(4个亿)进行训练，做对比学习
- 训练对角线上都是正样本，其余都是负样本
- 用自然语言的方法（弱监督），把单词组织成句子，与图片算cosine相似度
- 摆脱了categorical label，这就是利用了zero-shot的好处
# 三、设计的模型
1. 用自然语言预训练方法，用在视觉模型上；做大了规模
2. 文本当作监督信号，跨模态
![CLIP pseudocode](../pictures/CLIP%20pseudocode.png)

3. 单模态->多模态
4. 模型太大了，不需要考虑过拟合
5. 并没有选择非线性投射层，选择了线性投射层
6. 数据裁剪只使用了数据裁剪
7. temperature被设计为学习的标量（由于模型太大了，不方便手调）
8. 主要目的是训练一个图片编码器和一个文本编码器
9. 只用Linear probe（只重新训练分类头，其他网络全冻住），不用finetune（网络全开放）
# 四、实验结果
## 1、比之前模型的优势
1. 在多个领域的表现非常好，甚至可以匹敌监督学习的效果
2. 迁移学习效果和模型的大小成正相关
3. 泛化性、稳健性比有监督模型好的很多
4. 在普通的分类数据集上，表现得就很好；但是在检测纹理和计数的任务就不是很好了
## 2、有优势的原因
- 用自然语言的方式的好处
1. 不需要标注数据，且自然增大了数据集
2. 图片+文字就是多模态了，能学到语言+视觉的信息
## 3、改进空间
- 所有数据集SOTA，扩大规模，至少在现在计算量基础上，乘1000倍
- CLIP擅长分类物体，但是不知道什么是异常或者安全，还是有很多领域是瞎猜的
- 训练数据out of distribution就不行了，如在MNIST上88%准确率
- 受限于计算资源，做不到GPT的生成式模型，以后企图把生成式和对比式结合
- CLIP对数据集的利用效率不高
- 常用ImageNet做指导，或者27个数据集，无形之中带入了偏见，还缺数据集
- 图片和文本对都是从网上找的，没有清洗过，网上的言论很有可能带有偏见
- 很复杂的任务和概念，用语言都难以描述，可能提供样本更好？实时证明加入one-shot、two-shot反而下降了

# 五、结论
## 1、模型是否解决了目标问题
- 用于图像生成
- 用于目标检测(检测出新的类)
- 视频检索
## 2、模型是否遗留了问题
- 仍然是设定了多少个类，就会产生多少个句子，进行计算cosine相似度
- 文本多义性

## 3、模型是否引入了新的问题

# 六、代码

# 读者角度（挖掘文章中没有提到的）：
1. 总结文章发现问题的思路
- 研究动机：NLP大成功，如自己的GPT3
2. 总结文章改进的思想
- 预训练用对比学习
- 利用文本的提示，做了zero-shot的迁移学习
- 大规模模型和数据集的加持下，和精心设计的模型打成了平手
3. 总结文章还存在或者可以改进的问题
4. 提出对模型参数和细节的一些思考和讨论