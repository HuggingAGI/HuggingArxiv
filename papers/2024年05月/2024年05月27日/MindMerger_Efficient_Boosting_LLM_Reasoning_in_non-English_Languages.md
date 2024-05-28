# MindMerger：提升非英语语言中大型语言模型的推理效率

发布时间：2024年05月27日

`LLM应用

理由：这篇论文主要探讨了如何通过结合大型语言模型（LLMs）和多语言模型的语言理解能力来增强多语言推理，提出了一种名为MindMerger的方法，并设计了相应的训练策略。这种方法和策略的应用旨在提升LLMs在多语言环境下的推理和语言理解能力，特别是在资源匮乏的语言中。因此，这篇论文的内容更偏向于LLMs的实际应用，而不是理论研究或Agent、RAG的范畴。` `多语言技术`

> MindMerger: Efficient Boosting LLM Reasoning in non-English Languages

# 摘要

> 大型语言模型（LLMs）的推理能力至关重要，但英语与非英语语言间的差距显著。为此，一些研究通过微调LLMs来重新学习非英语语言的推理，另一些则通过外部模型的英语翻译输出绕过理解非英语的难题。然而，这些方法未能充分利用LLMs的内在推理与语言理解优势。为此，我们提出了MindMerger方法，将LLMs与多语言模型的语言理解能力结合，以增强多语言推理。我们还设计了一个两步训练策略：首先将外部能力融入LLMs，随后协同利用这些能力。实验结果显示，MindMerger在多语言推理和语言理解任务上均超越了其他方法，尤其在资源匮乏的语言中表现突出。在未更新LLMs参数的情况下，MGSM数据集上所有语言及资源较少语言的平均准确率分别提升了6.7%和8.0%。

> Reasoning capabilities are crucial for Large Language Models (LLMs), yet a notable gap exists between English and non-English languages. To bridge this disparity, some works fine-tune LLMs to relearn reasoning capabilities in non-English languages, while others replace non-English inputs with an external model's outputs such as English translation text to circumvent the challenge of LLM understanding non-English. Unfortunately, these methods often underutilize the built-in skilled reasoning and useful language understanding capabilities of LLMs. In order to better utilize the minds of reasoning and language understanding in LLMs, we propose a new method, namely MindMerger, which merges LLMs with the external language understanding capabilities from multilingual models to boost the multilingual reasoning performance. Furthermore, a two-step training scheme is introduced to first train to embeded the external capabilities into LLMs and then train the collaborative utilization of the external capabilities and the built-in capabilities in LLMs. Experiments on three multilingual reasoning datasets and a language understanding dataset demonstrate that MindMerger consistently outperforms all baselines, especially in low-resource languages. Without updating the parameters of LLMs, the average accuracy improved by 6.7% and 8.0% across all languages and low-resource languages on the MGSM dataset, respectively.

![MindMerger：提升非英语语言中大型语言模型的推理效率](../../../paper_images/2405.17386/x1.png)

![MindMerger：提升非英语语言中大型语言模型的推理效率](../../../paper_images/2405.17386/x2.png)

![MindMerger：提升非英语语言中大型语言模型的推理效率](../../../paper_images/2405.17386/x3.png)

![MindMerger：提升非英语语言中大型语言模型的推理效率](../../../paper_images/2405.17386/x4.png)

![MindMerger：提升非英语语言中大型语言模型的推理效率](../../../paper_images/2405.17386/x5.png)

![MindMerger：提升非英语语言中大型语言模型的推理效率](../../../paper_images/2405.17386/llama_embedding.jpg)

![MindMerger：提升非英语语言中大型语言模型的推理效率](../../../paper_images/2405.17386/adapter_output.jpg)

[Arxiv](https://arxiv.org/abs/2405.17386)