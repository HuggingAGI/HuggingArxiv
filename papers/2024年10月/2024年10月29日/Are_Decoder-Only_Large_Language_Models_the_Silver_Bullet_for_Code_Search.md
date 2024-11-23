# 仅解码器的大型语言模型会是解决代码搜索问题的万能良方吗？

发布时间：2024年10月29日

`LLM应用` `软件开发` `代码搜索`

> Are Decoder-Only Large Language Models the Silver Bullet for Code Search?

# 摘要

> 代码搜索对于代码复用意义重大，能助力开发者高效找到相关代码片段。当下的方法依赖基于编码器的模型，此类模型存在泛化能力欠佳、输入长度受限等缺陷。仅解码器的大型语言模型（LLMs），凭借其广泛的预训练、较大的规模以及更长的输入能力，为这些问题带来了潜在的解决办法，然而它们在代码搜索中的有效性尚未得到充分挖掘。为弥补这一空缺，我们的研究首次对仅解码器的LLMs用于代码搜索展开了系统探索。我们运用两种微调方式、两个数据集（CSN 和 CoSQA$^+$）以及三种模型规模，对九个前沿的仅解码器模型予以评估。我们的发现表明，微调后的 CodeGemma 明显优于像 UniXcoder 这样的仅编码器模型，在 CSN 上的 MRR 提升了 5.57%，在 CoSQA$^+$上的 MAP 相比零样本的 UniXcoder 提高了 49.6%。这些结果彰显了仅解码器模型的出色性能和适应性。另外，我们就优化这些用于代码搜索的模型提供了宝贵的看法，涵盖模型选择、微调方法、训练数据以及模型规模等方面，并探讨了它们的长处和不足。

> Code search is crucial for code reuse, enabling developers to efficiently locate relevant snippets. Current methods rely on encoder-based models, which suffer from limitations such as poor generalization and restricted input lengths. Decoder-only large language models (LLMs), with their extensive pre-training, larger size, and longer input capabilities, offer potential solutions to these issues, yet their effectiveness in code search remains underexplored. To fill this gap, our study presents the first systematic exploration of decoder-only LLMs for code search. We evaluate nine state-of-the-art decoder-only models using two fine-tuning methods, two datasets (CSN and CoSQA$^+$), and three model sizes. Our findings reveal that fine-tuned CodeGemma significantly outperforms encoder-only models like UniXcoder, achieving a 5.57% improvement in MRR on CSN and a 49.6% increase in MAP on CoSQA$^+$ compared to zero-shot UniXcoder. These results highlight the superior performance and adaptability of decoder-only models. Additionally, we provide valuable insights into optimizing these models for code search, covering aspects such as model selection, fine-tuning methods, training data, and model size, and discussing their strengths and limitations.

[Arxiv](https://arxiv.org/abs/2410.22240)