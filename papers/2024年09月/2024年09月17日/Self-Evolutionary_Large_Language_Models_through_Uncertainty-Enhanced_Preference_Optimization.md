# 大型语言模型通过不确定性增强的偏好优化实现自进化

发布时间：2024年09月17日

`LLM理论` `人工智能` `机器学习`

> Self-Evolutionary Large Language Models through Uncertainty-Enhanced Preference Optimization

# 摘要

> 迭代偏好优化已成为 LLM 的主要训练方式，但因循环中噪声数据过多，效果欠佳。为此，我们推出了 UPO 框架，通过可靠反馈让 LLM 自我进化。核心在于通过成对不确定性估计和精准反馈采样，减少当前策略和奖励模型产生的噪声数据。我们引入的估计器模型，结合贝叶斯神经网络中的蒙特卡罗丢弃法，对 LLM 策略生成的偏好数据进行不确定性评估。相比直接按奖励分数筛选响应的传统方法，我们的估计器更关注成对模型不确定性，有效避免奖励模型的确认偏误。此外，我们还设计了不确定性增强的自我进化算法，提升偏好优化的鲁棒性，促使 LLM 生成高奖励且确定性强的响应。多项基准测试表明，UPO 框架显著改善了噪声问题，大幅提升了迭代偏好优化的效果。

> Iterative preference optimization has recently become one of the de-facto training paradigms for large language models (LLMs), but the performance is still underwhelming due to too much noisy preference data yielded in the loop. To combat this issue, we present an \textbf{U}ncertainty-enhanced \textbf{P}reference \textbf{O}ptimization (UPO) framework to make the LLM self-evolve with reliable feedback. The key idea is mitigating the noisy preference data derived from the current policy and reward models by performing pair-wise uncertainty estimation and judiciously reliable feedback sampling. To reach this goal, we thus introduce an estimator model, which incorporates Monte Carlo (MC) dropout in Bayesian neural network (BNN) to perform uncertainty estimation for the preference data derived from the LLM policy. Compared to the existing methods that directly filter generated responses based on the reward score, the estimator focuses on the model uncertainty in a pair-wise manner and effectively bypasses the confirmation bias problem of the reward model. Additionally, we also propose an uncertainty-enhanced self-evolution algorithm to improve the robustness of preference optimization and encourage the LLM to generate responses with both high reward and certainty. Extensive experiments over multiple benchmarks demonstrate that our framework substantially alleviates the noisy problem and improves the performance of iterative preference optimization.

[Arxiv](https://arxiv.org/abs/2409.11212)