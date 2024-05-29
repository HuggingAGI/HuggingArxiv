# 大型语言模型（LLM）在算术推理中的应用：Prolog生成与排列探索

发布时间：2024年05月28日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）在解决数学问题上的应用，特别是通过思维链（CoT）方法和使用Prolog程序。它提出了一种新的方法，即利用LLM生成Prolog程序来解决数学问题，并进行了实验验证。这种方法的提出和实验结果的分析都是针对LLM在特定应用场景下的性能改进，因此属于LLM应用类别。` `人工智能`

> Arithmetic Reasoning with LLM: Prolog Generation & Permutation

# 摘要

> 通过思维链（CoT）方法，大型语言模型（LLMs）在解决小学数学问题上取得了显著成效。但CoT方法依赖LLM生成算术计算序列，易引发连锁错误。我们提出，LLM应专注于从问题描述中提取谓词和生成符号公式，利用外部代码解释器执行计算。我们探索了使用LLM生成Prolog程序解决数学问题，实验证明，在GSM8K基准上，基于Prolog的方法优于CoT，且适用于三种不同的LLM。鉴于Prolog对谓词和符号公式顺序的不敏感性，我们建议通过数据增强，对基本事实谓词进行排列，以增强LLM训练的鲁棒性。

> Instructing large language models (LLMs) to solve elementary school math problems has shown great success using Chain of Thought (CoT). However, the CoT approach relies on an LLM to generate a sequence of arithmetic calculations which can be prone to cascaded calculation errors. We hypothesize that an LLM should focus on extracting predicates and generating symbolic formulas from the math problem description so that the underlying calculation can be done via an external code interpreter. We investigate using LLM to generate Prolog programs to solve mathematical questions. Experimental results show that our Prolog-based arithmetic problem-solving outperforms CoT generation in the GSM8K benchmark across three distinct LLMs. In addition, given the insensitive ordering of predicates and symbolic formulas in Prolog, we propose to permute the ground truth predicates for more robust LLM training via data augmentation.

![大型语言模型（LLM）在算术推理中的应用：Prolog生成与排列探索](../../../paper_images/2405.17893/overview.drawio.pdf.png)

![大型语言模型（LLM）在算术推理中的应用：Prolog生成与排列探索](../../../paper_images/2405.17893/prolog.drawio.pdf.png)

![大型语言模型（LLM）在算术推理中的应用：Prolog生成与排列探索](../../../paper_images/2405.17893/permutation_ratio.png)

![大型语言模型（LLM）在算术推理中的应用：Prolog生成与排列探索](../../../paper_images/2405.17893/acc_check.png)

[Arxiv](https://arxiv.org/abs/2405.17893)