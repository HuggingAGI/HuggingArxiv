# 借助 LLM 嵌入，实现跨数据集标签对齐，并进行零-shot 音乐情感预测。

发布时间：2024年10月15日

`LLM应用` `情感识别`

> Leveraging LLM Embeddings for Cross Dataset Label Alignment and Zero Shot Music Emotion Prediction

# 摘要

> 我们提出了一种新颖的音乐情感识别方法，利用 LLM 嵌入实现跨数据集的标签对齐和零-shot 预测。首先，我们通过非参数聚类将多个数据集中的相似情感标签分组，并使用聚类中心将音乐特征映射到 LLM 嵌入空间。为增强模型，我们引入了对齐正则化，使 MERT 嵌入能从不同聚类中分离，从而提升对新数据集的适应能力。通过在新数据集上的零-shot 推理，我们展示了该方法在无需额外训练的情况下对新标签的泛化能力。

> In this work, we present a novel method for music emotion recognition that leverages Large Language Model (LLM) embeddings for label alignment across multiple datasets and zero-shot prediction on novel categories. First, we compute LLM embeddings for emotion labels and apply non-parametric clustering to group similar labels, across multiple datasets containing disjoint labels. We use these cluster centers to map music features (MERT) to the LLM embedding space. To further enhance the model, we introduce an alignment regularization that enables dissociation of MERT embeddings from different clusters. This further enhances the model's ability to better adaptation to unseen datasets. We demonstrate the effectiveness of our approach by performing zero-shot inference on a new dataset, showcasing its ability to generalize to unseen labels without additional training.

[Arxiv](https://arxiv.org/abs/2410.11522)