# 探讨中等规模语言模型在临床问答领域的应用潜力。

发布时间：2024年04月24日

`分类：LLM应用

这篇论文摘要讨论了大型语言模型（LLM）在临床任务上的表现，并比较了不同规模的模型在临床问答任务上的表现。这属于LLM应用的范畴，因为它关注的是LLM在特定领域（临床任务）的应用和性能评估。` `问答系统`

> Assessing The Potential Of Mid-Sized Language Models For Clinical QA

# 摘要

> 诸如 GPT-4 和 Med-PaLM 这样的大型语言模型在临床任务上表现卓越，但它们依赖于计算资源，且为闭源，无法在终端设备上运行。相比之下，BioGPT-large、BioMedLM、LLaMA 2 和 Mistral 7B 等中等规模模型克服了这些限制，尽管它们在处理临床任务上的能力尚未得到充分探究。为了评估它们在临床应用上的潜力并指导研究者选择合适的模型，我们对它们在两项临床问答任务——MedQA 和消费者健康查询回答——上的表现进行了比较。结果显示，Mistral 7B 在所有评估标准上均表现最佳，不仅超越了专为生物医学领域设计的模型，其 MedQA 的得分更是达到了 63.0%，接近原始的 Med-PaLM 水平。尽管 Mistral 7B 在回应消费者健康查询时经常能够给出合理的答案，但仍有提升空间。本研究首次对开源中等规模模型在临床任务上的表现进行了直接对比评估。

> Large language models, such as GPT-4 and Med-PaLM, have shown impressive performance on clinical tasks; however, they require access to compute, are closed-source, and cannot be deployed on device. Mid-size models such as BioGPT-large, BioMedLM, LLaMA 2, and Mistral 7B avoid these drawbacks, but their capacity for clinical tasks has been understudied. To help assess their potential for clinical use and help researchers decide which model they should use, we compare their performance on two clinical question-answering (QA) tasks: MedQA and consumer query answering. We find that Mistral 7B is the best performing model, winning on all benchmarks and outperforming models trained specifically for the biomedical domain. While Mistral 7B's MedQA score of 63.0% approaches the original Med-PaLM, and it often can produce plausible responses to consumer health queries, room for improvement still exists. This study provides the first head-to-head assessment of open source mid-sized models on clinical tasks.

[Arxiv](https://arxiv.org/abs/2404.15894)