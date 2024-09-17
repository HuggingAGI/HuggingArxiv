# DILA：高维多标签医学编码预测中，通过字典标签注意力提升机制可解释性

发布时间：2024年09月16日

`LLM应用` `人工智能`

> DILA: Dictionary Label Attention for Mechanistic Interpretability in High-dimensional Multi-label Medical Coding Prediction

# 摘要

> 在医疗编码等高维多标签预测中，准确性与可解释性缺一不可。现有方法多依赖局部解释，难以全面揭示多标签预测背后的整体机制。为此，我们设计了 DIctionary Label Attention (\method) 模块，将密集嵌入转化为稀疏空间，每个非零元素代表一个全局医疗概念。经人类评估，稀疏嵌入的可理解性比密集嵌入高出至少 50%。借助大型语言模型 (LLM)，我们自动识别字典特征，揭示数千医疗概念。通过稀疏矩阵，我们清晰呈现字典特征与医疗代码的关系，既提升了解释性，又保持了优异性能与扩展性，无需繁琐的人工注释。

> Predicting high-dimensional or extreme multilabels, such as in medical coding, requires both accuracy and interpretability. Existing works often rely on local interpretability methods, failing to provide comprehensive explanations of the overall mechanism behind each label prediction within a multilabel set. We propose a mechanistic interpretability module called DIctionary Label Attention (\method) that disentangles uninterpretable dense embeddings into a sparse embedding space, where each nonzero element (a dictionary feature) represents a globally learned medical concept. Through human evaluations, we show that our sparse embeddings are more human understandable than its dense counterparts by at least 50 percent. Our automated dictionary feature identification pipeline, leveraging large language models (LLMs), uncovers thousands of learned medical concepts by examining and summarizing the highest activating tokens for each dictionary feature. We represent the relationships between dictionary features and medical codes through a sparse interpretable matrix, enhancing the mechanistic and global understanding of the model's predictions while maintaining competitive performance and scalability without extensive human annotation.

[Arxiv](https://arxiv.org/abs/2409.10504)