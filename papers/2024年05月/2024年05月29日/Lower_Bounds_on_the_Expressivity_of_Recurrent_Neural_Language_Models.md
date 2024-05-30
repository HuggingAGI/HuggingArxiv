# 循环神经语言模型表达力下界探究

发布时间：2024年05月29日

`LLM理论

这篇论文主要探讨了大型神经语言模型（如RNN LMs）的计算能力和表征能力，特别是通过与概率性有限状态自动机（FSAs）的联系来重新评估这些模型的能力。这种研究关注的是模型的理论性质和计算潜力，而不是具体的应用或代理行为，因此最适合归类为LLM理论。` `计算语言学`

> Lower Bounds on the Expressivity of Recurrent Neural Language Models

# 摘要

> 随着大型神经语言模型的兴起，对其计算能力的深入理解变得至关重要。目前，研究者们热衷于通过LMs的表征能力来探索其计算潜力，但大多数研究仅限于这些模型识别形式语言的能力。例如，带有Heaviside激活的RNNs与正则语言（由有限状态自动机定义）紧密相关。然而，这些研究未能全面揭示RNN语言模型的能力，因为这些模型本质上是对字符串的概率分布。本研究通过将RNN LMs与概率性FSAs相联系，重新评估了RNN LMs的表征能力，并发现具有线性有界精度的RNN LMs能够表达任意正则LMs。

> The recent successes and spread of large neural language models (LMs) call for a thorough understanding of their computational ability. Describing their computational abilities through LMs' \emph{representational capacity} is a lively area of research. However, investigation into the representational capacity of neural LMs has predominantly focused on their ability to \emph{recognize} formal languages. For example, recurrent neural networks (RNNs) with Heaviside activations are tightly linked to regular languages, i.e., languages defined by finite-state automata (FSAs). Such results, however, fall short of describing the capabilities of RNN \emph{language models} (LMs), which are definitionally \emph{distributions} over strings. We take a fresh look at the representational capacity of RNN LMs by connecting them to \emph{probabilistic} FSAs and demonstrate that RNN LMs with linearly bounded precision can express arbitrary regular LMs.

[Arxiv](https://arxiv.org/abs/2405.19222)