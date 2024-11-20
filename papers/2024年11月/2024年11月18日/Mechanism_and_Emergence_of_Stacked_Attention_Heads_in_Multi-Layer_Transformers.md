# 多层 Transformer 中堆叠注意力头的机制与出现

发布时间：2024年11月18日

`LLM理论` `人工智能`

> Mechanism and Emergence of Stacked Attention Heads in Multi-Layer Transformers

# 摘要

> 在本文中，我引入了检索问题，这是个仅靠具有最少层数的转换器才能解决的简单推理任务。此任务难度可调，能将所需层数进一步提升至任意值。我证实大型语言模型在不同提示形式下能解决该任务，无需任何微调。为弄清楚转换器如何解决检索问题，我基于一个最简形式训练了若干转换器。我发现只有存在隐式课程时才会成功学习。通过研究训练后的转换器中的注意力图，我揭示了其学习机制。我还对训练过程进行了研究，发现注意力头总是按特定顺序出现。

> In this paper, I introduce the retrieval problem, a simple reasoning task that can be solved only by transformers with a minimum number of layers. The task has an adjustable difficulty that can further increase the required number of layers to any arbitrary value. I demonstrate that large language models can solve the task under different prompting formulations without any fine-tuning. To understand how transformers solve the retrieval problem, I train several transformers on a minimal formulation. I find that successful learning occurs only under the presence of an implicit curriculum. I uncover the learned mechanisms by studying the attention maps in the trained transformers. I also study the training process, uncovering that attention heads always emerge in a specific sequence.

[Arxiv](https://arxiv.org/abs/2411.12118)