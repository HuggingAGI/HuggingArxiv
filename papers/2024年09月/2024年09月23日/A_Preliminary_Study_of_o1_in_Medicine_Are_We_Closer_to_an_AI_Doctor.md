# 医学领域 o1 的初步探索：AI 医生，我们是否已近在咫尺？

发布时间：2024年09月23日

`LLM应用` `人工智能`

> A Preliminary Study of o1 in Medicine: Are We Closer to an AI Doctor?

# 摘要

> OpenAI 的最新模型 o1，作为首个集成强化学习策略的链式思维技术 LLM，在通用语言任务中表现出色。然而，其在医学领域的性能尚待探索。本报告深入研究了 o1 在医疗场景中的表现，聚焦于理解、推理和多语言能力三大关键方面。我们评估了 6 个任务，涉及 37 个医疗数据集，包括基于 NEJM 和《柳叶刀》专业测验的新型复杂问答任务。这些数据集比标准医疗 QA 基准更具临床相关性，更贴近实际应用。分析显示，o1 的增强推理能力显著提升了其理解和应对复杂临床场景的能力。在 19 个数据集和两个新场景中，o1 的准确性分别比 GPT-4 高出 6.2% 和 6.6%。然而，我们也发现了模型和评估协议中的若干不足，如幻觉现象、多语言能力不一致和评估指标不统一。我们将在 https://ucsc-vlaa.github.io/o1_medicine/ 公开原始数据和模型输出，供后续研究参考。

> Large language models (LLMs) have exhibited remarkable capabilities across various domains and tasks, pushing the boundaries of our knowledge in learning and cognition. The latest model, OpenAI's o1, stands out as the first LLM with an internalized chain-of-thought technique using reinforcement learning strategies. While it has demonstrated surprisingly strong capabilities on various general language tasks, its performance in specialized fields such as medicine remains unknown. To this end, this report provides a comprehensive exploration of o1 on different medical scenarios, examining 3 key aspects: understanding, reasoning, and multilinguality. Specifically, our evaluation encompasses 6 tasks using data from 37 medical datasets, including two newly constructed and more challenging question-answering (QA) tasks based on professional medical quizzes from the New England Journal of Medicine (NEJM) and The Lancet. These datasets offer greater clinical relevance compared to standard medical QA benchmarks such as MedQA, translating more effectively into real-world clinical utility. Our analysis of o1 suggests that the enhanced reasoning ability of LLMs may (significantly) benefit their capability to understand various medical instructions and reason through complex clinical scenarios. Notably, o1 surpasses the previous GPT-4 in accuracy by an average of 6.2% and 6.6% across 19 datasets and two newly created complex QA scenarios. But meanwhile, we identify several weaknesses in both the model capability and the existing evaluation protocols, including hallucination, inconsistent multilingual ability, and discrepant metrics for evaluation. We release our raw data and model outputs at https://ucsc-vlaa.github.io/o1_medicine/ for future research.

[Arxiv](https://arxiv.org/abs/2409.15277)