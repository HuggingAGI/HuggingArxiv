# 本文探讨了如何利用 Cogtale 数据集对大型语言模型进行基于文档的问答能力的评估，包括精确答案的选择和数值信息的提取。

发布时间：2024年01月03日

`LLM应用` `信息检索`

> Evaluating LLMs on Document-Based QA: Exact Answer Selection and Numerical Extraction using Cogtale dataset

# 摘要

> 文档型问答任务在精准信息检索中扮演着关键角色。尽管现有研究多聚焦于评估大型语言模型（LLM）在文档问答上的表现，但对于需要从预设选项中精确挑选答案或进行数值抽取的问答类型，LLM的性能尚待全面评估。本文专注于这一未被充分研究的领域，对LLM（包括GPT-4和GPT-3.5）在零样本环境下处理单选、是非、多选和数字抽取等类型问题进行了实证分析。我们采用CogTale数据集作为评估基准，该数据集包含专家标记的答案，为精确度和事实依据提供了坚实的参考。研究发现，特别是GPT-4，在给定相关上下文的情况下，能够准确回答许多单选和是非问题，证明了LLM在信息检索任务上的有效性。然而，面对多选和数字抽取问题时，其性能有所下降，影响了模型在这类任务上的整体表现，暗示这些模型可能尚未足够成熟以胜任此类任务。这限制了LLM在需要精确信息抽取的文档应用场景，如元分析任务中的使用。研究结果强调了检索器提供准确响应所需相关上下文的重要性，并指出了进一步研究的必要性。我们的研究为持续的数据集评估提供了框架，确保LLM在信息检索和文档分析领域的应用能够不断适应并满足新的标准。

> Document-based Question-Answering (QA) tasks are crucial for precise information retrieval. While some existing work focus on evaluating large language models performance on retrieving and answering questions from documents, assessing the LLMs performance on QA types that require exact answer selection from predefined options and numerical extraction is yet to be fully assessed. In this paper, we specifically focus on this underexplored context and conduct empirical analysis of LLMs (GPT-4 and GPT-3.5) on question types, including single-choice, yes-no, multiple-choice, and number extraction questions from documents in zero-shot setting. We use the CogTale dataset for evaluation, which provide human expert-tagged responses, offering a robust benchmark for precision and factual grounding. We found that LLMs, particularly GPT-4, can precisely answer many single-choice and yes-no questions given relevant context, demonstrating their efficacy in information retrieval tasks. However, their performance diminishes when confronted with multiple-choice and number extraction formats, lowering the overall performance of the model on this task, indicating that these models may not yet be sufficiently reliable for the task. This limits the applications of LLMs on applications demanding precise information extraction from documents, such as meta-analysis tasks. These findings hinge on the assumption that the retrievers furnish pertinent context necessary for accurate responses, emphasizing the need for further research. Our work offers a framework for ongoing dataset evaluation, ensuring that LLM applications for information retrieval and document analysis continue to meet evolving standards.

[Arxiv](https://arxiv.org/abs/2311.07878)