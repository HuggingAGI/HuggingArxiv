# 跨医疗关怀：探究预训练数据如何塑造语言模型偏见，及其对医疗领域的深远影响在这项研究中，我们将深入探讨预训练数据如何影响语言模型的偏见，并分析这些偏见如何渗透到医疗决策中，从而对患者的护理产生潜在影响。我们的目标是揭示这些偏见的根源，并提出策略以减轻其对医疗保健系统的负面影响。

发布时间：2024年05月08日

`LLM理论

这篇论文关注的是大型语言模型（LLMs）中的偏见和现实世界知识的准确性问题，特别是关于不同人口群体中疾病流行率的表示。它提出了一个名为Cross-Care的基准框架来评估这些偏见，并探讨了预训练语料库中的种族偏见如何影响LLMs的输出。这项研究不仅揭示了偏见的存在，还量化了这些偏见，并指出了医学应用中偏见传播的风险。因此，这篇论文更偏向于LLM的理论研究，因为它探讨了模型的内部机制和输出结果的准确性，而不是直接应用于某个特定的Agent或RAG系统，也不是关于LLM的具体应用案例。` `医疗健康`

> Cross-Care: Assessing the Healthcare Implications of Pre-training Data on Language Model Bias

# 摘要

> 大型语言模型（LLMs）在自然语言处理中扮演着越来越关键的角色，但其应用常因训练数据中的偏见和错误而受损。本研究推出了Cross-Care，首个专注于评估LLMs中偏见和现实世界知识的基准框架，特别聚焦于不同人口群体中疾病流行率的准确表示。我们系统地探讨了预训练语料库中的种族偏见如何影响LLMs的输出，并通过与实际疾病流行率对比，揭示并量化了这些偏见。研究结果显示，LLMs对疾病流行率的描述与实际数据在不同人口群体中存在显著差异，暗示了医学应用中偏见传播的风险和现实世界知识的缺失。我们还发现，尽管采用了多种对齐方法，模型在不同语言中对疾病流行率的描述仍存在不一致。为促进深入研究，我们提供了所有数据和一个数据可视化工具，访问网址为：www.crosscare.net。

> Large language models (LLMs) are increasingly essential in processing natural languages, yet their application is frequently compromised by biases and inaccuracies originating in their training data. In this study, we introduce Cross-Care, the first benchmark framework dedicated to assessing biases and real world knowledge in LLMs, specifically focusing on the representation of disease prevalence across diverse demographic groups. We systematically evaluate how demographic biases embedded in pre-training corpora like $ThePile$ influence the outputs of LLMs. We expose and quantify discrepancies by juxtaposing these biases against actual disease prevalences in various U.S. demographic groups. Our results highlight substantial misalignment between LLM representation of disease prevalence and real disease prevalence rates across demographic subgroups, indicating a pronounced risk of bias propagation and a lack of real-world grounding for medical applications of LLMs. Furthermore, we observe that various alignment methods minimally resolve inconsistencies in the models' representation of disease prevalence across different languages. For further exploration and analysis, we make all data and a data visualization tool available at: www.crosscare.net.

[Arxiv](https://arxiv.org/abs/2405.05506)