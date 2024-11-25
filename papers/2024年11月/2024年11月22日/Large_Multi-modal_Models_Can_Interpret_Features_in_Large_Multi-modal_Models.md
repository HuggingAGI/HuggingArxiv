# 大型多模态模型能够阐释其自身内部的特征。

发布时间：2024年11月22日

`LLM应用` `人工智能` `模型分析`

> Large Multi-modal Models Can Interpret Features in Large Multi-modal Models

# 摘要

> 近期，大型多模态模型（LMMs）的进步在学术和工业领域均取得重大突破。随之而来的一个问题是，身为人类的我们怎样去理解其内部神经表征。本文率先迈出一步来解决此问题，提出了一个通用框架以识别和阐释 LMMs 内部的语义。具体而言，1）首先运用稀疏自编码器（SAE）将表征拆解为人类能理解的特征。2）接着提出一个自动解释框架，让 LMMs 自身去解释在 SAE 中习得的开放语义特征。我们借助此框架对 LLaVA-NeXT-8B 模型进行分析，采用的是 LLaVA-OV-72B 模型，证明这些特征能够有效引导模型的行为。我们的成果有助于更深入地明白 LMMs 在特定任务（如 EQ 测试）中表现出色的缘由，也阐明了其错误的本质以及潜在的纠正策略。这些发现为 LMMs 的内部机制带来新的认识，并暗示了与人类大脑认知过程的相似性。

> Recent advances in Large Multimodal Models (LMMs) lead to significant breakthroughs in both academia and industry. One question that arises is how we, as humans, can understand their internal neural representations. This paper takes an initial step towards addressing this question by presenting a versatile framework to identify and interpret the semantics within LMMs. Specifically, 1) we first apply a Sparse Autoencoder(SAE) to disentangle the representations into human understandable features. 2) We then present an automatic interpretation framework to interpreted the open-semantic features learned in SAE by the LMMs themselves. We employ this framework to analyze the LLaVA-NeXT-8B model using the LLaVA-OV-72B model, demonstrating that these features can effectively steer the model's behavior. Our results contribute to a deeper understanding of why LMMs excel in specific tasks, including EQ tests, and illuminate the nature of their mistakes along with potential strategies for their rectification. These findings offer new insights into the internal mechanisms of LMMs and suggest parallels with the cognitive processes of the human brain.

[Arxiv](https://arxiv.org/abs/2411.14982)