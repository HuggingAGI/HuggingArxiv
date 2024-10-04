# 中性残基：重新评估模型扩展中的适配器应用

发布时间：2024年10月03日

`LLM理论` `人工智能`

> Neutral residues: revisiting adapters for model extension

# 摘要

> 我们探讨了如何将预训练的大型语言模型扩展到新领域，例如为模型未曾接触过的语言添加支持。尽管微调等方法在领域适应上表现出色，但它们并未增加模型容量，且可能损害原始领域的性能。我们的研究从数据、架构和训练过程三个角度入手，提出了一种改进的适配器方法，使模型能在不改变原始领域输出的前提下，学习全新的语言。通过调整残差块，使其在新领域输出接近零，我们实现了这一目标。这一结合了专家混合架构的解决方案效果显著：与仅在英语上训练的模型相比，仅增加20%的可学习参数，便在语言学习和保留原始能力之间取得了更好的平衡，超越了现有的微调等方法。

> We address the problem of extending a pretrained large language model to a new domain that was not seen at training time, like adding a language for which the original model has seen no or little training data. Popular solutions like fine-tuning or low-rank adaptation are successful at domain adaptation, but formally they do not add any extra capacity and degrade the performance in the original domain.
  Our paper analyzes this extension problem under three angles: data, architecture and training procedure, which are advantageously considered jointly. In particular, we improve adapters and make it possible to learn an entire new language while ensuring that the output of the neural network is almost unchanged in the original domain. For this purpose, we modify the new residual blocks in a way that leads each new residual block to output near-zeros in the original domain.
  This solution of neutral residues, which borrows architectural components from mixture of experts, is effective: with only 20% extra learnable weights compared to an original model trained on English, we get results that are significantly better than concurrent approaches (fine-tuning, low-rank or vanilla adapters) in terms of the trade-off between learning a new language and not forgetting English.

[Arxiv](https://arxiv.org/abs/2410.02744)