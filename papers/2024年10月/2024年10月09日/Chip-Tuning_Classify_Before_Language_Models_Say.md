# Chip-Tuning：先分类，后语言模型发声

发布时间：2024年10月09日

`LLM理论` `人工智能` `计算机视觉`

> Chip-Tuning: Classify Before Language Models Say

# 摘要

> 随着大型语言模型（LLM）性能的飞速提升，模型规模也在不断膨胀，导致训练和推理成本水涨船高。研究发现，LLM 中的某些层存在冗余，移除这些层对性能影响甚微。本文通过探针技术揭示了这种层冗余现象，并展示了如何利用探针分类器对语言模型进行高效剪枝。我们创新性地提出了 chip-tuning，一种专为分类问题设计的简洁高效的结构化剪枝框架。Chip-tuning 将微型探针分类器（chips）嵌入 LLM 的不同层，并在保持骨干模型不变的情况下训练这些 chips。一旦选定用于分类的 chip，其后的所有层均可安全移除，性能损失几乎可以忽略不计。实验结果显示，chip-tuning 在准确性和剪枝比例上均大幅超越现有最优方法，最高剪枝比例可达 50%。此外，chip-tuning 还能无缝应用于多模态模型，并与模型微调技术完美结合，展现出卓越的兼容性。

> The rapid development in the performance of large language models (LLMs) is accompanied by the escalation of model size, leading to the increasing cost of model training and inference. Previous research has discovered that certain layers in LLMs exhibit redundancy, and removing these layers brings only marginal loss in model performance. In this paper, we adopt the probing technique to explain the layer redundancy in LLMs and demonstrate that language models can be effectively pruned with probing classifiers. We propose chip-tuning, a simple and effective structured pruning framework specialized for classification problems. Chip-tuning attaches tiny probing classifiers named chips to different layers of LLMs, and trains chips with the backbone model frozen. After selecting a chip for classification, all layers subsequent to the attached layer could be removed with marginal performance loss. Experimental results on various LLMs and datasets demonstrate that chip-tuning significantly outperforms previous state-of-the-art baselines in both accuracy and pruning ratio, achieving a pruning ratio of up to 50%. We also find that chip-tuning could be applied on multimodal models, and could be combined with model finetuning, proving its excellent compatibility.

[Arxiv](https://arxiv.org/abs/2410.06541)