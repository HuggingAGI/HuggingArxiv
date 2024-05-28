# 安全LoRA：微调大型语言模型时降低安全风险的希望之光

发布时间：2024年05月27日

`LLM应用

这篇论文主要讨论了在大型语言模型（LLMs）中使用参数高效微调技术（如LoRA）时可能出现的安全问题，并提出了一种名为Safe LoRA的解决方案。该解决方案通过简单的代码补丁来降低微调过程中的安全风险，同时保持模型的实用性。这种技术特别关注于如何在微调过程中保护模型免受恶意数据的影响，同时确保模型在下游任务中的性能。因此，这篇论文的内容更偏向于LLM的实际应用，特别是在微调技术中的安全性和实用性问题。` `人工智能安全` `模型微调`

> Safe LoRA: the Silver Lining of Reducing Safety Risks when Fine-tuning Large Language Models

# 摘要

> 尽管大型语言模型如Llama-2或GPT-4已展现出卓越的零-shot能力，但在定制数据集、特定领域任务或私人需求上，微调仍是提升性能的关键。然而，全面微调LLMs的参数对普通用户而言，资源消耗巨大。为此，LoRA等参数高效微调技术应运而生，让用户无需大量计算资源即可微调模型，且性能损失微乎其微。遗憾的是，最新研究揭示，即便数据无害，微调也可能加剧LLMs的安全隐患。为此，我们开发了Safe LoRA，这一简单的一行代码补丁通过将LoRA权重投影至安全对齐子空间，既降低了微调中的安全风险，又保持了模型的实用性。值得一提的是，Safe LoRA无需训练和数据，仅需基础模型和对齐模型的权重信息。我们的实验证明，即使在恶意数据上微调，Safe LoRA也能维持与原始对齐模型相当的安全水平。当数据集混杂良性和恶意内容时，Safe LoRA有效缓解了恶意数据的影响，同时确保了下游任务的性能。

> While large language models (LLMs) such as Llama-2 or GPT-4 have shown impressive zero-shot performance, fine-tuning is still necessary to enhance their performance for customized datasets, domain-specific tasks, or other private needs. However, fine-tuning all parameters of LLMs requires significant hardware resources, which can be impractical for typical users. Therefore, parameter-efficient fine-tuning such as LoRA have emerged, allowing users to fine-tune LLMs without the need for considerable computing resources, with little performance degradation compared to fine-tuning all parameters. Unfortunately, recent studies indicate that fine-tuning can increase the risk to the safety of LLMs, even when data does not contain malicious content. To address this challenge, we propose Safe LoRA, a simple one-liner patch to the original LoRA implementation by introducing the projection of LoRA weights from selected layers to the safety-aligned subspace, effectively reducing the safety risks in LLM fine-tuning while maintaining utility. It is worth noting that Safe LoRA is a training-free and data-free approach, as it only requires the knowledge of the weights from the base and aligned LLMs. Our extensive experiments demonstrate that when fine-tuning on purely malicious data, Safe LoRA retains similar safety performance as the original aligned model. Moreover, when the fine-tuning dataset contains a mixture of both benign and malicious data, Safe LoRA mitigates the negative effect made by malicious data while preserving performance on downstream tasks.

![安全LoRA：微调大型语言模型时降低安全风险的希望之光](../../../paper_images/2405.16833/x1.png)

![安全LoRA：微调大型语言模型时降低安全风险的希望之光](../../../paper_images/2405.16833/x2.png)

![安全LoRA：微调大型语言模型时降低安全风险的希望之光](../../../paper_images/2405.16833/x3.png)

![安全LoRA：微调大型语言模型时降低安全风险的希望之光](../../../paper_images/2405.16833/x4.png)

![安全LoRA：微调大型语言模型时降低安全风险的希望之光](../../../paper_images/2405.16833/x5.png)

[Arxiv](https://arxiv.org/abs/2405.16833)