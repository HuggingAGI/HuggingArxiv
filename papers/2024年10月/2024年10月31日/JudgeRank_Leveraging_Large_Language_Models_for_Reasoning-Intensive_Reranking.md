# JudgeRank：借助大型语言模型实现推理密集型重排序

发布时间：2024年10月31日

`RAG` `文档检索` `重排序`

> JudgeRank: Leveraging Large Language Models for Reasoning-Intensive Reranking

# 摘要

> 准确的文档检索对于检索增强生成（RAG）应用（如开放领域问答和代码补全）的成功至关重要。尽管大型语言模型（LLMs）在 RAG 系统中充当密集编码器或列表重排序器，但在推理密集型任务中常遇困境，因其判断文档相关性时缺乏精细分析。为突破此局限，我们推出 JudgeRank，这一新型智能重排序器在评估文档相关性时模拟人类认知过程。其方法涵盖三个关键步骤：（1）查询分析以明确核心问题；（2）文档分析以提取查询相关摘要；（3）相关性判断以给出文档相关性的简明评估。我们在推理密集型的 BRIGHT 基准上对 JudgeRank 进行评估，展现出相比第一阶段检索方法的显著性能提升，且优于其他热门重排序方法。另外，JudgeRank 在流行的 BEIR 基准上与微调的顶尖重排序器表现持平，证实了其零样本泛化能力。通过全面的消融研究表明，JudgeRank 的性能在不同规模的 LLMs 中均可良好泛化，且将它们集成所得的重排序比单个模型更精准。

> Accurate document retrieval is crucial for the success of retrieval-augmented generation (RAG) applications, including open-domain question answering and code completion. While large language models (LLMs) have been employed as dense encoders or listwise rerankers in RAG systems, they often struggle with reasoning-intensive tasks because they lack nuanced analysis when judging document relevance. To address this limitation, we introduce JudgeRank, a novel agentic reranker that emulates human cognitive processes when assessing document relevance. Our approach consists of three key steps: (1) query analysis to identify the core problem, (2) document analysis to extract a query-aware summary, and (3) relevance judgment to provide a concise assessment of document relevance. We evaluate JudgeRank on the reasoning-intensive BRIGHT benchmark, demonstrating substantial performance improvements over first-stage retrieval methods and outperforming other popular reranking approaches. In addition, JudgeRank performs on par with fine-tuned state-of-the-art rerankers on the popular BEIR benchmark, validating its zero-shot generalization capability. Through comprehensive ablation studies, we demonstrate that JudgeRank's performance generalizes well across LLMs of various sizes while ensembling them yields even more accurate reranking than individual models.

[Arxiv](https://arxiv.org/abs/2411.00142)