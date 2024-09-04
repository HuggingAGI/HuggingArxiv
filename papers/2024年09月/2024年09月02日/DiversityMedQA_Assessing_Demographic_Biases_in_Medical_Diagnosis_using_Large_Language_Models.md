# DiversityMedQA 项目旨在通过大型语言模型，评估医疗诊断中存在的群体偏见。

发布时间：2024年09月02日

`LLM应用` `人工智能`

> DiversityMedQA: Assessing Demographic Biases in Medical Diagnosis using Large Language Models

# 摘要

> 随着 LLM 在医疗领域的普及，其对人口统计偏差的敏感性引起了关注。为此，我们推出了 {DiversityMedQA} 基准，专门评估 LLM 在处理不同性别和种族背景患者的医疗问题时的表现。通过对 MedQA 数据集中的问题进行调整，我们构建了一个能够反映不同患者特征下医疗诊断差异的基准。研究结果显示，模型在应对这些人口统计差异时的性能存在显著波动。为确保调整的准确性，我们还设计了一种过滤策略来验证每项调整。通过发布 DiversityMedQA，我们为业界提供了一个工具，用以评估并减少 LLM 在医疗诊断中的偏见。

> As large language models (LLMs) gain traction in healthcare, concerns about their susceptibility to demographic biases are growing. We introduce {DiversityMedQA}, a novel benchmark designed to assess LLM responses to medical queries across diverse patient demographics, such as gender and ethnicity. By perturbing questions from the MedQA dataset, which comprises medical board exam questions, we created a benchmark that captures the nuanced differences in medical diagnosis across varying patient profiles. Our findings reveal notable discrepancies in model performance when tested against these demographic variations. Furthermore, to ensure the perturbations were accurate, we also propose a filtering strategy that validates each perturbation. By releasing DiversityMedQA, we provide a resource for evaluating and mitigating demographic bias in LLM medical diagnoses.

[Arxiv](https://arxiv.org/abs/2409.01497)