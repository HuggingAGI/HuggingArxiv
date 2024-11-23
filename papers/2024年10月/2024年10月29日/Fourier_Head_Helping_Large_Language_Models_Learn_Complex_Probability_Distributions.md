# 傅里叶头：助力大型语言模型习得复杂概率分布

发布时间：2024年10月29日

`LLM应用` `决策制定` `时间序列预测`

> Fourier Head: Helping Large Language Models Learn Complex Probability Distributions

# 摘要

> 随着大型语言模型质量的提升，利用其对非语言标记进行建模的兴趣愈发浓厚。比如，决策转换器把智能体的决策制定重塑为序列建模问题，用仅解码器的大型语言模型为雅达利智能体模拟离散动作空间的分布。然而，在将大型语言模型应用于非语言领域时，对于离散箱的 softmax 是否能捕捉标记的连续结构以及高质量标记生成所需的潜在复杂分布，仍不明确。我们引入了一个由傅里叶级数构建的神经网络层，若想让输出具有更连续的结构，能轻易将其替代任何线性层。我们在合成数据集以及大规模决策制定和时间序列预测任务上展开了广泛分析。同时，我们还提供了理论依据，证明该层能更好地从数据中学习信号，同时忽略高频噪声。我们所有的结果都证实了我们所提出的傅里叶头在基础数据分布具有自然连续结构的场景中的有效性。例如，傅里叶头让雅达利《海之探索》游戏中决策转换器智能体的回报提升了 46％，还使最先进的时间序列基础模型在 20 个训练中未见过的基准上的预测性能提高了 3.5％。

> As the quality of large language models has improved, there has been increased interest in using them to model non-linguistic tokens. For example, the Decision Transformer recasts agentic decision making as a sequence modeling problem, using a decoder-only LLM to model the distribution over the discrete action space for an Atari agent. However, when adapting LLMs to non-linguistic domains, it remains unclear if softmax over discrete bins captures the continuous structure of the tokens and the potentially complex distributions needed for high quality token generation. We introduce a neural network layer, constructed using Fourier series, which we can easily substitute for any linear layer if we want the outputs to have a more continuous structure. We perform extensive analysis on synthetic datasets, as well as on large-scale decision making and time series forecasting tasks. We also provide theoretical evidence that this layer can better learn signal from data while ignoring high-frequency noise. All of our results support the effectiveness of our proposed Fourier head in scenarios where the underlying data distribution has a natural continuous structure. For example, the Fourier head improves a Decision Transformer agent's returns by 46% on the Atari Seaquest game, and increases a state-of-the-art times series foundation model's forecasting performance by 3.5% across 20 benchmarks unseen during training.

[Arxiv](https://arxiv.org/abs/2410.22269)