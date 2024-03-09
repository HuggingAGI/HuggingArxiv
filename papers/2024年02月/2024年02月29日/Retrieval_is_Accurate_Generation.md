# [检索，实现精准生成](https://arxiv.org/abs/2402.17532)

发布时间：2024年02月29日

`Agent`

> Retrieval is Accurate Generation

> 不同于传统标准语言模型从固定词汇库中选取符号进行文本生成，我们提出了一种创新方法，它能从关联文档集中智能选取情境相关的短语。然而，这一范式的核心难题在于如何设定训练准则，因为文本串可按多种方式进行切分，而每段内容又可能散落在大量文档之中。为此，我们建议首先运用语言学启发式规则初始化训练准则，并通过迭代自强化机制不断优化这个准则。大量实验结果显示，我们的模型不仅在一系列依赖专业知识的任务上超越了标准语言模型，在开放式文本生成的质量上也有显著提升。例如，在OpenbookQA任务上，相较于标准语言模型，我们的模型将准确率提高了12.8个百分点，而在开放式文本生成任务中，MAUVE评分则跃升至原来的近两倍。此外，令人瞩目的是，相比于其他几种基于检索增强的基准模型，我们的模型不仅表现最优，还拥有最低的响应延迟。因此，我们坚信检索辅助的生成方式更为精准，并期待这项工作能激发更多对该新型范式的研究探索。

> Standard language models generate text by selecting tokens from a fixed, finite, and standalone vocabulary. We introduce a novel method that selects context-aware phrases from a collection of supporting documents. One of the most significant challenges for this paradigm shift is determining the training oracles, because a string of text can be segmented in various ways and each segment can be retrieved from numerous possible documents. To address this, we propose to initialize the training oracles using linguistic heuristics and, more importantly, bootstrap the oracles through iterative self-reinforcement. Extensive experiments show that our model not only outperforms standard language models on a variety of knowledge-intensive tasks but also demonstrates improved generation quality in open-ended text generation. For instance, compared to the standard language model counterpart, our model raises the accuracy from 23.47% to 36.27% on OpenbookQA, and improves the MAUVE score from 42.61% to 81.58% in open-ended text generation. Remarkably, our model also achieves the best performance and the lowest latency among several retrieval-augmented baselines. In conclusion, we assert that retrieval is more accurate generation and hope that our work will encourage further research on this new paradigm shift.