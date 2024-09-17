# 通过20问游戏，辨别大型语言模型

发布时间：2024年09月16日

`LLM应用` `人工智能`

> The 20 questions game to distinguish large language models

# 摘要

> 我们借鉴“20问”游戏的思路，提出了一种方法，用于判断两个处于黑箱环境中的大型语言模型（LLM）是否相同。我们的目标是通过少量的（无害的）二进制问题，通常不超过20个，来实现这一判断。我们首先通过从已知基准数据集中随机选择问题，建立了一个基线，在20个问题内达到了近100%的准确率。随后，我们展示了该问题的最优界限，并引入了两种高效的提问策略，能够以一半的问题数量区分22个LLM。这些方法在隐秘性上具有显著优势，因此对怀疑模型泄露的审计员或版权所有者极具吸引力。

> In a parallel with the 20 questions game, we present a method to determine whether two large language models (LLMs), placed in a black-box context, are the same or not. The goal is to use a small set of (benign) binary questions, typically under 20. We formalize the problem and first establish a baseline using a random selection of questions from known benchmark datasets, achieving an accuracy of nearly 100% within 20 questions. After showing optimal bounds for this problem, we introduce two effective questioning heuristics able to discriminate 22 LLMs by using half as many questions for the same task. These methods offer significant advantages in terms of stealth and are thus of interest to auditors or copyright owners facing suspicions of model leaks.

[Arxiv](https://arxiv.org/abs/2409.10338)