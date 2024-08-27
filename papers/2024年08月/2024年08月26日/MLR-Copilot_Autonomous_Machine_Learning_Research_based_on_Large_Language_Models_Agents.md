# MLR-Copilot：依托大型语言模型代理，实现自主机器学习研究

发布时间：2024年08月26日

`Agent` `机器学习`

> MLR-Copilot: Autonomous Machine Learning Research based on Large Language Models Agents

# 摘要

> 机器学习研究因其复杂性和专业性而充满挑战，我们为此设计了一个新框架——MLR-Copilot，利用LLM自动生成并实施研究想法，以提升研究效率。框架分三步：首先，IdeaAgent基于现有论文提出假设和计划；其次，ExperimentAgent将计划转化为可执行实验，借助原型代码和可选模型数据；最后，实验执行阶段通过人工反馈和迭代调试确保成果质量。实验证明，该框架能有效促进研究创新。

> Machine learning research, crucial for technological advancements and innovation, often faces significant challenges due to its inherent complexity, slow pace of experimentation, and the necessity for specialized expertise. Motivated by this, we present a new systematic framework, autonomous Machine Learning Research with large language models (MLR-Copilot), designed to enhance machine learning research productivity through the automatic generation and implementation of research ideas using Large Language Model (LLM) agents. The framework consists of three phases: research idea generation, experiment implementation, and implementation execution. First, existing research papers are used to generate hypotheses and experimental plans vis IdeaAgent powered by LLMs. Next, the implementation generation phase translates these plans into executables with ExperimentAgent. This phase leverages retrieved prototype code and optionally retrieves candidate models and data. Finally, the execution phase, also managed by ExperimentAgent, involves running experiments with mechanisms for human feedback and iterative debugging to enhance the likelihood of achieving executable research outcomes. We evaluate our framework on five machine learning research tasks and the experimental results show the framework's potential to facilitate the research progress and innovations.

[Arxiv](https://arxiv.org/abs/2408.14033)