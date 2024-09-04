# 探索复杂过程工程示意图的人类级理解：一个结合教学与内省的多智能体框架，专为开放领域问答设计

发布时间：2024年08月24日

`RAG` `流程行业`

> Towards Human-Level Understanding of Complex Process Engineering Schematics: A Pedagogical, Introspective Multi-Agent Framework for Open-Domain Question Answering

# 摘要

> 在化工和流程行业，PFDs 和 P&IDs 是设计、施工和维护的关键。最新生成式AI技术，如 GPT4，虽在解读流程图方面有潜力，但专有模型带来隐私风险且计算复杂，难以在个人设备上定制。为此，我们设计了基于 RAG 框架的安全本地解决方案，强化数据隐私和成本效益。利用开源小规模模型和 ReAct 技术，我们的多代理系统整合多源信息，提供精准答案，并通过自我修正提升开放领域问答性能。实验证实了其有效性。

> In the chemical and process industries, Process Flow Diagrams (PFDs) and Piping and Instrumentation Diagrams (P&IDs) are critical for design, construction, and maintenance. Recent advancements in Generative AI, such as Large Multimodal Models (LMMs) like GPT4 (Omni), have shown promise in understanding and interpreting process diagrams for Visual Question Answering (VQA). However, proprietary models pose data privacy risks, and their computational complexity prevents knowledge editing for domain-specific customization on consumer hardware. To overcome these challenges, we propose a secure, on-premises enterprise solution using a hierarchical, multi-agent Retrieval Augmented Generation (RAG) framework for open-domain question answering (ODQA) tasks, offering enhanced data privacy, explainability, and cost-effectiveness. Our novel multi-agent framework employs introspective and specialized sub-agents using open-source, small-scale multimodal models with the ReAct (Reason+Act) prompting technique for PFD and P&ID analysis, integrating multiple information sources to provide accurate and contextually relevant answers. Our approach, supported by iterative self-correction, aims to deliver superior performance in ODQA tasks. We conducted rigorous experimental studies, and the empirical results validated the proposed approach effectiveness.

[Arxiv](https://arxiv.org/abs/2409.00082)