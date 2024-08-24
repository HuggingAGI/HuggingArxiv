# Open-FinLLMs：专为金融领域设计的开放多模态大型语言模型

发布时间：2024年08月20日

`LLM应用` `人工智能`

> Open-FinLLMs: Open Multimodal Large Language Models for Financial Applications

# 摘要

> 大型语言模型（LLM）虽在金融领域有所应用，但常因缺乏金融知识及处理多模态数据（如表格和时间序列）的能力而受限。为此，我们推出了\textit{Open-FinLLMs}系列金融LLM。首推的FinLLaMA，预训练于520亿金融语料，整合文本、表格及时序数据，全面嵌入金融知识。经573K金融指令微调后，FinLLaMA-instruct显著提升任务表现。FinLLaVA则是一款多模态LLM，通过1.43M图像-文本指令训练，擅长处理复杂金融数据。广泛评估显示，FinLLaMA在19和4个数据集的零-shot及few-shot场景中，均超越LLaMA3-8B、LLaMA3.1-8B及BloombergGPT。FinLLaMA-instruct在15个数据集上领先GPT-4及其他金融LLM。FinLLaVA在4项多模态任务中，对表格和图表的理解尤为出色。此外，FinLLaMA在交易模拟中展现出卓越的夏普比率，彰显其强大的金融应用潜力。我们将持续优化模型与基准，助力学术与产业创新。

> Large language models (LLMs) have advanced financial applications, yet they often lack sufficient financial knowledge and struggle with tasks involving multi-modal inputs like tables and time series data. To address these limitations, we introduce \textit{Open-FinLLMs}, a series of Financial LLMs. We begin with FinLLaMA, pre-trained on a 52 billion token financial corpus, incorporating text, tables, and time-series data to embed comprehensive financial knowledge. FinLLaMA is then instruction fine-tuned with 573K financial instructions, resulting in FinLLaMA-instruct, which enhances task performance. Finally, we present FinLLaVA, a multimodal LLM trained with 1.43M image-text instructions to handle complex financial data types. Extensive evaluations demonstrate FinLLaMA's superior performance over LLaMA3-8B, LLaMA3.1-8B, and BloombergGPT in both zero-shot and few-shot settings across 19 and 4 datasets, respectively. FinLLaMA-instruct outperforms GPT-4 and other Financial LLMs on 15 datasets. FinLLaVA excels in understanding tables and charts across 4 multimodal tasks. Additionally, FinLLaMA achieves impressive Sharpe Ratios in trading simulations, highlighting its robust financial application capabilities. We will continually maintain and improve our models and benchmarks to support ongoing innovation in academia and industry.

[Arxiv](https://arxiv.org/abs/2408.11878)