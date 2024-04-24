# 配置数据打印设备，以提升英语至乌克兰语的机器翻译质量。

发布时间：2024年04月23日

`分类：LLM应用` `机器翻译`

> Setting up the Data Printer with Improved English to Ukrainian Machine Translation

# 摘要

> 为了打造乌克兰语的大型语言模型，我们需扩充语料库，纳入大量以自然语言表述的新算法任务。鉴于英语表述的任务执行案例众多，借助高效的翻译系统，我们的社群将能够更迅速地构建数据集。为此，我们提出了一种构建翻译系统的方案：首先，利用3百万对乌克兰语和英语句子的并行语料，对一个大型预训练语言模型进行有监督的微调；其次，从另一个更优质的数据集中，通过k折交叉验证筛选出的17,000个样本进行第二阶段训练。我们研发的仅解码器模型Dragoman，在FLORES开发测试集上超越了之前所有最先进的编码器-解码器模型的性能。

> To build large language models for Ukrainian we need to expand our corpora with large amounts of new algorithmic tasks expressed in natural language. Examples of task performance expressed in English are abundant, so with a high-quality translation system our community will be enabled to curate datasets faster. To aid this goal, we introduce a recipe to build a translation system using supervised finetuning of a large pretrained language model with a noisy parallel dataset of 3M pairs of Ukrainian and English sentences followed by a second phase of training using 17K examples selected by k-fold perplexity filtering on another dataset of higher quality. Our decoder-only model named Dragoman beats performance of previous state of the art encoder-decoder models on the FLORES devtest set.

[Arxiv](https://arxiv.org/abs/2404.15196)