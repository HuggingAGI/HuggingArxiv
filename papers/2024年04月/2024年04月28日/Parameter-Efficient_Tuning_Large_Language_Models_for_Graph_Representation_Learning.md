# 通过参数高效的方法调整大型语言模型，以优化图表示学习的效果。

发布时间：2024年04月28日

`LLM应用` `商业应用` `图表示学习`

> Parameter-Efficient Tuning Large Language Models for Graph Representation Learning

# 摘要

> 文本丰富的图在众多现实世界的商业应用中无处不在，它们在节点和边中嵌入了丰富的文本信息。大型语言模型（LLMs）凭借其卓越的文本理解能力，为这类图的建模提供了新的表达潜力。然而，将LLMs应用于图的表示学习，尽管潜力巨大，却也面临着不小的挑战。最近，一种针对LLMs的参数高效微调技术，以最小的时间和内存消耗，实现了新任务的快速泛化。基于此，我们提出了图感知参数高效微调（GPEFT），这是一种创新的方法，用于在文本丰富的图上与LLMs一起进行高效的图表示学习。我们利用图神经网络（GNN）捕捉邻近节点的结构信息，并将这些信息编码成图提示，该提示置于文本序列的前端。为了提升图提示的质量，我们对GNN进行了预训练，以便在LLM固定的情况下预测节点文本中的下一个标记。与现有的GNN和语言模型的联合方法相比，我们的方法能够以较低的微调成本，直接从大型语言模型中生成节点嵌入。通过在8种不同的文本丰富图上进行的广泛实验，我们在链接预测评估中实现了平均2%的性能提升，无论是在命中率@1还是平均倒数排名（MRR）上。这些结果展示了我们模型的高效性和有效性，并证明了它可以无缝地与包括OPT、LLaMA和Falcon在内的多种大型语言模型集成。

> Text-rich graphs, which exhibit rich textual information on nodes and edges, are prevalent across a wide range of real-world business applications. Large Language Models (LLMs) have demonstrated remarkable abilities in understanding text, which also introduced the potential for more expressive modeling in text-rich graphs. Despite these capabilities, efficiently applying LLMs to representation learning on graphs presents significant challenges. Recently, parameter-efficient fine-tuning methods for LLMs have enabled efficient new task generalization with minimal time and memory consumption. Inspired by this, we introduce Graph-aware Parameter-Efficient Fine-Tuning - GPEFT, a novel approach for efficient graph representation learning with LLMs on text-rich graphs. Specifically, we utilize a graph neural network (GNN) to encode structural information from neighboring nodes into a graph prompt. This prompt is then inserted at the beginning of the text sequence. To improve the quality of graph prompts, we pre-trained the GNN to assist the frozen LLM in predicting the next token in the node text. Compared with existing joint GNN and LMs, our method directly generate the node embeddings from large language models with an affordable fine-tuning cost. We validate our approach through comprehensive experiments conducted on 8 different text-rich graphs, observing an average improvement of 2% in hit@1 and Mean Reciprocal Rank (MRR) in link prediction evaluations. Our results demonstrate the efficacy and efficiency of our model, showing that it can be smoothly integrated with various large language models, including OPT, LLaMA and Falcon.

[Arxiv](https://arxiv.org/abs/2404.18271)