# IndicGenBench：一项多语言评估基准，旨在衡量大型语言模型在印度诸语言上的表现力。

发布时间：2024年04月25日

`LLM应用` `机器翻译`

> IndicGenBench: A Multilingual Benchmark to Evaluate Generation Capabilities of LLMs on Indic Languages

# 摘要

> 随着大型语言模型（LLMs）在全球的广泛应用，确保它们能够体现全球语言多样性变得至关重要。印度，一个拥有14亿人口的多语言国家，为我们提供了丰富的研究素材。为了推动多语言LLM评估研究，我们推出了IndicGenBench——这是目前规模最大的基准测试平台，旨在评估LLM在29种印度语言上的用户生成任务表现，这些语言涵盖了13种不同的文字系统和4个语言系。IndicGenBench包含多种生成任务，包括跨语言摘要、机器翻译和跨语言问答等。该平台通过人工精选，首次为多种印度语言提供了多维度的并行评估数据，极大地扩展了现有基准测试的覆盖范围。我们在多种场景下对一系列商业和开源的LLMs进行了评估，包括GPT-3.5、GPT-4、PaLM-2、mT5、Gemma、BLOOM和LLaMA。其中，PaLM-2的最大模型在大多数任务上表现最为出色。然而，所有印度语言与英语相比仍有较大的性能差距，这表明我们仍需深化研究，以发展出更加全面和包容的多语言语言模型。IndicGenBench目前已在www.github.com/google-research-datasets/indic-gen-bench上线。

> As large language models (LLMs) see increasing adoption across the globe, it is imperative for LLMs to be representative of the linguistic diversity of the world. India is a linguistically diverse country of 1.4 Billion people. To facilitate research on multilingual LLM evaluation, we release IndicGenBench - the largest benchmark for evaluating LLMs on user-facing generation tasks across a diverse set 29 of Indic languages covering 13 scripts and 4 language families. IndicGenBench is composed of diverse generation tasks like cross-lingual summarization, machine translation, and cross-lingual question answering. IndicGenBench extends existing benchmarks to many Indic languages through human curation providing multi-way parallel evaluation data for many under-represented Indic languages for the first time. We evaluate a wide range of proprietary and open-source LLMs including GPT-3.5, GPT-4, PaLM-2, mT5, Gemma, BLOOM and LLaMA on IndicGenBench in a variety of settings. The largest PaLM-2 models performs the best on most tasks, however, there is a significant performance gap in all languages compared to English showing that further research is needed for the development of more inclusive multilingual language models. IndicGenBench is released at www.github.com/google-research-datasets/indic-gen-bench

[Arxiv](https://arxiv.org/abs/2404.16816)