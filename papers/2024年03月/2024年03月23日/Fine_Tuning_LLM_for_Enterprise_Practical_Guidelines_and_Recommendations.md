# 企业级大型语言模型（LLM）的微调：实用指南与建议

发布时间：2024年03月23日

`分类：LLM应用` `企业定制化`

> Fine Tuning LLM for Enterprise: Practical Guidelines and Recommendations

# 摘要

> 企业对大型语言模型（LLM）的定制化训练需求日益迫切，以适应其专有的领域知识。关键在于如何高效、经济且迅速地将特定领域的知识融入LLM。众多企业采用RAG技术，避免了对LLM的精细调整，但其效能受限于向量数据库的质量和检索系统的性能，而非LLM的内在能力。在本项研究中，我们专注于对开源的LLM——LLaMA进行定制化训练，利用企业库中的专有文档和代码，并利用这些经过训练的模型来评估回答的质量。此外，我们旨在为初学者提供指导，如何开始对LLM进行定制化训练，以处理文档和代码，包括合理估计所需的GPU大小和数据格式化的选项。我们还为文档和代码数据集的预处理提供了方法，包括构建段落块、问题与答案对以及关键词与段落块对。对于代码数据集，我们建议构建摘要与函数对。我们进一步对模型在特定领域查询上的表现进行了定性评估，并最终提出了微调LLM的实用指南和建议。

> There is a compelling necessity from enterprises for fine tuning LLMs (Large Language Models) o get them trained on proprietary domain knowledge. The challenge is to imbibe the LLMs with domain specific knowledge using the most optimial resource and cost and in the best possible time. Many enterprises rely on RAG (Retrieval Augmented Generation) which does not need LLMs to be ine-tuned but they are limited by the quality of vector databases and their retrieval capabilities rather than the intrinsic capabilities of the LLMs themselves. In our current work we focus on fine tuning LLaMA, an open source LLM using proprietary documents and code from an enterprise repository and use the fine tuned models to evaluate the quality of responses. As part of this work, we aim to guide beginners on how to start with fine tuning an LLM for documentation and code by making educated guesses on size of GPU required and options that are available for formatting the data. We also propose pre processing recipes for both documentation and code to prepare dataset in different formats. The proposed methods of data preparation for document datasets are forming paragraph chunks, forming question and answer pairs and forming keyword and paragraph chunk pairs. For code dataset we propose forming summary and function pairs. Further, we qualitatively evaluate the results of the models for domain specific queries. Finally, we also propose practical guidelines and recommendations for fine tuning LLMs.

![企业级大型语言模型（LLM）的微调：实用指南与建议](../../../paper_images/2404.10779/text_finetune.jpg)

![企业级大型语言模型（LLM）的微调：实用指南与建议](../../../paper_images/2404.10779/quantlatency.png)

![企业级大型语言模型（LLM）的微调：实用指南与建议](../../../paper_images/2404.10779/Llama2_7Bchat_modes.png)

![企业级大型语言模型（LLM）的微调：实用指南与建议](../../../paper_images/2404.10779/Llama2_13Bchat_modes.png)

[Arxiv](https://arxiv.org/abs/2404.10779)