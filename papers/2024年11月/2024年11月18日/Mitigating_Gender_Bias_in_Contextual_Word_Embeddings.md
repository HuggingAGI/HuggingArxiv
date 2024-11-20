# 缓解上下文词嵌入中的性别偏差

发布时间：2024年11月18日

`LLM应用` `机器学习`

> Mitigating Gender Bias in Contextual Word Embeddings

# 摘要

> 词嵌入在处理众多自然语言处理相关任务时，成果斐然。然而，词嵌入也会捕捉到社会中常见的刻板偏见，从而影响其在下游任务中的预测表现。尽管针对静态嵌入已提出了多种技术\cite{bolukbasi2016man, zhao2018learning}，也有批评之声\cite{gonen2019lipstick}，但致力于减轻上下文嵌入偏差的工作却寥寥无几。本文为 MLM（掩码语言模型）提出了全新的目标函数，能大幅减轻上下文嵌入中的性别偏差，同时保障下游任务的性能。鉴于以往测量上下文嵌入偏差的工作在规范推理方面有所欠缺，我们还提出了新颖的评估指标，这些指标简单直接，且与我们去偏的初衷相符。我们还给出了静态嵌入去偏的新方法，并通过大量的分析和实验提供了经验证据，解释了为何静态嵌入偏差的主要根源在于刻板名字的存在，而非性别词本身。除非另有说明，所有研究的实验和嵌入均为英语。\citep{bender2011achieving}。

> Word embeddings have been shown to produce remarkable results in tackling a vast majority of NLP related tasks. Unfortunately, word embeddings also capture the stereotypical biases that are prevalent in society, affecting the predictive performance of the embeddings when used in downstream tasks. While various techniques have been proposed \cite{bolukbasi2016man, zhao2018learning} and criticized\cite{gonen2019lipstick} for static embeddings, very little work has focused on mitigating bias in contextual embeddings. In this paper, we propose a novel objective function for MLM(Masked-Language Modeling) which largely mitigates the gender bias in contextual embeddings and also preserves the performance for downstream tasks. Since previous works on measuring bias in contextual embeddings lack in normative reasoning, we also propose novel evaluation metrics that are straight-forward and aligned with our motivations in debiasing. We also propose new methods for debiasing static embeddings and provide empirical proof via extensive analysis and experiments, as to why the main source of bias in static embeddings stems from the presence of stereotypical names rather than gendered words themselves. All experiments and embeddings studied are in English, unless otherwise specified.\citep{bender2011achieving}.

[Arxiv](https://arxiv.org/abs/2411.12074)