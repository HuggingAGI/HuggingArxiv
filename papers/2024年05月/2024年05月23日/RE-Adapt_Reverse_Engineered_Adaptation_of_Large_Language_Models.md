# RE-Adapt：大型语言模型的逆向适应工程

发布时间：2024年05月23日

`RAG

理由：这篇论文介绍了一种名为RE-Adapt的方法，该方法能够在不损害原有指令调整效果的前提下，对大型语言模型进行新领域的微调。这种方法通过逆向工程开发了一个适配器，用于隔离指令调整模型在预训练基础模型之外所获得的知识。这种方法特别强调了在结合检索增强生成（RAG）使用时的效果，因此归类为RAG。虽然论文涉及了LLM的微调和应用，但其核心贡献在于提供了一种新的微调方法，这种方法在RAG框架下表现出色，因此更适合归类于RAG而非LLM应用或LLM理论。` `机器学习`

> RE-Adapt: Reverse Engineered Adaptation of Large Language Models

# 摘要

> 我们推出了RE-Adapt方法，它能在不损害原有指令调整效果的前提下，对大型语言模型进行新领域的微调。通过逆向工程，我们开发了一个适配器，它能隔离指令调整模型在预训练基础模型之外所获得的知识。这一过程无需额外数据或训练。接着，我们可对基础模型在新领域进行微调，并借助逆向工程的适配器使其重新适应指令执行。无论是RE-Adapt还是其低秩版本LoRE-Adapt，在多个主流LLMs和数据集上的表现均超越了其他微调技术，即便在结合检索增强生成使用时亦是如此。

> We introduce RE-Adapt, an approach to fine-tuning large language models on new domains without degrading any pre-existing instruction-tuning. We reverse engineer an adapter which isolates what an instruction-tuned model has learned beyond its corresponding pretrained base model. Importantly, this requires no additional data or training. We can then fine-tune the base model on a new domain and readapt it to instruction following with the reverse engineered adapter. RE-Adapt and our low-rank variant LoRE-Adapt both outperform other methods of fine-tuning, across multiple popular LLMs and datasets, even when the models are used in conjunction with retrieval-augmented generation.

[Arxiv](https://arxiv.org/abs/2405.15007)