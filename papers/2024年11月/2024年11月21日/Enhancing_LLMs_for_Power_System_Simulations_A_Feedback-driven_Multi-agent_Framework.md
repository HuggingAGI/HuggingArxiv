# 为电力系统模拟优化大型语言模型：一个反馈驱动的多智能体框架

发布时间：2024年11月21日

`LLM应用` `电力系统` `科学研究`

> Enhancing LLMs for Power System Simulations: A Feedback-driven Multi-agent Framework

# 摘要

> 实验技术与大型语言模型（LLMs）相融合，正在变革科学研究，让人工智能成为全能的研究助手，而非单纯的问题解决工具。然而在电力系统领域，管理模拟这一关键实验技术，对 LLMs 而言仍是难题，因其特定领域知识有限、推理能力受约、模拟参数处理不精准。为突破这些局限，我们提出了一个反馈驱动的多智能体框架，涵盖三个模块：增强的检索增强生成（RAG）模块、改良的推理模块以及带有错误反馈机制的动态环境作用模块。在 Daline 和 MATPOWER 的 69 项不同任务中得到验证，此框架成功率分别达 93.13%和 96.85%，远超最新的 LLMs（ChatGPT 4o 和 o1-Preview），后者在标准模拟任务上成功率为 27.77%，复杂任务上为 0%。另外，我们的框架还支持快速、高性价比的任务执行，每个模拟约 30 秒完成，平均令牌成本 0.014 美元。总之，这个适应性强的框架为开发面向人类研究人员的基于智能 LLM 的助手奠定了基础，助力电力系统研究及其他领域的进步。

> The integration of experimental technologies with large language models (LLMs) is transforming scientific research, positioning AI as a versatile research assistant rather than a mere problem-solving tool. In the field of power systems, however, managing simulations -- one of the essential experimental technologies -- remains a challenge for LLMs due to their limited domain-specific knowledge, restricted reasoning capabilities, and imprecise handling of simulation parameters. To address these limitations, we propose a feedback-driven, multi-agent framework that incorporates three proposed modules: an enhanced retrieval-augmented generation (RAG) module, an improved reasoning module, and a dynamic environmental acting module with an error-feedback mechanism. Validated on 69 diverse tasks from Daline and MATPOWER, this framework achieves success rates of 93.13% and 96.85%, respectively, significantly outperforming the latest LLMs (ChatGPT 4o and o1-preview), which achieved a 27.77% success rate on standard simulation tasks and 0% on complex tasks. Additionally, our framework also supports rapid, cost-effective task execution, completing each simulation in approximately 30 seconds at an average cost of 0.014 USD for tokens. Overall, this adaptable framework lays a foundation for developing intelligent LLM-based assistants for human researchers, facilitating power system research and beyond.

[Arxiv](https://arxiv.org/abs/2411.16707)