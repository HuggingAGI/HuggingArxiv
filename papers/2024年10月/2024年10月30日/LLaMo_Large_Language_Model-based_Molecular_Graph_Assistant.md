# LLaMo：基于大型语言模型的分子图辅助工具

发布时间：2024年10月30日

`LLM应用`

> LLaMo: Large Language Model-based Molecular Graph Assistant

# 摘要

> 大型语言模型（LLMs）借助指令调整展现出了非凡的泛化及遵循指令的能力，LLMs 与指令调整的进步催生了大型视觉语言模型（LVLMs）。但在分子领域，LLMs 和指令调整的能力探索相对较少。于是，我们推出了 LLaMo：基于大型语言模型的分子图助手，这是一个端到端训练的大型分子图语言模型。为了消除语言和图形模式的差异，我们给出了多级图形投影仪，它利用交叉注意力机制，对每个 GNN 层的输出表示和基序表示进行抽象，从而将图形表示转化为图形标记。我们还引入了机器生成的分子图指令数据，对大型分子图语言模型进行指令调整，以实现通用分子和语言的理解。我们的大量实验表明，LLaMo 在诸如分子描述生成、属性预测和 IUPAC 名称预测等各类任务中表现出色。LLaMo 的代码可在 https://github.com/mlvlab/LLaMo 获取。

> Large Language Models (LLMs) have demonstrated remarkable generalization and instruction-following capabilities with instruction tuning. The advancements in LLMs and instruction tuning have led to the development of Large Vision-Language Models (LVLMs). However, the competency of the LLMs and instruction tuning have been less explored in the molecular domain. Thus, we propose LLaMo: Large Language Model-based Molecular graph assistant, which is an end-to-end trained large molecular graph-language model. To bridge the discrepancy between the language and graph modalities, we present the multi-level graph projector that transforms graph representations into graph tokens by abstracting the output representations of each GNN layer and motif representations with the cross-attention mechanism. We also introduce machine-generated molecular graph instruction data to instruction-tune the large molecular graph-language model for general-purpose molecule and language understanding. Our extensive experiments demonstrate that LLaMo shows the best performance on diverse tasks, such as molecular description generation, property prediction, and IUPAC name prediction. The code of LLaMo is available at https://github.com/mlvlab/LLaMo.

[Arxiv](https://arxiv.org/abs/2411.00871)