# 语言模型，实为图学习的高手。

发布时间：2024年10月03日

`LLM应用` `机器学习` `图神经网络`

> Language Models are Graph Learners

# 摘要

> 语言模型 (LMs) 正逐渐挑战图神经网络 (GNNs) 和图变换器 (GTs) 在图学习任务中的主导地位。我们提出了一种新方法，让现成的 LMs 在节点分类任务上无需架构修改就能媲美最先进的 GNNs。这种方法保留了 LM 指令调优的优势，即在多样数据集上联合训练，提升灵活性和效率。我们采用了两种增强策略：一是通过拓扑和语义检索丰富输入，提供更丰富的上下文信息；二是用轻量级 GNN 分类器指导分类过程，有效筛选候选类别。实验表明，配备这些策略的 Flan-T5 模型在文本输出节点分类器中表现优异，与顶级向量输出节点分类器相当。这项工作为更通用和广泛适用的图学习模型铺平了道路，并将开源代码。

> Language Models (LMs) are increasingly challenging the dominance of domain-specific models, including Graph Neural Networks (GNNs) and Graph Transformers (GTs), in graph learning tasks. Following this trend, we propose a novel approach that empowers off-the-shelf LMs to achieve performance comparable to state-of-the-art GNNs on node classification tasks, without requiring any architectural modification. By preserving the LM's original architecture, our approach retains a key benefit of LM instruction tuning: the ability to jointly train on diverse datasets, fostering greater flexibility and efficiency. To achieve this, we introduce two key augmentation strategies: (1) Enriching LMs' input using topological and semantic retrieval methods, which provide richer contextual information, and (2) guiding the LMs' classification process through a lightweight GNN classifier that effectively prunes class candidates. Our experiments on real-world datasets show that backbone Flan-T5 models equipped with these augmentation strategies outperform state-of-the-art text-output node classifiers and are comparable to top-performing vector-output node classifiers. By bridging the gap between specialized task-specific node classifiers and general LMs, this work paves the way for more versatile and widely applicable graph learning models. We will open-source the code upon publication.

[Arxiv](https://arxiv.org/abs/2410.02296)