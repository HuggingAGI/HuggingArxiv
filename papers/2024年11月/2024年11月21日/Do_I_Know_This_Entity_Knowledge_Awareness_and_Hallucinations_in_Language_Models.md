# 我是否了解此实体？语言模型中的知识感知与幻觉

发布时间：2024年11月21日

`LLM理论` `语言模型` `人工智能`

> Do I Know This Entity? Knowledge Awareness and Hallucinations in Language Models

# 摘要

> 大型语言模型中的幻觉现象普遍存在，然而对于模型产生幻觉的背后机制却了解甚少，这制约了我们解决此问题的能力。以稀疏自编码器作为解释工具，我们发现其中的关键在于实体识别，即模型会检测某个实体是否是其能够忆起相关事实的那种。稀疏自编码器揭示了表示空间中的有意义指向，能检测模型是否识别某个实体，比如检测它不了解某个运动员或某部电影。这意味着模型能够有自我认知，即关于自身能力的内部表征。这些指向具有因果关联：能够促使模型拒绝回答有关已知实体的问题，或者在原本拒绝的情况下对未知实体产生幻觉属性。我们证实，尽管稀疏自编码器是基于基础模型训练的，但这些指向对聊天模型的拒绝行为存在因果影响，表明聊天微调重新利用了这一现有机制。此外，我们对这些指向在模型中的作用机制进行了初步探究，发现它们会干扰下游头部的注意力，这些头部通常会将实体属性移至最终标记。

> Hallucinations in large language models are a widespread problem, yet the mechanisms behind whether models will hallucinate are poorly understood, limiting our ability to solve this problem. Using sparse autoencoders as an interpretability tool, we discover that a key part of these mechanisms is entity recognition, where the model detects if an entity is one it can recall facts about. Sparse autoencoders uncover meaningful directions in the representation space, these detect whether the model recognizes an entity, e.g. detecting it doesn't know about an athlete or a movie. This suggests that models can have self-knowledge: internal representations about their own capabilities. These directions are causally relevant: capable of steering the model to refuse to answer questions about known entities, or to hallucinate attributes of unknown entities when it would otherwise refuse. We demonstrate that despite the sparse autoencoders being trained on the base model, these directions have a causal effect on the chat model's refusal behavior, suggesting that chat finetuning has repurposed this existing mechanism. Furthermore, we provide an initial exploration into the mechanistic role of these directions in the model, finding that they disrupt the attention of downstream heads that typically move entity attributes to the final token.

[Arxiv](https://arxiv.org/abs/2411.14257)