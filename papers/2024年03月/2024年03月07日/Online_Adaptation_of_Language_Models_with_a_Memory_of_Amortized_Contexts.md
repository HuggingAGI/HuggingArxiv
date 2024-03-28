# 通过运用对上下文进行平均化的记忆技术，在线优化语言模型以适应不同场景。

发布时间：2024年03月07日

`LLM应用`

> Online Adaptation of Language Models with a Memory of Amortized Contexts

# 摘要

> 面对信息洪流导致LLMs即便投入巨资也迅速过时的问题，以及实时保持模型与时俱进的需求，在真实场景运用LLMs时，线上学习成为必不可少的关键环节。然而，面对持续扩容的未知文档集合及现代LLMs庞大的参数范围，实现高效的适应性调整尤为关键。为此，我们创新提出了MAC（记忆 amortized 上下文）这一高效且实用的LLM在线适应框架，其具备强大的知识保留能力。我们设计了一种新颖的摊销特征抽取与记忆强化技术，能将新文档的信息浓缩并提炼成紧凑的“调制”形式，存储于一个内存库中。当解答问题时，模型会根据需要从该内存库中注意力引导地抽取相关信息。为了高效地学习富含信息的“调制”，我们采用基于摊销的元学习策略，以编码器的一次正向传播过程取代复杂的优化步骤。进而，我们依据问题内容学习如何挑选并融合多篇文档至单一“调制”之中，使得在测试阶段无需进行额外梯度更新，也能灵活适应冻结状态下的语言模型。实验结果显示，MAC在多个维度上展现出卓越性能，涵盖了在线适应效果、时间和内存效率等方面。相关代码已开放在GitHub平台，地址为：https://github.com/jihoontack/MAC。

> Due to the rapid generation and dissemination of information, large language models (LLMs) quickly run out of date despite enormous development costs. Due to this crucial need to keep models updated, online learning has emerged as a critical necessity when utilizing LLMs for real-world applications. However, given the ever-expanding corpus of unseen documents and the large parameter space of modern LLMs, efficient adaptation is essential. To address these challenges, we propose Memory of Amortized Contexts (MAC), an efficient and effective online adaptation framework for LLMs with strong knowledge retention. We propose an amortized feature extraction and memory-augmentation approach to compress and extract information from new documents into compact modulations stored in a memory bank. When answering questions, our model attends to and extracts relevant knowledge from this memory bank. To learn informative modulations in an efficient manner, we utilize amortization-based meta-learning, which substitutes the optimization process with a single forward pass of the encoder. Subsequently, we learn to choose from and aggregate selected documents into a single modulation by conditioning on the question, allowing us to adapt a frozen language model during test time without requiring further gradient updates. Our experiment demonstrates the superiority of MAC in multiple aspects, including online adaptation performance, time, and memory efficiency. Code is available at: https://github.com/jihoontack/MAC.

[Arxiv](https://arxiv.org/abs/2403.04317)