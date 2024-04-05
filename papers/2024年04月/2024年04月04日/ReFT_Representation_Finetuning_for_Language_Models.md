# ReFT 代表「表示微调」，是一种针对语言模型的优化技术。

发布时间：2024年04月04日

`LLM理论` `人工智能` `模型优化`

> ReFT: Representation Finetuning for Language Models

# 摘要

> 参数高效微调（PEFT）寻求通过调整少数权重来优化大型模型。但以往的研究显示，模型的表示中蕴含丰富的语义信息，这表明直接编辑这些表示可能是一种更为有效的策略。基于此，我们提出了一系列“表示微调（ReFT）”技术。ReFT技术在保持基础模型不变的情况下，针对隐藏层的表示进行特定任务的调整。我们特别推出了低秩线性子空间ReFT（LoReFT），它不仅能够无缝替代现有的PEFT技术，而且其学习的干预措施在参数效率上比以往的PEFT技术提高了10到50倍。我们在多个任务上验证了LoReFT的效果，包括八个常识推理任务、四个算术推理任务、Alpaca-Eval v1.0以及GLUE基准，LoReFT均展现出了卓越的性能与效率的平衡，几乎在所有情况下都超越了当前最先进的PEFT技术。我们在 https://github.com/stanfordnlp/pyreft 上公开发布了一个通用的ReFT训练库。

> Parameter-efficient fine-tuning (PEFT) methods seek to adapt large models via updates to a small number of weights. However, much prior interpretability work has shown that representations encode rich semantic information, suggesting that editing representations might be a more powerful alternative. Here, we pursue this hypothesis by developing a family of $\textbf{Representation Finetuning (ReFT)}$ methods. ReFT methods operate on a frozen base model and learn task-specific interventions on hidden representations. We define a strong instance of the ReFT family, Low-rank Linear Subspace ReFT (LoReFT). LoReFT is a drop-in replacement for existing PEFTs and learns interventions that are 10x-50x more parameter-efficient than prior state-of-the-art PEFTs. We showcase LoReFT on eight commonsense reasoning tasks, four arithmetic reasoning tasks, Alpaca-Eval v1.0, and GLUE. In all these evaluations, LoReFT delivers the best balance of efficiency and performance, and almost always outperforms state-of-the-art PEFTs. We release a generic ReFT training library publicly at https://github.com/stanfordnlp/pyreft.

[Arxiv](https://arxiv.org/abs/2404.03592)