# 将自然语言与基于数据的自解释的 SQL 翻译相结合

发布时间：2024年11月05日

`LLM应用` `数据库`

> Grounding Natural Language to SQL Translation with Data-Based Self-Explanations

# 摘要

> 数据库的自然语言接口使非技术用户能够使用自然语言（NL）与数据进行交互。先进的方法，无论是利用神经序列到序列还是最近复杂的大规模语言模型，通常以端到端的方式实现 NL 到 SQL（NL2SQL）的翻译。然而，像人类一样，这些端到端的翻译模型可能并不总是在第一次尝试时生成最佳的 SQL 输出。在本文中，我们提出了 CycleSQL，这是一个为端到端翻译模型设计的迭代框架，旨在通过自我评估自主生成最佳输出。CycleSQL 的主要思想是引入查询结果的数据基础 NL 解释作为自我提供的反馈，并使用反馈迭代验证翻译的正确性，从而提高整体翻译准确性。进行了广泛的实验，包括定量和定性评估，通过将其应用于五个广泛使用的基准上的七个现有翻译模型来研究 CycleSQL。结果表明：1）CycleSQL 中引入的反馈循环可以持续提高现有模型的性能，特别是将 CycleSQL 应用于 RESDSQL 时，在 Spider 基准的验证集上获得了 82.0％（+2.6％）的翻译准确率，在测试集上获得了 81.6％（+3.2％）的翻译准确率；2）生成的 NL 解释也可以为用户提供有洞察力的信息，有助于理解翻译结果，从而提高 NL2SQL 翻译的可解释性。

> Natural Language Interfaces for Databases empower non-technical users to interact with data using natural language (NL). Advanced approaches, utilizing either neural sequence-to-sequence or more recent sophisticated large-scale language models, typically implement NL to SQL (NL2SQL) translation in an end-to-end fashion. However, like humans, these end-to-end translation models may not always generate the best SQL output on their first try. In this paper, we propose CycleSQL, an iterative framework designed for end-to-end translation models to autonomously generate the best output through self-evaluation. The main idea of CycleSQL is to introduce data-grounded NL explanations of query results as self-provided feedback, and use the feedback to validate the correctness of the translation iteratively, hence improving the overall translation accuracy. Extensive experiments, including quantitative and qualitative evaluations, are conducted to study CycleSQL by applying it to seven existing translation models on five widely used benchmarks. The results show that 1) the feedback loop introduced in CycleSQL can consistently improve the performance of existing models, and in particular, by applying CycleSQL to RESDSQL, obtains a translation accuracy of 82.0% (+2.6%) on the validation set, and 81.6% (+3.2%) on the test set of Spider benchmark; 2) the generated NL explanations can also provide insightful information for users, aiding in the comprehension of translation results and consequently enhancing the interpretability of NL2SQL translation.

[Arxiv](https://arxiv.org/abs/2411.02948)