# 在 AI 代理时代，我们需重新审视过程挖掘的实践与应用。

发布时间：2024年08月14日

`Agent` `人工智能` `过程挖掘`

> Re-Thinking Process Mining in the AI-Based Agents Era

# 摘要

> 大型语言模型 (LLM) 在对话接口领域表现卓越，尤其在过程挖掘 (PM) 任务中展现出潜力。然而，面对需要高级推理的复杂场景，LLM 的表现仍有不足。文献中提出了两种利用 LLM 进行 PM 的方法：一是通过文本抽象提供见解，二是生成原始工件上可执行的代码。本文提出采用基于 AI 的代理工作流 (AgWf) 范式，以提升 LLM 在 PM 任务中的效能。该方法通过分解复杂任务为简单流程，并结合 LLM 的领域知识与确定性工具，增强了处理能力。我们探讨了 AgWf 的不同实现方式及其涉及的 AI 任务类型，并介绍了 CrewAI 框架及其在过程挖掘中的应用实例。

> Large Language Models (LLMs) have emerged as powerful conversational interfaces, and their application in process mining (PM) tasks has shown promising results. However, state-of-the-art LLMs struggle with complex scenarios that demand advanced reasoning capabilities. In the literature, two primary approaches have been proposed for implementing PM using LLMs: providing textual insights based on a textual abstraction of the process mining artifact, and generating code executable on the original artifact. This paper proposes utilizing the AI-Based Agents Workflow (AgWf) paradigm to enhance the effectiveness of PM on LLMs. This approach allows for: i) the decomposition of complex tasks into simpler workflows, and ii) the integration of deterministic tools with the domain knowledge of LLMs. We examine various implementations of AgWf and the types of AI-based tasks involved. Additionally, we discuss the CrewAI implementation framework and present examples related to process mining.

[Arxiv](https://arxiv.org/abs/2408.07720)