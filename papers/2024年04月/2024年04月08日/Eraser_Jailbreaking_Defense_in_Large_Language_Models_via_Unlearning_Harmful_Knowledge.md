# Eraser：通过摒弃不良信息，实现大型语言模型的防御破解

发布时间：2024年04月08日

`LLM理论` `信息安全` `内容过滤`

> Eraser: Jailbreaking Defense in Large Language Models via Unlearning Harmful Knowledge

# 摘要

> 越狱攻击能令大型语言模型（LLMs）突破防护机制，产生不良内容。现有防御手段未能根除模型内潜藏的有害信息，留下了越狱隐患。本文提出了一项创新的防御策略——“橡皮擦”，旨在抹除有害知识、保持通识教育、确保安全一致。该策略基于一个简单直觉：若LLM遗忘了回答有害问题所需的特定信息，它便无法再生成有害内容。橡皮擦的训练过程无需依赖模型原有的有害信息，通过学习与有害查询无关的通用答案，实现了自我净化，无需外部红队支援。实验证明，橡皮擦能有效降低各类攻击的成功率，同时保持模型的通用性能不受影响。

> Jailbreaking attacks can enable Large Language Models (LLMs) to bypass the safeguard and generate harmful content. Existing jailbreaking defense methods have failed to address the fundamental issue that harmful knowledge resides within the model, leading to potential jailbreak risks for LLMs. In this paper, we propose a novel defense method called Eraser, which mainly includes three goals: unlearning harmful knowledge, retaining general knowledge, and maintaining safety alignment. The intuition is that if an LLM forgets the specific knowledge required to answer a harmful question, it will no longer have the ability to answer harmful questions. The training of Erase does not actually require the model's own harmful knowledge, and it can benefit from unlearning general answers related to harmful queries, which means it does not need assistance from the red team. The experimental results show that Eraser can significantly reduce the jailbreaking success rate for various attacks without compromising the general capabilities of the model.

![Eraser：通过摒弃不良信息，实现大型语言模型的防御破解](../../../paper_images/2404.05880/Motivation.jpg)

![Eraser：通过摒弃不良信息，实现大型语言模型的防御破解](../../../paper_images/2404.05880/x1.png)

![Eraser：通过摒弃不良信息，实现大型语言模型的防御破解](../../../paper_images/2404.05880/combine_acc_asr2.png)

![Eraser：通过摒弃不良信息，实现大型语言模型的防御破解](../../../paper_images/2404.05880/x2.png)

![Eraser：通过摒弃不良信息，实现大型语言模型的防御破解](../../../paper_images/2404.05880/x3.png)

![Eraser：通过摒弃不良信息，实现大型语言模型的防御破解](../../../paper_images/2404.05880/x4.png)

![Eraser：通过摒弃不良信息，实现大型语言模型的防御破解](../../../paper_images/2404.05880/x5.png)

![Eraser：通过摒弃不良信息，实现大型语言模型的防御破解](../../../paper_images/2404.05880/x6.png)

![Eraser：通过摒弃不良信息，实现大型语言模型的防御破解](../../../paper_images/2404.05880/x7.png)

![Eraser：通过摒弃不良信息，实现大型语言模型的防御破解](../../../paper_images/2404.05880/x8.png)

[Arxiv](https://arxiv.org/abs/2404.05880)