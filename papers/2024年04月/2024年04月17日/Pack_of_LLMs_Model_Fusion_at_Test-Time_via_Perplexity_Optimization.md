# 大型语言模型集群：在测试阶段通过优化困惑度实现模型融合。

发布时间：2024年04月17日

`LLM应用` `人工智能`

> Pack of LLMs: Model Fusion at Test-Time via Perplexity Optimization

# 摘要

> 融合多个大型语言模型（LLMs）的洞见，能够汇聚它们的不同优势，从而在特定任务上实现更佳的表现。不过，现有的融合技术要么建立在无法适应新型LLMs的学习机制上，要么忽略了各个LLM对输入内容理解的深度。本研究聚焦于测试阶段的LLM融合，允许在推理时调用任意用户选定的LLMs所蕴含的知识。我们提出了“LLMs集合”（PackLLM），这是一种在测试时进行融合的有效方法，它能够根据输入提示发挥每个LLM的专业能力。PackLLM通过求解一个优化问题来实现模型融合，确定每个LLM的权重，目标是最小化输入提示的困惑度。首先，我们的简化版本PackLLM-sim证实了困惑度是衡量LLM专业度的良好指标。其次，我们的优化版本PackLLM-opt采用贪婪算法近似求解了最小化困惑度的问题。所得的权重用于在推理过程中整合LLMs。我们在超过100个不同的LLMs上进行了广泛任务的实验。实验结果显示：（i）困惑度是衡量LLM融合效果的可靠标准；（ii）PackLLM在测试时融合的基线准确度上提升了1.89%；（iii）相较于基于学习的方法，PackLLM能通过引入新的LLMs，在准确度上实现3.92-11.94%的增长。

> Fusing knowledge from multiple Large Language Models (LLMs) can combine their diverse strengths to achieve improved performance on a given task. However, current fusion approaches either rely on learning-based fusers that do not generalize to new LLMs, or do not take into account how well each LLM understands the input. In this work, we study LLM fusion at test-time, which enables leveraging knowledge from arbitrary user-specified LLMs during inference. We introduce Pack of LLMs (PackLLM), an effective method for test-time fusion that leverages each LLM's expertise, given an input prompt. PackLLM performs model fusion by solving an optimization problem for determining each LLM's importance, so that perplexity over the input prompt is minimized. First, our simple PackLLM-sim variant validates that perplexity is a good indicator for measuring each LLM's expertise. Second, our PackLLM-opt variant approximately solves the perplexity minimization problem via a greedy algorithm. The derived importance weights are used to combine the LLMs during inference. We conduct experiments with over 100 total LLMs on a diverse set of tasks. Experimental results show that (i) perplexity is a reliable measure for LLM fusion, (ii) PackLLM outperforms test-time fusion baselines by 1.89% accuracy points, and (iii) PackLLM can leverage new LLMs to improve performance over learning-based fusion approaches by 3.92-11.94% accuracy points.

[Arxiv](https://arxiv.org/abs/2404.11531)