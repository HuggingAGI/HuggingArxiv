# LLM 在生物医学信息提取方面并非零-Shot 推理器。

发布时间：2024年08月22日

`LLM应用` `生物医学`

> LLMs are not Zero-Shot Reasoners for Biomedical Information Extraction

# 摘要

> 大型语言模型（LLM）在医疗领域的应用日益增多，其问答和文档摘要能力已媲美专家。然而，在生物医学传统任务如结构化信息提取上，LLM的表现尚不明朗。本文针对这一问题，系统评估了LLM在医学分类和命名实体识别（NER）任务中的表现，旨在剖析任务知识、推理能力、领域知识及外部知识等因素的影响。我们测试了包括BioMistral和Llama-2在内的多种LLM模型，采用标准提示、思维链（CoT）、自一致性推理及PubMed和Wikipedia语料库的检索增强生成（RAG）等方法。令人意外的是，标准提示在两项任务中均优于复杂技术，凸显了CoT、自一致性和RAG在生物医学领域的应用局限。研究结果表明，专为知识或推理密集型任务设计的先进提示方法，如CoT或RAG，难以直接适用于需要精确结构化输出的生物医学任务。这强调了在LLM中更有效地融合外部知识和推理机制，以提升其在实际生物医学应用中的性能的重要性。

> Large Language Models (LLMs) are increasingly adopted for applications in healthcare, reaching the performance of domain experts on tasks such as question answering and document summarisation. Despite their success on these tasks, it is unclear how well LLMs perform on tasks that are traditionally pursued in the biomedical domain, such as structured information extration. To breach this gap, in this paper, we systematically benchmark LLM performance in Medical Classification and Named Entity Recognition (NER) tasks. We aim to disentangle the contribution of different factors to the performance, particularly the impact of LLMs' task knowledge and reasoning capabilities, their (parametric) domain knowledge, and addition of external knowledge. To this end we evaluate various open LLMs -- including BioMistral and Llama-2 models -- on a diverse set of biomedical datasets, using standard prompting, Chain-of-Thought (CoT) and Self-Consistency based reasoning as well as Retrieval-Augmented Generation (RAG) with PubMed and Wikipedia corpora. Counter-intuitively, our results reveal that standard prompting consistently outperforms more complex techniques across both tasks, laying bare the limitations in the current application of CoT, self-consistency and RAG in the biomedical domain. Our findings suggest that advanced prompting methods developed for knowledge- or reasoning-intensive tasks, such as CoT or RAG, are not easily portable to biomedical tasks where precise structured outputs are required. This highlights the need for more effective integration of external knowledge and reasoning mechanisms in LLMs to enhance their performance in real-world biomedical applications.

[Arxiv](https://arxiv.org/abs/2408.12249)