# 利用合成数据探究大型语言模型的数学外推能力

发布时间：2024年06月04日

`LLM应用

这篇论文主要探讨了大型语言模型（LLMs）在处理复杂的多步推理问题，特别是数学推理任务中的应用。通过引入一种新颖的算术谜题，并展示了在优质合成数据上微调模型的效果，论文展示了模型在多步推理任务中的性能提升和泛化潜力。这属于LLM在特定任务上的应用研究，因此应归类为LLM应用。` `人工智能`

> Exploring Mathematical Extrapolation of Large Language Models with Synthetic Data

# 摘要

> 大型语言模型（LLMs）在语言理解、文本生成、代码合成等任务中大放异彩，但在处理复杂的多步推理问题，如数学推理时仍显吃力。本文通过引入一种新颖的算术谜题，揭示了通过在优质合成数据上微调，模型能在多步推理任务中大显身手。实验采用开放的llama-3B模型，在三个测试集上的结果不仅显示了在领域内数据集上0.44的零-shot pass@1，还展现了在领域外数据集上的泛化潜力。特别地，本文精心设计了两种领域外数据集，分别扩展了算术谜题的数值范围和组成元素。微调后的模型在这两个更具挑战性的任务上分别取得了0.33和0.35的零-shot pass@1，成绩令人振奋。

> Large Language Models (LLMs) have shown excellent performance in language understanding, text generation, code synthesis, and many other tasks, while they still struggle in complex multi-step reasoning problems, such as mathematical reasoning. In this paper, through a newly proposed arithmetical puzzle problem, we show that the model can perform well on multi-step reasoning tasks via fine-tuning on high-quality synthetic data. Experimental results with the open-llama-3B model on three different test datasets show that not only the model can reach a zero-shot pass@1 at 0.44 on the in-domain dataset, it also demonstrates certain generalization capabilities on the out-of-domain datasets. Specifically, this paper has designed two out-of-domain datasets in the form of extending the numerical range and the composing components of the arithmetical puzzle problem separately. The fine-tuned models have shown encouraging performance on these two far more difficult tasks with the zero-shot pass@1 at 0.33 and 0.35, respectively.

![利用合成数据探究大型语言模型的数学外推能力](../../../paper_images/2406.02100/dn.png)

![利用合成数据探究大型语言模型的数学外推能力](../../../paper_images/2406.02100/dx.png)

![利用合成数据探究大型语言模型的数学外推能力](../../../paper_images/2406.02100/DPL.png)

![利用合成数据探究大型语言模型的数学外推能力](../../../paper_images/2406.02100/DTL.png)

![利用合成数据探究大型语言模型的数学外推能力](../../../paper_images/2406.02100/loss.png)

![利用合成数据探究大型语言模型的数学外推能力](../../../paper_images/2406.02100/zeroshot.png)

![利用合成数据探究大型语言模型的数学外推能力](../../../paper_images/2406.02100/x1.png)

![利用合成数据探究大型语言模型的数学外推能力](../../../paper_images/2406.02100/x2.png)

[Arxiv](https://arxiv.org/abs/2406.02100)