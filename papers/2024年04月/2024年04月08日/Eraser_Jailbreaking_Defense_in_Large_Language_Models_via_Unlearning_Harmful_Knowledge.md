# Eraser：通过摒弃有害知识，打破大型语言模型的束缚

发布时间：2024年04月08日

`LLM理论` `信息安全` `内容过滤`

> Eraser: Jailbreaking Defense in Large Language Models via Unlearning Harmful Knowledge

# 摘要

> 越狱攻击能助长大型语言模型（LLMs）绕开防护机制，制造恶劣内容。传统的越狱防范策略未能触及问题核心——模型内潜藏的有害信息，从而留下安全隐患。本文提出了一种创新的防御机制，名为“橡皮擦”，旨在抹除有害知识、保留基础常识，并确保安全性。简而言之，LLM若遗忘了回答有害问题的关键信息，便无法再产出有害内容。有趣的是，“橡皮擦”训练过程中，并不需要利用模型原有的有害信息，它通过学习如何回避与有害查询相关的通用回答来提升效果，实现自我净化，无需外部红队的支援。实验数据显示，“橡皮擦”能有效降低各类攻击的成功率，同时保持模型的通用性能不受影响。

> Jailbreaking attacks can enable Large Language Models (LLMs) to bypass the safeguard and generate harmful content. Existing jailbreaking defense methods have failed to address the fundamental issue that harmful knowledge resides within the model, leading to potential jailbreak risks for LLMs. In this paper, we propose a novel defense method called Eraser, which mainly includes three goals: unlearning harmful knowledge, retaining general knowledge, and maintaining safety alignment. The intuition is that if an LLM forgets the specific knowledge required to answer a harmful question, it will no longer have the ability to answer harmful questions. The training of Erase does not actually require the model's own harmful knowledge, and it can benefit from unlearning general answers related to harmful queries, which means it does not need assistance from the red team. The experimental results show that Eraser can significantly reduce the jailbreaking success rate for various attacks without compromising the general capabilities of the model.

![Eraser：通过摒弃有害知识，打破大型语言模型的束缚](../../../paper_images/2404.05880/Motivation.jpg)

![Eraser：通过摒弃有害知识，打破大型语言模型的束缚](../../../paper_images/2404.05880/x1.png)

![Eraser：通过摒弃有害知识，打破大型语言模型的束缚](../../../paper_images/2404.05880/combine_acc_asr2.png)

![Eraser：通过摒弃有害知识，打破大型语言模型的束缚](../../../paper_images/2404.05880/x2.png)

![Eraser：通过摒弃有害知识，打破大型语言模型的束缚](../../../paper_images/2404.05880/x3.png)

![Eraser：通过摒弃有害知识，打破大型语言模型的束缚](../../../paper_images/2404.05880/x4.png)

![Eraser：通过摒弃有害知识，打破大型语言模型的束缚](../../../paper_images/2404.05880/x5.png)

![Eraser：通过摒弃有害知识，打破大型语言模型的束缚](../../../paper_images/2404.05880/x6.png)

![Eraser：通过摒弃有害知识，打破大型语言模型的束缚](../../../paper_images/2404.05880/x7.png)

![Eraser：通过摒弃有害知识，打破大型语言模型的束缚](../../../paper_images/2404.05880/x8.png)

[Arxiv](https://arxiv.org/abs/2404.05880)