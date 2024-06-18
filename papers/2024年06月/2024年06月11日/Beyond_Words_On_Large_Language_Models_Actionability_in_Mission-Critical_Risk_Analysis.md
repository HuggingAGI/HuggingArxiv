# 超越文字：探讨大型语言模型在关键任务风险分析中的实际应用能力

发布时间：2024年06月11日

`RAG

理由：这篇论文主要探讨了检索增强生成技术（RAG）与微调大型语言模型在风险分析中的应用和效能。论文通过实验对比了不同版本的LLMs（包括基础模型、检索增强模型和微调模型）在风险分析任务中的表现，并特别强调了RAG辅助的LLMs在揭示潜在风险方面的优势。因此，这篇论文更符合RAG分类，因为它专注于RAG技术在特定应用场景（风险分析）中的实际效能和优化。` `风险分析` `信息技术安全`

> Beyond Words: On Large Language Models Actionability in Mission-Critical Risk Analysis

# 摘要

> 风险分析旨在评估特定情境下的潜在风险，其原则通用，可应用于健康或信息技术安全等领域。此过程需深入了解国内外法规与标准，既耗时又费力。大型语言模型在此领域展现出优势，能迅速提炼信息，并针对特定任务进行优化。本研究旨在探究检索增强生成技术与微调大型语言模型在风险分析中的实际效能，填补了该领域的研究空白。我们精心挑选了\totalscenarios个场景，从过去五年中50余项关键任务分析中提取了\totalsamples个代表性样本，对比了基础GPT-3.5与GPT-4及其检索增强与微调版本。同时，我们邀请了两位人类专家与模型竞争，三位专家负责评审模型与人类专家的分析结果。评审涵盖了5,000个场景分析。结果显示，人类专家在准确性上更胜一筹，但大型语言模型在速度和操作性上占优。特别是RAG辅助的LLMs，其幻觉率最低，能有效揭示潜在风险，补充人类专业知识。因此，选择模型应根据具体需求：追求准确性可选FTMs，探索隐藏风险则选RAG，而基础模型适用于全面性和操作性。专家可利用LLMs在短时间内高效辅助风险分析，同时避免不必要的成本支出。

> Context. Risk analysis assesses potential risks in specific scenarios. Risk analysis principles are context-less; the same methodology can be applied to a risk connected to health and information technology security. Risk analysis requires a vast knowledge of national and international regulations and standards and is time and effort-intensive. A large language model can quickly summarize information in less time than a human and can be fine-tuned to specific tasks. Aim. Our empirical study aims to investigate the effectiveness of Retrieval-Augmented Generation and fine-tuned LLM in Risk analysis. To our knowledge, no prior study has explored its capabilities in risk analysis. Method. We manually curated \totalscenarios unique scenarios leading to \totalsamples representative samples from over 50 mission-critical analyses archived by the industrial context team in the last five years. We compared the base GPT-3.5 and GPT-4 models versus their Retrieval-Augmented Generation and fine-tuned counterparts. We employ two human experts as competitors of the models and three other three human experts to review the models and the former human expert's analysis. The reviewers analyzed 5,000 scenario analyses. Results and Conclusions. HEs demonstrated higher accuracy, but LLMs are quicker and more actionable. Moreover, our findings show that RAG-assisted LLMs have the lowest hallucination rates, effectively uncovering hidden risks and complementing human expertise. Thus, the choice of model depends on specific needs, with FTMs for accuracy, RAG for hidden risks discovery, and base models for comprehensiveness and actionability. Therefore, experts can leverage LLMs for an effective complementing companion in risk analysis within a condensed timeframe. They can also save costs by averting unnecessary expenses associated with implementing unwarranted countermeasures.

[Arxiv](https://arxiv.org/abs/2406.10273)