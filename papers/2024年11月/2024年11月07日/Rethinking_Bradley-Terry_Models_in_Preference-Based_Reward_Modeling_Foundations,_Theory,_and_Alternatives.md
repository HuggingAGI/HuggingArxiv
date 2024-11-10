# 在基于偏好的奖励建模中重新思考布拉德利-特里模型：基础、理论和替代方案

发布时间：2024年11月07日

`LLM理论` `语言模型` `奖励建模`

> Rethinking Bradley-Terry Models in Preference-Based Reward Modeling: Foundations, Theory, and Alternatives

# 摘要

> 布拉德利-特里（BT）模型在大型语言模型（LLM）对齐的奖励建模中是一种常见且成功的实践。然而，尚不清楚为什么这个最初为多人随机游戏匹配开发的模型能够被用于将成对的响应比较转换为奖励值并进行预测。特别是考虑到只有有限数量的提示-响应对与其他对稀疏地进行比较。在本文中，我们首先重新审视了在奖励建模中使用 BT 模型的基础，并基于使用嵌入的深度神经网络建立了 BT 奖励模型的收敛速度，为其使用提供了理论基础。尽管在理论上是合理的，但我们认为从下游优化的角度来看，BT 模型不是必要的选择。这是因为奖励模型只需要通过对真实奖励的单调变换来保留正确的排名预测。我们强调了奖励建模中顺序一致性的关键概念，并证明了 BT 模型具有此属性。因此，我们提出了一种简单直接的上限算法，与现成的二分类器兼容，作为替代的顺序一致奖励建模目标。为了提供实际的见解，我们通过超过 12,000 个实验设置，使用 6 个基础 LLM、2 个数据集以及在数量、质量和偏好注释中的配对选择方面各不相同的多样化注释设计，对这些不同的奖励建模方法的性能进行了实证评估。

> The Bradley-Terry (BT) model is a common and successful practice in reward modeling for Large Language Model (LLM) alignment. However, it remains unclear why this model -- originally developed for multi-player stochastic game matching -- can be adopted to convert pairwise response comparisons to reward values and make predictions. Especially given the fact that only a limited number of prompt-response pairs are sparsely compared with others. In this paper, we first revisit the foundations of using BT models in reward modeling, and establish the convergence rate of BT reward models based on deep neural networks using embeddings, providing a theoretical foundation for their use. Despite theoretically sound, we argue that the BT model is not a necessary choice from the perspective of downstream optimization. This is because a reward model only needs to preserve the correct ranking predictions through a monotonic transformation of the true reward. We highlight the critical concept of order consistency in reward modeling and demonstrate that the BT model possesses this property. Consequently, we propose a simple and straightforward upper-bound algorithm, compatible with off-the-shelf binary classifiers, as an alternative order-consistent reward modeling objective. To offer practical insights, we empirically evaluate the performance of these different reward modeling approaches across more than 12,000 experimental setups, using $6$ base LLMs, $2$ datasets, and diverse annotation designs that vary in quantity, quality, and pairing choices in preference annotations.

[Arxiv](https://arxiv.org/abs/2411.04991)