# FuxiTranyu：一款采用平衡数据训练的多语言大型语言模型

发布时间：2024年08月12日

`LLM应用` `人工智能`

> FuxiTranyu: A Multilingual Large Language Model Trained with Balanced Data

# 摘要

> 大型语言模型（LLM）在众多任务中表现出色，但高低资源语言间的性能差异显著。为此，我们推出了开源多语言模型 FuxiTranyu，旨在为研究界提供平衡且高效的多语言处理能力。FuxiTranyu-8B 基础模型，拥有 80 亿参数，基于一个包含 6000 亿标记、覆盖 43 种自然语言和 16 种编程语言的精心平衡数据集从头训练。此外，我们还开发了两个指令优化模型：FuxiTranyu-8B-SFT 在多样的多语言指令数据集上微调，而 FuxiTranyu-8B-DPO 通过 DPO 在偏好数据集上进一步精炼，提升对齐能力。广泛的多语言基准测试显示，FuxiTranyu 与现有模型如 BLOOM-7B、PolyLM-13B、Llama-2-Chat-7B 和 Mistral-7B-Instruct 相比，性能卓越。神经元和表示层面的分析揭示了其跨语言的一致多语言表示能力。为推动多语言 LLM 及其机制的研究，我们在 HuggingFace 和 Github 上发布了相关模型及 58 个预训练检查点。

> Large language models (LLMs) have demonstrated prowess in a wide range of tasks. However, many LLMs exhibit significant performance discrepancies between high- and low-resource languages. To mitigate this challenge, we present FuxiTranyu, an open-source multilingual LLM, which is designed to satisfy the need of the research community for balanced and high-performing multilingual capabilities. FuxiTranyu-8B, the base model with 8 billion parameters, is trained from scratch on a meticulously balanced multilingual data repository that contains 600 billion tokens covering 43 natural languages and 16 programming languages. In addition to the base model, we also develop two instruction-tuned models: FuxiTranyu-8B-SFT that is fine-tuned on a diverse multilingual instruction dataset, and FuxiTranyu-8B-DPO that is further refined with DPO on a preference dataset for enhanced alignment ability. Extensive experiments on a wide range of multilingual benchmarks demonstrate the competitive performance of FuxiTranyu against existing multilingual LLMs, e.g., BLOOM-7B, PolyLM-13B, Llama-2-Chat-7B and Mistral-7B-Instruct. Interpretability analyses at both the neuron and representation level suggest that FuxiTranyu is able to learn consistent multilingual representations across different languages. To promote further research into multilingual LLMs and their working mechanisms, we release both the base and instruction-tuned FuxiTranyu models together with 58 pretraining checkpoints at HuggingFace and Github.

[Arxiv](https://arxiv.org/abs/2408.06273)