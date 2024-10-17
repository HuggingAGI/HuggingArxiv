# 开放领域问答中的冲突上下文

发布时间：2024年10月16日

`LLM应用` `问答系统` `人工智能`

> Open Domain Question Answering with Conflicting Contexts

# 摘要

> 开放领域问答系统常依赖于从大量文本（如网络）中检索的信息，但这些信息常含冲突，盲目依赖可能导致错误答案。我们创建了QACC数据集，发现25%的明确问题在Google搜索中会引发冲突。通过测试三大LLMs，我们揭示了它们在处理冲突信息时的不足。为探究人类如何应对冲突，我们要求标注者提供答案解释。实验表明，通过微调LLMs使其解释答案，能引入更多信息，提升其在冲突情境下的推理能力。

> Open domain question answering systems frequently rely on information retrieved from large collections of text (such as the Web) to answer questions. However, such collections of text often contain conflicting information, and indiscriminately depending on this information may result in untruthful and inaccurate answers. To understand the gravity of this problem, we collect a human-annotated dataset, Question Answering with Conflicting Contexts (QACC), and find that as much as 25% of unambiguous, open domain questions can lead to conflicting contexts when retrieved using Google Search. We evaluate and benchmark three powerful Large Language Models (LLMs) with our dataset QACC and demonstrate their limitations in effectively addressing questions with conflicting information. To explore how humans reason through conflicting contexts, we request our annotators to provide explanations for their selections of correct answers. We demonstrate that by finetuning LLMs to explain their answers, we can introduce richer information into their training that guide them through the process of reasoning with conflicting contexts.

[Arxiv](https://arxiv.org/abs/2410.12311)