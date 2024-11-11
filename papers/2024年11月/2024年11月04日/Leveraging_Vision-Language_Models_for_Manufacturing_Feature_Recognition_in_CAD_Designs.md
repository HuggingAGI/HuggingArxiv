# 利用视觉语言模型进行 CAD 设计中的制造特征识别

发布时间：2024年11月04日

`LLM应用` `CAD 设计`

> Leveraging Vision-Language Models for Manufacturing Feature Recognition in CAD Designs

# 摘要

> 自动特征识别（AFR）对于将设计知识转化为可操作的制造信息至关重要。传统的 AFR 方法依赖于预定义的几何规则和大型数据集，通常耗时且在各种制造特征上缺乏通用性。为了应对这些挑战，本研究探讨了视觉语言模型（VLMs），用于在 CAD 设计中自动识别各种制造特征，无需大量训练数据集或预定义规则。相反，应用了提示工程技术，如多视图查询图像、少样本学习、顺序推理和思维链，以实现识别。该方法在新开发的 CAD 数据集中进行评估，该数据集包含与机械加工、增材制造、钣金成型、模具和铸造相关的不同复杂程度的设计。五个 VLMs，包括三个闭源模型（GPT-4o、Claude-3.5-Sonnet 和 Claude-3.0-Opus）和两个开源模型（LLava 和 MiniCPM），在这个由专家标记了真实特征的数据集上进行评估。关键指标包括特征数量准确性、特征名称匹配准确性、幻觉率和平均绝对误差（MAE）。结果表明，Claude-3.5-Sonnet 实现了最高的特征数量准确性（74％）和名称匹配准确性（75％），MAE 最低（3.2），而 GPT-4o 的幻觉率最低（8％）。相比之下，开源模型的幻觉率较高（> 30％），准确性较低（< 40％）。本研究展示了 VLMs 在不同制造场景中的 CAD 设计中自动特征识别的潜力。

> Automatic feature recognition (AFR) is essential for transforming design knowledge into actionable manufacturing information. Traditional AFR methods, which rely on predefined geometric rules and large datasets, are often time-consuming and lack generalizability across various manufacturing features. To address these challenges, this study investigates vision-language models (VLMs) for automating the recognition of a wide range of manufacturing features in CAD designs without the need for extensive training datasets or predefined rules. Instead, prompt engineering techniques, such as multi-view query images, few-shot learning, sequential reasoning, and chain-of-thought, are applied to enable recognition. The approach is evaluated on a newly developed CAD dataset containing designs of varying complexity relevant to machining, additive manufacturing, sheet metal forming, molding, and casting. Five VLMs, including three closed-source models (GPT-4o, Claude-3.5-Sonnet, and Claude-3.0-Opus) and two open-source models (LLava and MiniCPM), are evaluated on this dataset with ground truth features labelled by experts. Key metrics include feature quantity accuracy, feature name matching accuracy, hallucination rate, and mean absolute error (MAE). Results show that Claude-3.5-Sonnet achieves the highest feature quantity accuracy (74%) and name-matching accuracy (75%) with the lowest MAE (3.2), while GPT-4o records the lowest hallucination rate (8%). In contrast, open-source models have higher hallucination rates (>30%) and lower accuracies (<40%). This study demonstrates the potential of VLMs to automate feature recognition in CAD designs within diverse manufacturing scenarios.

[Arxiv](https://arxiv.org/abs/2411.02810)