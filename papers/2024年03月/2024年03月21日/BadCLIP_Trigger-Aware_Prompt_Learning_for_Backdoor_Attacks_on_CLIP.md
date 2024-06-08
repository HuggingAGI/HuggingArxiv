# BadCLIP：针对CLIP的后门攻击中的触发器感知提示学习方法

发布时间：2024年03月21日

`Agent

解释：这篇论文讨论的是一种名为BadCLIP的攻击方法，该方法通过在CLIP模型的提示学习阶段植入后门，以实现对特定下游任务的操控。这种攻击方法涉及到对模型的主动操控，类似于一个智能代理（Agent）的行为，因此将其归类为Agent。虽然这种方法涉及到大型语言模型（LLM）的应用，但其核心在于攻击策略的设计和实施，而不是LLM的理论研究或应用开发，因此不适合归类为LLM应用或LLM理论。同时，该论文并不直接涉及检索增强生成（RAG）技术，因此也不归类为RAG。` `人工智能`

> BadCLIP: Trigger-Aware Prompt Learning for Backdoor Attacks on CLIP

# 摘要

> CLIP，即对比视觉-语言预训练，在图像识别任务中表现出色。但近期发现，CLIP模型可能被植入针对特定下游任务的后门。具体来说，当特定触发器出现时，受害模型会将干净样本错误分类至预设的目标类别。传统后门攻击需要大量额外数据来微调模型，这在数据稀缺场景下不切实际。本研究受可学习提示启发，提出在提示学习阶段植入后门，命名为BadCLIP。该方法通过触发器同时操纵图像和文本编码器，包括一个可学习的图像触发器和一个触发器感知的文本上下文生成器，有效改变文本特征，实现高效且泛化的攻击。实验在11个数据集上证明，BadCLIP在保持高准确度的同时，攻击成功率超过99%，并展现出跨数据集和跨领域的强大泛化能力。

> Contrastive Vision-Language Pre-training, known as CLIP, has shown promising effectiveness in addressing downstream image recognition tasks. However, recent works revealed that the CLIP model can be implanted with a downstream-oriented backdoor. On downstream tasks, one victim model performs well on clean samples but predicts a specific target class whenever a specific trigger is present. For injecting a backdoor, existing attacks depend on a large amount of additional data to maliciously fine-tune the entire pre-trained CLIP model, which makes them inapplicable to data-limited scenarios. In this work, motivated by the recent success of learnable prompts, we address this problem by injecting a backdoor into the CLIP model in the prompt learning stage. Our method named BadCLIP is built on a novel and effective mechanism in backdoor attacks on CLIP, i.e., influencing both the image and text encoders with the trigger. It consists of a learnable trigger applied to images and a trigger-aware context generator, such that the trigger can change text features via trigger-aware prompts, resulting in a powerful and generalizable attack. Extensive experiments conducted on 11 datasets verify that the clean accuracy of BadCLIP is similar to those of advanced prompt learning methods and the attack success rate is higher than 99% in most cases. BadCLIP is also generalizable to unseen classes, and shows a strong generalization capability under cross-dataset and cross-domain settings.

[Arxiv](https://arxiv.org/abs/2311.16194)