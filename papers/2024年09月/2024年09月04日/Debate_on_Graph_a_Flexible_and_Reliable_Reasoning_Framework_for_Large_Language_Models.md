# 辩论图：为大型语言模型提供灵活且可靠的推理框架

发布时间：2024年09月04日

`LLM应用` `知识图谱` `问答系统`

> Debate on Graph: a Flexible and Reliable Reasoning Framework for Large Language Models

# 摘要

> 大型语言模型（LLM）在实际应用中因缺乏相关知识可能产生幻觉。而知识图谱则存储了丰富的多关系结构和符号事实。因此，将LLM与知识图谱结合的研究备受关注，其中知识图谱问答（KGQA）是关键的集成测试。然而，现有方法面临两大难题：过长推理路径分散答案生成注意力，以及假阳性关系阻碍路径优化。为此，我们提出迭代交互式KGQA框架，利用LLM的交互学习能力进行图上推理与辩论（DoG）。DoG通过子图聚焦机制，在每次推理后尝试生成答案，减轻长路径影响；同时，多角色辩论团队逐步简化问题，减少假阳性关系干扰。实验证明，DoG在多个数据集上表现优异，尤其在WebQuestions和GrailQA上，准确率分别比ToG高出23.7%和9.1%。此外，DoG与多种LLM的集成实验显示其灵活性。代码已公开，详见\url{https://github.com/reml-group/DoG}。

> Large Language Models (LLMs) may suffer from hallucinations in real-world applications due to the lack of relevant knowledge. In contrast, knowledge graphs encompass extensive, multi-relational structures that store a vast array of symbolic facts. Consequently, integrating LLMs with knowledge graphs has been extensively explored, with Knowledge Graph Question Answering (KGQA) serving as a critical touchstone for the integration. This task requires LLMs to answer natural language questions by retrieving relevant triples from knowledge graphs. However, existing methods face two significant challenges: \textit{excessively long reasoning paths distracting from the answer generation}, and \textit{false-positive relations hindering the path refinement}. In this paper, we propose an iterative interactive KGQA framework that leverages the interactive learning capabilities of LLMs to perform reasoning and Debating over Graphs (DoG). Specifically, DoG employs a subgraph-focusing mechanism, allowing LLMs to perform answer trying after each reasoning step, thereby mitigating the impact of lengthy reasoning paths. On the other hand, DoG utilizes a multi-role debate team to gradually simplify complex questions, reducing the influence of false-positive relations. This debate mechanism ensures the reliability of the reasoning process. Experimental results on five public datasets demonstrate the effectiveness and superiority of our architecture. Notably, DoG outperforms the state-of-the-art method ToG by 23.7\% and 9.1\% in accuracy on WebQuestions and GrailQA, respectively. Furthermore, the integration experiments with various LLMs on the mentioned datasets highlight the flexibility of DoG. Code is available at \url{https://github.com/reml-group/DoG}.

[Arxiv](https://arxiv.org/abs/2409.03155)