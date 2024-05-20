# 语言模型利用概率差异进行自我评估。

发布时间：2024年05月16日

`LLM理论

这篇论文主要探讨了大型语言模型（LLMs）的性能评估方法，特别是通过提出的ProbDiff自我评估方法来衡量不同LLMs的能力。这种方法不需要依赖外部模型，如GPT-4，而是通过分析模型对同一查询的初始与修订答案的概率差异来进行评估。研究内容涉及LLMs的理论性能评估，因此属于LLM理论分类。` `模型评估`

> Language Models can Evaluate Themselves via Probability Discrepancy

# 摘要

> 本文首先揭示了，当大型语言模型（LLMs）面对查询时，技能更高的模型给出的答案概率分布更为均匀。基于此，我们创新性地提出了ProbDiff自我评估方法，用以衡量不同LLMs的效能，无需依赖外部模型如GPT-4。该方法通过比较LLMs对同一查询的初始与修订答案的概率差异来评估其能力，差异越大，能力越弱。研究表明，ProbDiff在翻译、摘要及我们独创的“小红书”博客写作等NLG任务，以及AlignBench、MT-Bench和AlpacaEval等LLM评估基准上，其表现与GPT-4评估结果相当，适用于各类规模的LLMs。

> In this paper, we initiate our discussion by demonstrating how Large Language Models (LLMs), when tasked with responding to queries, display a more even probability distribution in their answers if they are more adept, as opposed to their less skilled counterparts. Expanding on this foundational insight, we propose a new self-evaluation method ProbDiff for assessing the efficacy of various LLMs. This approach obviates the necessity for an additional evaluation model or the dependence on external, proprietary models like GPT-4 for judgment. It uniquely utilizes the LLMs being tested to compute the probability discrepancy between the initial response and its revised versions. A higher discrepancy for a given query between two LLMs indicates a relatively weaker capability. Our findings reveal that ProbDiff achieves results on par with those obtained from evaluations based on GPT-4, spanning a range of scenarios that include natural language generation (NLG) tasks such as translation, summarization, and our proposed Xiaohongshu blog writing task, and benchmarks for LLM evaluation like AlignBench, MT-Bench, and AlpacaEval, across LLMs of varying magnitudes.

[Arxiv](https://arxiv.org/abs/2405.10516)