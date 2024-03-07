# [通过属性结构化优化，我们能够提升LLM在评估临床文本摘要时的表现。](https://arxiv.org/abs/2403.01002)

发布时间：2024年03月01日

`LLM应用`

> Attribute Structuring Improves LLM-Based Evaluation of Clinical Text Summaries

> 在健康决策辅助及临床研究中，对临床文本进行精炼总结极为重要。尽管LLMs展现出了生成精确临床摘要的能力，但在涉及安全的关键领域如医疗健康时，其在实现可靠性和有效评估上仍存在问题。面对全面评估摘要过程中可能出现的无根据信息难题，本研究引入了一种基于属性结构化（AS）的通用解决方案。这一方案重塑了评估流程，将其拆解为依托LLM完成的较为简易的结构化和评分任务，而非直接对整个摘要进行整体评估。实验证明，AS在临床文本摘要中能显著提升人工标注与自动评价指标之间的一致性。而且，AS还能生成对应于各输出的简短文本片段作为解释，便于进行高效的人工审核，为在资源有限情况下对临床信息进行可信赖评估开辟了新途径。目前，我们已公开源代码、提示语句以及一个开放源码基准测试，可在https://github.com/microsoft/attribute-structuring访问获取。

> Summarizing clinical text is crucial in health decision-support and clinical research. Large language models (LLMs) have shown the potential to generate accurate clinical text summaries, but still struggle with issues regarding grounding and evaluation, especially in safety-critical domains such as health. Holistically evaluating text summaries is challenging because they may contain unsubstantiated information. Here, we explore a general mitigation framework using Attribute Structuring (AS), which structures the summary evaluation process. It decomposes the evaluation process into a grounded procedure that uses an LLM for relatively simple structuring and scoring tasks, rather than the full task of holistic summary evaluation. Experiments show that AS consistently improves the correspondence between human annotations and automated metrics in clinical text summarization. Additionally, AS yields interpretations in the form of a short text span corresponding to each output, which enables efficient human auditing, paving the way towards trustworthy evaluation of clinical information in resource-constrained scenarios. We release our code, prompts, and an open-source benchmark at https://github.com/microsoft/attribute-structuring.