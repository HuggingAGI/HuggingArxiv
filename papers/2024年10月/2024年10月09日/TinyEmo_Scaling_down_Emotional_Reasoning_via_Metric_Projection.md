# TinyEmo：通过度量投影简化情感推理

发布时间：2024年10月09日

`LLM应用` `情感分析` `人工智能`

> TinyEmo: Scaling down Emotional Reasoning via Metric Projection

# 摘要

> 本文推出 TinyEmo，一款专为情感推理和分类设计的小型多模态语言模型。我们的方法包括：(1) 合成情感指令数据集，用于预训练和微调；(2) 度量投影器，提升训练和推理效率；(3) 多模态大型语言模型，助力情感推理；(4) 半自动化偏见检测框架。TinyEmo 以更少参数实现情感分类和推理，性能超越更大规模的先进模型。此外，度量投影器无需额外训练即可提升模型可解释性和偏见检测，助力 AI 系统优化。我们在 https://github.com/ggcr/TinyEmo 分享了代码、模型和数据集。

> This paper introduces TinyEmo, a family of small multi-modal language models for emotional reasoning and classification. Our approach features: (1) a synthetic emotional instruct dataset for both pre-training and fine-tuning stages, (2) a Metric Projector that delegates classification from the language model allowing for more efficient training and inference, (3) a multi-modal large language model (MM-LLM) for emotional reasoning, and (4) a semi-automated framework for bias detection. TinyEmo is able to perform emotion classification and emotional reasoning, all while using substantially fewer parameters than comparable models. This efficiency allows us to freely incorporate more diverse emotional datasets, enabling strong performance on classification tasks, with our smallest model (700M parameters) outperforming larger state-of-the-art models based on general-purpose MM-LLMs with over 7B parameters. Additionally, the Metric Projector allows for interpretability and indirect bias detection in large models without additional training, offering an approach to understand and improve AI systems.
  We release code, models, and dataset at https://github.com/ggcr/TinyEmo

[Arxiv](https://arxiv.org/abs/2410.07062)