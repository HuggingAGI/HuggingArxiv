# 大型语言模型代理的相互作用。可解释的模型与社会学习

发布时间：2024年11月02日

`Agent` `微观经济学` `语言模型`

> Interacting Large Language Model Agents. Interpretable Models and Social Learning

# 摘要

> 本文借助统计信号处理和微观经济学的手段，为交互大型语言模型代理（LLMAs）研发了理论与算法。尽管这两个领域已然成熟，但其在交互LLMAs决策方面的应用尚未被探索。受在线平台贝叶斯情感分析的启发，我们构建了可解释的模型和随机控制算法，让LLMAs能够相互交互并进行贝叶斯推理。由于交互LLMAs会从过往决策和外部输入中学习，所以它们呈现出偏差和从众行为。故而，开发可解释的模型和随机控制算法对于理解并缓解这些行为极为关键。本文有三项主要成果。其一，通过微观经济学中的贝叶斯显示偏好，我们表明单个LLMA满足理性疏忽（有限理性）效用最大化的充分条件，且在给定观察的情况下，LLMA会选择使正则化效用最大化的行动。其二，我们运用贝叶斯社会学习为依次相互交互并进行贝叶斯推理的LLMAs构建可解释模型。我们的模型捕捉到了交互LLMAs所表现出的从众行为。其三，我们提出了一个随机控制框架，在以下两种情形下延缓从众并提高状态估计的准确性：（a）集中控制的LLMAs；（b）有激励机制的自主LLMAs。在全文中，我们利用诸如Mistral的开源模型和ChatGPT之类的闭源模型，在仇恨言论分类和产品质量评估的真实数据集中展示了我们方法的有效性。基于大量的实证分析和数学形式化，本文的核心要点在于，LLMAs在交互时充当具有理性限制的贝叶斯代理，并展现出社会学习的特性。

> This paper develops theory and algorithms for interacting large language model agents (LLMAs) using methods from statistical signal processing and microeconomics. While both fields are mature, their application to decision-making by interacting LLMAs remains unexplored. Motivated by Bayesian sentiment analysis on online platforms, we construct interpretable models and stochastic control algorithms that enable LLMAs to interact and perform Bayesian inference. Because interacting LLMAs learn from prior decisions and external inputs, they exhibit bias and herding behavior. Thus, developing interpretable models and stochastic control algorithms is essential to understand and mitigate these behaviors. This paper has three main results. First, we show using Bayesian revealed preferences from microeconomics that an individual LLMA satisfies the sufficient conditions for rationally inattentive (bounded rationality) utility maximization and, given an observation, the LLMA chooses an action that maximizes a regularized utility. Second, we utilize Bayesian social learning to construct interpretable models for LLMAs that interact sequentially with each other and the environment while performing Bayesian inference. Our models capture the herding behavior exhibited by interacting LLMAs. Third, we propose a stochastic control framework to delay herding and improve state estimation accuracy under two settings: (a) centrally controlled LLMAs and (b) autonomous LLMAs with incentives. Throughout the paper, we demonstrate the efficacy of our methods on real datasets for hate speech classification and product quality assessment, using open-source models like Mistral and closed-source models like ChatGPT. The main takeaway of this paper, based on substantial empirical analysis and mathematical formalism, is that LLMAs act as rationally bounded Bayesian agents that exhibit social learning when interacting.

[Arxiv](https://arxiv.org/abs/2411.01271)