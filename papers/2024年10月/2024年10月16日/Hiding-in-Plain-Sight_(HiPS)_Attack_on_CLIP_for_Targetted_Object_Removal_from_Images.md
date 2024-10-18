# HiPS 攻击利用 CLIP 的漏洞，巧妙地将目标物体从图像中“隐身”。

发布时间：2024年10月16日

`LLM应用` `计算机视觉`

> Hiding-in-Plain-Sight (HiPS) Attack on CLIP for Targetted Object Removal from Images

# 摘要

> 机器学习模型易受对抗攻击，传统攻击多针对单一模态。随着 CLIP 等大型多模态模型的兴起，新的漏洞浮现。以往的多模态攻击试图完全操控模型输出，但在现实场景中，攻击者可能仅需微调输出，使其不易被察觉。我们提出了 Hiding-in-Plain-Sight (HiPS) 攻击，通过巧妙隐藏目标对象，微调模型预测，仿佛目标对象从未存在。我们设计了 HiPS-cls 和 HiPS-cap 两种变体，并验证了它们在下游图像字幕模型（如 CLIP-Cap）中移除目标对象的有效性。

> Machine learning models are known to be vulnerable to adversarial attacks, but traditional attacks have mostly focused on single-modalities. With the rise of large multi-modal models (LMMs) like CLIP, which combine vision and language capabilities, new vulnerabilities have emerged. However, prior work in multimodal targeted attacks aim to completely change the model's output to what the adversary wants. In many realistic scenarios, an adversary might seek to make only subtle modifications to the output, so that the changes go unnoticed by downstream models or even by humans. We introduce Hiding-in-Plain-Sight (HiPS) attacks, a novel class of adversarial attacks that subtly modifies model predictions by selectively concealing target object(s), as if the target object was absent from the scene. We propose two HiPS attack variants, HiPS-cls and HiPS-cap, and demonstrate their effectiveness in transferring to downstream image captioning models, such as CLIP-Cap, for targeted object removal from image captions.

[Arxiv](https://arxiv.org/abs/2410.13010)