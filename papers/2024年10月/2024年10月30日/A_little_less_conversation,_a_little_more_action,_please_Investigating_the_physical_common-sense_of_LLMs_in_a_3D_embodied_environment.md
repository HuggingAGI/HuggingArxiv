# 拜托，少些对话，多些行动：探究 3D 具身环境中 LLMs 的物理常识

发布时间：2024年10月30日

`LLM应用` `智能体`

> A little less conversation, a little more action, please: Investigating the physical common-sense of LLMs in a 3D embodied environment

# 摘要

> 作为通用工具，大型语言模型（LLMs）常常得对日常物理环境进行推理。在问答方面，要给出恰当回应，理解物理对象的相互作用是必要的。而且，LLMs 越来越多地充当智能体系统中的推理引擎，负责设计和控制动作序列。绝大多数研究都借助静态基准来处理此问题，这些基准由关于物理世界的基于文本或图像的问题构成。然而，这些基准无法涵盖现实物理过程的复杂与微妙之处。在此，我们倡导第二种相对未被探索的办法：让 LLMs 掌控 3D 环境中的智能体，从而实现“具身化”。我们对 LLMs 中的物理常识推理进行了首次具身且具认知意义的评估。我们的框架能够将 LLMs 与其他具身智能体（如基于深度强化学习的智能体）以及人类和非人类动物直接比较。我们利用动物 - AI（AAI）环境——一个模拟的 3D 虚拟实验室，来研究 LLMs 中的物理常识推理。为此，我们使用 AAI 测试平台，这是一套复刻非人类动物实验室研究的实验，用于研究物理推理能力，包括距离估算、跟踪视线外物体和工具使用。我们证明，无需微调的最先进多模态模型能够完成此类任务，从而能与 2019 年动物 - AI 奥运会的参赛者以及人类儿童进行有意义的对比。我们的结果显示，在这些任务上，LLMs 目前的表现逊于人类儿童。我们认为，这种方法能通过直接从认知科学中提取的生态有效实验来研究物理推理，提升 LLMs 的可预测性和可靠性。

> As general-purpose tools, Large Language Models (LLMs) must often reason about everyday physical environments. In a question-and-answer capacity, understanding the interactions of physical objects may be necessary to give appropriate responses. Moreover, LLMs are increasingly used as reasoning engines in agentic systems, designing and controlling their action sequences. The vast majority of research has tackled this issue using static benchmarks, comprised of text or image-based questions about the physical world. However, these benchmarks do not capture the complexity and nuance of real-life physical processes. Here we advocate for a second, relatively unexplored, approach: 'embodying' the LLMs by granting them control of an agent within a 3D environment. We present the first embodied and cognitively meaningful evaluation of physical common-sense reasoning in LLMs. Our framework allows direct comparison of LLMs with other embodied agents, such as those based on Deep Reinforcement Learning, and human and non-human animals. We employ the Animal-AI (AAI) environment, a simulated 3D virtual laboratory, to study physical common-sense reasoning in LLMs. For this, we use the AAI Testbed, a suite of experiments that replicate laboratory studies with non-human animals, to study physical reasoning capabilities including distance estimation, tracking out-of-sight objects, and tool use. We demonstrate that state-of-the-art multi-modal models with no finetuning can complete this style of task, allowing meaningful comparison to the entrants of the 2019 Animal-AI Olympics competition and to human children. Our results show that LLMs are currently outperformed by human children on these tasks. We argue that this approach allows the study of physical reasoning using ecologically valid experiments drawn directly from cognitive science, improving the predictability and reliability of LLMs.

[Arxiv](https://arxiv.org/abs/2410.23242)