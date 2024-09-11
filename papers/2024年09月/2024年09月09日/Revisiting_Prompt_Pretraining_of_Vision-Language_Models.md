# 重探视觉-语言模型的提示预训练

发布时间：2024年09月09日

`LLM应用` `计算机视觉` `人工智能`

> Revisiting Prompt Pretraining of Vision-Language Models

# 摘要

> 提示学习通过调整少量输入提示标记的参数，成为定制视觉-语言模型 (VLM) 以应对各种下游任务的有效方法。然而，我们发现，在大规模数据集 (如 ImageNet-21K) 中的提示预训练虽关键，但有限的可用提示可能导致欠拟合和泛化能力差。为此，我们提出了重新审视提示预训练 (RPP) 框架，从提示结构和提示监督两方面提升拟合与泛化能力。在提示结构上，我们打破常规，引入非共享的独立查询、键和值可学习提示，增加参数多样性以增强模型拟合能力。在提示监督上，我们利用预训练的对比语言图像预训练 (CLIP) 教师模型提供的零-shot 概率预测软标签，提供更细致的类间关系洞察，增强泛化能力。RPP 不仅产生更具弹性的提示初始化，还显著提升其在多样视觉识别任务中的鲁棒可迁移性。实验结果表明，我们的预训练提示在多个基准测试中均达到最新 (SOTA) 性能。代码和模型即将发布。

> Prompt learning is an effective method to customize Vision-Language Models (VLMs) for various downstream tasks, involving tuning very few parameters of input prompt tokens. Recently, prompt pretraining in large-scale dataset (e.g., ImageNet-21K) has played a crucial role in prompt learning for universal visual discrimination. However, we revisit and observe that the limited learnable prompts could face underfitting risks given the extensive images during prompt pretraining, simultaneously leading to poor generalization. To address the above issues, in this paper, we propose a general framework termed Revisiting Prompt Pretraining (RPP), which targets at improving the fitting and generalization ability from two aspects: prompt structure and prompt supervision. For prompt structure, we break the restriction in common practice where query, key, and value vectors are derived from the shared learnable prompt token. Instead, we introduce unshared individual query, key, and value learnable prompts, thereby enhancing the model's fitting capacity through increased parameter diversity. For prompt supervision, we additionally utilize soft labels derived from zero-shot probability predictions provided by a pretrained Contrastive Language Image Pretraining (CLIP) teacher model. These soft labels yield more nuanced and general insights into the inter-class relationships, thereby endowing the pretraining process with better generalization ability. RPP produces a more resilient prompt initialization, enhancing its robust transferability across diverse visual recognition tasks. Experiments across various benchmarks consistently confirm the state-of-the-art (SOTA) performance of our pretrained prompts. Codes and models will be made available soon.

[Arxiv](https://arxiv.org/abs/2409.06166)