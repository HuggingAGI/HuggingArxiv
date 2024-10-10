# 颠覆视觉感知：针对大型视觉-语言模型编码视觉标记的对抗攻击

发布时间：2024年10月09日

`LLM应用` `计算机视觉` `网络安全`

> Break the Visual Perception: Adversarial Attacks Targeting Encoded Visual Tokens of Large Vision-Language Models

# 摘要

> 大型视觉-语言模型（LVLMs）通过整合视觉信息，展现了卓越的多模态对话能力。然而，视觉模块的引入也为模型的鲁棒性带来了新挑战，因为攻击者可以制作看似无害但能误导模型生成错误答案的对抗性图像。LVLMs 通常依赖视觉编码器将图像转换为视觉令牌，这对于模型理解图像内容至关重要。因此，我们提出一个问题：当视觉令牌受到攻击并被破坏时，LVLMs 还能否生成正确答案？为此，我们设计了一种名为 VT-Attack 的非目标攻击方法，该方法从多个角度构建对抗性示例，旨在全面破坏视觉令牌的特征表示和语义属性。实验证明，VT-Attack 在攻击 LVLMs 方面表现优异，不仅在不同模型间具有可转移性，还能跨任务通用。这一研究不仅揭示了 LVLMs 的脆弱性，也为提升其鲁棒性提供了重要参考。

> Large vision-language models (LVLMs) integrate visual information into large language models, showcasing remarkable multi-modal conversational capabilities. However, the visual modules introduces new challenges in terms of robustness for LVLMs, as attackers can craft adversarial images that are visually clean but may mislead the model to generate incorrect answers. In general, LVLMs rely on vision encoders to transform images into visual tokens, which are crucial for the language models to perceive image contents effectively. Therefore, we are curious about one question: Can LVLMs still generate correct responses when the encoded visual tokens are attacked and disrupting the visual information? To this end, we propose a non-targeted attack method referred to as VT-Attack (Visual Tokens Attack), which constructs adversarial examples from multiple perspectives, with the goal of comprehensively disrupting feature representations and inherent relationships as well as the semantic properties of visual tokens output by image encoders. Using only access to the image encoder in the proposed attack, the generated adversarial examples exhibit transferability across diverse LVLMs utilizing the same image encoder and generality across different tasks. Extensive experiments validate the superior attack performance of the VT-Attack over baseline methods, demonstrating its effectiveness in attacking LVLMs with image encoders, which in turn can provide guidance on the robustness of LVLMs, particularly in terms of the stability of the visual feature space.

[Arxiv](https://arxiv.org/abs/2410.06699)