# [面对大型语言模型，我们有必要重新审视和改进分词方法，以创造出更能满足其需求的高性能分词器。](https://arxiv.org/abs/2403.00417)

发布时间：2024年03月01日

`LLM应用`

> Rethinking Tokenization: Crafting Better Tokenizers for Large Language Models

> 分词技术对LM性能具有举足轻重的作用。本文追溯了分词技术从单词到子词的进化路径，剖析了它们如何权衡令牌与类型以提升模型适应性，同时把控复杂性。虽然BPE等子词分词技术已突破许多单词分词的局限，但面对非拉丁语系及多词表达（MWEs）的微妙理解时，仍面临挑战，且高度依赖大量训练数据和计算资源。本文认为，分词技术不应止步于技术手段，更应汲取人类语言处理的认知科学智慧。为此，本研究引用了“最小努力原则”，指出人类本能地追求减少认知负担，并探讨该原则对分词技术研发的价值。在此基础上，我们提出了一种适用于LLM的新颖分词模型——Less-is-Better (LiB)模型。LiB模型能自主习得整合了子词、单词与MWEs的综合词汇库，从而有效缩减令牌与类型的数目。比较评估结果显示，LiB分词器超越了现有单词和BPE分词器，开创了分词器研发的新途径，预示着未来基于认知科学原理的分词器将有望实现更高效率。

> Tokenization significantly influences language models(LMs)' performance. This paper traces the evolution of tokenizers from word-level to subword-level, analyzing how they balance tokens and types to enhance model adaptability while controlling complexity. Despite subword tokenizers like Byte Pair Encoding (BPE) overcoming many word tokenizer limitations, they encounter difficulties in handling non-Latin languages and depend heavily on extensive training data and computational resources to grasp the nuances of multiword expressions (MWEs). This article argues that tokenizers, more than mere technical tools, should drawing inspiration from the cognitive science about human language processing. This study then introduces the "Principle of Least Effort" from cognitive science, that humans naturally seek to reduce cognitive effort, and discusses the benefits of this principle for tokenizer development. Based on this principle, the paper proposes that the Less-is-Better (LiB) model could be a new approach for LLM tokenizer. The LiB model can autonomously learn an integrated vocabulary consisting of subwords, words, and MWEs, which effectively reduces both the numbers of tokens and types. Comparative evaluations show that the LiB tokenizer outperforms existing word and BPE tokenizers, presenting an innovative method for tokenizer development, and hinting at the possibility of future cognitive science-based tokenizers being more efficient.

[Arxiv](https://arxiv.org/abs/2403.00417)