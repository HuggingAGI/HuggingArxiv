# CONGRA：自动冲突解决的基准挑战

发布时间：2024年09月21日

`LLM应用` `软件开发` `人工智能`

> CONGRA: Benchmarking Automatic Conflict Resolution

# 摘要

> 合并不同软件版本中的冲突解决是一项艰巨任务。为减少手动合并的负担，研究人员开发了多种基于程序分析的工具，但这些工具仅能处理特定类型的冲突，应用范围有限。随着语言模型的发展，研究人员将冲突代码视为文本，理论上可解决几乎所有冲突。然而，缺乏有效的冲突难度分级方法，阻碍了对大型语言模型（LLMs）的全面评估，使其局限性难以深入理解。此外，缺乏大规模开放基准来评估LLMs在自动冲突解决中的表现。为此，我们推出了ConGra，一种冲突分级基准测试方案，旨在评估软件合并工具在不同复杂度冲突场景下的性能。我们提出了一种基于代码操作的新方法来分类冲突，并构建了一个包含34个真实项目中44,948个冲突的大规模评估数据集。通过该数据集，我们评估了多个最先进的LLMs和代码LLMs的性能，揭示了两个反直觉但有见地的现象。ConGra将在https://github.com/HKU-System-Security-Lab/ConGra发布。

> Resolving conflicts from merging different software versions is a challenging task. To reduce the overhead of manual merging, researchers develop various program analysis-based tools which only solve specific types of conflicts and have a limited scope of application. With the development of language models, researchers treat conflict code as text, which theoretically allows for addressing almost all types of conflicts. However, the absence of effective conflict difficulty grading methods hinders a comprehensive evaluation of large language models (LLMs), making it difficult to gain a deeper understanding of their limitations. Furthermore, there is a notable lack of large-scale open benchmarks for evaluating the performance of LLMs in automatic conflict resolution. To address these issues, we introduce ConGra, a CONflict-GRAded benchmarking scheme designed to evaluate the performance of software merging tools under varying complexity conflict scenarios. We propose a novel approach to classify conflicts based on code operations and use it to build a large-scale evaluation dataset based on 44,948 conflicts from 34 real-world projects. We evaluate state-of-the-art LLMs on conflict resolution tasks using this dataset. By employing the dataset, we assess the performance of multiple state-of-the-art LLMs and code LLMs, ultimately uncovering two counterintuitive yet insightful phenomena. ConGra will be released at https://github.com/HKU-System-Security-Lab/ConGra.

[Arxiv](https://arxiv.org/abs/2409.14121)