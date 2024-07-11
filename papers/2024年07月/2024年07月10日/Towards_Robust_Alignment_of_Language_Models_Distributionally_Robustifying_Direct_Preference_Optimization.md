# 致力于提升语言模型的对齐稳健性：通过分布式稳健化方法优化直接偏好

发布时间：2024年07月10日

`LLM理论` `人工智能`

> Towards Robust Alignment of Language Models: Distributionally Robustifying Direct Preference Optimization

# 摘要

> 本研究针对DPO训练数据集中的噪声问题，提出了一种增强LLM与人类偏好对齐的方法。我们区分了点态噪声和成对噪声，并利用DRO技术提升DPO的抗噪能力。理论分析表明，DPO天然具备DRO特性，特别是正则化系数$β$对抗噪至关重要。进一步，我们创新性地提出了Dr. DPO，通过优化最差成对情况，增强成对鲁棒性。Dr. DPO中的$β'$参数精细调控数据对可靠性，实现噪声环境下的探索与利用平衡。实证结果显示，Dr. DPO在各类环境下均显著提升文本质量和响应准确性。相关代码已公开于https://github.com/junkangwu/Dr_DPO。

> This study addresses the challenge of noise in training datasets for Direct Preference Optimization (DPO), a method for aligning Large Language Models (LLMs) with human preferences. We categorize noise into pointwise noise, which includes low-quality data points, and pairwise noise, which encompasses erroneous data pair associations that affect preference rankings. Utilizing Distributionally Robust Optimization (DRO), we enhance DPO's resilience to these types of noise. Our theoretical insights reveal that DPO inherently embeds DRO principles, conferring robustness to pointwise noise, with the regularization coefficient $β$ playing a critical role in its noise resistance. Extending this framework, we introduce Distributionally Robustifying DPO (Dr. DPO), which integrates pairwise robustness by optimizing against worst-case pairwise scenarios. The novel hyperparameter $β'$ in Dr. DPO allows for fine-tuned control over data pair reliability, providing a strategic balance between exploration and exploitation in noisy training environments. Empirical evaluations demonstrate that Dr. DPO substantially improves the quality of generated text and response accuracy in preference datasets, showcasing enhanced performance in both noisy and noise-free settings. The code is available at https://github.com/junkangwu/Dr_DPO.

[Arxiv](https://arxiv.org/abs/2407.07880)