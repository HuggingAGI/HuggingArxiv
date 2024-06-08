# 工具规划器：利用工具聚类，为大型语言模型打造动态解决方案树规划

发布时间：2024年06月06日

`Agent

理由：这篇论文主要讨论了大型语言模型（LLMs）在工具学习领域的应用，特别是通过Tool-Planner框架来优化工具调用计划。这种方法涉及到LLMs作为智能代理（Agent）在多任务环境中执行任务的能力，包括工具的选择、调用和错误纠正。因此，这篇论文更符合Agent分类，因为它关注的是LLMs作为智能代理如何有效地使用工具来完成任务。` `工具学习` `人工智能`

> Tool-Planner: Dynamic Solution Tree Planning for Large Language Model with Tool Clustering

# 摘要

> 大型语言模型（LLMs）以其卓越的推理能力，成功解决了众多复杂问题。近期，这一能力被应用于工具学习的领域，通过展示工具使用示例及其功能，LLMs能够制定并执行工具调用计划。这种方法使LLMs能够处理原本无法独立完成的任务，从而在多任务环境中发挥更大潜力。然而，此方法也面临两大挑战：一是冗余的错误纠正导致计划不稳定和执行时间延长；二是在多个工具中设计正确计划。为此，我们提出了Tool-Planner框架，该框架根据功能相似的API将工具分组，并允许LLMs跨工具包进行规划。当出现工具错误时，语言模型可依据工具包重新选择和调整工具。实验结果显示，我们的方法在多个数据集上均表现出高通过率和胜率，并优化了GPT-4和Claude 3等模型中工具学习的规划策略，充分展示了我们方法的潜力。

> Large language models (LLMs) have demonstrated exceptional reasoning capabilities, enabling them to solve various complex problems. Recently, this ability has been applied to the paradigm of tool learning. Tool learning involves providing examples of tool usage and their corresponding functions, allowing LLMs to formulate plans and demonstrate the process of invoking and executing each tool. LLMs can address tasks that they cannot complete independently, thereby enhancing their potential across different tasks. However, this approach faces two key challenges. First, redundant error correction leads to unstable planning and long execution time. Additionally, designing a correct plan among multiple tools is also a challenge in tool learning. To address these issues, we propose Tool-Planner, a task-processing framework based on toolkits. Tool-Planner groups tools based on the API functions with the same function into a toolkit and allows LLMs to implement planning across the various toolkits. When a tool error occurs, the language model can reselect and adjust tools based on the toolkit. Experiments show that our approach demonstrates a high pass and win rate across different datasets and optimizes the planning scheme for tool learning in models such as GPT-4 and Claude 3, showcasing the potential of our method.

[Arxiv](https://arxiv.org/abs/2406.03807)