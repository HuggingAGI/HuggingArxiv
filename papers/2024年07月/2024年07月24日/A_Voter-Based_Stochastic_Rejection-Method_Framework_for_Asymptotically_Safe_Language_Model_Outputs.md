# 采用基于投票的随机拒绝框架，确保语言模型输出渐近安全

发布时间：2024年07月24日

`LLM应用` `人工智能` `网络安全`

> A Voter-Based Stochastic Rejection-Method Framework for Asymptotically Safe Language Model Outputs

# 摘要

> 本文通过利用 LLM 的随机性，提出了一种防止不安全或低质量输出的新方法。我们设计了一个系统，其中 LLM 检查器通过投票决定输出是否可接受，若不通过则重新生成，直至获得足够批准。此外，我们还提出了成本和失败率的估算方法，并据此设计了一种算法，以最低成本实现预定失败率。实验表明，在遵循该算法的条件下，失败率随成本增加而指数下降，且模型能合理预测系统实际运行性能，即便数据有限。

> This paper proposes a new method for preventing unsafe or otherwise low quality large language model (LLM) outputs, by leveraging the stochasticity of LLMs. We propose a system whereby LLM checkers vote on the acceptability of a generated output, regenerating it if a threshold of disapproval is reached, until sufficient checkers approve. We further propose estimators for cost and failure rate, and based on those estimators and experimental data tailored to the application, we propose an algorithm that achieves a desired failure rate at the least possible cost. We demonstrate that, under these models, failure rate decreases exponentially as a function of cost when voter count and threshold are chosen according to the algorithm, and that the models reasonably estimate the actual performance of such a system in action, even with limited data.

[Arxiv](https://arxiv.org/abs/2407.16994)