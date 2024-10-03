# InfiniPot：为内存受限的 LLM 提供无限上下文处理能力

发布时间：2024年10月02日

`LLM应用` `移动设备`

> InfiniPot: Infinite Context Processing on Memory-Constrained LLMs

# 摘要

> 在移动设备等资源受限的环境中，处理长输入上下文一直是 LLM 面临的难题。为此，我们推出了 InfiniPot，一个创新的 KV 缓存控制框架，让预训练 LLM 在固定内存下高效管理长序列，无需额外训练。InfiniPot 通过持续上下文蒸馏 (CCD) 技术，利用新颖的重要性度量，即使无法预见未来上下文，也能精确保留关键信息。评估显示，InfiniPot 在多项 NLP 任务中超越了专为长上下文设计的模型，展现了其卓越性能和广泛适用性。这项研究为 LLM 在更多实际场景中的应用铺平了道路。

> Handling long input contexts remains a significant challenge for Large Language Models (LLMs), particularly in resource-constrained environments such as mobile devices. Our work aims to address this limitation by introducing InfiniPot, a novel KV cache control framework designed to enable pre-trained LLMs to manage extensive sequences within fixed memory constraints efficiently, without requiring additional training. InfiniPot leverages Continual Context Distillation (CCD), an iterative process that compresses and retains essential information through novel importance metrics, effectively maintaining critical data even without access to future context. Our comprehensive evaluations indicate that InfiniPot significantly outperforms models trained for long contexts in various NLP tasks, establishing its efficacy and versatility. This work represents a substantial advancement toward making LLMs applicable to a broader range of real-world scenarios.

[Arxiv](https://arxiv.org/abs/2410.01518)