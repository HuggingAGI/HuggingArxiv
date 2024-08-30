# LoraMap：发掘 LoRA 连接的潜能

发布时间：2024年08月29日

`LLM应用` `人工智能` `数据分析`

> LoraMap: Harnessing the Power of LoRA Connections

# 摘要

> 大型语言模型 (LLM) 通过事实核查减少幻觉，并利用低秩适应 (LoRA) 等技术降低计算成本。本文探讨了多个 LoRA 间的联系建立方法，定制了三个事实核查推理数据集，微调 LoRA 以多视角推理。我们提出 LoraMap，一种新的 LoRA 间联系映射方法，其在事实核查任务中超越了现有组合方法 LoraHub 和参数更多的 LoraConcat。

> Large Language Models (LLMs) can benefit from mitigating hallucinations through fact-checking and overcoming substantial computational overhead with parameter-efficient techniques such as Low-Rank Adaptation (LoRA). While some studies have explored the parallel integration of multiple LoRAs, these approaches need attention to the connections between them. This paper investigates methods to establish connections among multiple LoRAs. We create three reasoning datasets tailored to fact-checking and fine-tune individual LoRAs, allowing them to view and reason from diverse perspectives. Then, we explore strategies for allocating these reasoning LoRAs and introduce LoraMap, an approach to map connections between them. The results on the fact-checking task demonstrate that the performance of LoraMap is superior to LoraHub, an existing LoRA composition method. LoraMap also outperforms with significantly fewer parameters than LoraConcat, which concatenates LoRAs and further fine-tunes them.

[Arxiv](https://arxiv.org/abs/2408.16264)