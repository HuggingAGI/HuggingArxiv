# 偏好对齐是否总能提升基于 LLM 的翻译效果？一项实证研究揭示真相。

发布时间：2024年09月30日

`LLM应用` `机器翻译`

> Is Preference Alignment Always the Best Option to Enhance LLM-Based Translation? An Empirical Analysis

# 摘要

> 神经度量在机器翻译评估中因其优于传统词汇度量的人类判断相关性而日益突出。研究人员通过质量引导的解码策略利用这些度量，取得了比基于似然的方法更好的结果。随着大型语言模型的兴起，基于偏好的对齐技术因其通过优化由质量估计器诱导的偏好的模型权重来提升翻译质量的潜力而受到关注。本研究聚焦于对比偏好优化 (CPO)，并进行了广泛实验来评估其对翻译质量的影响。结果显示，尽管 CPO 在高质量数据上的对齐度量方面优于监督微调 (SFT)，但在下游评估度量上可能存在不稳定性，尤其是在神经度量和词汇度量之间。此外，我们发现，仅依赖基础模型生成候选翻译即可达到与使用多个外部系统相当的性能，同时确保下游度量之间更好的稳定性。

> Neural metrics for machine translation (MT) evaluation have become increasingly prominent due to their superior correlation with human judgments compared to traditional lexical metrics. Researchers have therefore utilized neural metrics through quality-informed decoding strategies, achieving better results than likelihood-based methods. With the rise of Large Language Models (LLMs), preference-based alignment techniques have gained attention for their potential to enhance translation quality by optimizing model weights directly on preferences induced by quality estimators. This study focuses on Contrastive Preference Optimization (CPO) and conducts extensive experiments to evaluate the impact of preference-based alignment on translation quality. Our findings indicate that while CPO consistently outperforms Supervised Fine-Tuning (SFT) on high-quality data with regard to the alignment metric, it may lead to instability across downstream evaluation metrics, particularly between neural and lexical ones. Additionally, we demonstrate that relying solely on the base model for generating candidate translations achieves performance comparable to using multiple external systems, while ensuring better consistency across downstream metrics.

[Arxiv](https://arxiv.org/abs/2409.20059)