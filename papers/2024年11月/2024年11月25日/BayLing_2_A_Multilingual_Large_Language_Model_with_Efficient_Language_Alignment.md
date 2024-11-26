# BayLing 2：一款具备高效语言对齐功能的多语言大型语言模型

发布时间：2024年11月25日

`LLM应用` `语言模型` `多语言处理`

> BayLing 2: A Multilingual Large Language Model with Efficient Language Alignment

# 摘要

> 大型语言模型（LLMs）凭借强大的生成能力和海量知识，为日常生活中的各类任务助力。但这些能力主要集中于高资源语言，低资源语言的生成能力较弱，知识也相对有限。所以，增强 LLMs 的多语言能力对服务全球百余个语言社区极为关键。增强多语言能力的一个直观办法是为各种语言构建指令数据，然而为百余种语言构建指令数据成本极高。在本文中，我们推出了 BayLing 2，它通过语言对齐，将高资源语言的生成能力和知识高效地转移到低资源语言。为此，我们构建了一个包含 320 万条指令的数据集，涵盖高资源语言指令（中文和英语）以及 100 多种语言的跨语言指令，并基于该数据集进行指令调优，以推动语言间的能力转移。以 Llama 作为基础模型，我们开发了 BayLing-2-7B、BayLing-2-13B 和 BayLing-3-8B，并对 BayLing 进行了全面评估。在 100 多种语言的多语言翻译方面，BayLing 比类似规模的开源模型表现更优。在多语言知识和理解基准测试中，BayLing 在 20 多种低资源语言上有显著提升，展现出从高资源语言向低资源语言有效转移知识的能力。此外，英语基准测试结果显示，BayLing 在保持高资源语言高性能的同时，提升了低资源语言的性能。BayLing 的演示、主页、代码和模型均可获取。

> Large language models (LLMs), with their powerful generative capabilities and vast knowledge, empower various tasks in everyday life. However, these abilities are primarily concentrated in high-resource languages, leaving low-resource languages with weaker generative capabilities and relatively limited knowledge. Enhancing the multilingual capabilities of LLMs is therefore crucial for serving over 100 linguistic communities worldwide. An intuitive approach to enhance the multilingual capabilities would be to construct instruction data for various languages, but constructing instruction data for over 100 languages is prohibitively costly. In this paper, we introduce BayLing 2, which efficiently transfers generative capabilities and knowledge from high-resource languages to low-resource languages through language alignment. To achieve this, we constructed a dataset of 3.2 million instructions, comprising high-resource language instructions (Chinese and English) and cross-lingual instructions for 100+ languages and performed instruction tuning based on the dataset to facilitate the capability transfer between languages. Using Llama as the foundation model, we developed BayLing-2-7B, BayLing-2-13B, and BayLing-3-8B, and conducted a comprehensive evaluation of BayLing. For multilingual translation across 100+ languages, BayLing shows superior performance compared to open-source models of similar scale. For multilingual knowledge and understanding benchmarks, BayLing achieves significant improvements across over 20 low-resource languages, demonstrating its capability of effective knowledge transfer from high-resource to low-resource languages. Furthermore, results on English benchmarks indicate that BayLing maintains high performance in highresource languages while enhancing the performance in low-resource languages. Demo, homepage, code and models of BayLing are available.

[Arxiv](https://arxiv.org/abs/2411.16300)