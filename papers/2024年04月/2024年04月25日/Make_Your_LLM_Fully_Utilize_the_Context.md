# 充分发挥您的大型语言模型的上下文理解能力

发布时间：2024年04月25日

`LLM应用` `信息检索`

> Make Your LLM Fully Utilize the Context

# 摘要

> 现代大型语言模型（LLMs）虽然能处理长文本输入，但常面临“信息中间丢失”的难题，即难以完全吸收长文本中的信息。我们认为这可能是由于在长文本训练时缺乏足够的显式指导，未能充分强调长文本中任何位置都可能蕴含重要信息。针对这一问题，本研究引入了一种全新的信息密集型（IN2）训练方法，这是一种纯粹基于数据驱动的解决方案。IN2训练通过构建一个合成的长文本问答数据集，要求答案不仅要对长文本中的一小段（约128个令牌）进行精细的信息感知，还要能够整合并推理来自两个或更多短片段的信息。我们将这种训练方法应用于Mistral-7B模型，进而推出了FILM-7B（意为“填补中间的空白”）。为了全面测试FILM-7B处理长文本的能力，我们设计了三种探测任务，覆盖了不同的文本风格和信息检索模式。测试结果显示，FILM-7B能够有效地从其32K的上下文窗口中检索信息。此外，FILM-7B在现实世界的长文本任务中表现出色，例如在NarrativeQA上将F1得分从23.5提升至26.9，同时在短文本任务中也保持了相当的性能，如在MMLU上的准确度从59.3微降至59.2。项目详情可访问GitHub链接：https://github.com/microsoft/FILM。

> While many contemporary large language models (LLMs) can process lengthy input, they still struggle to fully utilize information within the long context, known as the lost-in-the-middle challenge. We hypothesize that it stems from insufficient explicit supervision during the long-context training, which fails to emphasize that any position in a long context can hold crucial information. Based on this intuition, our study presents information-intensive (IN2) training, a purely data-driven solution to overcome lost-in-the-middle. Specifically, IN2 training leverages a synthesized long-context question-answer dataset, where the answer requires (1) fine-grained information awareness on a short segment (~128 tokens) within a synthesized long context (4K-32K tokens), and (2) the integration and reasoning of information from two or more short segments. Through applying this information-intensive training on Mistral-7B, we present FILM-7B (FILl-in-the-Middle). To thoroughly assess the ability of FILM-7B for utilizing long contexts, we design three probing tasks that encompass various context styles (document, code, and structured-data context) and information retrieval patterns (forward, backward, and bi-directional retrieval). The probing results demonstrate that FILM-7B can robustly retrieve information from different positions in its 32K context window. Beyond these probing tasks, FILM-7B significantly improves the performance on real-world long-context tasks (e.g., 23.5->26.9 F1 score on NarrativeQA), while maintaining a comparable performance on short-context tasks (e.g., 59.3->59.2 accuracy on MMLU). Github Link: https://github.com/microsoft/FILM.

[Arxiv](https://arxiv.org/abs/2404.16811)