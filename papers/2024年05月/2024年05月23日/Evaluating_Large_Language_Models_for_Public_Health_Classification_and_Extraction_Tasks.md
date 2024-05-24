# 大型语言模型在公共卫生分类与信息提取任务中的评估

发布时间：2024年05月23日

`LLM应用

这篇论文主要探讨了大型语言模型（LLMs）在公共卫生领域的应用，特别是在处理自由文本分类和提取等任务中的表现。研究通过使用多个数据集评估了不同规模的LLMs在这些任务上的性能，并比较了不同模型的表现。这表明LLMs在公共卫生领域的应用潜力，尤其是在文本处理和信息提取方面，这对于公共卫生监测和干预措施的实施具有重要意义。因此，这篇论文属于LLM应用类别。` `公共卫生` `健康监测`

> Evaluating Large Language Models for Public Health Classification and Extraction Tasks

# 摘要

> 随着大型语言模型（LLMs）技术的进步，其在公共卫生等领域的应用潜力引起了广泛关注。本研究通过自动化评估，探讨了LLMs在处理自由文本分类和提取等公共卫生任务中的表现。我们整合了六个外部数据集和七个内部新标注的数据集，专门评估LLMs在健康负担、流行病学风险因素及公共卫生干预相关文本处理上的能力。初步测试了五种参数规模从70亿到700亿的LLMs，在零-shot上下文学习下的表现。结果显示，Llama-3-70B-Instruct模型在17项任务中15项上表现最佳。尽管在某些如接触分类的挑战性任务上，所有模型的微观F1分数未超过60%，但在其他如胃肠道疾病分类任务上，所有LLMs的微观F1分数均超过80%。此外，GPT-4在12项任务中的表现与Llama-3-70B-Instruct相当，后者在6项任务上与GPT-4持平或更优。这些初步结果表明，LLMs有望成为公共卫生专家的有力工具，帮助他们从多样化的文本资源中提取信息，进而支持公共卫生监测、研究和实施干预措施。

> Advances in Large Language Models (LLMs) have led to significant interest in their potential to support human experts across a range of domains, including public health. In this work we present automated evaluations of LLMs for public health tasks involving the classification and extraction of free text. We combine six externally annotated datasets with seven new internally annotated datasets to evaluate LLMs for processing text related to: health burden, epidemiological risk factors, and public health interventions. We initially evaluate five open-weight LLMs (7-70 billion parameters) across all tasks using zero-shot in-context learning. We find that Llama-3-70B-Instruct is the highest performing model, achieving the best results on 15/17 tasks (using micro-F1 scores). We see significant variation across tasks with all open-weight LLMs scoring below 60% micro-F1 on some challenging tasks, such as Contact Classification, while all LLMs achieve greater than 80% micro-F1 on others, such as GI Illness Classification. For a subset of 12 tasks, we also evaluate GPT-4 and find comparable results to Llama-3-70B-Instruct, which scores equally or outperforms GPT-4 on 6 of the 12 tasks. Overall, based on these initial results we find promising signs that LLMs may be useful tools for public health experts to extract information from a wide variety of free text sources, and support public health surveillance, research, and interventions.

[Arxiv](https://arxiv.org/abs/2405.14766)