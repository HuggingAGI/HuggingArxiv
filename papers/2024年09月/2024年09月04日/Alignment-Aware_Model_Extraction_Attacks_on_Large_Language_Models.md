# 针对大型语言模型的对齐感知模型提取攻击

发布时间：2024年09月04日

`LLM理论` `网络安全` `人工智能`

> Alignment-Aware Model Extraction Attacks on Large Language Models

# 摘要

> 近期，针对大型语言模型的模型提取攻击备受关注。现有攻击方法虽借鉴了深度神经网络的策略，却忽视了攻击与模型对齐任务间的差异，导致攻击效果不佳。为此，我们创新性地提出了局部强化蒸馏算法，专为大型语言模型设计。该算法通过策略梯度训练，利用目标模型响应优化局部模型偏好，确保攻击收敛与模型对齐一致，同时降低查询需求并规避水印保护。实验证明，该方法在提取各类顶尖商业语言模型时表现卓越。

> Model extraction attacks (MEAs) on large language models (LLMs) have received increasing research attention lately. Existing attack methods on LLMs inherit the extraction strategies from those designed for deep neural networks (DNNs) yet neglect the inconsistency of training tasks between MEA and LLMs' alignments. As such, they result in poor attack performances. To tackle this issue, we present Locality Reinforced Distillation (LoRD), a novel model extraction attack algorithm specifically for LLMs. In particular, we design a policy-gradient-style training task, which utilizes victim models' responses as a signal to guide the crafting of preference for the local model. Theoretical analysis has shown that i) LoRD's convergence procedure in MEAs is consistent with the alignments of LLMs, and ii) LoRD can reduce query complexity while mitigating watermark protection through exploration-based stealing. Extensive experiments on domain-specific extractions demonstrate the superiority of our method by examining the extraction of various state-of-the-art commercial LLMs.

[Arxiv](https://arxiv.org/abs/2409.02718)