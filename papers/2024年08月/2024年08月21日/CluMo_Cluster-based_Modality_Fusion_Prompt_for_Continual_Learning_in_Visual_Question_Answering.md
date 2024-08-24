# CluMo：一种基于聚类的模态融合提示方法，专为视觉问答领域的持续学习设计。

发布时间：2024年08月21日

`LLM应用` `人工智能` `持续学习`

> CluMo: Cluster-based Modality Fusion Prompt for Continual Learning in Visual Question Answering

# 摘要

> 大型视觉-语言模型（VLMs）在多个领域表现出色，但应用于连续任务时面临挑战，因为微调可能导致泛化能力下降和灾难性遗忘。为此，我们提出了一种基于提示的持续学习方法CluMo，通过创新的Key-Key-Prompt对和两阶段训练策略，有效提升了泛化能力并防止遗忘。实验证明，CluMo在多模态持续学习中表现卓越。

> Large vision-language models (VLMs) have shown significant performance boost in various application domains. However, adopting them to deal with several sequentially encountered tasks has been challenging because finetuning a VLM on a task normally leads to reducing its generalization power and the capacity of learning new tasks as well as causing catastrophic forgetting on previously learned tasks. Enabling using VLMs in multimodal continual learning (CL) settings can help to address such scenarios. To improve generalization capacity and prevent catastrophic forgetting, we propose a novel prompt-based CL method for VLMs, namely $\textbf{Clu}$ster-based $\textbf{Mo}$dality Fusion Prompt (\textbf{CluMo}). We design a novel \textbf{Key-Key-Prompt} pair, where each prompt is associated with a visual prompt key and a textual prompt key. We adopt a two-stage training strategy. During the first stage, the single-modal keys are trained via $K$-means clustering algorithm to help select the best semantically matched prompt. During the second stage, the prompt keys are frozen, the selected prompt is attached to the input for training the VLM in the CL scenario. Experiments on two benchmarks demonstrate that our method achieves SOTA performance.

[Arxiv](https://arxiv.org/abs/2408.11742)