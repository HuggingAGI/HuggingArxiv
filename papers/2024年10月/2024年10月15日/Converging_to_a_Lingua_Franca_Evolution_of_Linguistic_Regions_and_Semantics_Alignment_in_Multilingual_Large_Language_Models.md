# 多语言大型语言模型中，语言区域逐渐趋同，语义对齐也在不断演进，共同迈向通用语言的境界。

发布时间：2024年10月15日

`LLM理论` `语言学` `人工智能`

> Converging to a Lingua Franca: Evolution of Linguistic Regions and Semantics Alignment in Multilingual Large Language Models

# 摘要

> 大型语言模型 (LLMs) 在多语言环境中表现卓越。尽管研究表明 LLMs 能将一种语言的技能迁移到其他语言，但其内在机制仍不明确。我们发现，处理同一种语言时，LLMs 的神经元激活模式相似，揭示了关键语言区域的存在。此外，处理不同语言中语义相同的句子时，激活模式也相似，表明 LLMs 将不同语言的语义输入映射到一个“通用语”，即一个跨语言一致处理的共同语义空间。随着训练和模型规模的增加，这种语义对齐更加明显，激活模式也更加语言无关。关键语言神经元主要集中在 LLMs 的第一层和最后一层，且第一层的密度随训练增加。BLOOM 和 LLaMA2 的实验验证了这些发现，展示了多语言 LLMs 在训练和扩展过程中的结构演变。本文深入探讨了 LLMs 的内部机制，为提升其跨语言能力提供了基础。

> Large language models (LLMs) have demonstrated remarkable performance, particularly in multilingual contexts. While recent studies suggest that LLMs can transfer skills learned in one language to others, the internal mechanisms behind this ability remain unclear. We observed that the neuron activation patterns of LLMs exhibit similarities when processing the same language, revealing the existence and location of key linguistic regions. Additionally, we found that neuron activation patterns are similar when processing sentences with the same semantic meaning in different languages. This indicates that LLMs map semantically identical inputs from different languages into a "Lingua Franca", a common semantic latent space that allows for consistent processing across languages. This semantic alignment becomes more pronounced with training and increased model size, resulting in a more language-agnostic activation pattern. Moreover, we found that key linguistic neurons are concentrated in the first and last layers of LLMs, becoming denser in the first layers as training progresses. Experiments on BLOOM and LLaMA2 support these findings, highlighting the structural evolution of multilingual LLMs during training and scaling up. This paper provides insights into the internal workings of LLMs, offering a foundation for future improvements in their cross-lingual capabilities.

[Arxiv](https://arxiv.org/abs/2410.11718)