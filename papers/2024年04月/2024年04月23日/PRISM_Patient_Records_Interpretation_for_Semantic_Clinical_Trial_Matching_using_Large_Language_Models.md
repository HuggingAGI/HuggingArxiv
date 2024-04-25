# PRISM：利用大型语言模型，对患者病历进行深入解读，以实现语义化的临床试验匹配。

发布时间：2024年04月23日

`LLM应用` `临床试验`

> PRISM: Patient Records Interpretation for Semantic Clinical Trial Matching using Large Language Models

# 摘要

> 临床试验匹配旨在为患者筛选出他们可能符合条件参与的试验。这一任务通常既繁琐又耗时，需要对患者的电子健康档案进行详尽核对，以符合临床试验的严格标准。这种手动流程不仅效率低下，而且难以扩展，导致众多患者错失潜在治疗机会。幸运的是，大型语言模型（LLMs）的最新进展为自动化患者与试验的匹配提供了可能，这一点已在多项研究中得到证实。尽管如此，现有方法多局限于简化或合成数据集，这些数据集并未充分模拟现实医疗数据的复杂性。本研究首次进行了大规模的实证评估，采用真实世界的电子健康记录（EHRs）来匹配临床试验。我们的研究证明了LLMs在精准匹配患者与临床试验方面的潜力。实验采用了包括GPT-4和GPT-3.5在内的专有LLMs，以及我们定制的微调模型OncoLLM。结果显示，尽管OncoLLM规模较小，但其表现不仅超越了GPT-3.5，更媲美专业医生的匹配效果。所有实验均基于美国一家癌症中心的真实EHRs数据，包括临床笔记和可用的临床试验信息。

> Clinical trial matching is the task of identifying trials for which patients may be potentially eligible. Typically, this task is labor-intensive and requires detailed verification of patient electronic health records (EHRs) against the stringent inclusion and exclusion criteria of clinical trials. This process is manual, time-intensive, and challenging to scale up, resulting in many patients missing out on potential therapeutic options. Recent advancements in Large Language Models (LLMs) have made automating patient-trial matching possible, as shown in multiple concurrent research studies. However, the current approaches are confined to constrained, often synthetic datasets that do not adequately mirror the complexities encountered in real-world medical data. In this study, we present the first, end-to-end large-scale empirical evaluation of clinical trial matching using real-world EHRs. Our study showcases the capability of LLMs to accurately match patients with appropriate clinical trials. We perform experiments with proprietary LLMs, including GPT-4 and GPT-3.5, as well as our custom fine-tuned model called OncoLLM and show that OncoLLM, despite its significantly smaller size, not only outperforms GPT-3.5 but also matches the performance of qualified medical doctors. All experiments were carried out on real-world EHRs that include clinical notes and available clinical trials from a single cancer center in the United States.

[Arxiv](https://arxiv.org/abs/2404.15549)