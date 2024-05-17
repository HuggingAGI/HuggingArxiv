# 多模态大型语言模型的视觉定位需要对抗性鲁棒性的保障。

发布时间：2024年05月16日

`Agent

这篇论文关注的是多模态大型语言模型（MLLMs）在视觉-语言任务中的对抗性鲁棒性问题，特别是指称表达理解（REC）任务中的对抗性攻击策略。虽然它涉及到了大型语言模型（LLM）的应用，但主要焦点是模型在面对对抗性攻击时的行为和鲁棒性，这更接近于Agent的范畴，即模型如何作为一个智能体应对外部威胁。因此，将其归类为Agent更为合适。` `视觉定位` `对抗性鲁棒性`

> Adversarial Robustness for Visual Grounding of Multimodal Large Language Models

# 摘要

> 多模态大型语言模型（MLLMs）在视觉-语言任务中表现出色，特别是在视觉定位方面。然而，其对抗性鲁棒性仍是一个未解之谜。我们以指称表达理解（REC）为例，探索了三种对抗性攻击策略：无目标攻击、排他性目标攻击和置换目标攻击。这些策略旨在误导模型生成错误的边界框或使所有输出指向同一目标。实验证明，这些攻击有效，为提升MLLMs在视觉定位任务中的鲁棒性提供了新思路和基准。

> Multi-modal Large Language Models (MLLMs) have recently achieved enhanced performance across various vision-language tasks including visual grounding capabilities. However, the adversarial robustness of visual grounding remains unexplored in MLLMs. To fill this gap, we use referring expression comprehension (REC) as an example task in visual grounding and propose three adversarial attack paradigms as follows. Firstly, untargeted adversarial attacks induce MLLMs to generate incorrect bounding boxes for each object. Besides, exclusive targeted adversarial attacks cause all generated outputs to the same target bounding box. In addition, permuted targeted adversarial attacks aim to permute all bounding boxes among different objects within a single image. Extensive experiments demonstrate that the proposed methods can successfully attack visual grounding capabilities of MLLMs. Our methods not only provide a new perspective for designing novel attacks but also serve as a strong baseline for improving the adversarial robustness for visual grounding of MLLMs.

![多模态大型语言模型的视觉定位需要对抗性鲁棒性的保障。](../../../paper_images/2405.09981/x1.png)

[Arxiv](https://arxiv.org/abs/2405.09981)