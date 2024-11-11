# 基于大型语言模型（LLM）的轴承故障诊断框架

发布时间：2024年11月04日

`LLM应用` `故障诊断`

> LLM-based Framework for Bearing Fault Diagnosis

# 摘要

> 准确诊断轴承故障对于维持旋转机械的高效运行至关重要。然而，由于应用环境的多样化，传统诊断方法面临挑战，包括跨工况适应性、小样本学习困难和跨数据集泛化。这些挑战阻碍了现有方法的有效性并限制了其应用。大型语言模型（LLMs）为提高诊断模型的泛化能力提供了新的可能性。然而，将 LLMs 与传统诊断技术集成以实现最佳泛化仍未得到充分探索。本文提出了一种基于 LLMs 的轴承故障诊断框架来应对这些挑战。首先，提出了一种信号特征量化方法来解决从振动数据中提取语义信息的问题，该方法基于统计分析框架集成了时域和频域特征提取。该方法将时间序列数据文本化，旨在通过简洁的特征选择有效地学习跨工况和小样本的共同特征。采用基于 LoRA 和 QLoRA 的微调方法来增强 LLMs 在分析振动数据特征方面的泛化能力。此外，通过具有完整和有限数据的单数据集跨工况和跨数据集迁移实验验证了这两项创新（振动特征文本化和预训练模型微调）。结果表明，所提出的框架能够同时执行三种泛化任务。跨数据集训练的模型在准确性上大约提高了 10％，证明了 LLMs 对输入模式的适应性。最终，结果有效地增强了泛化能力，并填补了在轴承故障诊断中使用 LLMs 的研究空白。

> Accurately diagnosing bearing faults is crucial for maintaining the efficient operation of rotating machinery. However, traditional diagnosis methods face challenges due to the diversification of application environments, including cross-condition adaptability, small-sample learning difficulties, and cross-dataset generalization. These challenges have hindered the effectiveness and limited the application of existing approaches. Large language models (LLMs) offer new possibilities for improving the generalization of diagnosis models. However, the integration of LLMs with traditional diagnosis techniques for optimal generalization remains underexplored. This paper proposed an LLM-based bearing fault diagnosis framework to tackle these challenges. First, a signal feature quantification method was put forward to address the issue of extracting semantic information from vibration data, which integrated time and frequency domain feature extraction based on a statistical analysis framework. This method textualized time-series data, aiming to efficiently learn cross-condition and small-sample common features through concise feature selection. Fine-tuning methods based on LoRA and QLoRA were employed to enhance the generalization capability of LLMs in analyzing vibration data features. In addition, the two innovations (textualizing vibration features and fine-tuning pre-trained models) were validated by single-dataset cross-condition and cross-dataset transfer experiment with complete and limited data. The results demonstrated the ability of the proposed framework to perform three types of generalization tasks simultaneously. Trained cross-dataset models got approximately a 10% improvement in accuracy, proving the adaptability of LLMs to input patterns. Ultimately, the results effectively enhance the generalization capability and fill the research gap in using LLMs for bearing fault diagnosis.

[Arxiv](https://arxiv.org/abs/2411.02718)