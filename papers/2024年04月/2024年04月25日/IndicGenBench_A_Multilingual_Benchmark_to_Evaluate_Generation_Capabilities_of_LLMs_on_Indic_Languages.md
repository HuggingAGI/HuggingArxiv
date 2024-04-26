# IndicGenBench：一个多语言评估基准，旨在测试大型语言模型在印度语系上的文本生成能力。

发布时间：2024年04月25日

`分类：LLM应用` `机器翻译`

> IndicGenBench: A Multilingual Benchmark to Evaluate Generation Capabilities of LLMs on Indic Languages

# 摘要

> 随着大型语言模型（LLMs）在全球的普及，它们必须反映全球语言的多样性。印度，一个拥有14亿人口的语言丰富多样的国家，对于多语言LLM评估的研究至关重要。为此，我们推出了IndicGenBench——这是目前最大的基准测试，用于评估LLM在29种印度语言上的用户面向生成任务，这些语言涵盖了13种不同的文字系统和4个语言系。IndicGenBench包含多样化的生成任务，如跨语言摘要、机器翻译和跨语言问答。通过人工策划，它首次为许多未被充分代表的印度语言提供了多向并行评估数据，扩展了现有基准。我们在多种设置下对一系列专有和开源的LLMs进行了评估，包括GPT-3.5、GPT-4、PaLM-2、mT5、Gemma、BLOOM和LLaMA。尽管PaLM-2的最大模型在大多数任务上表现最佳，但所有语言与英语相比都有显著的性能差距，这表明我们仍需进一步研究，以开发更具包容性的多语言语言模型。IndicGenBench已在www.github.com/google-research-datasets/indic-gen-bench上线。

> As large language models (LLMs) see increasing adoption across the globe, it is imperative for LLMs to be representative of the linguistic diversity of the world. India is a linguistically diverse country of 1.4 Billion people. To facilitate research on multilingual LLM evaluation, we release IndicGenBench - the largest benchmark for evaluating LLMs on user-facing generation tasks across a diverse set 29 of Indic languages covering 13 scripts and 4 language families. IndicGenBench is composed of diverse generation tasks like cross-lingual summarization, machine translation, and cross-lingual question answering. IndicGenBench extends existing benchmarks to many Indic languages through human curation providing multi-way parallel evaluation data for many under-represented Indic languages for the first time. We evaluate a wide range of proprietary and open-source LLMs including GPT-3.5, GPT-4, PaLM-2, mT5, Gemma, BLOOM and LLaMA on IndicGenBench in a variety of settings. The largest PaLM-2 models performs the best on most tasks, however, there is a significant performance gap in all languages compared to English showing that further research is needed for the development of more inclusive multilingual language models. IndicGenBench is released at www.github.com/google-research-datasets/indic-gen-bench

[Arxiv](https://arxiv.org/abs/2404.16816)