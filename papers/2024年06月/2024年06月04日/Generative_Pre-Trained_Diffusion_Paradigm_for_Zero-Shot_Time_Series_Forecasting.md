# 零-shot时间序列预测的生成预训练扩散范式

发布时间：2024年06月04日

`LLM应用

这篇论文探讨了生成预训练扩散（GPD）范式在多变量时间序列预测（TSF）中的应用，特别是在时间序列建模中利用了生成预训练技术。虽然文中提到了大型语言模型（LLMs）和大型视觉模型（LVMs），但主要关注点是利用这些技术在时间序列预测领域的应用，而不是理论探讨或Agent的设计与应用。因此，这篇论文最适合归类为LLM应用。` `时间序列预测` `机器学习`

> Generative Pre-Trained Diffusion Paradigm for Zero-Shot Time Series Forecasting

# 摘要

> 近年来，生成预训练范式如大型语言模型（LLMs）和大型视觉模型（LVMs）引领了技术革新，广泛应用于现实世界。特别是基于预训练LLMs的时间序列研究，相比传统深度模型，展现出更强的泛化与鲁棒性，预示着生成预训练范式在时间序列领域的巨大潜力。然而，这些研究多聚焦于跨模态应用，即利用LLMs的语言能力处理时间序列数据，虽成绩斐然，却也面临数据分布差异导致的概念漂移和维度错配引发的灵活性缺失。鉴于此，我们借鉴LVMs的最新进展，重新审视时间序列建模。本文首次深入探讨了生成预训练扩散（GPD）范式在实际多变量时间序列预测（TSF）中的卓越表现。我们提出了一种简化的MLP扩散网络，以无条件方式建模时间序列，并通过零-shot、无需调优的方法，利用历史数据预测未来。GPD范式专为时间序列设计，有效避免了概念漂移，实现了灵活的任意长度预测。实验表明，GPD范式在主流基准和多样TSF任务中，与顶尖的LLM和深度模型范式并驾齐驱，展现了其在未来研究中的巨大潜力。

> In recent years, generative pre-trained paradigms such as Large Language Models (LLMs) and Large Vision Models (LVMs) have achieved revolutionary advancements and widespread real-world applications. Particularly, the emergence of pre-trained LLMs-based temporal works, compared to previous deep model approaches, has demonstrated superior generalization and robustness, showcasing the potential of generative pre-trained paradigms as foundation models for time series. However, those LLMs-based works mainly focus on cross-modal research, i.e., leveraging the language capabilities of LLMs in time series contexts. Although they have achieved impressive performance, there still exist the issues of concept drift caused by differences in data distribution and inflexibility caused by misalignment of dimensions. To this end, inspired by recent work on LVMs, we reconsider the paradigm of time series modeling. In this paper, we comprehensively explore, for the first time, the effectiveness and superiority of the Generative Pre-trained Diffusion (GPD) paradigm in real-world multivariate time series forecasting (TSF). Specifically, to mitigate performance bias introduced by sophisticated networks, we propose a straightforward MLP diffusion network for unconditional modeling of time series. Then we employ a zero-shot and tuning-free method to predict (generate) future data using historical data as prompts. The GPD paradigm is established on the time series modality, effectively preventing the phenomenon of concept drift, and enabling flexible forecasting of arbitrary lengths. We demonstrate that the GPD paradigm achieves comprehensive performance and generalization comparable to current SOTA LLM-based and deep model paradigms on mainstream benchmarks and various TSF tasks. Extensive experiments validate the potential of the GPD paradigm and its assistance in future related research.

![零-shot时间序列预测的生成预训练扩散范式](../../../paper_images/2406.02212/x1.png)

![零-shot时间序列预测的生成预训练扩散范式](../../../paper_images/2406.02212/x2.png)

![零-shot时间序列预测的生成预训练扩散范式](../../../paper_images/2406.02212/x3.png)

![零-shot时间序列预测的生成预训练扩散范式](../../../paper_images/2406.02212/x4.png)

[Arxiv](https://arxiv.org/abs/2406.02212)