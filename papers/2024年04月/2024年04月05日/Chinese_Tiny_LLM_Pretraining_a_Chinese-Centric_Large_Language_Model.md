# 中文迷你巨模：打造一个专注于中文的超大语言预训练模型

发布时间：2024年04月05日

`LLM理论` `语言模型` `中文处理`

> Chinese Tiny LLM: Pretraining a Chinese-Centric Large Language Model

# 摘要

> 本研究推出了CT-LLM，一个2B规模的大型中文语言模型，它标志着在构建语言模型时将中文置于核心地位的重要转变。CT-LLM从无到有，打破常规，主要基于中文文本数据，涵盖了1200亿个token的庞大语料库，包括800亿个中文token、300亿个英文token和100亿个代码token。这种策略性的数据组合，使得模型在理解和处理中文方面表现出色，并通过对齐技术进一步提升了这一能力。CT-LLM在CHC-Bench测试中表现卓越，不仅在中文任务上游刃有余，也在SFT中展现了其英文处理的高超技巧。本研究颠覆了以往以英文语料库为主训练LLM，再适配其他语言的传统模式，为LLM的训练方法开辟了新天地。我们开源了从数据处理到模型训练的全过程，包括MAP-CC的详细数据预处理流程、精心挑选的多学科中文难题基准CHC-Bench，以及2B规模的CT-LLM，旨在激励学术界和工业界的深入探索与创新，推动语言模型向更加全面和多样化的方向发展。

> In this study, we introduce CT-LLM, a 2B large language model (LLM) that illustrates a pivotal shift towards prioritizing the Chinese language in developing LLMs. Uniquely initiated from scratch, CT-LLM diverges from the conventional methodology by primarily incorporating Chinese textual data, utilizing an extensive corpus of 1,200 billion tokens, including 800 billion Chinese tokens, 300 billion English tokens, and 100 billion code tokens. This strategic composition facilitates the model's exceptional proficiency in understanding and processing Chinese, a capability further enhanced through alignment techniques. Demonstrating remarkable performance on the CHC-Bench, CT-LLM excels in Chinese language tasks, and showcases its adeptness in English through SFT. This research challenges the prevailing paradigm of training LLMs predominantly on English corpora and then adapting them to other languages, broadening the horizons for LLM training methodologies. By open-sourcing the full process of training a Chinese LLM, including a detailed data processing procedure with the obtained Massive Appropriate Pretraining Chinese Corpus (MAP-CC), a well-chosen multidisciplinary Chinese Hard Case Benchmark (CHC-Bench), and the 2B-size Chinese Tiny LLM (CT-LLM), we aim to foster further exploration and innovation in both academia and industry, paving the way for more inclusive and versatile language models.

![中文迷你巨模：打造一个专注于中文的超大语言预训练模型](../../../paper_images/2404.04167/x1.png)

![中文迷你巨模：打造一个专注于中文的超大语言预训练模型](../../../paper_images/2404.04167/x2.png)

![中文迷你巨模：打造一个专注于中文的超大语言预训练模型](../../../paper_images/2404.04167/x3.png)

![中文迷你巨模：打造一个专注于中文的超大语言预训练模型](../../../paper_images/2404.04167/x4.png)

![中文迷你巨模：打造一个专注于中文的超大语言预训练模型](../../../paper_images/2404.04167/x5.png)

![中文迷你巨模：打造一个专注于中文的超大语言预训练模型](../../../paper_images/2404.04167/x6.png)

![中文迷你巨模：打造一个专注于中文的超大语言预训练模型](../../../paper_images/2404.04167/x7.png)

[Arxiv](https://arxiv.org/abs/2404.04167)