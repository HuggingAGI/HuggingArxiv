# MHPP：深入挖掘语言模型超越基础代码生成的潜能与局限

发布时间：2024年05月18日

`LLM应用

理由：这篇论文主要关注于大型语言模型（LLMs）在代码生成能力评估方面的应用。它提出了一个新的数据集MHPP，用于更全面地评估LLMs在复杂规范理解、多步推理和编程知识运用方面的能力。这与LLM的理论研究不同，因为它不涉及模型内部的工作原理或算法改进，而是关注如何更好地应用和评估这些模型。因此，它属于LLM应用类别。` `软件开发` `人工智能`

> MHPP: Exploring the Capabilities and Limitations of Language Models Beyond Basic Code Generation

# 摘要

> 大型语言模型（LLMs）在函数级代码生成方面取得了显著进步，如GPT-4在HumanEval测试中通过率高达88.4%。但这引发了对现有基准是否足以全面评估LLMs代码生成能力的疑问。我们研究了HumanEval和MBPP两个基准，发现它们因质量、难度和粒度的限制，可能未能充分检验LLMs的潜力。为此，我们推出了Mostly Hard Python Problems（MHPP）数据集，包含140个精心设计的问题，专门评估LLMs在理解复杂规范、进行多步推理及有效运用编程知识方面的能力。初步测试表明，许多在HumanEval上表现出色的模型在MHPP上却遭遇挑战，揭示了LLMs的潜在局限。我们认为，MHPP有望深化我们对LLMs能力的理解。数据集和相关代码已公开于https://github.com/SparksofAGI/MHPP。

> Recent advancements in large language models (LLMs) have greatly improved code generation, specifically at the function level. For instance, GPT-4 has achieved an 88.4% pass rate on HumanEval. However, this draws into question the adequacy of existing benchmarks in thoroughly assessing function-level code generation capabilities. Our study analyzed two common benchmarks, HumanEval and MBPP, and found that these might not thoroughly evaluate LLMs' code generation capacities due to limitations in quality, difficulty, and granularity. To resolve this, we introduce the Mostly Hard Python Problems (MHPP) dataset, consisting of 140 unique human-curated problems. By focusing on the combination of natural language and code reasoning, MHPP gauges LLMs' abilities to comprehend specifications and restrictions, engage in multi-step reasoning, and apply coding knowledge effectively. Initial evaluations of 22 LLMs using MHPP showed many high-performing models on HumanEval failed to achieve similar success on MHPP. Moreover, MHPP highlighted various previously undiscovered limitations within various LLMs, leading us to believe that it could pave the way for a better understanding of LLMs' capabilities and limitations. Dataset and code are available at https://github.com/SparksofAGI/MHPP.

[Arxiv](https://arxiv.org/abs/2405.11430)