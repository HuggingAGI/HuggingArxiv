# MetaAlign：在推理时将大型语言模型与多样偏好精准匹配

发布时间：2024年10月18日

`LLM理论` `人工智能`

> MetaAlign: Align Large Language Models with Diverse Preferences during Inference Time

# 摘要

> 大型语言模型（LLM）通过海量文本语料库积累了丰富的知识和能力，成为多领域应用的利器。为了让 LLM 更贴近人类需求，对齐人类偏好至关重要。现有技术如 RLHF 和 DPO，虽能将预设偏好嵌入模型，但往往导致静态对齐，难以应对人类偏好的多样性。为此，我们提出了 MetaAlign 方法，旨在让 LLM 在推理时动态适应各种偏好。实验证明，基于 MetaAlign 数据集优化的 LLM 能灵活对齐不同偏好，验证了 MetaAlign 的可行性。我们期待这项研究能为语言模型的对齐提供新思路。

> Large Language Models (LLMs) acquire extensive knowledge and remarkable abilities from extensive text corpora, making them powerful tools for various applications. To make LLMs more usable, aligning them with human preferences is essential. Existing alignment techniques, such as Reinforcement Learning from Human Feedback (RLHF) and Direct Preference Optimization (DPO), typically embed predefined preferences directly within the model's parameters. These methods, however, often result in a static alignment that can not account for the diversity of human preferences in practical applications. In response to this challenge, we propose an effective method, \textbf{MetaAlign}, which aims to help LLMs dynamically align with various explicit or implicit preferences specified at inference time. Experimental results show that LLMs optimized on our meticulously constructed MetaAlign Dataset can effectively align with any preferences specified at the inference stage, validating the feasibility of MetaAlign. We hope that our work can provide some insights into the alignment of language models.

[Arxiv](https://arxiv.org/abs/2410.14184)