# 超越内容相关性：对检索模型中的指令遵循进行评估

发布时间：2024年10月31日

`LLM应用`

> Beyond Content Relevance: Evaluating Instruction Following in Retrieval Models

# 摘要

> 大型语言模型（LLMs）的指令遵循能力大幅提升，借助详细的提示能够实现更复杂的用户交互。然而，检索系统却未能跟上这一进步步伐，多数仍依赖传统的词汇和语义匹配技术，难以充分领会用户意图。近期出现的努力引入了指令感知检索模型，可这些主要着眼于内在内容的相关性，忽略了针对更广泛文档级属性的定制偏好的重要性。本研究对包括基于LLM的密集检索和重排序模型在内的各类检索模型在内容相关性之外的指令遵循能力进行了评估。我们打造了InfoSearch这一全新的检索评估基准，涵盖了受众、关键字、格式、语言、长度和来源这六个文档级属性，并推出了新的指标——严格指令合规率（SICR）和加权指令敏感性评估（WISE），用于精准评估模型对指令的响应情况。我们的发现表明，虽然重排序模型在指令遵循方面总体上优于检索模型，但在处理某些属性时仍存在难题。此外，尽管指令微调以及模型规模的增大能提升性能，但依据我们的基准评估，大多数模型仍未达到全面的指令合规。

> Instruction-following capabilities in large language models (LLMs) have significantly progressed, enabling more complex user interactions through detailed prompts. However, retrieval systems have not matched these advances, most of them still relies on traditional lexical and semantic matching techniques that fail to fully capture user intent. Recent efforts have introduced instruction-aware retrieval models, but these primarily focus on intrinsic content relevance, which neglects the importance of customized preferences for broader document-level attributes. This study evaluates the instruction-following capabilities of various retrieval models beyond content relevance, including LLM-based dense retrieval and reranking models. We develop InfoSearch, a novel retrieval evaluation benchmark spanning six document-level attributes: Audience, Keyword, Format, Language, Length, and Source, and introduce novel metrics -- Strict Instruction Compliance Ratio (SICR) and Weighted Instruction Sensitivity Evaluation (WISE) to accurately assess the models' responsiveness to instructions. Our findings reveal that while reranking models generally surpass retrieval models in instruction following, they still face challenges in handling certain attributes. Moreover, although instruction fine-tuning and increased model size lead to better performance, most models fall short of achieving comprehensive instruction compliance as assessed by our benchmark.

[Arxiv](https://arxiv.org/abs/2410.23841)