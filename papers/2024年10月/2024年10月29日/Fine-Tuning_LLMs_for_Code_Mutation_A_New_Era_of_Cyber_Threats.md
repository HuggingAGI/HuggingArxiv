# 微调 LLMs 以用于代码变异：网络威胁的崭新时代

发布时间：2024年10月29日

`LLM应用`

> Fine-Tuning LLMs for Code Mutation: A New Era of Cyber Threats

# 摘要

> 近期，大型语言模型（LLMs）的进步显著提升了其在自然语言处理和代码合成方面的能力，从而在不同领域实现了更复杂的应用。本文探究了 LLMs 在代码变异这一领域的应用，即不改变程序代码功能而改变其结构的过程。传统上，代码变异用于增强关键任务应用中的软件健壮性。此外，恶意软件开发者利用变异引擎来躲避恶意软件检测系统采用的基于签名的检测手段。现有的代码变异引擎，常被这类威胁行为者使用，通常仅导致恶意软件有限的变化，仍能通过静态代码分析识别。然而，基于 LLM 的代码合成器所展现的敏捷性可能极大地改变这种威胁态势，允许更复杂的代码变异，难以通过静态分析检测。通过微调及再训练能够增加预训练 LLM 合成的代码的变化，此过程即我们所说的代码变异训练。在本文中，我们为基于预训练 LLM 的代码合成器提出了全新的代码变异训练定义，并在一个轻量级预训练模型上进行了展示。我们的方法涉及在子程序层面重构（即变异）代码，便于管理变异，同时通过单元测试保持语义完整性。我们的实验结果表明，我们的方法在提高基于 LLM 的程序合成器的代码变异能力方面效果显著，能够生成多样且功能正确的代码解决方案，展现了其在改变代码变异格局及相关威胁方面的潜力。

> Recent advancements in Large Language Models (LLMs) have significantly improved their capabilities in natural language processing and code synthesis, enabling more complex applications across different fields. This paper explores the application of LLMs in the context of code mutation, a process where the structure of program code is altered without changing its functionality. Traditionally, code mutation has been employed to increase software robustness in mission-critical applications. Additionally, mutation engines have been exploited by malware developers to evade the signature-based detection methods employed by malware detection systems. Existing code mutation engines, often used by such threat actors, typically result in only limited variations in the malware, which can still be identified through static code analysis. However, the agility demonstrated by an LLM-based code synthesizer could significantly change this threat landscape by allowing for more complex code mutations that are not easily detected using static analysis. One can increase variations of codes synthesized by a pre-trained LLM through fine-tuning and retraining. This process is what we refer to as code mutation training. In this paper, we propose a novel definition of code mutation training tailored for pre-trained LLM-based code synthesizers and demonstrate this training on a lightweight pre-trained model. Our approach involves restructuring (i.e., mutating) code at the subroutine level, which allows for more manageable mutations while maintaining the semantic integrity verified through unit testing. Our experimental results illustrate the effectiveness of our approach in improving code mutation capabilities of LLM-based program synthesizers in producing varied and functionally correct code solutions, showcasing their potential to transform the landscape of code mutation and the threats associated with it.

[Arxiv](https://arxiv.org/abs/2410.22293)