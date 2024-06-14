# 探究大型语言模型在仅依赖平行数据训练下的翻译潜能

发布时间：2024年06月13日

`LLM应用

这篇论文介绍了专门为加泰罗尼亚语平行数据设计的平行语言模型（PLUME），并探讨了这些模型在机器翻译任务中的性能。研究内容涉及模型的设计和性能分析，以及对跨语言表示的探索，这些都是大型语言模型在特定应用场景下的具体应用和优化。因此，这篇论文应归类于LLM应用。` `机器翻译` `语言模型`

> Investigating the translation capabilities of Large Language Models trained on parallel data only

# 摘要

> 近年来，大型语言模型（LLMs）在众多NLP任务中大放异彩，机器翻译也不例外。然而，过去的研究多依赖于迭代调整，如指令微调和持续预训练，对于仅依赖平行数据训练LLMs的挑战鲜有涉猎。本研究推出了PLUME（平行语言模型），一组包含三个20亿参数的模型，分别拥有32k、128k和256k的词汇量，专为加泰罗尼亚语平行数据量身打造。这些模型在16个监督翻译和56个零-shot翻译任务中与传统编码器-解码器架构不相上下。我们通过这些模型深入挖掘LLMs的翻译潜力，分析其性能、提示元素的影响及跨语言表示的奥秘。

> In recent years, Large Language Models (LLMs) have demonstrated exceptional proficiency across a broad spectrum of Natural Language Processing (NLP) tasks, including Machine Translation. However, previous methods predominantly relied on iterative processes such as instruction fine-tuning or continual pre-training, leaving unexplored the challenges of training LLMs solely on parallel data. In this work, we introduce PLUME (Parallel Language Model), a collection of three 2B LLMs featuring varying vocabulary sizes (32k, 128k, and 256k) trained exclusively on Catalan-centric parallel examples. These models perform comparably to previous encoder-decoder architectures on 16 supervised translation directions and 56 zero-shot ones. Utilizing this set of models, we conduct a thorough investigation into the translation capabilities of LLMs, probing their performance, the impact of the different elements of the prompt, and their cross-lingual representation space.

[Arxiv](https://arxiv.org/abs/2406.09140)