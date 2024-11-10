# TexLiverNet：利用医学知识和空间频率感知来增强肝脏肿瘤分割

发布时间：2024年11月07日

`Agent` `肝脏肿瘤`

> TexLiverNet: Leveraging Medical Knowledge and Spatial-Frequency Perception for Enhanced Liver Tumor Segmentation

# 摘要

> 将文本数据与肝脏肿瘤分割中的成像相结合对于提高诊断准确性至关重要。然而，当前的多模态医学数据集仅提供一般的文本注释，缺乏对于提取细微特征至关重要的病变特定细节，特别是对于肿瘤边界和小病变的细粒度分割。为了解决这些限制，我们为肝脏肿瘤开发了具有病变特定文本注释的数据集，并引入了 TexLiverNet 模型。TexLiverNet 采用基于代理的交叉注意力模块，有效地将文本特征与视觉特征相结合，显著降低了计算成本。此外，还提出了增强的空间和自适应频域感知，以精确描绘病变边界，减少背景干扰，并恢复小病变中的精细细节。在公共和私有数据集上的综合评估表明，TexLiverNet 与当前最先进的方法相比实现了卓越的性能。

> Integrating textual data with imaging in liver tumor segmentation is essential for enhancing diagnostic accuracy. However, current multi-modal medical datasets offer only general text annotations, lacking lesion-specific details critical for extracting nuanced features, especially for fine-grained segmentation of tumor boundaries and small lesions. To address these limitations, we developed datasets with lesion-specific text annotations for liver tumors and introduced the TexLiverNet model. TexLiverNet employs an agent-based cross-attention module that integrates text features efficiently with visual features, significantly reducing computational costs. Additionally, enhanced spatial and adaptive frequency domain perception is proposed to precisely delineate lesion boundaries, reduce background interference, and recover fine details in small lesions. Comprehensive evaluations on public and private datasets demonstrate that TexLiverNet achieves superior performance compared to current state-of-the-art methods.

[Arxiv](https://arxiv.org/abs/2411.04595)