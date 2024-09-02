# 大型语言模型的安全层对齐：确保 LLM 安全的核心

发布时间：2024年08月30日

`LLM理论` `人工智能`

> Safety Layers of Aligned Large Language Models: The Key to LLM Security

# 摘要

> 对齐的LLMs高度安全，能识别并拒绝恶意问题。但内部参数在维护安全中的作用不明，且易受非恶意数据微调影响。我们揭示了参数级安全机制，识别出关键的“安全层”。通过分析输入向量变化和参数缩放，我们确认并定位了这些层。基于此，提出安全部分参数微调（SPPFT），固定安全层梯度，有效防止安全降级。实验显示，该方法在保持性能的同时，显著提升了安全性并节省了计算资源。

> Aligned LLMs are highly secure, capable of recognizing and refusing to answer malicious questions. However, the role of internal parameters in maintaining this security is not well understood, further these models are vulnerable to security degradation when fine-tuned with non-malicious backdoor data or normal data. To address these challenges, our work uncovers the mechanism behind security in aligned LLMs at the parameter level, identifying a small set of contiguous layers in the middle of the model that are crucial for distinguishing malicious queries from normal ones, referred to as "safety layers." We first confirm the existence of these safety layers by analyzing variations in input vectors within the model's internal layers. Additionally, we leverage the over-rejection phenomenon and parameters scaling analysis to precisely locate the safety layers. Building on this understanding, we propose a novel fine-tuning approach, Safely Partial-Parameter Fine-Tuning (SPPFT), that fixes the gradient of the safety layers during fine-tuning to address the security degradation. Our experiments demonstrate that this approach significantly preserves model security while maintaining performance and reducing computational resources compared to full fine-tuning.

[Arxiv](https://arxiv.org/abs/2408.17003)