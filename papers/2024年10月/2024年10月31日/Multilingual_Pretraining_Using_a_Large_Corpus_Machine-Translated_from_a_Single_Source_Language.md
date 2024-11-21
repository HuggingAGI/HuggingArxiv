# 利用从单一源语言进行大规模语料机器翻译来实现多语言预训练

发布时间：2024年10月31日

`LLM应用` `多语言模型`

> Multilingual Pretraining Using a Large Corpus Machine-Translated from a Single Source Language

# 摘要

> 英语作为一种资源丰富度极高的语言，能够用于预训练高质量的大型语言模型（LLMs）。但大多数其他语言并非如此，领先的 LLMs 在非英语语言上的表现欠佳，这或许是因为可用的多语言预训练语料库在质量和多样性上存在差距。在本研究中，我们发现从单一高质量源语言机器翻译而来的文本，能为多语言 LLMs 的预训练带来显著贡献。我们把高质量的英语网络数据集 FineWeb-Edu 翻译成法语、德语和西班牙语，形成最终 3000 亿标记的数据集，命名为 TransWeb-Edu，并基于此数据集从头预训练一个 13 亿参数的模型 CuatroLLM。在五个非英语推理任务中，我们发现，尽管使用的数据量比 Llama3.2 训练所用标记少了一个数量级，约为其 6％，但 CuatroLLM 能与使用封闭数据训练的诸如 Llama3.2 和 Gemma2 等最先进的多语言模型相媲美甚至更优。我们还进一步证实，通过进行额外的特定领域预训练，其规模不到 TransWeb-Edu 的 1％，CuatroLLM 在多语言推理方面超越了现有水平。为推动可重复性，我们在 hf.co/britllm/CuatroLLM 以开放许可的形式发布了我们的语料库、模型和训练流程。

> English, as a very high-resource language, enables the pretraining of high-quality large language models (LLMs). The same cannot be said for most other languages, as leading LLMs still underperform for non-English languages, likely due to a gap in the quality and diversity of the available multilingual pretraining corpora. In this work, we find that machine-translated text from a single high-quality source language can contribute significantly to the pretraining of multilingual LLMs. We translate FineWeb-Edu, a high-quality English web dataset, into French, German, and Spanish, resulting in a final 300B-token dataset, which we call TransWeb-Edu, and pretrain a 1.3B-parameter model, CuatroLLM, from scratch on this dataset. Across five non-English reasoning tasks, we show that CuatroLLM matches or outperforms state-of-the-art multilingual models trained using closed data, such as Llama3.2 and Gemma2, despite using an order of magnitude less data, such as about 6% of the tokens used for Llama3.2's training. We further demonstrate that with additional domain-specific pretraining, amounting to less than 1% of TransWeb-Edu, CuatroLLM surpasses the state of the art in multilingual reasoning. To promote reproducibility, we release our corpus, models, and training pipeline under open licenses at hf.co/britllm/CuatroLLM.

[Arxiv](https://arxiv.org/abs/2410.23956)