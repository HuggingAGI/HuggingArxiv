# 文字之外：探究大型语言模型在关键任务风险分析中的实际应用能力

发布时间：2024年06月11日

`RAG

理由：这篇论文主要探讨了检索增强生成（RAG）和微调大型语言模型（LLMs）在风险分析中的应用。通过对比基础模型和增强模型的表现，论文展示了RAG辅助的LLMs在揭示潜在风险方面的有效性。因此，这篇论文更符合RAG分类，因为它专注于RAG技术在特定应用场景（风险分析）中的实际应用和效果评估。` `风险分析` `信息技术安全`

> Beyond Words: On Large Language Models Actionability in Mission-Critical Risk Analysis

# 摘要

> 风险分析旨在评估特定情境下的潜在风险，其原则具有普适性，可应用于健康或信息技术安全等领域。这项工作需要深入了解国内外法规与标准，且耗时费力。大型语言模型在此领域展现出优势，能迅速处理信息，并针对特定任务进行优化。我们的研究首次探索了检索增强生成和微调大型语言模型在风险分析中的应用。通过精心挑选的\totalscenarios个场景，我们提取了\totalsamples个样本，这些样本源自过去五年中工业界的关键任务分析。我们对比了基础GPT-3.5和GPT-4与其检索增强和微调版本的表现，并邀请了两位人类专家与模型竞争，三位专家进行评审。评审涵盖了5,000个场景分析。结果表明，尽管人类专家在准确性上占优，但大型语言模型在速度和实用性上更胜一筹。特别是RAG辅助的LLMs，其幻觉率最低，能有效揭示潜在风险，补充人类专家的能力。因此，根据需求选择模型：追求准确性可选微调模型，发现隐藏风险则依赖RAG，而基础模型提供全面性和操作性。专家可利用LLMs在短时间内高效辅助风险分析，同时避免不必要的成本支出。

> Context. Risk analysis assesses potential risks in specific scenarios. Risk analysis principles are context-less; the same methodology can be applied to a risk connected to health and information technology security. Risk analysis requires a vast knowledge of national and international regulations and standards and is time and effort-intensive. A large language model can quickly summarize information in less time than a human and can be fine-tuned to specific tasks. Aim. Our empirical study aims to investigate the effectiveness of Retrieval-Augmented Generation and fine-tuned LLM in Risk analysis. To our knowledge, no prior study has explored its capabilities in risk analysis. Method. We manually curated \totalscenarios unique scenarios leading to \totalsamples representative samples from over 50 mission-critical analyses archived by the industrial context team in the last five years. We compared the base GPT-3.5 and GPT-4 models versus their Retrieval-Augmented Generation and fine-tuned counterparts. We employ two human experts as competitors of the models and three other three human experts to review the models and the former human expert's analysis. The reviewers analyzed 5,000 scenario analyses. Results and Conclusions. HEs demonstrated higher accuracy, but LLMs are quicker and more actionable. Moreover, our findings show that RAG-assisted LLMs have the lowest hallucination rates, effectively uncovering hidden risks and complementing human expertise. Thus, the choice of model depends on specific needs, with FTMs for accuracy, RAG for hidden risks discovery, and base models for comprehensiveness and actionability. Therefore, experts can leverage LLMs for an effective complementing companion in risk analysis within a condensed timeframe. They can also save costs by averting unnecessary expenses associated with implementing unwarranted countermeasures.

[Arxiv](https://arxiv.org/abs/2406.10273)