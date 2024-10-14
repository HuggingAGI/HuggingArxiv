# 探讨广义“跳跃连接”在对抗性场景中的可迁移性

发布时间：2024年10月11日

`LLM理论` `网络安全` `人工智能`

> On the Adversarial Transferability of Generalized "Skip Connections"

# 摘要

> 跳跃连接是现代深度模型变得更强大和深邃的关键。尽管在常规场景中表现卓越，我们发现跳跃连接在对抗场景下有一个有趣特性：它使得生成高度可转移的对抗样本变得更容易。具体来说，在类似 ResNet 的模型中，通过反向传播时更多地利用跳跃连接的梯度，可以制作出更具转移性的对抗样本。这种方法被称为跳跃梯度方法（SGM）。我们从视觉领域的 ResNet 模型出发，进一步将 SGM 应用于更复杂的架构，如视觉变换器（ViTs）和自然语言处理模型。我们对多种模型进行了全面的转移攻击测试，结果显示 SGM 在几乎所有情况下都能显著提升攻击的转移性。此外，考虑到实际应用的复杂性，SGM 还能提高对模型集合和目标攻击的转移性，并增强对现有防御的隐蔽性。最后，我们提供了 SGM 工作原理的理论解释和实证见解。这些发现不仅推动了对抗研究的新方向，也为安全模型设计带来了新的挑战。代码已公开在 https://github.com/mo666666/SGM。

> Skip connection is an essential ingredient for modern deep models to be deeper and more powerful. Despite their huge success in normal scenarios (state-of-the-art classification performance on natural examples), we investigate and identify an interesting property of skip connections under adversarial scenarios, namely, the use of skip connections allows easier generation of highly transferable adversarial examples. Specifically, in ResNet-like models (with skip connections), we find that using more gradients from the skip connections rather than the residual modules according to a decay factor during backpropagation allows one to craft adversarial examples with high transferability. The above method is termed as Skip Gradient Method (SGM). Although starting from ResNet-like models in vision domains, we further extend SGM to more advanced architectures, including Vision Transformers (ViTs) and models with length-varying paths and other domains, i.e. natural language processing. We conduct comprehensive transfer attacks against various models including ResNets, Transformers, Inceptions, Neural Architecture Search, and Large Language Models (LLMs). We show that employing SGM can greatly improve the transferability of crafted attacks in almost all cases. Furthermore, considering the big complexity for practical use, we further demonstrate that SGM can even improve the transferability on ensembles of models or targeted attacks and the stealthiness against current defenses. At last, we provide theoretical explanations and empirical insights on how SGM works. Our findings not only motivate new adversarial research into the architectural characteristics of models but also open up further challenges for secure model architecture design. Our code is available at https://github.com/mo666666/SGM.

[Arxiv](https://arxiv.org/abs/2410.08950)