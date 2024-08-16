# FuseChat：融合聊天模型中的知识

发布时间：2024年08月15日

`LLM理论` `人工智能` `软件开发`

> FuseChat: Knowledge Fusion of Chat Models

# 摘要

> 尽管从头训练大型语言模型 (LLM) 能带来独特优势，但成本高昂且可能造成能力冗余。为此，我们提出知识融合，通过轻量级持续训练整合不同架构的 LLM，打造更强大的模型，减少开发成本。我们的新框架 FuseChat 分两步走：首先，对不同源聊天 LLM 进行成对融合，通过轻量级微调生成结构一致的目标 LLM，并引入基于统计的令牌对齐方法；其次，在参数空间内合并这些目标 LLM，并创新性地根据微调前后参数更新幅度确定合并系数。我们用六个不同架构的聊天 LLM 验证了 FuseChat，实验表明，FuseChat-7B 在 AlpacaEval 2.0 和 MT-Bench 上表现优异，甚至与更大模型相媲美，接近 GPT-3.5-Turbo-1106。相关代码和数据已公开在 \url{https://github.com/fanqiwan/FuseAI}。

> While training large language models (LLMs) from scratch can indeed lead to models with distinct capabilities and strengths, it incurs substantial costs and may lead to redundancy in competencies. Knowledge fusion aims to integrate existing LLMs of diverse architectures and capabilities into a more potent LLM through lightweight continual training, thereby reducing the need for costly LLM development. In this work, we propose a new framework for the knowledge fusion of chat LLMs through two main stages, resulting in FuseChat. Firstly, we conduct pairwise knowledge fusion on source chat LLMs of varying structures and scales to create multiple target LLMs with identical structure and size via lightweight fine-tuning. During this process, a statistics-based token alignment approach is introduced as the cornerstone for fusing LLMs with different structures. Secondly, we merge these target LLMs within the parameter space, where we propose a novel method for determining the merging coefficients based on the magnitude of parameter updates before and after fine-tuning. We implement and validate FuseChat using six prominent chat LLMs with diverse architectures and scales, including OpenChat-3.5-7B, Starling-LM-7B-alpha, NH2-SOLAR-10.7B, InternLM2-Chat-20B, Mixtral-8x7B-Instruct, and Qwen-1.5-Chat-72B. Experimental results on two instruction-following benchmarks, AlpacaEval 2.0 and MT-Bench, demonstrate the superiority of FuseChat-7B over baselines of various sizes. Our model is even comparable to the larger Mixtral-8x7B-Instruct and approaches GPT-3.5-Turbo-1106 on MT-Bench. Our code, model weights, and data are public at \url{https://github.com/fanqiwan/FuseAI}.

[Arxiv](https://arxiv.org/abs/2408.07990)