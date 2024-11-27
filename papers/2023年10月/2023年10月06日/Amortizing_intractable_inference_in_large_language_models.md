# 大型语言模型中难以处理的推理的摊销

发布时间：2023年10月06日

`LLM应用` `语言模型`

> Amortizing intractable inference in large language models

# 摘要

> 摘要：自回归大型语言模型（LLMs）借助下一个标记的条件分布从训练数据中压缩知识，这使得对这些知识的有效查询局限于从头到尾的自回归采样。然而，众多备受关注的任务，比如序列延续、填充以及其他形式的约束生成，都涉及从难以处理的后验分布中采样。我们利用摊销贝叶斯推理从这些难以处理的后验中采样，以此来解决这一局限。从算法层面，这一摊销是通过借助追求多样性的强化学习算法——生成流网络（GFlowNets）来微调 LLMs 实现的。我们通过实践证明，LLM 微调的这种分布匹配模式能够成为最大似然训练和奖励最大化策略优化的有效替代。作为一项重要应用，我们把思维链推理视作潜在变量建模问题，并表明我们的方法能让 LLMs 高效适应需要多步推理和工具使用的任务。

> 
Abstract:Autoregressive large language models (LLMs) compress knowledge from their training data through next-token conditional distributions. This limits tractable querying of this knowledge to start-to-end autoregressive sampling. However, many tasks of interest -- including sequence continuation, infilling, and other forms of constrained generation -- involve sampling from intractable posterior distributions. We address this limitation by using amortized Bayesian inference to sample from these intractable posteriors. Such amortization is algorithmically achieved by fine-tuning LLMs via diversity-seeking reinforcement learning algorithms: generative flow networks (GFlowNets). We empirically demonstrate that this distribution-matching paradigm of LLM fine-tuning can serve as an effective alternative to maximum-likelihood training and reward-maximizing policy optimization. As an important application, we interpret chain-of-thought reasoning as a latent variable modeling problem and demonstrate that our approach enables data-efficient adaptation of LLMs to tasks that require multi-step rationalization and tool use.
    

[Arxiv](https://arxiv.org/pdf/2310.04363)