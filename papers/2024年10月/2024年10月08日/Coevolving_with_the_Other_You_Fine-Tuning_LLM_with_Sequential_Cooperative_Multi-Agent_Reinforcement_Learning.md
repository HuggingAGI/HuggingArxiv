# 与“另一个你”共同成长：通过顺序合作多智能体强化学习微调 LLM

发布时间：2024年10月08日

`Agent` `人工智能` `机器学习`

> Coevolving with the Other You: Fine-Tuning LLM with Sequential Cooperative Multi-Agent Reinforcement Learning

# 摘要

> 强化学习 (RL) 已成为微调大型语言模型 (LLM) 的关键技术，但现有方法主要依赖 PPO 及其变体，这些算法在 LLM 微调中常表现不佳且易受分布崩溃影响。本文提出 CORY，将 LLM 微调扩展至顺序合作多智能体 RL 框架，利用多智能体系统的共进化和涌现能力。CORY 将 LLM 复制为先驱者和观察者两个智能体，分别基于查询和查询加先驱者响应生成响应，并共同训练，定期交换角色以促进合作和共进化。实验表明，CORY 在策略最优性、抗分布崩溃和训练鲁棒性方面均优于 PPO，展现了其在现实应用中微调 LLM 的巨大潜力。

> Reinforcement learning (RL) has emerged as a pivotal technique for fine-tuning large language models (LLMs) on specific tasks. However, prevailing RL fine-tuning methods predominantly rely on PPO and its variants. Though these algorithms are effective in general RL settings, they often exhibit suboptimal performance and vulnerability to distribution collapse when applied to the fine-tuning of LLMs. In this paper, we propose CORY, extending the RL fine-tuning of LLMs to a sequential cooperative multi-agent reinforcement learning framework, to leverage the inherent coevolution and emergent capabilities of multi-agent systems. In CORY, the LLM to be fine-tuned is initially duplicated into two autonomous agents: a pioneer and an observer. The pioneer generates responses based on queries, while the observer generates responses using both the queries and the pioneer's responses. The two agents are trained together. During training, the agents exchange roles periodically, fostering cooperation and coevolution between them. Experiments evaluate CORY's performance by fine-tuning GPT-2 and Llama-2 under subjective and objective reward functions on the IMDB Review and GSM8K datasets, respectively. Results show that CORY outperforms PPO in terms of policy optimality, resistance to distribution collapse, and training robustness, thereby underscoring its potential as a superior methodology for refining LLMs in real-world applications.

[Arxiv](https://arxiv.org/abs/2410.06101)