# 根塑造果实：关于对齐语言模型中性别排他性危害的持续性

发布时间：2024年11月06日

`LLM应用` `性别研究`

> The Root Shapes the Fruit: On the Persistence of Gender-Exclusive Harms in Aligned Language Models

# 摘要

> 自然语言助手旨在为用户提供有用的响应，同时避免有害的输出，这在很大程度上是通过与人类偏好对齐来实现的。然而，对于对齐技术是否可能无意中延续甚至放大从其预对齐的基础模型继承的有害偏差，理解有限。这个问题因流行的偏好微调模型中偏差评估基准的选择而变得更加复杂，这些基准主要关注占主导地位的社会类别，如二元性别，从而限制了对影响代表性不足群体的偏差的洞察。为了解决这一差距，我们以跨性别、非二元和其他性别多样化身份为中心，研究对齐程序如何与 LLM 中预先存在的性别多样化偏差相互作用。我们的主要贡献包括：1）对领先的偏好微调 LLM 中的偏差评估模式进行全面调查，突出性别多样化表示中的关键差距，2）对跨越直接偏好优化（DPO）阶段的 12 个模型中的性别多样化偏差进行系统评估，揭示流行偏差基准未能检测到的危害，3）一个用于测量适用于其他社会背景的隐式奖励信号中的有害偏差的灵活框架。我们的研究结果表明，DPO 对齐的模型对有监督的微调（SFT）特别敏感，并且可以从其基础模型中放大两种现实世界中的性别多样化危害：污名化和否定性别的语言。我们最后针对 DPO 和更广泛的对齐实践提出了建议，主张采用社区知情的偏差评估框架，以更有效地识别和解决 LLM 中代表性不足的危害。

> Natural-language assistants are designed to provide users with helpful responses while avoiding harmful outputs, largely achieved through alignment to human preferences. Yet there is limited understanding of whether alignment techniques may inadvertently perpetuate or even amplify harmful biases inherited from their pre-aligned base models. This issue is compounded by the choice of bias evaluation benchmarks in popular preference-finetuned models, which predominantly focus on dominant social categories, such as binary gender, thereby limiting insights into biases affecting underrepresented groups. Towards addressing this gap, we center transgender, nonbinary, and other gender-diverse identities to investigate how alignment procedures interact with pre-existing gender-diverse bias in LLMs. Our key contributions include: 1) a comprehensive survey of bias evaluation modalities across leading preference-finetuned LLMs, highlighting critical gaps in gender-diverse representation, 2) systematic evaluation of gender-diverse biases across 12 models spanning Direct Preference Optimization (DPO) stages, uncovering harms popular bias benchmarks fail to detect, and 3) a flexible framework for measuring harmful biases in implicit reward signals applicable to other social contexts. Our findings reveal that DPO-aligned models are particularly sensitive to supervised finetuning (SFT), and can amplify two forms of real-world gender-diverse harms from their base models: stigmatization and gender non-affirmative language. We conclude with recommendations tailored to DPO and broader alignment practices, advocating for the adoption of community-informed bias evaluation frameworks to more effectively identify and address underrepresented harms in LLMs.

[Arxiv](https://arxiv.org/abs/2411.03700)