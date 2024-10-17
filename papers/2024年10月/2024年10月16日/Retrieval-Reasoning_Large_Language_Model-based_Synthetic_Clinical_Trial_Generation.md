# 基于检索与推理的大型语言模型，用于合成临床试验的生成

发布时间：2024年10月16日

`LLM应用` `临床研究`

> Retrieval-Reasoning Large Language Model-based Synthetic Clinical Trial Generation

# 摘要

> 机器学习在临床领域潜力巨大，但受限于数据稀缺和伦理问题。临床试验因隐私法规严格、成本高昂且耗时长而面临挑战。尽管大型语言模型在通用生成任务中表现出色，但在合成临床试验生成方面的应用仍待探索。为此，我们提出了一种创新的检索-推理少样本框架，利用LLM生成逼真且多样化的合成临床试验，并附带成功/失败标签。实验证明，这些合成数据能有效增强真实数据集。通过在合成数据上微调预训练模型，我们发现这显著提升了下游任务如试验结果预测的模型训练效果。这表明，LLM在合成临床试验生成方面有望加速临床研究，同时确保患者隐私的伦理标准。相关代码已公开，详见 https://anonymous.4open.science/r/Retrieval_Reasoning_Clinical_Trial_Generation-3EC4。

> Machine learning (ML) exhibits promise in the clinical domain. However, it is constrained by data scarcity and ethical considerations, as the generation of clinical trials presents significant challenges due to stringent privacy regulations, high costs, and the extended duration required for conducting studies with human participants. Despite the advancements of large language models (LLMs) in general generation tasks, their potential in facilitating the generation of synthetic clinical trials is under-explored. To address this gap, we introduce a novel Retrieval-Reasoning few-shot framework that leverages LLMs to generate artificial yet realistic and diverse clinical trials with binary success/failure labels. Experiments conducted on real clinical trials from the \url{ClinicalTrials.gov} database demonstrate that our synthetic data can effectively augment real datasets. Furthermore, by fine-tuning a pre-trained model as a binary classifier on synthetic clinical trial datasets, we demonstrate that this augmentation enhances model training for downstream tasks such as trial outcome prediction. Our findings suggest that LLMs for synthetic clinical trial generation hold promise for accelerating clinical research and upholding ethical standards for patient privacy. The code is publicly available at https://anonymous.4open.science/r/Retrieval_Reasoning_Clinical_Trial_Generation-3EC4.

[Arxiv](https://arxiv.org/abs/2410.12476)