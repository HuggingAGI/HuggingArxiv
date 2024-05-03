# 探讨模型架构和规模对于分子属性预测的影响：通过对 RoBERTa、BART 和 LLaMA 进行微调获得的深刻见解。

发布时间：2024年05月01日

`LLM应用` `化学信息学` `药物发现`

> The Role of Model Architecture and Scale in Predicting Molecular Properties: Insights from Fine-Tuning RoBERTa, BART, and LLaMA

# 摘要

> 本研究建立了一套系统框架，旨在对比不同大型语言模型（LLM）在化学信息学任务微调中的效能。我们采用统一的训练策略，对RoBERTa、BART和LLaMA三款知名模型进行了评估，考察它们利用简化分子输入行条目系统（SMILES）这一通用分子表示格式来预测分子属性的能力。通过预训练这些模型的18种不同配置，并在DeepChem的六个基准任务上进行微调，我们进行了深入的比较分析。为确保比较的可靠性，我们在所有模型间保持了一致的训练环境。我们的研究揭示了模型类型、规模和训练数据集大小对性能的影响。特别是，基于LLaMA的模型在验证损失上普遍表现最佳，显示出其在不同任务和规模上的卓越适应性。然而，我们发现验证损失的绝对值并非模型性能的决定性指标，这与先前的研究相矛盾，至少在微调任务中，模型大小才是关键因素。通过严格的重复和验证，包括多轮训练和微调，本研究不仅清晰地展示了各模型的优势与局限，还为特定化学信息学应用选择最合适的LLM提供了一种稳固的方法论。本研究强调了在将AI应用于分子属性预测时，考虑模型架构和数据集特性的重要性，为AI在药物发现等相关领域的更明智和有效应用奠定了基础。

> This study introduces a systematic framework to compare the efficacy of Large Language Models (LLMs) for fine-tuning across various cheminformatics tasks. Employing a uniform training methodology, we assessed three well-known models-RoBERTa, BART, and LLaMA-on their ability to predict molecular properties using the Simplified Molecular Input Line Entry System (SMILES) as a universal molecular representation format. Our comparative analysis involved pre-training 18 configurations of these models, with varying parameter sizes and dataset scales, followed by fine-tuning them on six benchmarking tasks from DeepChem. We maintained consistent training environments across models to ensure reliable comparisons. This approach allowed us to assess the influence of model type, size, and training dataset size on model performance. Specifically, we found that LLaMA-based models generally offered the lowest validation loss, suggesting their superior adaptability across tasks and scales. However, we observed that absolute validation loss is not a definitive indicator of model performance - contradicts previous research - at least for fine-tuning tasks: instead, model size plays a crucial role. Through rigorous replication and validation, involving multiple training and fine-tuning cycles, our study not only delineates the strengths and limitations of each model type but also provides a robust methodology for selecting the most suitable LLM for specific cheminformatics applications. This research underscores the importance of considering model architecture and dataset characteristics in deploying AI for molecular property prediction, paving the way for more informed and effective utilization of AI in drug discovery and related fields.

[Arxiv](https://arxiv.org/abs/2405.00949)