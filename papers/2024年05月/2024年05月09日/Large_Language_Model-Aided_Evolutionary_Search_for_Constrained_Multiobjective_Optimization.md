# 借助大型语言模型之力，进化搜索在约束多目标优化领域展翅高飞。

发布时间：2024年05月09日

`LLM应用

这篇论文探讨了如何利用大型语言模型（LLM）来增强进化算法在受约束多目标优化问题上的性能，特别是在加速收敛方面。通过定制化的提示工程和微调LLM，研究者能够更好地评估解决方案的质量，并生成更优的解决方案。这种方法在实验中显示出了与顶尖进化算法相比的竞争优势，因此属于LLM在实际应用中的一个案例，即在优化问题求解领域的应用。` `多目标优化` `进化算法`

> Large Language Model-Aided Evolutionary Search for Constrained Multiobjective Optimization

# 摘要

> 进化算法在多目标优化问题上表现卓越，但随机性有时会阻碍其在约束场景下的快速收敛。本研究采用LLM来提升进化搜索，旨在加速受约束多目标问题的收敛。通过定制提示工程微调LLM，我们整合了目标值与约束违反信息，使其能洞察优秀与不佳解决方案间的联系。我们依据约束与目标性能评估解决方案质量，并利用精细调整的LLM作为搜索算子，生成更优解。实验证明，LLM辅助的进化搜索在多个测试基准上显著提升了收敛速度，与顶尖进化算法相比，展现出竞争优势。

> Evolutionary algorithms excel in solving complex optimization problems, especially those with multiple objectives. However, their stochastic nature can sometimes hinder rapid convergence to the global optima, particularly in scenarios involving constraints. In this study, we employ a large language model (LLM) to enhance evolutionary search for solving constrained multi-objective optimization problems. Our aim is to speed up the convergence of the evolutionary population. To achieve this, we finetune the LLM through tailored prompt engineering, integrating information concerning both objective values and constraint violations of solutions. This process enables the LLM to grasp the relationship between well-performing and poorly performing solutions based on the provided input data. Solution's quality is assessed based on their constraint violations and objective-based performance. By leveraging the refined LLM, it can be used as a search operator to generate superior-quality solutions. Experimental evaluations across various test benchmarks illustrate that LLM-aided evolutionary search can significantly accelerate the population's convergence speed and stands out competitively against cutting-edge evolutionary algorithms.

[Arxiv](https://arxiv.org/abs/2405.05767)