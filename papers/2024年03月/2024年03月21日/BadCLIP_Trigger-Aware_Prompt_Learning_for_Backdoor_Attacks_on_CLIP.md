# BadCLIP：针对CLIP的后门攻击中的触发器感知提示学习方法

发布时间：2024年03月21日

`Agent

解释：这篇论文主要讨论了如何在CLIP模型中植入后门，这是一种针对特定下游任务的攻击策略。通过在提示学习阶段植入后门，研究者设计了一种名为BadCLIP的方法，该方法能够通过特定的触发器操控图像和文本编码器，从而改变文本特征，实现对模型的攻击。这种研究更偏向于设计一种能够执行特定任务（即植入后门并操控模型输出）的Agent，而不是关于LLM的理论研究或应用开发。因此，将其归类为Agent。` `网络安全` `人工智能`

> BadCLIP: Trigger-Aware Prompt Learning for Backdoor Attacks on CLIP

# 摘要

> CLIP，即对比视觉-语言预训练，已在图像识别的下游任务中展现出巨大潜力。但近期发现，CLIP模型可能被植入针对特定下游任务的后门：当特定触发器出现时，模型虽能正确识别无害样本，却会错误地预测特定类别。传统后门攻击需大量额外数据微调模型，不适用于数据稀缺场景。本研究受可学习提示启发，提出在提示学习阶段植入后门的新方法BadCLIP。该方法通过触发器同时操控图像和文本编码器，包括可学习触发器和触发器感知的上下文生成器，有效改变文本特征，实现高效且泛化的攻击。实验证明，BadCLIP在11个数据集上的表现与顶尖提示学习方法相当，攻击成功率高达99%，并展现出跨数据集和跨领域的强大泛化能力。

> Contrastive Vision-Language Pre-training, known as CLIP, has shown promising effectiveness in addressing downstream image recognition tasks. However, recent works revealed that the CLIP model can be implanted with a downstream-oriented backdoor. On downstream tasks, one victim model performs well on clean samples but predicts a specific target class whenever a specific trigger is present. For injecting a backdoor, existing attacks depend on a large amount of additional data to maliciously fine-tune the entire pre-trained CLIP model, which makes them inapplicable to data-limited scenarios. In this work, motivated by the recent success of learnable prompts, we address this problem by injecting a backdoor into the CLIP model in the prompt learning stage. Our method named BadCLIP is built on a novel and effective mechanism in backdoor attacks on CLIP, i.e., influencing both the image and text encoders with the trigger. It consists of a learnable trigger applied to images and a trigger-aware context generator, such that the trigger can change text features via trigger-aware prompts, resulting in a powerful and generalizable attack. Extensive experiments conducted on 11 datasets verify that the clean accuracy of BadCLIP is similar to those of advanced prompt learning methods and the attack success rate is higher than 99% in most cases. BadCLIP is also generalizable to unseen classes, and shows a strong generalization capability under cross-dataset and cross-domain settings.

[Arxiv](https://arxiv.org/abs/2311.16194)