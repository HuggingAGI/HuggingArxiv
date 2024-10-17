# 模型集群：利用集群智能，协同搜索以适应 LLM 专家

发布时间：2024年10月15日

`LLM理论` `人工智能` `机器学习`

> Model Swarms: Collaborative Search to Adapt LLM Experts via Swarm Intelligence

# 摘要

> 我们提出 Model Swarms，一种利用群体智能协作搜索的算法，用于优化大型语言模型 (LLM)。该算法从一组 LLM 专家和效用函数出发，在最佳检查点的引导下，专家们在权重空间中协作移动，优化模型适应目标。与传统方法相比，Model Swarms 无需调优，适用于低数据环境，且不依赖于特定专家的假设。实验显示，该方法在单任务、多任务、奖励模型及人类兴趣等多领域中，比现有基线提升高达 21.0%。深入分析表明，LLM 专家在初始阶段即展现出新能力，而 Model Swarms 通过协作搜索，实现了专家能力的提升。

> 
Abstract:We propose Model Swarms, a collaborative search algorithm to adapt LLMs via swarm intelligence, the collective behavior guiding individual systems. Specifically, Model Swarms starts with a pool of LLM experts and a utility function. Guided by the best-found checkpoints across models, diverse LLM experts collaboratively move in the weight space and optimize a utility function representing model adaptation objectives. Compared to existing model composition approaches, Model Swarms offers tuning-free model adaptation, works in low-data regimes with as few as 200 examples, and does not require assumptions about specific experts in the swarm or how they should be composed. Extensive experiments demonstrate that Model Swarms could flexibly adapt LLM experts to a single task, multi-task domains, reward models, as well as diverse human interests, improving over 12 model composition baselines by up to 21.0% across tasks and contexts. Further analysis reveals that LLM experts discover previously unseen capabilities in initial checkpoints and that Model Swarms enable the weak-to-strong transition of experts through the collaborative search process.
    

[Arxiv](https://arxiv.org/pdf/2410.11163)