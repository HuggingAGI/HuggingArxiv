# 通过语言指令，轻松分割任意三维物体

发布时间：2024年04月02日

`LLM应用` `三维图像处理`

> Segment Any 3D Object with Language

# 摘要

> 本文探讨了利用自由形式语言指令进行开放词汇三维实例分割（OV-3DIS）的技术。先前研究仅基于带注释的基本类别进行训练，导致对新颖类别的泛化能力受限。最新研究通过创建类别无关遮罩或将二维遮罩推广至三维来提高泛化性，但忽略了语义和几何信息，使得性能不尽人意。直接从三维点云生成具有语义关联的通用遮罩，将带来更佳成效。我们提出了一种名为“语言驱动的三维对象分割”（SOLE）的框架，它通过直接从点云数据中生成语义关联遮罩，实现了强大的泛化能力。我们设计了一个多模态融合网络，以整合骨干和解码器中的多模态语义。同时，为使三维分割模型更好地适应多样化的语言指令并提升遮罩质量，我们引入了三种多模态关联监督机制。在ScanNetv2、ScanNet200和Replica等基准测试中，SOLE的性能远超先前方法，即便在缺乏类别注释的训练条件下，其结果也近乎与全监督方法相媲美。此外，丰富的定性分析结果证明了SOLE在响应语言指令方面的广泛适用性。

> In this paper, we investigate Open-Vocabulary 3D Instance Segmentation (OV-3DIS) with free-form language instructions. Earlier works that rely on only annotated base categories for training suffer from limited generalization to unseen novel categories. Recent works mitigate poor generalizability to novel categories by generating class-agnostic masks or projecting generalized masks from 2D to 3D, but disregard semantic or geometry information, leading to sub-optimal performance. Instead, generating generalizable but semantic-related masks directly from 3D point clouds would result in superior outcomes. In this paper, we introduce Segment any 3D Object with LanguagE (SOLE), which is a semantic and geometric-aware visual-language learning framework with strong generalizability by generating semantic-related masks directly from 3D point clouds. Specifically, we propose a multimodal fusion network to incorporate multimodal semantics in both backbone and decoder. In addition, to align the 3D segmentation model with various language instructions and enhance the mask quality, we introduce three types of multimodal associations as supervision. Our SOLE outperforms previous methods by a large margin on ScanNetv2, ScanNet200, and Replica benchmarks, and the results are even close to the fully-supervised counterpart despite the absence of class annotations in the training. Furthermore, extensive qualitative results demonstrate the versatility of our SOLE to language instructions.

[Arxiv](https://arxiv.org/abs/2404.02157)