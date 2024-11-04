# 通过核主成分分析揭示自注意力的隐藏结构

发布时间：2024年06月19日

`LLM理论` `计算机视觉`

> Unveiling the Hidden Structure of Self-Attention via Kernel Principal Component Analysis

# 摘要

> 摘要：在自然语言处理和计算机视觉的各种应用中，Transformer 在序列建模任务中取得了显著的成功，这归因于自注意力的关键作用。与大多数深度学习模型的发展类似，这些注意力机制的构建依赖于启发式方法和经验。在我们的工作中，我们从核主成分分析（kernel PCA）推导出自注意力，并表明自注意力将其查询向量投影到其键矩阵在特征空间中的主成分轴上。然后，我们为自注意力中的值矩阵制定了精确的公式，从理论和经验上证明了这个值矩阵捕获了自注意力中键向量的 Gram 矩阵的特征向量。利用我们的核 PCA 框架，我们提出了具有鲁棒主成分的注意力（RPC-Attention），这是一种新型的鲁棒注意力，对数据污染具有弹性。我们通过实验证明了 RPC-Attention 在 ImageNet-1K 目标分类、WikiText-103 语言建模和 ADE20K 图像分割任务上优于 softmax 注意力的优势。

> 
Abstract:The remarkable success of transformers in sequence modeling tasks, spanning various applications in natural language processing and computer vision, is attributed to the critical role of self-attention. Similar to the development of most deep learning models, the construction of these attention mechanisms relies on heuristics and experience. In our work, we derive self-attention from kernel principal component analysis (kernel PCA) and show that self-attention projects its query vectors onto the principal component axes of its key matrix in a feature space. We then formulate the exact formula for the value matrix in self-attention, theoretically and empirically demonstrating that this value matrix captures the eigenvectors of the Gram matrix of the key vectors in self-attention. Leveraging our kernel PCA framework, we propose Attention with Robust Principal Components (RPC-Attention), a novel class of robust attention that is resilient to data contamination. We empirically demonstrate the advantages of RPC-Attention over softmax attention on the ImageNet-1K object classification, WikiText-103 language modeling, and ADE20K image segmentation task.
    

[Arxiv](https://arxiv.org/pdf/2406.13762)