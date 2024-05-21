# MHPP：深入挖掘语言模型超越基础代码生成的潜能与限制

发布时间：2024年05月18日

`LLM应用

这篇论文主要关注的是大型语言模型（LLMs）在代码生成能力评估方面的应用。作者通过分析现有的基准测试（如HumanEval和MBPP）的局限性，并提出了一个新的数据集Mostly Hard Python Problems（MHPP），旨在更全面地评估LLMs在代码生成方面的能力，特别是在理解规范、进行复杂推理及应用编程知识方面的能力。这一研究直接应用于LLMs的性能评估和改进，因此属于LLM应用分类。` `软件开发` `人工智能`

> MHPP: Exploring the Capabilities and Limitations of Language Models Beyond Basic Code Generation

# 摘要

> 大型语言模型（LLMs）的最新进展显著提升了函数级代码生成能力，如GPT-4在HumanEval上的通过率高达88.4%。但这引发了对现有基准是否能充分评估此类能力的疑问。我们研究了HumanEval和MBPP这两个常用基准，发现它们因质量、难度和粒度的限制，可能无法全面衡量LLMs的代码生成潜力。为此，我们推出了Mostly Hard Python Problems（MHPP）数据集，包含140个精心挑选的问题，专注于自然语言与代码推理的结合，以评估LLMs在理解规范、进行复杂推理及应用编程知识方面的能力。初步测试显示，许多在HumanEval上表现出色的模型在MHPP上表现不佳，揭示了LLMs的多方面局限性。我们相信，MHPP将有助于更深入地理解LLMs的能力与局限。相关数据集和代码已发布于https://github.com/SparksofAGI/MHPP。

> Recent advancements in large language models (LLMs) have greatly improved code generation, specifically at the function level. For instance, GPT-4 has achieved an 88.4% pass rate on HumanEval. However, this draws into question the adequacy of existing benchmarks in thoroughly assessing function-level code generation capabilities. Our study analyzed two common benchmarks, HumanEval and MBPP, and found that these might not thoroughly evaluate LLMs' code generation capacities due to limitations in quality, difficulty, and granularity. To resolve this, we introduce the Mostly Hard Python Problems (MHPP) dataset, consisting of 140 unique human-curated problems. By focusing on the combination of natural language and code reasoning, MHPP gauges LLMs' abilities to comprehend specifications and restrictions, engage in multi-step reasoning, and apply coding knowledge effectively. Initial evaluations of 22 LLMs using MHPP showed many high-performing models on HumanEval failed to achieve similar success on MHPP. Moreover, MHPP highlighted various previously undiscovered limitations within various LLMs, leading us to believe that it could pave the way for a better understanding of LLMs' capabilities and limitations. Dataset and code are available at https://github.com/SparksofAGI/MHPP.

[Arxiv](https://arxiv.org/abs/2405.11430)