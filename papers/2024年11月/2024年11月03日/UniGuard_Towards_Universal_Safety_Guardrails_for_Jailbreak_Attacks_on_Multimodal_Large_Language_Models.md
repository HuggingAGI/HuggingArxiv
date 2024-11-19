# UniGuard：致力于为多模态大型语言模型的越狱攻击打造通用安全护栏

发布时间：2024年11月03日

`LLM应用` `多模态` `语言模型`

> UniGuard: Towards Universal Safety Guardrails for Jailbreak Attacks on Multimodal Large Language Models

# 摘要

> 多模态大型语言模型（MLLMs）极大地革新了视觉语言理解，然而却易受多模态越狱攻击，在此类攻击中，对手精心设计输入来引发有害或不当的回应。我们提出了 UniGuard，这是一种新型的多模态安全防护栏，它同时考虑了单模态和跨模态的有害信号。UniGuard 经过训练，能将在有毒语料库中生成有害回应的可能性降到最低，并且在推理时能以极低的计算成本无缝应用于任何输入提示。大量实验表明，UniGuard 在多种模态和攻击策略中具有通用性。它在包括 LLaVA、Gemini Pro、GPT-4、MiniGPT-4 和 InstructBLIP 等多个最先进的 MLLMs 中展现出了出色的通用性，从而拓宽了我们解决方案的适用范围。

> Multimodal large language models (MLLMs) have revolutionized vision-language understanding but are vulnerable to multimodal jailbreak attacks, where adversaries meticulously craft inputs to elicit harmful or inappropriate responses. We propose UniGuard, a novel multimodal safety guardrail that jointly considers the unimodal and cross-modal harmful signals. UniGuard is trained such that the likelihood of generating harmful responses in a toxic corpus is minimized, and can be seamlessly applied to any input prompt during inference with minimal computational costs. Extensive experiments demonstrate the generalizability of UniGuard across multiple modalities and attack strategies. It demonstrates impressive generalizability across multiple state-of-the-art MLLMs, including LLaVA, Gemini Pro, GPT-4, MiniGPT-4, and InstructBLIP, thereby broadening the scope of our solution.

[Arxiv](https://arxiv.org/abs/2411.01703)