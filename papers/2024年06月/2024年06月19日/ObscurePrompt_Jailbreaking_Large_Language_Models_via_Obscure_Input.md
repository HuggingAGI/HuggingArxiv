# 模糊提示：利用模糊输入解锁大型语言模型的潜能

发布时间：2024年06月19日

`Agent

这篇论文主要探讨了如何通过一种名为ObscurePrompt的新方法来“越狱”大型语言模型（LLMs），即通过模糊文本影响LLM的伦理判断，从而绕过模型的安全限制。这种方法涉及构建一个基础提示，并通过LLMs的迭代变换来模糊这一提示，以增强攻击的稳健性。研究的重点在于开发一种攻击策略，以测试和挑战LLMs的安全性和可信度。因此，这篇论文更符合Agent分类，因为它关注的是如何作为外部代理（Agent）来影响和测试LLMs的行为和安全性。` `人工智能`

> ObscurePrompt: Jailbreaking Large Language Models via Obscure Input

# 摘要

> 大型语言模型（LLMs）因其卓越的自然语言处理能力而备受瞩目，但对其可信度的疑虑依旧存在，尤其是在应对“越狱”攻击方面。以往研究多依赖于白盒模型或固定提示模板，这些方法既不切实际也缺乏广泛适用性。本文提出了一种名为ObscurePrompt的新方法，旨在越狱LLMs，灵感源自分布外数据中对齐的脆弱性。我们首先定义了越狱过程中的决策边界，进而探究模糊文本如何影响LLM的伦理判断。该方法从构建一个融合了多种越狱技巧的基础提示开始，再通过LLMs的迭代变换来模糊这一提示，以增强攻击的稳健性。实验结果显示，我们的方法在攻击效果上显著超越了以往技术，并能有效抵御两种主流防御机制。我们期望这项研究能为未来提升LLM对齐性的研究提供新的视角。

> Recently, Large Language Models (LLMs) have garnered significant attention for their exceptional natural language processing capabilities. However, concerns about their trustworthiness remain unresolved, particularly in addressing "jailbreaking" attacks on aligned LLMs. Previous research predominantly relies on scenarios with white-box LLMs or specific and fixed prompt templates, which are often impractical and lack broad applicability. In this paper, we introduce a straightforward and novel method, named ObscurePrompt, for jailbreaking LLMs, inspired by the observed fragile alignments in Out-of-Distribution (OOD) data. Specifically, we first formulate the decision boundary in the jailbreaking process and then explore how obscure text affects LLM's ethical decision boundary. ObscurePrompt starts with constructing a base prompt that integrates well-known jailbreaking techniques. Powerful LLMs are then utilized to obscure the original prompt through iterative transformations, aiming to bolster the attack's robustness. Comprehensive experiments show that our approach substantially improves upon previous methods in terms of attack effectiveness, maintaining efficacy against two prevalent defense mechanisms. We believe that our work can offer fresh insights for future research on enhancing LLM alignment.

![模糊提示：利用模糊输入解锁大型语言模型的潜能](../../../paper_images/2406.13662/x1.png)

![模糊提示：利用模糊输入解锁大型语言模型的潜能](../../../paper_images/2406.13662/x2.png)

![模糊提示：利用模糊输入解锁大型语言模型的潜能](../../../paper_images/2406.13662/x3.png)

![模糊提示：利用模糊输入解锁大型语言模型的潜能](../../../paper_images/2406.13662/x4.png)

![模糊提示：利用模糊输入解锁大型语言模型的潜能](../../../paper_images/2406.13662/x5.png)

![模糊提示：利用模糊输入解锁大型语言模型的潜能](../../../paper_images/2406.13662/x6.png)

[Arxiv](https://arxiv.org/abs/2406.13662)