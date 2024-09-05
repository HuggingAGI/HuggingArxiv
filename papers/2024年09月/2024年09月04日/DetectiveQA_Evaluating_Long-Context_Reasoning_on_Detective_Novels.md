# DetectiveQA：探究侦探小说中的长篇推理能力

发布时间：2024年09月04日

`LLM应用` `人工智能`

> DetectiveQA: Evaluating Long-Context Reasoning on Detective Novels

# 摘要

> 随着大型语言模型的飞速进步，长上下文信息的理解和处理已成为学术与工业界的焦点。然而，评估这些模型处理长上下文能力的基准却未能同步发展。尽管现有多种评估基准，但它们所涵盖的能力维度仍显狭窄。本文推出的 DetectiveQA 基准，以其超过 100K 令牌的平均上下文长度，专注于测试模型的长上下文推理能力。这不仅要求模型深入理解上下文，还需从中提取关键证据，并据此推理以解答问题。这一新评估维度更贴合当前模型的智能水平。我们选取侦探小说作为数据源，因其富含推理元素。此外，我们精心标注了 600 个中文问题，并提供了相应的英文版本。通过在 DetectiveQA 上测试多种长上下文模型，包括商业与开源模型，结果显示现有模型在处理真正的长上下文依赖问题上仍有显著提升空间。

> With the rapid advancement of Large Language Models (LLMs), long-context information understanding and processing have become a hot topic in academia and industry. However, benchmarks for evaluating the ability of LLMs to handle long-context information do not seem to have kept pace with the development of LLMs. Despite the emergence of various long-context evaluation benchmarks, the types of capability assessed are still limited, without new capability dimensions. In this paper, we introduce DetectiveQA, a narrative reasoning benchmark featured with an average context length of over 100K tokens. DetectiveQA focuses on evaluating the long-context reasoning ability of LLMs, which not only requires a full understanding of context but also requires extracting important evidences from the context and reasoning according to extracted evidences to answer the given questions. This is a new dimension of capability evaluation, which is more in line with the current intelligence level of LLMs. We use detective novels as data sources, which naturally have various reasoning elements. Finally, we manually annotated 600 questions in Chinese and then also provided an English edition of the context information and questions. We evaluate many long-context LLMs on DetectiveQA, including commercial and open-sourced models, and the results indicate that existing long-context LLMs still require significant advancements to effectively process true long-context dependency questions.

[Arxiv](https://arxiv.org/abs/2409.02465)