# HELPER-X：一款集成的可指导实体代理，搭载记忆增强型语言模型，旨在攻克四大交互式视觉-语言领域的挑战。

发布时间：2024年04月29日

`Agent` `人工智能` `任务规划`

> HELPER-X: A Unified Instructable Embodied Agent to Tackle Four Interactive Vision-Language Domains with Memory-Augmented Language Models

# 摘要

> 最新研究利用具备增强记忆功能的大型语言模型（LLMs）作为任务规划器，通过检索与输入指令紧密相关的语言程序实例，并将其作为上下文示例嵌入LLM的提示中，从而提升了LLM在推导正确行动和任务规划方面的性能。本技术报告进一步扩展了HELPER的功能，不仅扩充了其记忆库，加入了更多样的示例和提示，还整合了更多API以支持提问。这一扩展使得HELPER能够在多个领域内发挥作用，包括从对话中执行计划、遵循自然语言指令、主动提问以及基于常识的房间重组。我们在四个多样化的交互式视觉-语言体现代理基准测试中对代理进行了评估：ALFRED、TEACh、DialFRED和Tidy Task。HELPER-X在这些测试中展现了少量样本学习下的顶尖性能，且无需特定领域训练即可与经过领域训练的代理相媲美。

> Recent research on instructable agents has used memory-augmented Large Language Models (LLMs) as task planners, a technique that retrieves language-program examples relevant to the input instruction and uses them as in-context examples in the LLM prompt to improve the performance of the LLM in inferring the correct action and task plans. In this technical report, we extend the capabilities of HELPER, by expanding its memory with a wider array of examples and prompts, and by integrating additional APIs for asking questions. This simple expansion of HELPER into a shared memory enables the agent to work across the domains of executing plans from dialogue, natural language instruction following, active question asking, and commonsense room reorganization. We evaluate the agent on four diverse interactive visual-language embodied agent benchmarks: ALFRED, TEACh, DialFRED, and the Tidy Task. HELPER-X achieves few-shot, state-of-the-art performance across these benchmarks using a single agent, without requiring in-domain training, and remains competitive with agents that have undergone in-domain training.

[Arxiv](https://arxiv.org/abs/2404.19065)