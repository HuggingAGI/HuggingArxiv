# AAVENUE 基准测试：揭示 LLM 在 AAVE 语境下 NLU 任务的偏差

发布时间：2024年08月27日

`LLM应用` `语言学`

> AAVENUE: Detecting LLM Biases on NLU Tasks in AAVE via a Novel Benchmark

# 摘要

> 为了确保自然语言处理系统的包容性，关键在于检测非洲裔美国人白话英语（AAVE）在自然语言理解（NLU）中的偏见。为此，我们推出了AAVENUE，这是一个评估大型语言模型（LLM）在AAVE和标准美国英语（SAE）中NLU任务性能的基准。AAVENUE通过灵活的LLM翻译方法，改进了现有基准，提升了关键任务的翻译质量。我们通过五种流行LLM和多项指标（如流畅性和连贯性）进行了对比测试，并邀请AAVE母语者验证翻译的真实性。结果显示，LLM在SAE任务上的表现优于AAVE，揭示了潜在偏见，强调了开发更包容NLP模型的迫切性。我们的工作已在GitHub开源，并在https://aavenue.live网站上展示。

> Detecting biases in natural language understanding (NLU) for African American Vernacular English (AAVE) is crucial to developing inclusive natural language processing (NLP) systems. To address dialect-induced performance discrepancies, we introduce AAVENUE ({AAVE} {N}atural Language {U}nderstanding {E}valuation), a benchmark for evaluating large language model (LLM) performance on NLU tasks in AAVE and Standard American English (SAE). AAVENUE builds upon and extends existing benchmarks like VALUE, replacing deterministic syntactic and morphological transformations with a more flexible methodology leveraging LLM-based translation with few-shot prompting, improving performance across our evaluation metrics when translating key tasks from the GLUE and SuperGLUE benchmarks. We compare AAVENUE and VALUE translations using five popular LLMs and a comprehensive set of metrics including fluency, BARTScore, quality, coherence, and understandability. Additionally, we recruit fluent AAVE speakers to validate our translations for authenticity. Our evaluations reveal that LLMs consistently perform better on SAE tasks than AAVE-translated versions, underscoring inherent biases and highlighting the need for more inclusive NLP models. We have open-sourced our source code on GitHub and created a website to showcase our work at https://aavenue.live.

[Arxiv](https://arxiv.org/abs/2408.14845)