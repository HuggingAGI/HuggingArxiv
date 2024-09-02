# 遗忘以繁荣：借助预训练语言模型中的机器遗忘技术，守护隐私安全。

发布时间：2024年08月30日

`LLM应用` `网络安全` `人工智能`

> Forget to Flourish: Leveraging Machine-Unlearning on Pretrained Language Models for Privacy Leakage

# 摘要

> 微调大型语言模型以适应私有数据，虽能提升下游应用性能，却也潜藏隐私泄露之虞。当前，众多社区平台便捷地分发各类预训练模型，发布门槛低，审核不严，这无疑为隐私安全埋下隐患。预训练模型若被恶意设计，便可能成为窥探微调数据隐私的工具。为此，我们创新性地提出一种利用模型遗忘机制的攻击技术，旨在微调过程中加剧数据泄露。该技术不仅提升了成员推理和数据提取攻击的效果，还巧妙地维持了模型的实用性。跨模型、数据集及微调环境的实验均证实，我们的攻击手段远超传统基线。此项研究警示用户，从非官方渠道获取预训练模型需谨慎，以防不测之风险。

> Fine-tuning large language models on private data for downstream applications poses significant privacy risks in potentially exposing sensitive information. Several popular community platforms now offer convenient distribution of a large variety of pre-trained models, allowing anyone to publish without rigorous verification. This scenario creates a privacy threat, as pre-trained models can be intentionally crafted to compromise the privacy of fine-tuning datasets. In this study, we introduce a novel poisoning technique that uses model-unlearning as an attack tool. This approach manipulates a pre-trained language model to increase the leakage of private data during the fine-tuning process. Our method enhances both membership inference and data extraction attacks while preserving model utility. Experimental results across different models, datasets, and fine-tuning setups demonstrate that our attacks significantly surpass baseline performance. This work serves as a cautionary note for users who download pre-trained models from unverified sources, highlighting the potential risks involved.

[Arxiv](https://arxiv.org/abs/2408.17354)