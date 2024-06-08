# 探究中国开源大型语言模型在信息提取领域的性能表现

发布时间：2024年06月04日

`LLM应用

理由：这篇论文主要关注的是大型语言模型（LLMs）在中文信息抽取（IE）任务中的应用表现，包括零样本条件下的性能评估以及与知名模型ChatGPT的比较。论文通过实验和分析，探讨了中文开源LLMs在NLP信息抽取领域的优势、局限及改进潜力。这属于对LLM在特定应用场景（即信息抽取）中的实际应用和性能评估，因此归类为LLM应用。` `信息抽取`

> Assessing the Performance of Chinese Open Source Large Language Models in Information Extraction Tasks

# 摘要

> 信息抽取（IE）是NLP中的关键技术，它从非结构化文本中提炼出结构化信息，助力各类依赖结构化数据的应用。尽管重要，但英语IE任务的最新实验显示，大型语言模型（LLMs）在如命名实体识别（NER）等子任务上达到最佳性能仍面临挑战。本文深入分析了主流中文开源LLMs在零样本条件下的IE任务表现，并展示了少量样本实验的结果，以评估其能力。我们还对比了这些模型与知名语言模型ChatGPT的IE性能。通过详尽的实验与分析，本文旨在揭示中文开源LLMs在NLP信息抽取领域的优势、局限及改进潜力。

> Information Extraction (IE) plays a crucial role in Natural Language Processing (NLP) by extracting structured information from unstructured text, thereby facilitating seamless integration with various real-world applications that rely on structured data. Despite its significance, recent experiments focusing on English IE tasks have shed light on the challenges faced by Large Language Models (LLMs) in achieving optimal performance, particularly in sub-tasks like Named Entity Recognition (NER). In this paper, we delve into a comprehensive investigation of the performance of mainstream Chinese open-source LLMs in tackling IE tasks, specifically under zero-shot conditions where the models are not fine-tuned for specific tasks. Additionally, we present the outcomes of several few-shot experiments to further gauge the capability of these models. Moreover, our study includes a comparative analysis between these open-source LLMs and ChatGPT, a widely recognized language model, on IE performance. Through meticulous experimentation and analysis, we aim to provide insights into the strengths, limitations, and potential enhancements of existing Chinese open-source LLMs in the domain of Information Extraction within the context of NLP.

[Arxiv](https://arxiv.org/abs/2406.02079)