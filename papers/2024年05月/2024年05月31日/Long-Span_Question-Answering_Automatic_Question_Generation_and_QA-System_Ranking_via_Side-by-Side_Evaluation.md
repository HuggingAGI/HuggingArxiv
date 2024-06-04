# 长跨度问答：并排评估助力自动问题生成与问答系统排名优化

发布时间：2024年05月31日

`LLM应用

这篇论文探讨了如何利用大型语言模型（LLMs）的长上下文能力来自动生成阅读理解数据，这是一个具体的应用场景。论文中提到的自动数据生成流程、模型评分以及与人类判断的比较，都是围绕如何有效利用LLMs处理长文本段落的问题展开的。因此，这篇论文属于LLM应用类别。` `阅读理解`

> Long-Span Question-Answering: Automatic Question Generation and QA-System Ranking via Side-by-Side Evaluation

# 摘要

> 我们研究了如何利用大型语言模型的长上下文能力，从整本书中自动生成阅读理解数据。过去，这类数据集的构建依赖于众包，但如今拥有百万级上下文长度的transformer使得全自动化成为可能。我们的研究旨在检验LLMs处理需要深入理解长文本段落的问题的能力，如角色发展、主题探讨或故事早期行为后果等。我们设计了一套自动数据生成流程，涵盖问题生成、回答及利用“评估者”进行模型评分。通过比较模型间的答案并采用Bradley-Terry模型排名，我们发现这种相对评分方法比单独评估答案的绝对评分更为一致和有效。此外，不同模型家族的LLMs在评分上显示出一定的一致性。我们以NarrativeQA数据集为基准，验证了我们的评估者与人类判断高度一致，甚至能发现数据集中的错误。实验结果显示，相较于无上下文基线和基于检索的方法，使用整本书作为上下文能显著提升阅读理解性能。

> We explore the use of long-context capabilities in large language models to create synthetic reading comprehension data from entire books. Previous efforts to construct such datasets relied on crowd-sourcing, but the emergence of transformers with a context size of 1 million or more tokens now enables entirely automatic approaches. Our objective is to test the capabilities of LLMs to analyze, understand, and reason over problems that require a detailed comprehension of long spans of text, such as questions involving character arcs, broader themes, or the consequences of early actions later in the story. We propose a holistic pipeline for automatic data generation including question generation, answering, and model scoring using an ``Evaluator''. We find that a relative approach, comparing answers between models in a pairwise fashion and ranking with a Bradley-Terry model, provides a more consistent and differentiating scoring mechanism than an absolute scorer that rates answers individually. We also show that LLMs from different model families produce moderate agreement in their ratings. We ground our approach using the manually curated NarrativeQA dataset, where our evaluator shows excellent agreement with human judgement and even finds errors in the dataset. Using our automatic evaluation approach, we show that using an entire book as context produces superior reading comprehension performance compared to baseline no-context (parametric knowledge only) and retrieval-based approaches.

[Arxiv](https://arxiv.org/abs/2406.00179)