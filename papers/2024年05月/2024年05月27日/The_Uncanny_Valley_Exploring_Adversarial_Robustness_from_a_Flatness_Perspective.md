# 《诡异谷效应：从平坦度视角探究对抗性鲁棒性》

发布时间：2024年05月27日

`LLM理论

这篇论文主要探讨了大型语言模型（LLMs）在对抗性攻击下的鲁棒性问题，特别是损失表面的平坦性与对抗性鲁棒性之间的关系。论文通过实证研究分析了模型层参数与对抗性示例之间的关系，并提出了理论上的见解，强调了鲁棒模型需要兼具平坦性和低全局Lipschitz常数。这些内容属于对LLM理论层面的深入探讨，因此归类为LLM理论。` `机器学习` `网络安全`

> The Uncanny Valley: Exploring Adversarial Robustness from a Flatness Perspective

# 摘要

> 损失表面的平坦性不仅有助于泛化，还与对抗性鲁棒性息息相关，因为输入与权重的扰动之间存在非线性联系。本文实证探讨了对抗性示例与模型层参数相关的相对平坦性之间的关系。我们发现，在迭代的一阶白盒攻击中，对抗性示例周围的损失表面起初会变得更尖锐，直至标签翻转，但若攻击持续，则会陷入一个标签持续翻转的平坦诡异谷。此现象在多种模型和数据集中均有体现。尽管大型语言模型（LLMs）也受此影响，但因输入空间的离散性和攻击的相对弱势，对抗性示例很少触及真正的平坦区域。这一发现强调，仅凭平坦性不足以确保对抗性鲁棒性，还需确保函数在示例周围的行为。我们通过限制损失表面的第三导数，理论上揭示了相对平坦性与对抗性鲁棒性的联系，强调了鲁棒模型需兼具平坦性与低全局Lipschitz常数。

> Flatness of the loss surface not only correlates positively with generalization but is also related to adversarial robustness, since perturbations of inputs relate non-linearly to perturbations of weights. In this paper, we empirically analyze the relation between adversarial examples and relative flatness with respect to the parameters of one layer. We observe a peculiar property of adversarial examples: during an iterative first-order white-box attack, the flatness of the loss surface measured around the adversarial example first becomes sharper until the label is flipped, but if we keep the attack running it runs into a flat uncanny valley where the label remains flipped. We find this phenomenon across various model architectures and datasets. Our results also extend to large language models (LLMs), but due to the discrete nature of the input space and comparatively weak attacks, the adversarial examples rarely reach a truly flat region. Most importantly, this phenomenon shows that flatness alone cannot explain adversarial robustness unless we can also guarantee the behavior of the function around the examples. We theoretically connect relative flatness to adversarial robustness by bounding the third derivative of the loss surface, underlining the need for flatness in combination with a low global Lipschitz constant for a robust model.

[Arxiv](https://arxiv.org/abs/2405.16918)