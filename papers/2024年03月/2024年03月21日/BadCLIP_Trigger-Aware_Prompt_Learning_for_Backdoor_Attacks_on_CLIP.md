# BadCLIP：针对CLIP的后门攻击，利用触发器感知的提示学习策略

发布时间：2024年03月21日

`Agent

理由：这篇论文主要讨论了如何在CLIP模型中植入后门，通过特定的触发器影响模型的行为，使其在特定条件下错误地分类图像。这种对模型的操控和攻击行为更符合Agent的定义，即一个能够感知环境并采取行动以达到目标的系统。虽然涉及到了模型的应用（CLIP模型），但核心在于设计一种攻击手段，而不是探讨模型的应用场景或理论基础。因此，将其归类为Agent更为合适。` `网络安全` `人工智能安全`

> BadCLIP: Trigger-Aware Prompt Learning for Backdoor Attacks on CLIP

# 摘要

> CLIP，即对比视觉-语言预训练，已在图像识别任务中展现出巨大潜力。但近期发现，CLIP模型可能被植入针对特定下游任务的后门：当特定触发器出现时，模型虽能正确识别无害样本，却会错误地将目标指向特定类别。传统后门攻击需大量额外数据微调模型，不适用于数据稀缺场景。本研究受可学习提示启发，提出在提示学习阶段植入后门的新方法BadCLIP。该方法通过触发器同时操控图像和文本编码器，包括可学习图像触发器和触发感知文本生成器，实现了一种高效且泛化的攻击手段。实验证明，BadCLIP在保持高准确度的同时，攻击成功率超99%，并能有效泛化至新类别及跨数据集、跨领域场景。

> Contrastive Vision-Language Pre-training, known as CLIP, has shown promising effectiveness in addressing downstream image recognition tasks. However, recent works revealed that the CLIP model can be implanted with a downstream-oriented backdoor. On downstream tasks, one victim model performs well on clean samples but predicts a specific target class whenever a specific trigger is present. For injecting a backdoor, existing attacks depend on a large amount of additional data to maliciously fine-tune the entire pre-trained CLIP model, which makes them inapplicable to data-limited scenarios. In this work, motivated by the recent success of learnable prompts, we address this problem by injecting a backdoor into the CLIP model in the prompt learning stage. Our method named BadCLIP is built on a novel and effective mechanism in backdoor attacks on CLIP, i.e., influencing both the image and text encoders with the trigger. It consists of a learnable trigger applied to images and a trigger-aware context generator, such that the trigger can change text features via trigger-aware prompts, resulting in a powerful and generalizable attack. Extensive experiments conducted on 11 datasets verify that the clean accuracy of BadCLIP is similar to those of advanced prompt learning methods and the attack success rate is higher than 99% in most cases. BadCLIP is also generalizable to unseen classes, and shows a strong generalization capability under cross-dataset and cross-domain settings.

[Arxiv](https://arxiv.org/abs/2311.16194)