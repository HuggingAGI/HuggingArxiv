# 大型语言模型驱动的多目标启发式进化

发布时间：2024年09月25日

`LLM应用` `人工智能`

> Multi-objective Evolution of Heuristic Using Large Language Model

# 摘要

> 启发式方法常用于解决复杂的搜索和优化问题，但设计这些方法往往需要繁琐的手动操作和深厚的领域知识。最近，研究者们开始利用大型语言模型（LLM）的强大语言和编码能力，实现自动化的启发式搜索。然而，现有研究多聚焦于目标问题的最佳性能，忽略了效率和可扩展性等实际应用中的关键因素。为此，我们提出将启发式搜索视为多目标优化问题，并引入除最佳性能外的其他实际标准。面对搜索空间的复杂性，传统多目标优化方法显得力不从心。我们首创了基于LLM的多目标启发式搜索框架——多目标启发式进化（MEoH），通过零-shot方式生成满足多重设计标准的启发式集合。我们设计了新的支配-相异性机制，有效管理种群并进行选择，结合搜索空间中的代码相异性和目标空间中的支配性。MEoH在在线装箱问题（BPP）和旅行商问题（TSP）中展示了其能力，一次运行即可生成多种精英启发式，提供更多权衡选择。实验表明，MEoH不仅性能优越，效率也提升了十倍之多。此外，多目标搜索还为启发式设计带来了新视角，促进了多样化启发式的发现。

> Heuristics are commonly used to tackle diverse search and optimization problems. Design heuristics usually require tedious manual crafting with domain knowledge. Recent works have incorporated large language models (LLMs) into automatic heuristic search leveraging their powerful language and coding capacity. However, existing research focuses on the optimal performance on the target problem as the sole objective, neglecting other criteria such as efficiency and scalability, which are vital in practice. To tackle this challenge, we propose to model heuristic search as a multi-objective optimization problem and consider introducing other practical criteria beyond optimal performance. Due to the complexity of the search space, conventional multi-objective optimization methods struggle to effectively handle multi-objective heuristic search. We propose the first LLM-based multi-objective heuristic search framework, Multi-objective Evolution of Heuristic (MEoH), which integrates LLMs in a zero-shot manner to generate a non-dominated set of heuristics to meet multiple design criteria. We design a new dominance-dissimilarity mechanism for effective population management and selection, which incorporates both code dissimilarity in the search space and dominance in the objective space. MEoH is demonstrated in two well-known combinatorial optimization problems: the online Bin Packing Problem (BPP) and the Traveling Salesman Problem (TSP). Results indicate that a variety of elite heuristics are automatically generated in a single run, offering more trade-off options than existing methods. It successfully achieves competitive or superior performance while improving efficiency up to 10 times. Moreover, we also observe that the multi-objective search introduces novel insights into heuristic design and leads to the discovery of diverse heuristics.

[Arxiv](https://arxiv.org/abs/2409.16867)