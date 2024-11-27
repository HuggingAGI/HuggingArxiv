# MulModSeg：借助模态条件文本嵌入和交替训练来提升未配对的多模态医学图像分割效果

发布时间：2024年11月23日

`其他` `医学成像` `图像分割`

> MulModSeg: Enhancing Unpaired Multi-Modal Medical Image Segmentation with Modality-Conditioned Text Embedding and Alternating Training

# 摘要

> 在医学成像这一多元化领域，自动分割应用广泛，需应对诸如不同类型的计算机断层扫描（CT）和磁共振（MR）图像等各类输入域。由于需要空间对齐和配对的图像，这种异质性给自动分割算法在不同模态下保持稳定性能带来了挑战。通常，分割模型仅用单一模态训练，这使其在不运用迁移学习技术时难以推广到其他类型的输入数据。而且，利用不同模态的互补信息来提升分割精度往往需要对流行的编码器 - 解码器设计进行大幅修改，比如为每种模态引入多个分支编码或解码路径。在本研究中，我们提出了一种简便的多模态分割（MulModSeg）策略，以强化在多种模态（尤其是 CT 和 MR）下的医学图像分割。它涵盖了两个关键设计：借助冻结的文本编码器的模态条件文本嵌入框架，在不对现有分割框架做重大结构改动或增加计算开销的情况下增强模态感知；还有交替训练程序，有助于从未配对的 CT 和 MR 输入中整合关键特征。通过基于全卷积网络和 Transformer 的骨干网络开展的大量实验，MulModSeg 在分割 CT 和 MR 模态的腹部多器官和心脏子结构方面始终胜过以往方法。代码可在这个{\href{https://github.com/ChengyinLee/MulModSeg_2024}{链接}}获取。

> In the diverse field of medical imaging, automatic segmentation has numerous applications and must handle a wide variety of input domains, such as different types of Computed Tomography (CT) scans and Magnetic Resonance (MR) images. This heterogeneity challenges automatic segmentation algorithms to maintain consistent performance across different modalities due to the requirement for spatially aligned and paired images. Typically, segmentation models are trained using a single modality, which limits their ability to generalize to other types of input data without employing transfer learning techniques. Additionally, leveraging complementary information from different modalities to enhance segmentation precision often necessitates substantial modifications to popular encoder-decoder designs, such as introducing multiple branched encoding or decoding paths for each modality. In this work, we propose a simple Multi-Modal Segmentation (MulModSeg) strategy to enhance medical image segmentation across multiple modalities, specifically CT and MR. It incorporates two key designs: a modality-conditioned text embedding framework via a frozen text encoder that adds modality awareness to existing segmentation frameworks without significant structural modifications or computational overhead, and an alternating training procedure that facilitates the integration of essential features from unpaired CT and MR inputs. Through extensive experiments with both Fully Convolutional Network and Transformer-based backbones, MulModSeg consistently outperforms previous methods in segmenting abdominal multi-organ and cardiac substructures for both CT and MR modalities. The code is available in this {\href{https://github.com/ChengyinLee/MulModSeg_2024}{link}}.

[Arxiv](https://arxiv.org/abs/2411.15576)