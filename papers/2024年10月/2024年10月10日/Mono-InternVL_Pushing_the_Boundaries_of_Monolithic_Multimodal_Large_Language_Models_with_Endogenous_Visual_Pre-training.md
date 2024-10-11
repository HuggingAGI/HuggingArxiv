# Mono-InternVL：借助内生视觉预训练，拓展单体多模态大型语言模型的极限

发布时间：2024年10月10日

`LLM应用` `人工智能` `计算机视觉`

> Mono-InternVL: Pushing the Boundaries of Monolithic Multimodal Large Language Models with Endogenous Visual Pre-training

# 摘要

> 随着 LLM 的迅猛发展，将其能力扩展到多模态任务的研究如雨后春笋般涌现。其中，单体多模态大型语言模型 (MLLM) 备受瞩目，它将视觉与语言处理融为一体。尽管结构简单、便于部署，但训练高性能的单体 MLLM 仍充满挑战。常见方法通过连续预训练扩展 LLM，却常遭遇灾难性遗忘，导致性能下滑。本文从增量调优视角出发，提出将视觉参数嵌入预训练 LLM，逐步学习视觉知识，同时冻结 LLM。基于此，我们打造了 Mono-InternVL，通过多模态专家混合结构集成视觉专家。此外，创新的内生视觉预训练 (EViP) 策略，使视觉专家从噪声数据到高质量数据渐进学习。实验表明，Mono-InternVL 在多模态基准上表现卓越，部署效率也显著提升。

> The rapid advancement of Large Language Models (LLMs) has led to an influx of efforts to extend their capabilities to multimodal tasks. Among them, growing attention has been focused on monolithic Multimodal Large Language Models (MLLMs) that integrate visual encoding and language decoding into a single LLM. Despite the structural simplicity and deployment-friendliness, training a monolithic MLLM with promising performance still remains challenging. In particular, the popular approaches adopt continuous pre-training to extend a pre-trained LLM to a monolithic MLLM, which suffers from catastrophic forgetting and leads to performance degeneration. In this paper, we aim to overcome this limitation from the perspective of delta tuning. Specifically, our core idea is to embed visual parameters into a pre-trained LLM, thereby incrementally learning visual knowledge from massive data via delta tuning, i.e., freezing the LLM when optimizing the visual parameters. Based on this principle, we present Mono-InternVL, a novel monolithic MLLM that seamlessly integrates a set of visual experts via a multimodal mixture-of-experts structure. Moreover, we propose an innovative pre-training strategy to maximize the visual capability of Mono-InternVL, namely Endogenous Visual Pre-training (EViP). In particular, EViP is designed as a progressive learning process for visual experts, which aims to fully exploit the visual knowledge from noisy data to high-quality data. To validate our approach, we conduct extensive experiments on 16 benchmarks. Experimental results not only validate the superior performance of Mono-InternVL compared to the state-of-the-art MLLM on 6 multimodal benchmarks, e.g., +113 points over InternVL-1.5 on OCRBench, but also confirm its better deployment efficiency, with first token latency reduced by up to 67%.

[Arxiv](https://arxiv.org/abs/2410.08202)