# 用自注意力网络实现确定逻辑程序的推导

发布时间：2024年10月15日

`LLM理论` `人工智能` `逻辑推理`

> Implementing Derivations of Definite Logic Programs with Self-Attention Networks

# 摘要

> 本文提出，通过自注意力网络可以实现一种简化的逻辑推理。我们旨在证明，基于变换器的大型语言模型 (LLM) 具备逻辑推理能力。通过分析变换器核心组件——自注意力网络，我们将揭示 LLM 的这一潜力。我们的方法不依赖自然语言的语义，而是基于逻辑推理的操作。研究表明，结合前馈网络 (FFN) 的自注意力网络分层结构，能够实现一类逻辑公式的自上而下和自下而上的推导。这表明 LLM 内在具备逻辑推理的潜力。

> In this paper we propose that a restricted version of logical inference can be implemented with self-attention networks. We are aiming at showing that LLMs (Large Language Models) constructed with transformer networks can make logical inferences. We would reveal the potential of LLMs by analyzing self-attention networks, which are main components of transformer networks. Our approach is not based on semantics of natural languages but operations of logical inference. %point of view. We show that hierarchical constructions of self-attention networks with feed forward networks (FFNs) can implement top-down derivations for a class of logical formulae. We also show bottom-up derivations are also implemented for the same class. We believe that our results show that LLMs implicitly have the power of logical inference.

[Arxiv](https://arxiv.org/abs/2410.11396)