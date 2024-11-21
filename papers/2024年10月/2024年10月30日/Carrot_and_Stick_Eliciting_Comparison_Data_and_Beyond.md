# “胡萝卜加大棒”：获取比较数据及更多

发布时间：2024年10月30日

`Agent` `机器学习` `数据获取`

> Carrot and Stick: Eliciting Comparison Data and Beyond

# 摘要

> 从人们那里获取的比较数据是众多机器学习任务的基础，涵盖了大型语言模型基于人类反馈的强化学习以及估计排名模型等。这些数据通常具有主观性，且无法直接核实。那怎样才能从理性个体那里如实获取此类比较数据呢？我们设计了同伴预测机制，通过奖励-惩罚支付来获取比较数据。我们的设计借助比较数据的强随机传递性创建了对称的强真实机制，使得说实话 1）构成严格的贝叶斯纳什均衡，2）在所有对称均衡中获得最高支付。在我们的机制里，每个人仅需评估一对项目并报告其比较结果。
  我们进一步把奖励-惩罚支付的概念拓展到获取网络数据上，当代理的私人信号依据伊辛模型采样时，设计了一个对称的强真实机制。我们给出了我们的奖励-惩罚支付将说实话作为严格贝叶斯纳什均衡的充要条件。在两个真实世界数据集上开展的实验进一步支撑了我们的理论发现。

> Comparison data elicited from people are fundamental to many machine learning tasks, including reinforcement learning from human feedback for large language models and estimating ranking models. They are typically subjective and not directly verifiable. How to truthfully elicit such comparison data from rational individuals? We design peer prediction mechanisms for eliciting comparison data using a bonus-penalty payment. Our design leverages on the strong stochastic transitivity for comparison data to create symmetrically strongly truthful mechanisms such that truth-telling 1) forms a strict Bayesian Nash equilibrium, and 2) yields the highest payment among all symmetric equilibria. Each individual only needs to evaluate one pair of items and report her comparison in our mechanism.
  We further extend the bonus-penalty payment concept to eliciting networked data, designing a symmetrically strongly truthful mechanism when agents' private signals are sampled according to the Ising models. We provide the necessary and sufficient conditions for our bonus-penalty payment to have truth-telling as a strict Bayesian Nash equilibrium. Experiments on two real-world datasets further support our theoretical discoveries.

[Arxiv](https://arxiv.org/abs/2410.23243)