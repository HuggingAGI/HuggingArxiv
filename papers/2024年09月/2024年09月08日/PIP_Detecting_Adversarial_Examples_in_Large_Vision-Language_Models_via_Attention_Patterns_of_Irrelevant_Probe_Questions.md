# PIP：利用无关探测问题的注意力模式，识别大型视觉-语言模型中的对抗性示例。

发布时间：2024年09月08日

`LLM应用` `人工智能`

> PIP: Detecting Adversarial Examples in Large Vision-Language Models via Attention Patterns of Irrelevant Probe Questions

# 摘要

> 大型视觉语言模型 (LVLMs) 虽然展示了强大的多模态能力，但也面临着严重的安全问题，因为对手可以通过精心设计的对抗性示例引发鲁棒性问题。因此，LVLMs 急需对抗性示例的检测工具。我们发现，LVLMs 对干净图像在面对探测问题时会表现出规律的注意力模式。为此，我们提出了一种名为 PIP 的非传统方法，利用一个无关探测问题（如“那里有钟吗？”）的注意力模式来区分对抗性示例和干净示例。PIP 只需对图像和探测问题进行一次额外推理，即可成功检测对抗性示例。即使在黑盒攻击和开放数据集场景下，PIP 结合简单 SVM 仍能实现超过 98% 的召回率和 90% 以上的精确度。PIP 首次尝试通过简单无关探测问题检测 LVLMs 上的对抗性攻击，为更深入的理解和内省提供了新视角。代码已开源，详见 https://github.com/btzyd/pip。

> Large Vision-Language Models (LVLMs) have demonstrated their powerful multimodal capabilities. However, they also face serious safety problems, as adversaries can induce robustness issues in LVLMs through the use of well-designed adversarial examples. Therefore, LVLMs are in urgent need of detection tools for adversarial examples to prevent incorrect responses. In this work, we first discover that LVLMs exhibit regular attention patterns for clean images when presented with probe questions. We propose an unconventional method named PIP, which utilizes the attention patterns of one randomly selected irrelevant probe question (e.g., "Is there a clock?") to distinguish adversarial examples from clean examples. Regardless of the image to be tested and its corresponding question, PIP only needs to perform one additional inference of the image to be tested and the probe question, and then achieves successful detection of adversarial examples. Even under black-box attacks and open dataset scenarios, our PIP, coupled with a simple SVM, still achieves more than 98% recall and a precision of over 90%. Our PIP is the first attempt to detect adversarial attacks on LVLMs via simple irrelevant probe questions, shedding light on deeper understanding and introspection within LVLMs. The code is available at https://github.com/btzyd/pip.

[Arxiv](https://arxiv.org/abs/2409.05076)