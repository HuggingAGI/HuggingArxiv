# 针对无 OCR 文档理解的分层视觉特征聚合

发布时间：2024年11月07日

`LLM应用` `文档处理` `多模态`

> Hierarchical Visual Feature Aggregation for OCR-Free Document Understanding

# 摘要

> 我们推出了一个基于预训练多模态大型语言模型（MLLMs）的全新无 OCR 文档理解框架。我们的方法运用多尺度视觉特征，能有效应对文档图像里的各种字体大小。鉴于为 MLLMs 考虑多尺度视觉输入的成本持续攀升，我们提出了分层视觉特征聚合（HVFA）模块，旨在削减输入至 LLM 的标记数量。借助带有交叉注意力池化的特征金字塔，我们的方法在信息损失和效率之间实现了有效平衡，不受文档图像大小差异的影响。另外，我们引入了一项新颖的指令调整任务，通过学习预测输入文本的相对位置，提升模型的文本阅读能力，最终将因 LLM 容量有限导致的文本截断风险降到最低。综合实验证实了我们方法的有效性，在各类文档理解任务中展现出了出色的性能。

> We present a novel OCR-free document understanding framework based on pretrained Multimodal Large Language Models (MLLMs). Our approach employs multi-scale visual features to effectively handle various font sizes within document images. To address the increasing costs of considering the multi-scale visual inputs for MLLMs, we propose the Hierarchical Visual Feature Aggregation (HVFA) module, designed to reduce the number of input tokens to LLMs. Leveraging a feature pyramid with cross-attentive pooling, our approach effectively manages the trade-off between information loss and efficiency without being affected by varying document image sizes. Furthermore, we introduce a novel instruction tuning task, which facilitates the model's text-reading capability by learning to predict the relative positions of input text, eventually minimizing the risk of truncated text caused by the limited capacity of LLMs. Comprehensive experiments validate the effectiveness of our approach, demonstrating superior performance in various document understanding tasks.

[Arxiv](https://arxiv.org/abs/2411.05254)