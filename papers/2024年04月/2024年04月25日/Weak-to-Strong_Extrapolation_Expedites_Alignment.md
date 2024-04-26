# 弱至强外推法加速了对齐过程。

发布时间：2024年04月25日

`LLM应用` `人工智能`

> Weak-to-Strong Extrapolation Expedites Alignment

# 摘要

> 大型语言模型（LLMs）的性能理应随着数据和计算资源的增加而提升，但现实中却受限于资源的紧缺。若我们已拥有一个经过适度训练的LLM（比如，针对人类偏好进行了优化），是否有可能进一步挖掘其潜力，以较低成本获得更优的模型？本文提出了一种简洁的方法——ExPO，旨在提升LLM与人类偏好的契合度。ExPO基于这样的假设：在较不匹配的模型（例如初始的SFT模型）与更匹配的模型之间，可以通过插值得到一个中等匹配度的模型，进而通过外推这两个相对较弱模型的权重，直接构建出更优的模型。在AlpacaEval 2.0的基准测试中，我们证明了ExPO能够使那些仅使用了少量偏好数据（如10%或20%）训练的模型达到甚至超越全量训练模型的性能，且无需额外的训练。此外，ExPO还能显著提升现成的DPO/RLHF模型，并在7B至70B不同规模的模型上展现出良好的扩展性。本研究证实了模型外推在挖掘LLM潜力方面的有效性，为未来的探索指明了一个充满希望的方向。

> Although the capabilities of large language models (LLMs) ideally scale up with increasing data and compute, they are inevitably constrained by limited resources in reality. Suppose we have a moderately trained LLM (e.g., trained to align with human preference) in hand, can we further exploit its potential and cheaply acquire a stronger model? In this paper, we propose a simple method called ExPO to boost LLMs' alignment with human preference. ExPO assumes that a medium-aligned model can be interpolated between a less-aligned (weaker) model, e.g., the initial SFT model, and a better-aligned (stronger) one, thereby directly obtaining this stronger model by extrapolating from the weights of the former two relatively weaker models. On the AlpacaEval 2.0 benchmark, we show that ExPO pushes models trained with less preference data (e.g., 10% or 20%) to reach and even surpass the fully-trained one, without any additional training. Furthermore, ExPO also significantly improves off-the-shelf DPO/RLHF models and exhibits decent scalability across model sizes from 7B to 70B. Our work demonstrates the efficacy of model extrapolation in exploiting LLMs' capabilities, suggesting a promising direction that deserves future exploration.

[Arxiv](https://arxiv.org/abs/2404.16792)