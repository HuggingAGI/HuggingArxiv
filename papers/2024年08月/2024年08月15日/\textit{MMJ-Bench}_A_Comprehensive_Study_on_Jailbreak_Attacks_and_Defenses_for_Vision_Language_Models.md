# MMJ-Bench：深入探讨视觉语言模型中的越狱攻击与防御策略

发布时间：2024年08月15日

`LLM应用` `人工智能`

> \textit{MMJ-Bench}: A Comprehensive Study on Jailbreak Attacks and Defenses for Vision Language Models

# 摘要

> 随着深度学习的发展，大型语言模型（LLMs）和视觉-语言模型（VLMs）在众多实际任务中表现出色。但VLMs面临严重安全挑战，如越狱攻击，攻击者试图绕过安全机制引发有害响应。这些威胁源于LLMs的固有漏洞和VLMs处理的多信息通道。尽管已有多种攻击和防御方法，但缺乏统一评估，因每种方法在不同数据集和指标上评估，难以比较其有效性。为此，我们推出MMJ-Bench，一个统一评估VLMs越狱攻击和防御的流程。通过广泛实验，我们评估了攻击方法对先进VLMs的有效性，并考察了防御机制对防御效果和模型正常任务实用性的影响。我们的全面评估不仅提供了统一系统框架，还发布了首个公开VLM越狱研究基准，并揭示了未来研究方向。

> As deep learning advances, Large Language Models (LLMs) and their multimodal counterparts, Vision-Language Models (VLMs), have shown exceptional performance in many real-world tasks. However, VLMs face significant security challenges, such as jailbreak attacks, where attackers attempt to bypass the model's safety alignment to elicit harmful responses. The threat of jailbreak attacks on VLMs arises from both the inherent vulnerabilities of LLMs and the multiple information channels that VLMs process. While various attacks and defenses have been proposed, there is a notable gap in unified and comprehensive evaluations, as each method is evaluated on different dataset and metrics, making it impossible to compare the effectiveness of each method. To address this gap, we introduce \textit{MMJ-Bench}, a unified pipeline for evaluating jailbreak attacks and defense techniques for VLMs. Through extensive experiments, we assess the effectiveness of various attack methods against SoTA VLMs and evaluate the impact of defense mechanisms on both defense effectiveness and model utility for normal tasks. Our comprehensive evaluation contribute to the field by offering a unified and systematic evaluation framework and the first public-available benchmark for VLM jailbreak research. We also demonstrate several insightful findings that highlights directions for future studies.

[Arxiv](https://arxiv.org/abs/2408.08464)