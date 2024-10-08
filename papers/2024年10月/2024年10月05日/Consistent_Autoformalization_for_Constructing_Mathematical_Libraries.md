# 构建数学库的自动形式化一致性

发布时间：2024年10月05日

`RAG`

> Consistent Autoformalization for Constructing Mathematical Libraries

# 摘要

> 自动形式化是将自然语言数学内容转化为形式语言的任务。随着大型语言模型（LLMs）在语言解释能力上的提升，自动形式化的门槛正在降低。然而，仅靠LLMs难以始终如一地实现这一目标，尤其是在领域复杂性和专业化程度增加时。随着自动形式化在大型数学库中的系统应用，提高句法、术语和语义控制的需求日益迫切。本文提出协调使用三种机制——最相似检索增强生成（MS-RAG）、去噪步骤和句法错误反馈自动校正（Auto-SEF），以提升自动形式化质量。实证分析显示，这些机制在不同模型上均能提供更加一致的句法、术语和语义结果。这些机制适用于不同LLMs，并在多种模型类型中展现出改进效果。

> Autoformalization is the task of automatically translating mathematical content written in natural language to a formal language expression. The growing language interpretation capabilities of Large Language Models (LLMs), including in formal languages, are lowering the barriers for autoformalization. However, LLMs alone are not capable of consistently and reliably delivering autoformalization, in particular as the complexity and specialization of the target domain grows. As the field evolves into the direction of systematically applying autoformalization towards large mathematical libraries, the need to improve syntactic, terminological and semantic control increases. This paper proposes the coordinated use of three mechanisms, most-similar retrieval augmented generation (MS-RAG), denoising steps, and auto-correction with syntax error feedback (Auto-SEF) to improve autoformalization quality. The empirical analysis, across different models, demonstrates that these mechanisms can deliver autoformalizaton results which are syntactically, terminologically and semantically more consistent. These mechanisms can be applied across different LLMs and have shown to deliver improve results across different model types.

[Arxiv](https://arxiv.org/abs/2410.04194)