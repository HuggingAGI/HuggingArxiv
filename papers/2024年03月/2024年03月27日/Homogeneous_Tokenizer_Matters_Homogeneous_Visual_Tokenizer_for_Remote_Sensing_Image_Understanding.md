# 同质化令牌化器至关重要：专为遥感图像解读打造的同质化视觉令牌化技术。

发布时间：2024年03月27日

`Agent` `计算机视觉` `图像处理`

> Homogeneous Tokenizer Matters: Homogeneous Visual Tokenizer for Remote Sensing Image Understanding

# 摘要

> 分词器，作为大型模型的核心组件，在视觉任务中常被忽略或误解。自然语言分词器以有意义的词或词根为基石，而主流视觉分词器，如Patch Embed，却以无意义的矩形区块为基本单元，效果远不及自然语言。为此，我们为视觉领域定义了语义独立区域（SIRs），并设计了一款简洁的均匀视觉分词器HOOK。HOOK由对象感知模块（OPM）和对象矢量化模块（OVM）组成。OPM通过注意力机制将图像划分为4*4像素的种子，感知SIRs；OVM则使用交叉注意力将种子聚合。为提高适应性，OVM定义了可学习的向量作为交叉注意力查询，以调整令牌数量。我们在NWPU-RESISC45、WHU-RS19分类数据集和GID5分割数据集上进行了实验，结果表明HOOK生成的视觉令牌与独立对象相对应，证明了其均匀性。与Patch Embed相比，HOOK在两项任务中分别提升了6%和10%的性能，达到了最先进的水平。相较于Patch Embed一个图像需要上百个令牌，HOOK只需6至8个，效率提升了1.5至2.8倍。相关代码已在https://github.com/GeoX-Lab/Hook发布。

> The tokenizer, as one of the fundamental components of large models, has long been overlooked or even misunderstood in visual tasks. One key factor of the great comprehension power of the large language model is that natural language tokenizers utilize meaningful words or subwords as the basic elements of language. In contrast, mainstream visual tokenizers, represented by patch-based methods such as Patch Embed, rely on meaningless rectangular patches as basic elements of vision, which cannot serve as effectively as words or subwords in language. Starting from the essence of the tokenizer, we defined semantically independent regions (SIRs) for vision. We designed a simple HOmogeneous visual tOKenizer: HOOK. HOOK mainly consists of two modules: the Object Perception Module (OPM) and the Object Vectorization Module (OVM). To achieve homogeneity, the OPM splits the image into 4*4 pixel seeds and then utilizes the attention mechanism to perceive SIRs. The OVM employs cross-attention to merge seeds within the same SIR. To achieve adaptability, the OVM defines a variable number of learnable vectors as cross-attention queries, allowing for the adjustment of token quantity. We conducted experiments on the NWPU-RESISC45, WHU-RS19 classification dataset, and GID5 segmentation dataset for sparse and dense tasks. The results demonstrate that the visual tokens obtained by HOOK correspond to individual objects, which demonstrates homogeneity. HOOK outperformed Patch Embed by 6\% and 10\% in the two tasks and achieved state-of-the-art performance compared to the baselines used for comparison. Compared to Patch Embed, which requires more than one hundred tokens for one image, HOOK requires only 6 and 8 tokens for sparse and dense tasks, respectively, resulting in efficiency improvements of 1.5 to 2.8 times. The code is available at https://github.com/GeoX-Lab/Hook.

[Arxiv](https://arxiv.org/abs/2403.18593)