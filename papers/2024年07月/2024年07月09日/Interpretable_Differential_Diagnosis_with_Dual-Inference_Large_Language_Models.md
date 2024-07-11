# 双重推理大型语言模型助力可解释的差异诊断

发布时间：2024年07月09日

`LLM应用` `人工智能`

> Interpretable Differential Diagnosis with Dual-Inference Large Language Models

# 摘要

> 在临床推理和决策支持应用中，自动化生成鉴别诊断（DDx）至关重要。然而，为DDx提供解释更具价值。得益于大型语言模型（LLMs）的强大语言处理能力，我们探索了其在此领域的应用。我们首先创建了一个包含570份临床笔记的DDx数据集，并附有专家解释。接着，我们提出了Dual-Inf框架，使LLMs能够进行双向推理，从而提供解释。评估结果显示，Dual-Inf在预测和解释诊断方面表现出色，性能提升显著，且在罕见疾病诊断方面展现出潜力。

> Methodological advancements to automate the generation of differential diagnosis (DDx) to predict a list of potential diseases as differentials given patients' symptom descriptions are critical to clinical reasoning and applications such as decision support. However, providing reasoning or interpretation for these differential diagnoses is more meaningful. Fortunately, large language models (LLMs) possess powerful language processing abilities and have been proven effective in various related tasks. Motivated by this potential, we investigate the use of LLMs for interpretable DDx. First, we develop a new DDx dataset with expert-derived interpretation on 570 public clinical notes. Second, we propose a novel framework, named Dual-Inf, that enables LLMs to conduct bidirectional inference for interpretation. Both human and automated evaluation demonstrate the effectiveness of Dual-Inf in predicting differentials and diagnosis explanations. Specifically, the performance improvement of Dual-Inf over the baseline methods exceeds 32% w.r.t. BERTScore in DDx interpretation. Furthermore, experiments verify that Dual-Inf (1) makes fewer errors in interpretation, (2) has great generalizability, (3) is promising for rare disease diagnosis and explanation.

[Arxiv](https://arxiv.org/abs/2407.07330)