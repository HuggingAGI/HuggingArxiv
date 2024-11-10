# 一种用于数据点选择的贝叶斯方法

发布时间：2024年11月06日

`LLM应用` `语言模型`

> A Bayesian Approach to Data Point Selection

# 摘要

> 数据点选择（DPS）在深度学习中正成为一个关键话题，因为与获取经过整理或处理的数据的难度相比，获取未经整理的训练数据较为容易。现有的 DPS 方法主要基于双层优化（BLO）公式，这在内存和计算方面要求很高，并且在小批量方面存在一些理论缺陷。因此，我们提出了一种新的贝叶斯方法用于 DPS。我们将 DPS 问题视为新贝叶斯模型中的后验推断，在合理的先验和似然模型下推断实例权重和主要神经网络参数的后验分布。我们采用随机梯度朗之万 MCMC 采样来共同学习主网络和实例权重，即使对于小批量也能确保收敛。我们的更新方程与广泛使用的 SGD 相当，并且比现有的基于 BLO 的方法效率高得多。通过在视觉和语言领域的受控实验，我们给出了概念验证。此外，我们证明了我们的方法能有效地扩展到大型语言模型，并有助于为指令微调数据集进行自动的每个任务优化。

> Data point selection (DPS) is becoming a critical topic in deep learning due to the ease of acquiring uncurated training data compared to the difficulty of obtaining curated or processed data. Existing approaches to DPS are predominantly based on a bi-level optimisation (BLO) formulation, which is demanding in terms of memory and computation, and exhibits some theoretical defects regarding minibatches. Thus, we propose a novel Bayesian approach to DPS. We view the DPS problem as posterior inference in a novel Bayesian model where the posterior distributions of the instance-wise weights and the main neural network parameters are inferred under a reasonable prior and likelihood model. We employ stochastic gradient Langevin MCMC sampling to learn the main network and instance-wise weights jointly, ensuring convergence even with minibatches. Our update equation is comparable to the widely used SGD and much more efficient than existing BLO-based methods. Through controlled experiments in both the vision and language domains, we present the proof-of-concept. Additionally, we demonstrate that our method scales effectively to large language models and facilitates automated per-task optimization for instruction fine-tuning datasets.

[Arxiv](https://arxiv.org/abs/2411.03768)