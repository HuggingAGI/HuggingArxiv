# 通过两阶段指令微调，推动医学领域多语言大型语言模型的普及化。

发布时间：2024年09月09日

`LLM应用` `人工智能`

> Towards Democratizing Multilingual Large Language Models For Medicine Through A Two-Stage Instruction Fine-tuning Approach

# 摘要

> 开源的多语言医疗 LLM 有望服务于全球语言多样化的群体。然而，将通用 LLM 应用于医疗领域通常需要昂贵的持续预训练，且有时不切实际。指令微调虽能提升特定任务性能，但因缺乏广泛的领域知识，效果有限。为此，我们推出了包含 20 万高质量医疗样本的 MMed-IFT 和 MMed-IFT-MC 数据集，并设计了两阶段训练方法：先注入通用医疗知识，再微调多项选择题。该方法在英语和多语言测试中表现优异，兼顾了计算效率与性能。未来，我们将在 \url{https://github.com/SpassMed/Med-Llama3} 公开数据集和模型权重。

> Open-source, multilingual medical large language models (LLMs) have the potential to serve linguistically diverse populations across different regions. Adapting generic LLMs for healthcare often requires continual pretraining, but this approach is computationally expensive and sometimes impractical. Instruction fine-tuning on a specific task may not always guarantee optimal performance due to the lack of broader domain knowledge that the model needs to understand and reason effectively in diverse scenarios. To address these challenges, we introduce two multilingual instruction fine-tuning datasets, MMed-IFT and MMed-IFT-MC, containing over 200k high-quality medical samples in six languages. We propose a two-stage training paradigm: the first stage injects general medical knowledge using MMed-IFT, while the second stage fine-tunes task-specific multiple-choice questions with MMed-IFT-MC. Our method achieves competitive results on both English and multilingual benchmarks, striking a balance between computational efficiency and performance. We plan to make our dataset and model weights public at \url{https://github.com/SpassMed/Med-Llama3} in the future.

[Arxiv](https://arxiv.org/abs/2409.05732)