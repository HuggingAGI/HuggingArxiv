# 跨任务防御：通过指令调优提升大型语言模型的内容安全性能

发布时间：2024年05月24日

`LLM应用

这篇论文主要关注大型语言模型（LLMs）在处理长文本时的安全性和实用性问题，并提出了一种新的方法来增强LLMs在面对恶意文档和良性NLP任务时的安全性。论文通过创建一个包含安全相关示例的数据集，并提出了针对指令调优的单任务与混合任务损失，来提升LLMs的安全管理能力。这些内容直接关联到LLMs的实际应用，特别是在安全性方面的应用，因此将其归类为LLM应用。` `网络安全`

> Cross-Task Defense: Instruction-Tuning LLMs for Content Safety

# 摘要

> 最新研究表明，大型语言模型（LLMs）在处理长文本如总结和翻译等NLP任务时，如何在安全与实用性之间取得平衡面临挑战。虽然已有措施防御恶意简短问题，但LLMs处理危险长内容（例如非法活动教学手册）的安全性仍存疑。我们的研究旨在为LLMs在面对恶意文档和良性NLP任务时构建坚固防线。我们创建了一个包含安全相关示例的数据集，并提出了针对指令调优的单任务与混合任务损失。实证结果显示，通过恰当的指令调优，LLMs能大幅提升其安全管理危险内容的能力。同时，强化易被滥用的任务防御，有效保护LLMs免受有害信息侵害。我们还发现，防御策略中实用性和安全性之间存在权衡，而采用我们方法的Llama2在此平衡上明显优于Llama1。

> Recent studies reveal that Large Language Models (LLMs) face challenges in balancing safety with utility, particularly when processing long texts for NLP tasks like summarization and translation. Despite defenses against malicious short questions, the ability of LLMs to safely handle dangerous long content, such as manuals teaching illicit activities, remains unclear. Our work aims to develop robust defenses for LLMs in processing malicious documents alongside benign NLP task queries. We introduce a defense dataset comprised of safety-related examples and propose single-task and mixed-task losses for instruction tuning. Our empirical results demonstrate that LLMs can significantly enhance their capacity to safely manage dangerous content with appropriate instruction tuning. Additionally, strengthening the defenses of tasks most susceptible to misuse is effective in protecting LLMs against processing harmful information. We also observe that trade-offs between utility and safety exist in defense strategies, where Llama2, utilizing our proposed approach, displays a significantly better balance compared to Llama1.

![跨任务防御：通过指令调优提升大型语言模型的内容安全性能](../../../paper_images/2405.15202/x1.png)

![跨任务防御：通过指令调优提升大型语言模型的内容安全性能](../../../paper_images/2405.15202/x2.png)

![跨任务防御：通过指令调优提升大型语言模型的内容安全性能](../../../paper_images/2405.15202/x3.png)

![跨任务防御：通过指令调优提升大型语言模型的内容安全性能](../../../paper_images/2405.15202/x4.png)

![跨任务防御：通过指令调优提升大型语言模型的内容安全性能](../../../paper_images/2405.15202/x5.png)

![跨任务防御：通过指令调优提升大型语言模型的内容安全性能](../../../paper_images/2405.15202/x6.png)

[Arxiv](https://arxiv.org/abs/2405.15202)