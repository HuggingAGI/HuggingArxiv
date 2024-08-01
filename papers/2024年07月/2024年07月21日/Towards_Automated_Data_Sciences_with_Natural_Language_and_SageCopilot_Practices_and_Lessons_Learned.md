# 探索自然语言与 SageCopilot 在自动化数据科学领域的实践与心得

发布时间：2024年07月21日

`LLM应用` `数据科学` `自动化`

> Towards Automated Data Sciences with Natural Language and SageCopilot: Practices and Lessons Learned

# 摘要

> NL2SQL领域虽在将自然语言转换为SQL脚本方面取得显著进展，但在整个数据科学流程中实现自动化仍具挑战。为此，我们推出了SageCopilot系统，该系统通过整合LLMs、AutoAgents和LUIs，实现了数据科学流程的自动化。SageCopilot采用双阶段设计：在线阶段通过ICL将用户输入转化为可执行脚本并进行结果可视化，离线阶段则为ICL准备演示。通过应用思维链和提示调优等策略，SageCopilot性能得到显著提升。实证测试表明，该系统在脚本生成与执行及结果可视化方面表现卓越，且基于真实数据集。深入的消融研究进一步揭示了各组件与策略对数据科学流程正确性的具体贡献。

> While the field of NL2SQL has made significant advancements in translating natural language instructions into executable SQL scripts for data querying and processing, achieving full automation within the broader data science pipeline - encompassing data querying, analysis, visualization, and reporting - remains a complex challenge. This study introduces SageCopilot, an advanced, industry-grade system system that automates the data science pipeline by integrating Large Language Models (LLMs), Autonomous Agents (AutoAgents), and Language User Interfaces (LUIs). Specifically, SageCopilot incorporates a two-phase design: an online component refining users' inputs into executable scripts through In-Context Learning (ICL) and running the scripts for results reporting & visualization, and an offline preparing demonstrations requested by ICL in the online phase. A list of trending strategies such as Chain-of-Thought and prompt-tuning have been used to augment SageCopilot for enhanced performance. Through rigorous testing and comparative analysis against prompt-based solutions, SageCopilot has been empirically validated to achieve superior end-to-end performance in generating or executing scripts and offering results with visualization, backed by real-world datasets. Our in-depth ablation studies highlight the individual contributions of various components and strategies used by SageCopilot to the end-to-end correctness for data sciences.

[Arxiv](https://arxiv.org/abs/2407.21040)