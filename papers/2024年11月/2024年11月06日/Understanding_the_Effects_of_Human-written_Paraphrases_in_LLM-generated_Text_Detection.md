# 理解人类编写的释义在 LLM 生成的文本检测中的影响

发布时间：2024年11月06日

`LLM应用` `模型检测`

> Understanding the Effects of Human-written Paraphrases in LLM-generated Text Detection

# 摘要

> 自然语言生成随着大型语言模型（LLM）的出现而迅速发展。虽然它们的使用引起了公众的极大关注，但读者了解一段文本是否是 LLM 生成的很重要。这就带来了构建能够自动检测 LLM 生成文本的模型的需求，以减轻此类内容的潜在负面结果。现有的 LLM 生成检测器在区分 LLM 生成和人工编写的文本方面表现出有竞争力的性能，但当考虑改写的文本时，这种性能可能会恶化。在这项研究中，我们设计了一种新的数据收集策略来收集人类和 LLM 改写集合（HLPC），这是第一个包含人工编写的文本和改写，以及 LLM 生成的文本和改写的数据集。为了了解人工编写的改写对最先进的 LLM 生成文本检测器 OpenAI RoBERTa 和水印检测器性能的影响，我们进行了分类实验，其中包括人工编写的改写、来自 GPT 和 OPT 的带水印和不带水印的 LLM 生成文档，以及来自 DIPPER 和 BART 的 LLM 生成的改写。结果表明，包含人工编写的改写对 LLM 生成的检测器性能有显著影响，提高了 TPR@1%FPR，但可能会在 AUROC 和准确性方面进行权衡。

> Natural Language Generation has been rapidly developing with the advent of large language models (LLMs). While their usage has sparked significant attention from the general public, it is important for readers to be aware when a piece of text is LLM-generated. This has brought about the need for building models that enable automated LLM-generated text detection, with the aim of mitigating potential negative outcomes of such content. Existing LLM-generated detectors show competitive performances in telling apart LLM-generated and human-written text, but this performance is likely to deteriorate when paraphrased texts are considered. In this study, we devise a new data collection strategy to collect Human & LLM Paraphrase Collection (HLPC), a first-of-its-kind dataset that incorporates human-written texts and paraphrases, as well as LLM-generated texts and paraphrases. With the aim of understanding the effects of human-written paraphrases on the performance of state-of-the-art LLM-generated text detectors OpenAI RoBERTa and watermark detectors, we perform classification experiments that incorporate human-written paraphrases, watermarked and non-watermarked LLM-generated documents from GPT and OPT, and LLM-generated paraphrases from DIPPER and BART. The results show that the inclusion of human-written paraphrases has a significant impact of LLM-generated detector performance, promoting TPR@1%FPR with a possible trade-off of AUROC and accuracy.

[Arxiv](https://arxiv.org/abs/2411.03806)