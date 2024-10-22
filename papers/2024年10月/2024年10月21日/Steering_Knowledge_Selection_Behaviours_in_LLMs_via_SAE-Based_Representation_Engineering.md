# 利用 SAE 表示工程，精准引导 LLM 中的知识选择行为

发布时间：2024年10月21日

`LLM理论` `人工智能` `问答系统`

> Steering Knowledge Selection Behaviours in LLMs via SAE-Based Representation Engineering

# 摘要

> 大型语言模型 (LLM) 能够存储大量事实知识，但其参数知识可能与上下文信息冲突，导致依赖过时或错误信息。我们发现，LLM 能在中间层识别知识冲突信号，从而在推理时进行干预。为此，我们提出了 \textsc{SpARE}，一种无需训练的表示工程方法，利用预训练稀疏自编码器 (SAE) 控制 LLM 的知识选择行为。实验显示，\textsc{SpARE} 在开放域问答任务中有效解决知识冲突，性能优于现有方法。

> Large language models (LLMs) can store a significant amount of factual knowledge in their parameters. However, their parametric knowledge may conflict with the information provided in the context -- this phenomenon, known as \emph{context-memory knowledge conflicts}, can lead to undesirable model behaviour, such as reliance on outdated or incorrect information. Analysing the internal activations of LLMs, we find that they can internally register the signals of knowledge conflict at mid-layers. Such signals allow us to detect whether a knowledge conflict occurs and use \emph{inference-time} intervention strategies to resolve it. In this work, we propose \textsc{SpARE}, a \emph{training-free} representation engineering method that uses pre-trained sparse auto-encoders (SAEs) to control the knowledge selection behaviour of LLMs. \textsc{SpARE} identifies the functional features that control the knowledge selection behaviours and applies them to edit the internal activations of LLMs at inference time. Our experimental results show that \textsc{SpARE} can effectively control the usage of either knowledge source to resolve knowledge conflict in open-domain question-answering tasks, surpassing existing representation engineering methods ($+10\%$) as well as contrastive decoding methods ($+15\%$).

[Arxiv](https://arxiv.org/abs/2410.15999)