# 整合大型语言模型至生产系统，提升任务自动化与灵活性

发布时间：2024年07月11日

`Agent` `制造业` `自动化`

> Incorporating Large Language Models into Production Systems for Enhanced Task Automation and Flexibility

# 摘要

> 本文提出了一种创新方法，将大型语言模型（LLM）代理融入自动化生产系统，以提升任务自动化与灵活性。我们采用基于自动化金字塔的层级框架来组织生产操作，将原子操作功能建模为微服务，并通过专用数字孪生系统进行接口调用执行，从而构建了一个可扩展且灵活的生产流程编排基础。在该数字孪生系统中，硬件特定的低级数据经过语义增强，变得对LLM可解释，用于生产规划与控制。LLM代理系统地解读这些生产特定数据与知识，并在接收到用户请求或触发事件后，生成过程计划，随后分解为一系列原子操作，作为微服务在实际自动化系统中执行。我们在实验室的自动化模块化生产设施上实施了这一方法，通过具体案例展示了LLM在生产规划与控制中的应用，实现了更高级别的任务自动化与灵活性。同时，我们也指出了在自主系统中充分发挥LLM潜力的局限与前景。相关研究演示可访问：https://github.com/YuchenXia/GPT4IndustrialAutomation。

> This paper introduces a novel approach to integrating large language model (LLM) agents into automated production systems, aimed at enhancing task automation and flexibility. We organize production operations within a hierarchical framework based on the automation pyramid. Atomic operation functionalities are modeled as microservices, which are executed through interface invocation within a dedicated digital twin system. This allows for a scalable and flexible foundation for orchestrating production processes. In this digital twin system, low-level, hardware-specific data is semantically enriched and made interpretable for LLMs for production planning and control tasks. Large language model agents are systematically prompted to interpret these production-specific data and knowledge. Upon receiving a user request or identifying a triggering event, the LLM agents generate a process plan. This plan is then decomposed into a series of atomic operations, executed as microservices within the real-world automation system. We implement this overall approach on an automated modular production facility at our laboratory, demonstrating how the LLMs can handle production planning and control tasks through a concrete case study. This results in an intuitive production facility with higher levels of task automation and flexibility. Finally, we reveal the several limitations in realizing the full potential of the large language models in autonomous systems and point out promising benefits. Demos of this series of ongoing research series can be accessed at: https://github.com/YuchenXia/GPT4IndustrialAutomation

[Arxiv](https://arxiv.org/abs/2407.08550)