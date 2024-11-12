# 金标准：用于评估金融大型语言模型的全面双语基准

发布时间：2024年11月09日

`LLM应用` `语言模型`

> Golden Touchstone: A Comprehensive Bilingual Benchmark for Evaluating Financial Large Language Models

# 摘要

> 随着大型语言模型在金融领域变得越来越普遍，迫切需要一种标准化的方法来全面评估其性能。然而，现有的金融基准通常存在语言和任务覆盖范围有限的问题，以及诸如低质量数据集和对 LLM 评估适应性不足等挑战。为了解决这些限制，我们提出了“黄金试金石”，这是第一个针对金融 LLM 的综合双语基准，它整合了来自中文和英文的具有代表性的数据集，涵盖了八个核心金融 NLP 任务。这个基准是从广泛的开源数据收集和特定行业需求开发而来，包括各种金融任务，旨在全面评估模型的语言理解和生成能力。通过对基准上的主要模型（如 GPT-4o、Llama3、FinGPT 和 FinMA）进行比较分析，我们揭示了它们在处理复杂金融信息方面的优势和局限性。此外，我们开源了 Touchstone-GPT，这是一个通过持续预训练和金融指令调整训练的金融 LLM，它在双语基准上表现出色，但在特定任务中仍存在局限性。这项研究不仅为金融大型语言模型提供了实用的评估工具，还指导了未来研究的发展和优化。“黄金试金石”的源代码和 Touchstone-GPT 的模型权重已在 url{https://github.com/IDEA-FinAI/Golden-Touchstone}公开，为 FinLLM 的不断发展做出贡献，并促进了这一关键领域的进一步研究。

> As large language models become increasingly prevalent in the financial sector, there is a pressing need for a standardized method to comprehensively assess their performance. However, existing finance benchmarks often suffer from limited language and task coverage, as well as challenges such as low-quality datasets and inadequate adaptability for LLM evaluation. To address these limitations, we propose "Golden Touchstone", the first comprehensive bilingual benchmark for financial LLMs, which incorporates representative datasets from both Chinese and English across eight core financial NLP tasks. Developed from extensive open source data collection and industry-specific demands, this benchmark includes a variety of financial tasks aimed at thoroughly assessing models' language understanding and generation capabilities. Through comparative analysis of major models on the benchmark, such as GPT-4o Llama3, FinGPT and FinMA, we reveal their strengths and limitations in processing complex financial information. Additionally, we open-sourced Touchstone-GPT, a financial LLM trained through continual pre-training and financial instruction tuning, which demonstrates strong performance on the bilingual benchmark but still has limitations in specific tasks.This research not only provides the financial large language models with a practical evaluation tool but also guides the development and optimization of future research. The source code for Golden Touchstone and model weight of Touchstone-GPT have been made publicly available at \url{https://github.com/IDEA-FinAI/Golden-Touchstone}, contributing to the ongoing evolution of FinLLMs and fostering further research in this critical area.

[Arxiv](https://arxiv.org/abs/2411.06272)