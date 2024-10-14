# 一种基于社交上下文和图结构的多模态注意力学习框架，专为紧急情况下的灾难内容分类设计

发布时间：2024年10月11日

`其他` `公共安全` `社交媒体`

> A Social Context-aware Graph-based Multimodal Attentive Learning Framework for Disaster Content Classification during Emergencies

# 摘要

> 在危机时刻，社交媒体上灾难信息的及时准确分类对灾难响应和公共安全至关重要。然而，大量未过滤数据的涌入使人道主义组织难以有效利用这些信息。现有方法往往忽视了用户的可信度、情感背景和社会互动，而这些对准确分类至关重要。为此，我们提出了CrisisSpot，利用图神经网络捕捉文本和视觉模态的复杂关系，并引入社会背景特征。我们还设计了倒置双重嵌入注意力（IDEA），以捕捉数据中的和谐与对比模式，增强多模态交互。此外，我们发布了TSEqD数据集，包含10,352个样本。实验表明，CrisisSpot在CrisisMMD和TSEqD数据集上分别比最先进方法提升了9.45%和5.01%的F1分数。

> In times of crisis, the prompt and precise classification of disaster-related information shared on social media platforms is crucial for effective disaster response and public safety. During such critical events, individuals use social media to communicate, sharing multimodal textual and visual content. However, due to the significant influx of unfiltered and diverse data, humanitarian organizations face challenges in leveraging this information efficiently. Existing methods for classifying disaster-related content often fail to model users' credibility, emotional context, and social interaction information, which are essential for accurate classification. To address this gap, we propose CrisisSpot, a method that utilizes a Graph-based Neural Network to capture complex relationships between textual and visual modalities, as well as Social Context Features to incorporate user-centric and content-centric information. We also introduce Inverted Dual Embedded Attention (IDEA), which captures both harmonious and contrasting patterns within the data to enhance multimodal interactions and provide richer insights. Additionally, we present TSEqD (Turkey-Syria Earthquake Dataset), a large annotated dataset for a single disaster event, containing 10,352 samples. Through extensive experiments, CrisisSpot demonstrated significant improvements, achieving an average F1-score gain of 9.45% and 5.01% compared to state-of-the-art methods on the publicly available CrisisMMD dataset and the TSEqD dataset, respectively.

[Arxiv](https://arxiv.org/abs/2410.08814)