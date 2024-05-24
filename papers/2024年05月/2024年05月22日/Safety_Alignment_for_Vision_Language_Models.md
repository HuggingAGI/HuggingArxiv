# 视觉语言模型的安全对齐研究

发布时间：2024年05月22日

`LLM应用

这篇论文主要讨论了如何通过引入安全模块和采用两阶段训练来提升视觉语言模型（VLMs）的安全性，特别是在防御风险图像攻击方面的应用。这种方法利用了大型语言模型（LLMs）的能力，并专注于提高VLMs的安全性，而不是探讨LLMs的理论基础或Agent的行为。因此，它更适合归类于LLM应用。` `多模态学习`

> Safety Alignment for Vision Language Models

# 摘要

> 借助大型语言模型（LLMs）的强大功能，预训练的视觉编码器与LLMs结合，能够构建视觉语言模型（VLMs）。但研究发现，VLMs的视觉模态安全性较低，攻击者能轻易利用视觉特征绕过LLMs的安全机制进行攻击。为此，我们通过引入安全投影器、安全令牌和安全头等安全模块，并采用两阶段训练，显著提升了VLMs对风险图像的防御能力。以LLaVA-v1.5模型为例，我们在RTVLM基准上取得了8.26的安全评分，超越了GPT-4V。我们的方法不仅操作简便、灵活性强、控制力高，且在不影响模型整体性能的前提下，大幅提升了安全性。此外，我们的对齐策略还揭示了常见开源多模态数据集中潜在的风险内容。代码将在匿名评审后公开。

> Benefiting from the powerful capabilities of Large Language Models (LLMs), pre-trained visual encoder models connected to an LLMs can realize Vision Language Models (VLMs). However, existing research shows that the visual modality of VLMs is vulnerable, with attackers easily bypassing LLMs' safety alignment through visual modality features to launch attacks. To address this issue, we enhance the existing VLMs' visual modality safety alignment by adding safety modules, including a safety projector, safety tokens, and a safety head, through a two-stage training process, effectively improving the model's defense against risky images. For example, building upon the LLaVA-v1.5 model, we achieve a safety score of 8.26, surpassing the GPT-4V on the Red Teaming Visual Language Models (RTVLM) benchmark. Our method boasts ease of use, high flexibility, and strong controllability, and it enhances safety while having minimal impact on the model's general performance. Moreover, our alignment strategy also uncovers some possible risky content within commonly used open-source multimodal datasets. Our code will be open sourced after the anonymous review.

[Arxiv](https://arxiv.org/abs/2405.13581)