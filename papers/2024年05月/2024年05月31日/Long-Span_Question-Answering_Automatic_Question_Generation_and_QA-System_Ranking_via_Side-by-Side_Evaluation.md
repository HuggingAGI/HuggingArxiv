# 长跨度问答：通过并排对比评估，实现自动问题生成与问答系统排名优化

发布时间：2024年05月31日

`LLM应用

这篇论文探讨了如何利用大型语言模型（LLMs）的长上下文能力来自动生成阅读理解数据，这是一个直接应用LLMs技术到实际问题中的案例。论文中提到的自动数据生成流程、问题生成、答案提供及模型评分等，都是LLMs在阅读理解领域的具体应用。因此，这篇论文属于LLM应用分类。` `阅读理解`

> Long-Span Question-Answering: Automatic Question Generation and QA-System Ranking via Side-by-Side Evaluation

# 摘要

> 我们研究了如何利用大型语言模型的长上下文能力，从整本书中自动生成阅读理解数据。过去，这类数据集的构建依赖于众包，但如今拥有百万级上下文长度的transformer使得全自动化成为可能。我们的研究旨在检验LLMs处理需要深入理解长文本段落的问题的能力，如角色发展、主题探讨或故事早期行为的长远影响。我们设计了一套自动数据生成流程，涵盖问题生成、答案提供及利用“评估器”进行模型评分。通过对比不同模型答案的相对评估方法，我们发现这种方法比单独评估答案的绝对评分更为一致和有效。此外，不同模型家族的LLMs在评分上显示出一定的一致性。我们采用了人工精心编制的NarrativeQA数据集来验证我们的方法，结果显示我们的评估器与人类判断高度一致，甚至能发现数据集中的错误。通过自动评估，我们证明了使用整本书作为上下文能够显著提升阅读理解性能，超越了无上下文基线和基于检索的方法。

> We explore the use of long-context capabilities in large language models to create synthetic reading comprehension data from entire books. Previous efforts to construct such datasets relied on crowd-sourcing, but the emergence of transformers with a context size of 1 million or more tokens now enables entirely automatic approaches. Our objective is to test the capabilities of LLMs to analyze, understand, and reason over problems that require a detailed comprehension of long spans of text, such as questions involving character arcs, broader themes, or the consequences of early actions later in the story. We propose a holistic pipeline for automatic data generation including question generation, answering, and model scoring using an ``Evaluator''. We find that a relative approach, comparing answers between models in a pairwise fashion and ranking with a Bradley-Terry model, provides a more consistent and differentiating scoring mechanism than an absolute scorer that rates answers individually. We also show that LLMs from different model families produce moderate agreement in their ratings. We ground our approach using the manually curated NarrativeQA dataset, where our evaluator shows excellent agreement with human judgement and even finds errors in the dataset. Using our automatic evaluation approach, we show that using an entire book as context produces superior reading comprehension performance compared to baseline no-context (parametric knowledge only) and retrieval-based approaches.

[Arxiv](https://arxiv.org/abs/2406.00179)