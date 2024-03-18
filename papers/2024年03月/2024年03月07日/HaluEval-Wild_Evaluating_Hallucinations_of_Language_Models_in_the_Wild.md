# [HaluEval-Wild 是一项针对真实环境中的语言模型所生成的幻觉内容进行评估的研究项目。]

发布时间：2024年03月07日

`LLM应用`

> HaluEval-Wild: Evaluating Hallucinations of Language Models in the Wild

> 在关键领域，LLMs面临的幻觉问题对其可靠性构成了严峻考验。现有针对LLM在QA、摘要等传统NLP任务中幻觉现象的评测标准，并不能全面揭示真实环境下的用户与LLM交互复杂度。为此，我们创新推出首个面向真实场景LLM幻觉评估的基准——HaluEval-Wild。我们精心挑选并借助Alpaca过滤手段，从诸如ShareGPT的实际用户-LLM交互数据集中获取了一系列极具挑战性的用户查询，用以衡量各类LLMs的幻觉发生率。通过深入分析这些查询案例，我们将幻觉类型细分为五大类别，从而能更细致地剖析LLMs可能产生的幻觉类型，并运用顶尖的GPT-4模型结合检索增强生成（RAG）技术来合成参照答案。这项全新的基准测试为我们深化理解并提升真实交互情境下LLM的可靠性开辟了新的途径。

> Hallucinations pose a significant challenge to the reliability of large language models (LLMs) in critical domains. Recent benchmarks designed to assess LLM hallucinations within conventional NLP tasks, such as knowledge-intensive question answering (QA) and summarization, are insufficient for capturing the complexities of user-LLM interactions in dynamic, real-world settings. To address this gap, we introduce HaluEval-Wild, the first benchmark specifically designed to evaluate LLM hallucinations in the wild. We meticulously collect challenging (adversarially filtered by Alpaca) user queries from existing real-world user-LLM interaction datasets, including ShareGPT, to evaluate the hallucination rates of various LLMs. Upon analyzing the collected queries, we categorize them into five distinct types, which enables a fine-grained analysis of the types of hallucinations LLMs exhibit, and synthesize the reference answers with the powerful GPT-4 model and retrieval-augmented generation (RAG). Our benchmark offers a novel approach towards enhancing our comprehension and improvement of LLM reliability in scenarios reflective of real-world interactions.

[Arxiv](https://arxiv.org/abs/2403.04307)