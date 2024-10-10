# SpaLLM：通过草图技术实现大型语言模型的统一压缩适应

发布时间：2024年10月08日

`LLM理论` `人工智能`

> SpaLLM: Unified Compressive Adaptation of Large Language Models with Sketching

# 摘要

> 压缩适应方法如QLoRA，在微调大型语言模型（LLMs）时，既能减少内存需求，又能生成处理多种下游任务的模型。其核心在于“双塔”架构：将预训练的LLM参数压缩成紧凑形式，并微调低秩格式的加性全精度适配器。然而，严格的低秩假设和双塔架构的复杂性，导致精度与效率的权衡不佳。为此，我们提出SpaLLM，一种创新的LLM压缩适应方法，首次展示无需严格低秩假设的参数共享压缩。SpaLLM将模型压缩与适应合二为一，简化流程，避免双塔架构。它将预训练的LLM权重草图化为查找表，直接微调表中值，简化工作流程，提升多用户服务效率，显著提高自然语言理解和生成任务的准确性。此外，每层仅需一次压缩矩阵乘法，推理效率优于以往方法。

> Compressive adaptation approaches, such as QLoRA, are widely popular alternatives for reducing memory requirements during fine-tuning of large language models (LLMs) while producing models capable of handling various downstream tasks. The key idea is to employ a "two-tower" architecture: compressing pre-trained LLM parameters into compact representations and fine-tuning the additive full-precision adapter, which typically has few tunable parameters in low-rank format. However, the strict algebraic assumptions, such as low-rank assumption, and the complexity of composing two-tower architectures are some of the known shortcomings, resulting in a poor accuracy-efficiency trade-off. In response to these known limitations, we propose SpaLLM (Sketched Parameter Adaptation of LLMs), a novel compressive adaptation approach for LLMs. This method is also the first to illustrate parameter-sharing compression methods for LLM fine-tuning, which, unlike QLoRA, are free from strict low-rank algebraic assumptions on adapters. Furthermore, our proposal unifies model compression and adaptation into a single, streamlined process, eliminating the need for two-tower architectures. SpaLLM sketches pre-trained LLM weights into lookup tables and directly fine-tunes the values in these tables. This approach simplifies LLMs' compressive adaptation workflow, potentially improves multi-user serving efficiency, and delivers significantly better accuracy for both natural language understanding and generation tasks. Moreover, by avoiding the "two-tower" architecture, our framework only requires one compressed matrix multiplication per layer during inference, demonstrating superior inference efficiency compared to previous methods.

[Arxiv](https://arxiv.org/abs/2410.06364)