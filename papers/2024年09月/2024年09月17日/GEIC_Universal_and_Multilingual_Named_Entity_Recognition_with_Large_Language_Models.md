# GEIC：借助大型语言模型实现通用且多语言的命名实体识别

发布时间：2024年09月17日

`LLM应用` `数据集`

> GEIC: Universal and Multilingual Named Entity Recognition with Large Language Models

# 摘要

> 大型语言模型 (LLM) 已在众多自然语言处理任务中超越传统方法，但在命名实体识别 (NER) 领域，现有 LLM 方法表现不佳且资源消耗巨大。为此，我们提出基于生成的提取与上下文分类 (GEIC) 任务，并设计了 CascadeNER 框架，通过模型级联技术，利用两个小参数 LLM 独立完成提取与分类，既节省资源又提升准确性。此外，我们还推出了 AnythingNER 数据集，这是首个专为 LLM 设计的 NER 数据集，涵盖 8 种语言、155 种实体类型及动态分类系统。实验结果显示，CascadeNER 在低资源与细粒度场景中表现卓越，包括 CrossNER 和 FewNERD。我们的研究成果已公开，欢迎访问。

> Large Language Models (LLMs) have supplanted traditional methods in numerous natural language processing tasks. Nonetheless, in Named Entity Recognition (NER), existing LLM-based methods underperform compared to baselines and require significantly more computational resources, limiting their application. In this paper, we introduce the task of generation-based extraction and in-context classification (GEIC), designed to leverage LLMs' prior knowledge and self-attention mechanisms for NER tasks. We then propose CascadeNER, a universal and multilingual GEIC framework for few-shot and zero-shot NER. CascadeNER employs model cascading to utilize two small-parameter LLMs to extract and classify independently, reducing resource consumption while enhancing accuracy. We also introduce AnythingNER, the first NER dataset specifically designed for LLMs, including 8 languages, 155 entity types and a novel dynamic categorization system. Experiments show that CascadeNER achieves state-of-the-art performance on low-resource and fine-grained scenarios, including CrossNER and FewNERD. Our work is openly accessible.

[Arxiv](https://arxiv.org/abs/2409.11022)