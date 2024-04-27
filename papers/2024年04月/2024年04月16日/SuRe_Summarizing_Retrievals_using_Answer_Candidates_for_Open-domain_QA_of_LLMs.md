# SuRe：为大型语言模型（LLMs）的开放域问答任务，通过候选答案对检索结果进行精炼总结。

发布时间：2024年04月16日

`LLM应用` `问答系统`

> SuRe: Summarizing Retrievals using Answer Candidates for Open-domain QA of LLMs

# 摘要

> 大型语言模型（LLMs）在自然语言处理的多个领域取得了突破性进展，尤其是在问答（QA）任务上。尽管结合新信息和检索相关内容是提升LLMs QA性能的一条有前景的途径，但现有的技术往往需要额外的微调，这在最新的LLMs中变得不切实际。通过提示来增强检索段落，有望突破这一瓶颈，但这方面的研究还相对有限。为了解决这一问题，我们提出了一个基于总结检索（SuRe）的简洁而高效的框架，用于提升LLMs在开放域问答（ODQA）中的表现。SuRe通过为每个可能的答案构建检索段落的摘要，帮助LLMs更准确地预测问题的答案，这些摘要可视为从检索内容中提取的明确理由。SuRe首先为多个答案候选者生成摘要，然后通过评估这些摘要的准确性和排序来确定最可信的答案。在多个ODQA基准上的实验结果显示，SuRe的性能优于传统提示方法，精确匹配（EM）准确度提升了4.6%，F1分数提升了4.0%。此外，SuRe能够与多种检索方法和LLMs兼容。SuRe生成的摘要还具有额外的优势，它们不仅能够衡量检索内容的重要性，还能作为模型和人类更倾向的理由。

> Large language models (LLMs) have made significant advancements in various natural language processing tasks, including question answering (QA) tasks. While incorporating new information with the retrieval of relevant passages is a promising way to improve QA with LLMs, the existing methods often require additional fine-tuning which becomes infeasible with recent LLMs. Augmenting retrieved passages via prompting has the potential to address this limitation, but this direction has been limitedly explored. To this end, we design a simple yet effective framework to enhance open-domain QA (ODQA) with LLMs, based on the summarized retrieval (SuRe). SuRe helps LLMs predict more accurate answers for a given question, which are well-supported by the summarized retrieval that could be viewed as an explicit rationale extracted from the retrieved passages. Specifically, SuRe first constructs summaries of the retrieved passages for each of the multiple answer candidates. Then, SuRe confirms the most plausible answer from the candidate set by evaluating the validity and ranking of the generated summaries. Experimental results on diverse ODQA benchmarks demonstrate the superiority of SuRe, with improvements of up to 4.6% in exact match (EM) and 4.0% in F1 score over standard prompting approaches. SuRe also can be integrated with a broad range of retrieval methods and LLMs. Finally, the generated summaries from SuRe show additional advantages to measure the importance of retrieved passages and serve as more preferred rationales by models and humans.

![SuRe：为大型语言模型（LLMs）的开放域问答任务，通过候选答案对检索结果进行精炼总结。](../../../paper_images/2404.13081/x1.png)

![SuRe：为大型语言模型（LLMs）的开放域问答任务，通过候选答案对检索结果进行精炼总结。](../../../paper_images/2404.13081/x2.png)

![SuRe：为大型语言模型（LLMs）的开放域问答任务，通过候选答案对检索结果进行精炼总结。](../../../paper_images/2404.13081/x3.png)

![SuRe：为大型语言模型（LLMs）的开放域问答任务，通过候选答案对检索结果进行精炼总结。](../../../paper_images/2404.13081/x4.png)

![SuRe：为大型语言模型（LLMs）的开放域问答任务，通过候选答案对检索结果进行精炼总结。](../../../paper_images/2404.13081/x5.png)

![SuRe：为大型语言模型（LLMs）的开放域问答任务，通过候选答案对检索结果进行精炼总结。](../../../paper_images/2404.13081/x6.png)

![SuRe：为大型语言模型（LLMs）的开放域问答任务，通过候选答案对检索结果进行精炼总结。](../../../paper_images/2404.13081/x7.png)

![SuRe：为大型语言模型（LLMs）的开放域问答任务，通过候选答案对检索结果进行精炼总结。](../../../paper_images/2404.13081/x8.png)

![SuRe：为大型语言模型（LLMs）的开放域问答任务，通过候选答案对检索结果进行精炼总结。](../../../paper_images/2404.13081/x9.png)

![SuRe：为大型语言模型（LLMs）的开放域问答任务，通过候选答案对检索结果进行精炼总结。](../../../paper_images/2404.13081/x10.png)

![SuRe：为大型语言模型（LLMs）的开放域问答任务，通过候选答案对检索结果进行精炼总结。](../../../paper_images/2404.13081/x11.png)

![SuRe：为大型语言模型（LLMs）的开放域问答任务，通过候选答案对检索结果进行精炼总结。](../../../paper_images/2404.13081/x12.png)

![SuRe：为大型语言模型（LLMs）的开放域问答任务，通过候选答案对检索结果进行精炼总结。](../../../paper_images/2404.13081/x13.png)

![SuRe：为大型语言模型（LLMs）的开放域问答任务，通过候选答案对检索结果进行精炼总结。](../../../paper_images/2404.13081/x14.png)

![SuRe：为大型语言模型（LLMs）的开放域问答任务，通过候选答案对检索结果进行精炼总结。](../../../paper_images/2404.13081/x15.png)

![SuRe：为大型语言模型（LLMs）的开放域问答任务，通过候选答案对检索结果进行精炼总结。](../../../paper_images/2404.13081/x16.png)

![SuRe：为大型语言模型（LLMs）的开放域问答任务，通过候选答案对检索结果进行精炼总结。](../../../paper_images/2404.13081/x17.png)

![SuRe：为大型语言模型（LLMs）的开放域问答任务，通过候选答案对检索结果进行精炼总结。](../../../paper_images/2404.13081/x18.png)

[Arxiv](https://arxiv.org/abs/2404.13081)