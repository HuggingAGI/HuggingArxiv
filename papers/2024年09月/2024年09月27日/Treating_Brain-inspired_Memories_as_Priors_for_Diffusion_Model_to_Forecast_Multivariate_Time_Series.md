# 借鉴脑记忆作为扩散模型的先验，精准预测多变量时间序列

发布时间：2024年09月27日

`LLM应用` `时间序列分析` `人工智能`

> Treating Brain-inspired Memories as Priors for Diffusion Model to Forecast Multivariate Time Series

# 摘要

> 多变量时间序列预测面临诸多挑战，尤其是在捕捉有限输入长度内的时间模式。我们借鉴人类记忆机制，提出了一种通道共享的脑启发记忆模块，用于捕捉周期性和突发事件。该模块包含语义和情景记忆，分别用于捕捉一般和特殊模式，并设计了相应的回忆和更新机制。此外，我们结合扩散模型，提出了记忆增强的扩散模型，显著提升了预测的准确性和鲁棒性。实验结果表明，我们的方法在捕捉和利用不同通道上的多样化时间模式方面表现优异。

> Forecasting Multivariate Time Series (MTS) involves significant challenges in various application domains. One immediate challenge is modeling temporal patterns with the finite length of the input. These temporal patterns usually involve periodic and sudden events that recur across different channels. To better capture temporal patterns, we get inspiration from humans' memory mechanisms and propose a channel-shared, brain-inspired memory module for MTS. Specifically, brain-inspired memory comprises semantic and episodic memory, where the former is used to capture general patterns, such as periodic events, and the latter is employed to capture special patterns, such as sudden events, respectively. Meanwhile, we design corresponding recall and update mechanisms to better utilize these patterns. Furthermore, acknowledging the capacity of diffusion models to leverage memory as a prior, we present a brain-inspired memory-augmented diffusion model. This innovative model retrieves relevant memories for different channels, utilizing them as distinct priors for MTS predictions. This incorporation significantly enhances the accuracy and robustness of predictions. Experimental results on eight datasets consistently validate the superiority of our approach in capturing and leveraging diverse recurrent temporal patterns across different channels.

[Arxiv](https://arxiv.org/abs/2409.18491)