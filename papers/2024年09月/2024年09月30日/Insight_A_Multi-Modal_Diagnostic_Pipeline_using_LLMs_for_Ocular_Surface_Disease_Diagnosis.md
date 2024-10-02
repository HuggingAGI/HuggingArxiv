# Insight：基于 LLM 的眼表疾病多模态诊断流程

发布时间：2024年09月30日

`LLM应用`

> Insight: A Multi-Modal Diagnostic Pipeline using LLMs for Ocular Surface Disease Diagnosis

# 摘要

> 眼表疾病的准确诊断在眼科和眼视光学中至关重要，依赖于整合临床数据源。传统人工评估缺乏精确性，而现有机器方法常将诊断简化为多类分类问题，限制了诊断的灵活性和临床相关性。为此，我们创新性地引入了多模态诊断管道（MDPipe），利用大型语言模型（LLMs）进行眼表疾病诊断。首先，我们通过视觉翻译器将睑板腺图像转换为可量化的形态数据，与临床元数据整合，使LLMs能够传达细微的医学见解。接着，我们引入基于LLM的总结器，情境化结合形态和临床元数据的见解，生成临床报告摘要。最后，通过真实临床医生诊断的领域特定见解，完善LLMs的推理能力。评估结果显示，MDPipe不仅超越现有标准，包括GPT-4，还为诊断提供了临床上合理的理由。

> Accurate diagnosis of ocular surface diseases is critical in optometry and ophthalmology, which hinge on integrating clinical data sources (e.g., meibography imaging and clinical metadata). Traditional human assessments lack precision in quantifying clinical observations, while current machine-based methods often treat diagnoses as multi-class classification problems, limiting the diagnoses to a predefined closed-set of curated answers without reasoning the clinical relevance of each variable to the diagnosis. To tackle these challenges, we introduce an innovative multi-modal diagnostic pipeline (MDPipe) by employing large language models (LLMs) for ocular surface disease diagnosis. We first employ a visual translator to interpret meibography images by converting them into quantifiable morphology data, facilitating their integration with clinical metadata and enabling the communication of nuanced medical insight to LLMs. To further advance this communication, we introduce a LLM-based summarizer to contextualize the insight from the combined morphology and clinical metadata, and generate clinical report summaries. Finally, we refine the LLMs' reasoning ability with domain-specific insight from real-life clinician diagnoses. Our evaluation across diverse ocular surface disease diagnosis benchmarks demonstrates that MDPipe outperforms existing standards, including GPT-4, and provides clinically sound rationales for diagnoses.

[Arxiv](https://arxiv.org/abs/2410.00292)