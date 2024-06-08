# 零-shot时间序列预测的新范式：生成预训练扩散模型

发布时间：2024年06月04日

`LLM应用

这篇论文探讨了生成预训练扩散（GPD）范式在多变量时间序列预测（TSF）中的应用，特别是在时间序列建模中的实效与优势。它提出了一种简化的MLP扩散网络，并展示了GPD范式在处理时间序列数据时的灵活性和有效性。虽然文中提到了大型语言模型（LLMs）和大型视觉模型（LVMs），但重点在于将GPD范式应用于时间序列预测，这属于LLM的应用领域，而不是理论探讨或Agent系统的构建。因此，最合适的分类是LLM应用。` `时间序列预测` `机器学习`

> Generative Pre-Trained Diffusion Paradigm for Zero-Shot Time Series Forecasting

# 摘要

> 近年来，生成预训练范式如大型语言模型（LLMs）和大型视觉模型（LVMs）引领了技术革命，广泛应用于现实世界。特别是基于预训练LLMs的时间序列研究，相比传统深度模型，展现出更强的泛化与鲁棒性，凸显了生成预训练范式作为时间序列基础模型的潜力。但这些研究多聚焦于跨模态应用，利用LLMs的语言能力处理时间序列数据，虽性能卓越，却面临数据分布差异导致的概念漂移和维度错配引发的灵活性问题。受LVMs启发，我们重新审视时间序列建模范式。本文首次深入探讨生成预训练扩散（GPD）范式在多变量时间序列预测（TSF）中的实效与优势。我们提出一种简化的MLP扩散网络，避免复杂网络带来的性能偏差，并采用零样本、无需调优的方法，以历史数据为提示预测未来。GPD范式专为时间序列设计，有效避免概念漂移，实现灵活的任意长度预测。实验证明，GPD范式在主流基准和多样TSF任务中，与顶尖LLM和深度模型范式并驾齐驱，展现了其作为未来研究工具的巨大潜力。

> In recent years, generative pre-trained paradigms such as Large Language Models (LLMs) and Large Vision Models (LVMs) have achieved revolutionary advancements and widespread real-world applications. Particularly, the emergence of pre-trained LLMs-based temporal works, compared to previous deep model approaches, has demonstrated superior generalization and robustness, showcasing the potential of generative pre-trained paradigms as foundation models for time series. However, those LLMs-based works mainly focus on cross-modal research, i.e., leveraging the language capabilities of LLMs in time series contexts. Although they have achieved impressive performance, there still exist the issues of concept drift caused by differences in data distribution and inflexibility caused by misalignment of dimensions. To this end, inspired by recent work on LVMs, we reconsider the paradigm of time series modeling. In this paper, we comprehensively explore, for the first time, the effectiveness and superiority of the Generative Pre-trained Diffusion (GPD) paradigm in real-world multivariate time series forecasting (TSF). Specifically, to mitigate performance bias introduced by sophisticated networks, we propose a straightforward MLP diffusion network for unconditional modeling of time series. Then we employ a zero-shot and tuning-free method to predict (generate) future data using historical data as prompts. The GPD paradigm is established on the time series modality, effectively preventing the phenomenon of concept drift, and enabling flexible forecasting of arbitrary lengths. We demonstrate that the GPD paradigm achieves comprehensive performance and generalization comparable to current SOTA LLM-based and deep model paradigms on mainstream benchmarks and various TSF tasks. Extensive experiments validate the potential of the GPD paradigm and its assistance in future related research.

![零-shot时间序列预测的新范式：生成预训练扩散模型](../../../paper_images/2406.02212/x1.png)

![零-shot时间序列预测的新范式：生成预训练扩散模型](../../../paper_images/2406.02212/x2.png)

![零-shot时间序列预测的新范式：生成预训练扩散模型](../../../paper_images/2406.02212/x3.png)

![零-shot时间序列预测的新范式：生成预训练扩散模型](../../../paper_images/2406.02212/x4.png)

[Arxiv](https://arxiv.org/abs/2406.02212)