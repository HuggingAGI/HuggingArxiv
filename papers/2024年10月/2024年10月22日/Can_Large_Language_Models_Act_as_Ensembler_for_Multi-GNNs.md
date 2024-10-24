# 大型语言模型能作为多 GNN 的集成器吗？

发布时间：2024年10月22日

`LLM应用` `图学习`

> Can Large Language Models Act as Ensembler for Multi-GNNs?

# 摘要

> 图神经网络（GNNs）已成为从图结构数据中学习的强大模型。然而，GNNs 缺乏丰富文本节点属性的固有语义理解能力，限制了它们在应用中的有效性。另一方面，我们凭经验观察到，对于现有的 GNN 模型，没有一个能在不同的数据集上始终优于其他模型。在本文中，我们研究了大型语言模型（LLMs）是否可以作为多 GNNs 的集成器，并提出了 LensGNN 模型。该模型首先对齐多个 GNNs，将不同 GNNs 的表示映射到同一空间。然后，通过 LoRA 微调，它对齐 GNN 和 LLM 之间的空间，将图标记和文本信息注入到 LLMs 中。这使得 LensGNN 能够集成多个 GNNs 并利用 LLM 的优势，从而获得更好的性能。实验结果表明，LensGNN 优于现有模型。这项研究通过为整合语义和结构信息提供一个强大、优越的解决方案，推进了具有文本属性的图集成学习。我们在此提供我们的代码和数据：https://anonymous.4open.science/r/EnsemGNN-E267/。

> Graph Neural Networks (GNNs) have emerged as powerful models for learning from graph-structured data. However, GNNs lack the inherent semantic understanding capability of rich textual nodesattributes, limiting their effectiveness in applications. On the other hand, we empirically observe that for existing GNN models, no one can consistently outperforms others across diverse datasets. In this paper, we study whether LLMs can act as an ensembler for multi-GNNs and propose the LensGNN model. The model first aligns multiple GNNs, mapping the representations of different GNNs into the same space. Then, through LoRA fine-tuning, it aligns the space between the GNN and the LLM, injecting graph tokens and textual information into LLMs. This allows LensGNN to integrate multiple GNNs and leverage LLM's strengths, resulting in better performance. Experimental results show that LensGNN outperforms existing models. This research advances text-attributed graph ensemble learning by providing a robust, superior solution for integrating semantic and structural information. We provide our code and data here: https://anonymous.4open.science/r/EnsemGNN-E267/.

[Arxiv](https://arxiv.org/abs/2410.16822)