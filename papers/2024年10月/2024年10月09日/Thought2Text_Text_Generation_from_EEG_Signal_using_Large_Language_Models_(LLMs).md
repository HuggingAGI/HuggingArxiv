# Thought2Text：借助 LLM 将 EEG 信号转化为文本

发布时间：2024年10月09日

`LLM应用` `神经科学`

> Thought2Text: Text Generation from EEG Signal using Large Language Models (LLMs)

# 摘要

> 将大脑活动转化为可理解的文本是 AI 领域的一大挑战。本文提出的 Thought2Text 系统，通过微调大型语言模型 (LLM) 与 EEG 数据，实现了这一目标。该系统分三步走：首先，训练 EEG 编码器提取视觉特征；其次，微调 LLM 处理图像和文本数据，生成多模态描述；最后，进一步微调以直接从 EEG 数据生成文本。实验结果表明，多模态 LLM 在处理 EEG 数据时表现出色，得到了传统评估指标、GPT-4 评估及专家评审的验证。这一技术为低成本、便携式的“思维转文本”设备铺平了道路，有望在神经科学和 NLP 领域大放异彩。

> Decoding and expressing brain activity in a comprehensible form is a challenging frontier in AI. This paper presents Thought2Text, which uses instruction-tuned Large Language Models (LLMs) fine-tuned with EEG data to achieve this goal. The approach involves three stages: (1) training an EEG encoder for visual feature extraction, (2) fine-tuning LLMs on image and text data, enabling multimodal description generation, and (3) further fine-tuning on EEG embeddings to generate text directly from EEG during inference. Experiments on a public EEG dataset collected for six subjects with image stimuli demonstrate the efficacy of multimodal LLMs (LLaMa-v3, Mistral-v0.3, Qwen2.5), validated using traditional language generation evaluation metrics, GPT-4 based assessments, and evaluations by human expert. This approach marks a significant advancement towards portable, low-cost "thoughts-to-text" technology with potential applications in both neuroscience and natural language processing (NLP).

[Arxiv](https://arxiv.org/abs/2410.07507)