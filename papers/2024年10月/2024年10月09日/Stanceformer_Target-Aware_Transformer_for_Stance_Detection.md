# Stanceformer：一种目标感知的 Transformer，专为立场检测而生。

发布时间：2024年10月09日

`LLM应用` `社交媒体` `情感分析`

> Stanceformer: Target-Aware Transformer for Stance Detection

# 摘要

> 立场检测任务旨在识别文本中对特定主题的态度。传统模型未能有效聚焦目标，导致性能提升有限。为此，我们推出了 Stanceformer，一种能敏锐感知目标的 transformer 模型，通过 \textit{Target Awareness} 矩阵强化目标关注。实验证明，Stanceformer 在多个 BERT 模型和 LLM 中表现卓越，且在不同数据集上均显成效。更令人振奋的是，它还能应用于情感分析等其他领域。代码已公开，欢迎探索。\footnote{\scriptsize\url{https://github.com/kgarg8/Stanceformer}}

> The task of Stance Detection involves discerning the stance expressed in a text towards a specific subject or target. Prior works have relied on existing transformer models that lack the capability to prioritize targets effectively. Consequently, these models yield similar performance regardless of whether we utilize or disregard target information, undermining the task's significance. To address this challenge, we introduce Stanceformer, a target-aware transformer model that incorporates enhanced attention towards the targets during both training and inference. Specifically, we design a \textit{Target Awareness} matrix that increases the self-attention scores assigned to the targets. We demonstrate the efficacy of the Stanceformer with various BERT-based models, including state-of-the-art models and Large Language Models (LLMs), and evaluate its performance across three stance detection datasets, alongside a zero-shot dataset. Our approach Stanceformer not only provides superior performance but also generalizes even to other domains, such as Aspect-based Sentiment Analysis. We make the code publicly available.\footnote{\scriptsize\url{https://github.com/kgarg8/Stanceformer}}

[Arxiv](https://arxiv.org/abs/2410.07083)