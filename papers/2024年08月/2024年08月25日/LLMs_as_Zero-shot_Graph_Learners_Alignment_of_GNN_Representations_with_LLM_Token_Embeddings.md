# LLM 作为零-shot 图学习器，探讨 GNN 表示与 LLM 令牌嵌入的匹配问题。

发布时间：2024年08月25日

`LLM应用` `机器学习` `图神经网络`

> LLMs as Zero-shot Graph Learners: Alignment of GNN Representations with LLM Token Embeddings

# 摘要

> 零-shot图机器学习，尤其是借助图神经网络（GNNs），因标签数据稀缺而备受关注。尽管自监督学习和图提示学习等方法已被广泛研究，但它们往往依赖于特定任务标签的微调，限制了其在零-shot场景中的效能。受指令微调大型语言模型（LLMs）零-shot能力的启发，我们推出了一个创新框架——Token嵌入对齐图语言模型（TEA-GLM），利用LLMs作为跨数据集和跨任务的零-shot学习者，应用于图机器学习。具体而言，我们预训练GNN，使其表示与LLM的token嵌入相匹配，并训练一个线性投影器，将GNN的表示转换为固定数量的图token嵌入，无需调整LLM。针对节点分类（节点级）和链接预测（边级）等不同级别的图任务，我们设计了一个统一的指令。这些设计选择共同提升了我们方法在零-shot学习中的效能，使其脱颖而出。实验结果显示，我们的图token嵌入助力LLM预测器在未见数据集和任务上超越其他使用LLMs作为预测器的方法，达到行业领先水平。

> Zero-shot graph machine learning, especially with graph neural networks (GNNs), has garnered significant interest due to the challenge of scarce labeled data. While methods like self-supervised learning and graph prompt learning have been extensively explored, they often rely on fine-tuning with task-specific labels, limiting their effectiveness in zero-shot scenarios. Inspired by the zero-shot capabilities of instruction-fine-tuned large language models (LLMs), we introduce a novel framework named Token Embedding-Aligned Graph Language Model (TEA-GLM) that leverages LLMs as cross-dataset and cross-task zero-shot learners for graph machine learning. Concretely, we pretrain a GNN, aligning its representations with token embeddings of an LLM. We then train a linear projector that transforms the GNN's representations into a fixed number of graph token embeddings without tuning the LLM. A unified instruction is designed for various graph tasks at different levels, such as node classification (node-level) and link prediction (edge-level). These design choices collectively enhance our method's effectiveness in zero-shot learning, setting it apart from existing methods. Experiments show that our graph token embeddings help the LLM predictor achieve state-of-the-art performance on unseen datasets and tasks compared to other methods using LLMs as predictors.

[Arxiv](https://arxiv.org/abs/2408.14512)