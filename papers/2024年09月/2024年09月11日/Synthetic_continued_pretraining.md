# 合成延续预训练

发布时间：2024年09月11日

`LLM理论` `人工智能`

> Synthetic continued pretraining

# 摘要

> 通过在大规模互联网文本上预训练，语言模型积累了丰富的世界知识。然而，这种知识获取方式效率低下，模型需要从数百到数千种不同表述中学习单一事实。当将预训练模型应用于特定领域的小型文档时，这一问题尤为突出，因为每个事实可能仅出现一次或很少出现。为此，我们提出合成继续预训练的方法：利用小型领域语料库合成一个更易学习的大型语料库，并在其上进行继续预训练。我们通过 EntiGraph 算法实现这一构想，该算法从源文档中提取关键实体，并通过连接这些实体生成多样文本。这种合成继续预训练使模型能够在不接触源文档的情况下，回答相关问题并执行通用指令。若在推理时可访问源文档，我们的方法还能与检索增强生成相结合，进一步提升效果。为深入理解这一过程，我们构建了 EntiGraph 的数学模型，揭示了合成数据增强如何“重组”知识，从而实现更高效的学习。

> Pretraining on large-scale, unstructured internet text has enabled language models to acquire a significant amount of world knowledge. However, this knowledge acquisition is data-inefficient -- to learn a given fact, models must be trained on hundreds to thousands of diverse representations of it. This poses a challenge when adapting a pretrained model to a small corpus of domain-specific documents, where each fact may appear rarely or only once. We propose to bridge this gap with synthetic continued pretraining: using the small domain-specific corpus to synthesize a large corpus more amenable to learning, and then performing continued pretraining on the synthesized corpus. We instantiate this proposal with EntiGraph, a synthetic data augmentation algorithm that extracts salient entities from the source documents and then generates diverse text by drawing connections between the sampled entities. Synthetic continued pretraining using EntiGraph enables a language model to answer questions and follow generic instructions related to the source documents without access to them. If instead, the source documents are available at inference time, we show that the knowledge acquired through our approach compounds with retrieval-augmented generation. To better understand these results, we build a simple mathematical model of EntiGraph, and show how synthetic data augmentation can "rearrange" knowledge to enable more data-efficient learning.

[Arxiv](https://arxiv.org/abs/2409.07431)