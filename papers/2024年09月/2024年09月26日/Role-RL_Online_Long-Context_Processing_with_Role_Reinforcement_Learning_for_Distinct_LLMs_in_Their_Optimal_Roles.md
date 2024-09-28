# Role-RL：通过角色强化学习实现 LLMs 在线长上下文处理，确保每个模型在其最佳角色中发挥作用。

发布时间：2024年09月26日

`LLM应用` `流媒体` `电子商务`

> Role-RL: Online Long-Context Processing with Role Reinforcement Learning for Distinct LLMs in Their Optimal Roles

# 摘要

> 大型语言模型 (LLM) 因其复杂的实现、低效的训练和数据稀疏性而面临挑战。为此，我们提出了在线长上下文处理 (OLP) 的新方法，适用于处理无限长文档，如自动化新闻、直播电商和短视频等流媒体的信息处理。此外，在众多 LLM 中选择最优模型时，常需权衡性能、成本和响应时间。为此，我们引入了角色强化学习 (Role-RL)，根据实际性能自动分配不同 LLM 在 OLP 中的角色。实验表明，Role-RL 框架下的 OLP 平均召回率达 93.2%，LLM 成本降低 79.4%。代码和数据集已公开，详见：https://anonymous.4open.science/r/Role-RL。

> Large language models (LLMs) with long-context processing are still challenging because of their implementation complexity, training efficiency and data sparsity. To address this issue, a new paradigm named Online Long-context Processing (OLP) is proposed when we process a document of unlimited length, which typically occurs in the information reception and organization of diverse streaming media such as automated news reporting, live e-commerce, and viral short videos. Moreover, a dilemma was often encountered when we tried to select the most suitable LLM from a large number of LLMs amidst explosive growth aiming for outstanding performance, affordable prices, and short response delays. In view of this, we also develop Role Reinforcement Learning (Role-RL) to automatically deploy different LLMs in their respective roles within the OLP pipeline according to their actual performance. Extensive experiments are conducted on our OLP-MINI dataset and it is found that OLP with Role-RL framework achieves OLP benchmark with an average recall rate of 93.2% and the LLM cost saved by 79.4%. The code and dataset are publicly available at: https://anonymous.4open.science/r/Role-RL.

[Arxiv](https://arxiv.org/abs/2409.18014)