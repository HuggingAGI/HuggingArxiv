# 从弱到强的外推过程，有效地促进了数据的对齐工作。

发布时间：2024年04月25日

`LLM理论` `人工智能`

> Weak-to-Strong Extrapolation Expedites Alignment

# 摘要

> 大型语言模型（LLM）的性能本应随着数据量和计算力的提升而增强，但实际上却受限于资源的有限性。如果我们已经拥有一个根据人类偏好适度训练的LLM，是否有可能进一步挖掘其潜力，以较低成本获得更强大的模型呢？本文提出了一种简洁的方法——ExPO，旨在提升LLM与人类偏好的契合度。ExPO基于这样的假设：在对齐程度较低（即较弱）的模型（如初始的SFT模型）和对齐程度较高（即较强）的模型之间，可以构建一个中等对齐度的模型，并通过从这两个较弱模型的权重进行外推，直接获得更强大的模型。在AlpacaEval 2.0基准测试中，我们证明了ExPO能够使使用较少偏好数据（如10%或20%）训练的模型达到甚至超过完全训练模型的性能，且无需额外训练。此外，ExPO还能显著提升现成的DPO/RLHF模型的性能，并且在从7B到70B不同规模的模型上都显示出良好的扩展性。我们的研究展示了通过模型外推来挖掘LLM潜力的有效性，为未来的探索指明了一个充满希望的方向。

> Although the capabilities of large language models (LLMs) ideally scale up with increasing data and compute, they are inevitably constrained by limited resources in reality. Suppose we have a moderately trained LLM (e.g., trained to align with human preference) in hand, can we further exploit its potential and cheaply acquire a stronger model? In this paper, we propose a simple method called ExPO to boost LLMs' alignment with human preference. ExPO assumes that a medium-aligned model can be interpolated between a less-aligned (weaker) model, e.g., the initial SFT model, and a better-aligned (stronger) one, thereby directly obtaining this stronger model by extrapolating from the weights of the former two relatively weaker models. On the AlpacaEval 2.0 benchmark, we show that ExPO pushes models trained with less preference data (e.g., 10% or 20%) to reach and even surpass the fully-trained one, without any additional training. Furthermore, ExPO also significantly improves off-the-shelf DPO/RLHF models and exhibits decent scalability across model sizes from 7B to 70B. Our work demonstrates the efficacy of model extrapolation in exploiting LLMs' capabilities, suggesting a promising direction that deserves future exploration.

[Arxiv](https://arxiv.org/abs/2404.16792)