# 大型语言模型在机器翻译评估中需要哪些要素？

发布时间：2024年10月04日

`LLM应用` `机器翻译`

> What do Large Language Models Need for Machine Translation Evaluation?

# 摘要

> 利用大型语言模型 (LLM) 进行自然语言处理任务，其性能备受赞誉。在机器翻译 (MT) 评估中，LLM 的表现与微调的多语言预训练模型不相上下。本文探讨了 LLM 评估 MT 质量所需的信息，如源文本、参考译文、翻译错误和注释指南。我们还研究了针对八种语言的提示技术，包括零-shot、Chain of Thought (CoT) 和 few-shot 提示，利用不同的 LLM 变体。研究发现，参考译文对 LLM 评估至关重要。虽然大模型不一定更优，但它们更受益于 CoT 提示。此外，LLM 在评估时并不总是提供数值分数，这对其可靠性提出了质疑。我们的研究为资源受限和无需训练的 LLM 机器翻译评估提供了全面分析，并公开了相关数据和代码，以供复现。

> Leveraging large language models (LLMs) for various natural language processing tasks has led to superlative claims about their performance. For the evaluation of machine translation (MT), existing research shows that LLMs are able to achieve results comparable to fine-tuned multilingual pre-trained language models. In this paper, we explore what translation information, such as the source, reference, translation errors and annotation guidelines, is needed for LLMs to evaluate MT quality. In addition, we investigate prompting techniques such as zero-shot, Chain of Thought (CoT) and few-shot prompting for eight language pairs covering high-, medium- and low-resource languages, leveraging varying LLM variants. Our findings indicate the importance of reference translations for an LLM-based evaluation. While larger models do not necessarily fare better, they tend to benefit more from CoT prompting, than smaller models. We also observe that LLMs do not always provide a numerical score when generating evaluations, which poses a question on their reliability for the task. Our work presents a comprehensive analysis for resource-constrained and training-less LLM-based evaluation of machine translation. We release the accrued prompt templates, code and data publicly for reproducibility.

[Arxiv](https://arxiv.org/abs/2410.03278)