# 构建高效的大型语言模型基础，促进具身多智能体协同合作
发布时间：2024年05月23日

`多Agent应用`
> Towards Efficient LLM Grounding for Embodied Multi-Agent Collaboration
>
> 大型语言模型（LLMs）在实体任务中的推理能力应用面临物理世界复杂性的挑战。特别是在多代理协作中，LLM的规划需要通过代理间通信或信用分配进行反馈，以调整计划并实现有效协调。现有方法因过度依赖物理验证或自我反思，导致对LLMs的查询效率低下。本文提出了一种创新的多代理协作框架，引入了强化优势反馈（ReAd），以高效地自我优化计划。我们通过批评回归从LLM规划数据中学习序列优势函数，并将LLM规划器作为优化器，生成最大化优势函数的动作，赋予LLM预见能力，判断动作是否有助于任务完成。理论分析表明，我们扩展了强化学习中的优势加权回归到多代理系统。实验结果显示，ReAd在成功率上优于基线，并显著减少了代理交互和LLMs查询的次数，证明了其在实现LLMs基础上的高效性。更多详情请访问 \url{https://read-llm.github.io/}。
>
> https://arxiv.org/abs/2405.14314


<hr />

- 论文原文: [https://arxiv.org/abs/2405.14314](https://arxiv.org/abs/2405.14314)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886