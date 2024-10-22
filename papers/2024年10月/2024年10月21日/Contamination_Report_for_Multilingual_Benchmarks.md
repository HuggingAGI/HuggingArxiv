# 多语言基准污染报告

发布时间：2024年10月21日

`LLM理论` `人工智能`

> Contamination Report for Multilingual Benchmarks

# 摘要

> 基准污染是指在 LLM 的训练数据中混入了测试数据，这可能导致评估结果失真，难以准确衡量模型的真实能力。我们针对支持多语言的 LLM，研究了 7 个常用多语言基准的污染情况。通过黑盒测试，我们发现几乎所有被测模型都存在污染问题。这一发现有助于社区选择更可靠的多语言评估基准。

> Benchmark contamination refers to the presence of test datasets in Large Language Model (LLM) pre-training or post-training data. Contamination can lead to inflated scores on benchmarks, compromising evaluation results and making it difficult to determine the capabilities of models. In this work, we study the contamination of popular multilingual benchmarks in LLMs that support multiple languages. We use the Black Box test to determine whether $7$ frequently used multilingual benchmarks are contaminated in $7$ popular open and closed LLMs and find that almost all models show signs of being contaminated with almost all the benchmarks we test. Our findings can help the community determine the best set of benchmarks to use for multilingual evaluation.

[Arxiv](https://arxiv.org/abs/2410.16186)