# BadCLIP：针对CLIP的后门攻击中的触发器感知提示学习方法

发布时间：2024年03月21日

`Agent

解释：这篇论文讨论的是一种针对CLIP模型的后门攻击方法，即BadCLIP。这种攻击方法通过在提示学习阶段植入后门，使得模型在特定触发器出现时产生错误的分类结果。这种类型的研究通常被归类为“Agent”，因为它涉及设计一种能够影响或操纵模型行为的智能实体（在这个案例中是后门攻击）。这与“RAG”（检索增强生成）、“LLM应用”（大型语言模型的应用）或“LLM理论”（大型语言模型的理论研究）不同，因为它更侧重于模型的安全性和对抗性攻击，而不是模型的应用或理论基础。` `网络安全` `人工智能`

> BadCLIP: Trigger-Aware Prompt Learning for Backdoor Attacks on CLIP

# 摘要

> CLIP，即对比视觉-语言预训练，在图像识别任务中表现出色。但最新研究发现，CLIP模型可能被植入针对特定下游任务的后门：在无触发器时表现正常，一旦触发器出现，便错误分类。传统后门攻击需大量数据微调模型，不适用于数据稀缺场景。本研究受可学习提示启发，提出在提示学习阶段植入后门的新方法BadCLIP。该方法通过触发器同时操控图像和文本编码器，包括图像上的可学习触发器和触发器感知的文本生成器，实现高效攻击。实验证明，BadCLIP在保持高准确度的同时，攻击成功率超99%，并展现出跨数据集和跨领域的强大泛化能力。

> Contrastive Vision-Language Pre-training, known as CLIP, has shown promising effectiveness in addressing downstream image recognition tasks. However, recent works revealed that the CLIP model can be implanted with a downstream-oriented backdoor. On downstream tasks, one victim model performs well on clean samples but predicts a specific target class whenever a specific trigger is present. For injecting a backdoor, existing attacks depend on a large amount of additional data to maliciously fine-tune the entire pre-trained CLIP model, which makes them inapplicable to data-limited scenarios. In this work, motivated by the recent success of learnable prompts, we address this problem by injecting a backdoor into the CLIP model in the prompt learning stage. Our method named BadCLIP is built on a novel and effective mechanism in backdoor attacks on CLIP, i.e., influencing both the image and text encoders with the trigger. It consists of a learnable trigger applied to images and a trigger-aware context generator, such that the trigger can change text features via trigger-aware prompts, resulting in a powerful and generalizable attack. Extensive experiments conducted on 11 datasets verify that the clean accuracy of BadCLIP is similar to those of advanced prompt learning methods and the attack success rate is higher than 99% in most cases. BadCLIP is also generalizable to unseen classes, and shows a strong generalization capability under cross-dataset and cross-domain settings.

[Arxiv](https://arxiv.org/abs/2311.16194)