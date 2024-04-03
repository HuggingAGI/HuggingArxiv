# 通过对比集对大型语言模型进行评估：探索性实验途径

发布时间：2024年04月01日

`LLM应用` `机器学习`

> Evaluating Large Language Models Using Contrast Sets: An Experimental Approach

# 摘要

> 自然语言推理（NLI）领域，尤其是面对多文本分类任务时，交叉熵损失度量作为误差评估的标准被普遍采用。然而，这一度量标准在衡量模型对语言蕴含理解的深度上力有不逮。本研究提出了一种创新方法，为斯坦福自然语言推理（SNLI）数据集构建对比集。通过自动将句中的动词、副词和形容词替换为其同义词，保持句子原意不变，我们旨在验证模型是否真正理解了语言，抑或仅仅是识别出了模式。利用ELECTRA-small模型进行分析，该模型在标准SNLI数据集上准确率高达89.9%，但在新构建的对比集上准确率降至72.5%，降幅达17%。这一发现促使我们深入探究模型的学习行为。通过使用专为SNLI设计的、增强对比度的训练数据集对模型进行微调，我们成功提升了其在对比集上的准确率至85.5%。我们的研究结果凸显了为NLI任务数据集融入丰富语言表达的必要性。我们期望这项研究能激发更多全面数据集的构建，进而推动NLI模型向更精细、更有效的方向发展。

> In the domain of Natural Language Inference (NLI), especially in tasks involving the classification of multiple input texts, the Cross-Entropy Loss metric is widely employed as a standard for error measurement. However, this metric falls short in effectively evaluating a model's capacity to understand language entailments. In this study, we introduce an innovative technique for generating a contrast set for the Stanford Natural Language Inference (SNLI) dataset. Our strategy involves the automated substitution of verbs, adverbs, and adjectives with their synonyms to preserve the original meaning of sentences. This method aims to assess whether a model's performance is based on genuine language comprehension or simply on pattern recognition. We conducted our analysis using the ELECTRA-small model. The model achieved an accuracy of 89.9% on the conventional SNLI dataset but showed a reduced accuracy of 72.5% on our contrast set, indicating a substantial 17% decline. This outcome led us to conduct a detailed examination of the model's learning behaviors. Following this, we improved the model's resilience by fine-tuning it with a contrast-enhanced training dataset specifically designed for SNLI, which increased its accuracy to 85.5% on the contrast sets. Our findings highlight the importance of incorporating diverse linguistic expressions into datasets for NLI tasks. We hope that our research will encourage the creation of more inclusive datasets, thereby contributing to the development of NLI models that are both more sophisticated and effective.

[Arxiv](https://arxiv.org/abs/2404.01569)