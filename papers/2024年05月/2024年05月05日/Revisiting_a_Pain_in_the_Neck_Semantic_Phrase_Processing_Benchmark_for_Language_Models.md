# 再次聚焦“颈部之痛”：为语言模型设立的语义短语处理性能评估标准

发布时间：2024年05月05日

`LLM应用` `机器学习`

> Revisiting a Pain in the Neck: Semantic Phrase Processing Benchmark for Language Models

# 摘要

> 我们推出了 LexBench，一套全面的评估工具，旨在对语言模型（LMs）进行十项语义短语处理任务的测试。与过往研究相比，本工作首次提出一个比较视角下的框架，用于模拟一般语义短语（例如词汇搭配）以及三种更细致的语义短语类型：成语表达、名词复合词和动词结构。借助我们的基准测试，我们对15种不同架构和参数规模的LMs在分类、提取和解释任务中的表现进行了评估。实验首先证实了规模法则，发现大型模型在大多数任务上的表现确实优于小型模型。其次，通过语义关系分类的进一步探索，我们发现少数镜头LMs在任务上仍然未能赶超常规的微调模型。再次，通过人工评估，我们发现顶尖模型在处理语义短语方面的性能已接近人类水平。我们的基准测试结果将为未来旨在提升LMs在语义短语理解上的通用能力的研究提供参考。相关源代码和数据已在 https://github.com/jacklanda/LexBench 上发布。

> We introduce LexBench, a comprehensive evaluation suite enabled to test language models (LMs) on ten semantic phrase processing tasks. Unlike prior studies, it is the first work to propose a framework from the comparative perspective to model the general semantic phrase (i.e., lexical collocation) and three fine-grained semantic phrases, including idiomatic expression, noun compound, and verbal construction. Thanks to \ourbenchmark, we assess the performance of 15 LMs across model architectures and parameter scales in classification, extraction, and interpretation tasks. Through the experiments, we first validate the scaling law and find that, as expected, large models excel better than the smaller ones in most tasks. Second, we investigate further through the scaling semantic relation categorization and find that few-shot LMs still lag behind vanilla fine-tuned models in the task. Third, through human evaluation, we find that the performance of strong models is comparable to the human level regarding semantic phrase processing. Our benchmarking findings can serve future research aiming to improve the generic capability of LMs on semantic phrase comprehension. Our source code and data are available at https://github.com/jacklanda/LexBench

[Arxiv](https://arxiv.org/abs/2405.02861)