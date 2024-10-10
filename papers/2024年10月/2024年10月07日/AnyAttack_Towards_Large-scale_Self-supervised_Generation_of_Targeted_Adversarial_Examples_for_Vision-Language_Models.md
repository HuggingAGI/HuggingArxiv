# AnyAttack：为视觉-语言模型大规模自监督生成目标对抗样本

发布时间：2024年10月07日

`LLM应用` `计算机视觉` `网络安全`

> AnyAttack: Towards Large-scale Self-supervised Generation of Targeted Adversarial Examples for Vision-Language Models

# 摘要

> 视觉-语言模型（VLMs）因其多模态能力，在现实应用中展现出巨大潜力。然而，最新研究发现，VLMs 对基于图像的对抗攻击尤为脆弱，尤其是那些诱导模型生成有害内容的目标对抗图像。现有攻击方法依赖预定义标签，限制了其在大规模评估中的应用。为此，我们提出 AnyAttack，一个无需标签监督的自监督框架，可生成针对任何图像的目标对抗攻击。通过在 LAION-400M 数据集上使用对比损失训练生成器，我们的方法在多种 VLMs 中展现出强大的可迁移性。实验表明，AnyAttack 在多个主流开源 VLMs 和商业模型上均有效，揭示了 VLMs 面临的前所未有的风险，呼吁采取有效对策。

> Due to their multimodal capabilities, Vision-Language Models (VLMs) have found numerous impactful applications in real-world scenarios. However, recent studies have revealed that VLMs are vulnerable to image-based adversarial attacks, particularly targeted adversarial images that manipulate the model to generate harmful content specified by the adversary. Current attack methods rely on predefined target labels to create targeted adversarial attacks, which limits their scalability and applicability for large-scale robustness evaluations. In this paper, we propose AnyAttack, a self-supervised framework that generates targeted adversarial images for VLMs without label supervision, allowing any image to serve as a target for the attack. To address the limitation of existing methods that require label supervision, we introduce a contrastive loss that trains a generator on a large-scale unlabeled image dataset, LAION-400M dataset, for generating targeted adversarial noise. This large-scale pre-training endows our method with powerful transferability across a wide range of VLMs. Extensive experiments on five mainstream open-source VLMs (CLIP, BLIP, BLIP2, InstructBLIP, and MiniGPT-4) across three multimodal tasks (image-text retrieval, multimodal classification, and image captioning) demonstrate the effectiveness of our attack. Additionally, we successfully transfer AnyAttack to multiple commercial VLMs, including Google's Gemini, Claude's Sonnet, and Microsoft's Copilot. These results reveal an unprecedented risk to VLMs, highlighting the need for effective countermeasures.

[Arxiv](https://arxiv.org/abs/2410.05346)