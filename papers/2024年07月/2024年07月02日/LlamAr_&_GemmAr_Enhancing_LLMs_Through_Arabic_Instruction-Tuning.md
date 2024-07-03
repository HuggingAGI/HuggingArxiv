# LlamAr 与 GemmAr：借助阿拉伯语指令调优提升大型语言模型性能

发布时间：2024年07月02日

`LLM应用` `阿拉伯语`

> LlamAr & GemmAr: Enhancing LLMs Through Arabic Instruction-Tuning

# 摘要

> 大型语言模型（LLMs）在自然语言处理（NLP）领域，尤其是在英语方面，展现了显著的影响力。这些模型不仅理解力强，还能生成逼真的文本。然而，模型的成功极大地依赖于高质量的指令数据集，这些数据集包含了详尽的任务描述和相应的回答，对训练模型应对多样化的提示至关重要。尽管在英语中表现出色，但由于缺乏针对阿拉伯语的微调数据集，模型在阿拉伯语任务上往往表现不佳。为此，我们推出了InstAr-500k，一个全新的阿拉伯语指令数据集，涵盖了多个领域和指令类型。通过在多个下游任务上微调Llama-3-8B-Instruct和Gemma-7B-IT这两个开源模型，我们评估了该数据集的效果，并实现了功能的显著提升。评估结果显示，我们的微调模型在阿拉伯语NLP基准测试中达到了顶尖水平，凸显了该数据集在提升阿拉伯语模型性能方面的强大作用。通过提供丰富的资源，我们的数据集有效缩小了英语与阿拉伯语模型之间的性能差距，并在此基础上，我们进一步开发了LlamAr-8B和GemmAr-7B这两款专为阿拉伯语NLP任务优化的顶尖模型。

> Large language models (LLMs) have greatly impacted the natural language processing (NLP) field, particularly for the English language. These models have demonstrated capabilities in understanding and generating human-like text. The success of language models largely depends on the availability of high-quality instruction datasets, which consist of detailed task descriptions and corresponding responses that are essential for training the models to accurately address a variety of prompts. However, the availability and quality of these resources vary by language. While models perform well in English, they often struggle with languages like Arabic, due to the lack of datasets for fine-tuning Arabic-specific tasks. To address this issue, we introduce InstAr-500k, a new Arabic instruction dataset created by generating and collecting content that covers several domains and instruction types. We then assess this dataset by fine-tuning two open-source models, Llama-3-8B-Instruct and Gemma-7B-IT, on several downstream tasks to scale improvements in their functionality. Based on multiple evaluations, our fine-tuned models achieve state-of-the-art performance on several Arabic NLP benchmarks. These outcomes emphasize the effectiveness of our dataset in elevating the capabilities of language models for Arabic. Our instruction dataset bridges the performance gap between English and Arabic language models by providing resources that amplify Arabic NLP development. Building on this foundation, we developed two state-of-the-art models, LlamAr-8B and GemmAr-7B, which are specifically tuned to excel at a wide range of Arabic NLP tasks.

[Arxiv](https://arxiv.org/abs/2407.02147)