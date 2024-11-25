# FOCUS：用于少样本全切片图像分类的知识增强型自适应视觉压缩

发布时间：2024年11月22日

`LLM应用` `病理学`

> FOCUS: Knowledge-enhanced Adaptive Visual Compression for Few-shot Whole Slide Image Classification

# 摘要

> 少样本学习为计算病理学（CPath）中的癌症诊断给出了关键解法，化解了数据可用性的根本限制，尤其是专家标注稀缺和患者隐私受限的问题。此范式中的关键挑战源于整个切片图像（WSIs）有限的训练集与所含大量切片之间的内在差异，其中不少切片缺乏诊断相关信息，可能削弱模型学习并聚焦关键诊断特征的能力。尽管近来的工作尝试通过融入额外知识来应对，然而几个关键差距阻碍了更进一步发展：（1）尽管强大的病理学基础模型（FMs）已出现，但它们的潜力大多未被挖掘，多数方法仅将其用于基础特征提取；（2）当下的语言引导机制试图一次性让文本提示与大量WSI切片对齐，难以利用丰富的病理语义信息。为此，我们推出了知识增强的自适应视觉压缩框架，名为FOCUS，它独特地将病理学FMs和语言先验知识相结合，通过优先处理有区分度的WSI切片来实现对诊断相关区域的重点分析。我们的方法采用逐步的三阶段压缩策略：首先借助FMs消除全局视觉冗余，将压缩特征与语言提示整合以进行语义相关性评估，然后在保持空间连贯性的同时进行邻居感知的视觉标记过滤。在涵盖乳腺癌、肺癌和卵巢癌的病理数据集上开展的大量实验表明其在少样本病理诊断中的卓越性能。代码将在https://github.com/dddavid4real/FOCUS 上提供。

> Few-shot learning presents a critical solution for cancer diagnosis in computational pathology (CPath), addressing fundamental limitations in data availability, particularly the scarcity of expert annotations and patient privacy constraints. A key challenge in this paradigm stems from the inherent disparity between the limited training set of whole slide images (WSIs) and the enormous number of contained patches, where a significant portion of these patches lacks diagnostically relevant information, potentially diluting the model's ability to learn and focus on critical diagnostic features. While recent works attempt to address this by incorporating additional knowledge, several crucial gaps hinder further progress: (1) despite the emergence of powerful pathology foundation models (FMs), their potential remains largely untapped, with most approaches limiting their use to basic feature extraction; (2) current language guidance mechanisms attempt to align text prompts with vast numbers of WSI patches all at once, struggling to leverage rich pathological semantic information. To this end, we introduce the knowledge-enhanced adaptive visual compression framework, dubbed FOCUS, which uniquely combines pathology FMs with language prior knowledge to enable a focused analysis of diagnostically relevant regions by prioritizing discriminative WSI patches. Our approach implements a progressive three-stage compression strategy: we first leverage FMs for global visual redundancy elimination, and integrate compressed features with language prompts for semantic relevance assessment, then perform neighbor-aware visual token filtering while preserving spatial coherence. Extensive experiments on pathological datasets spanning breast, lung, and ovarian cancers demonstrate its superior performance in few-shot pathology diagnosis. Code will be made available at https://github.com/dddavid4real/FOCUS.

[Arxiv](https://arxiv.org/abs/2411.14743)