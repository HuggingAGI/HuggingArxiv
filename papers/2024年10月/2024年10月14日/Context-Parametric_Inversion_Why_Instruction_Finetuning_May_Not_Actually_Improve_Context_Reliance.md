# 指令微调未必能提升上下文依赖性，这背后的原因在于“上下文参数反转”现象。

发布时间：2024年10月14日

`LLM理论` `人工智能`

> Context-Parametric Inversion: Why Instruction Finetuning May Not Actually Improve Context Reliance

# 摘要

> 大型语言模型通过指令微调提升其遵循用户指令和处理上下文的能力。然而，即使是最先进的模型，在输入上下文与模型知识不匹配时，也常难以遵循指令，导致响应过时、有偏见或包含未验证的事实。我们发现，指令微调初期，模型对上下文的依赖性增加，但随着微调深入，这种依赖性反而减弱，这种现象称为“上下文-参数化反转”。我们在多个数据集和模型家族中观察到这一现象。通过理论分析，我们发现这种现象与微调数据中输入上下文重复模型已有知识有关。我们提出了一些缓解策略，并希望这项研究能为解决LLM训练中的这一问题提供新思路。

> Large language models are instruction-finetuned to enhance their ability to follow user instructions and process the input context. However, even state-of-the-art models often struggle to follow the instruction, especially when the input context is not aligned with the model's parametric knowledge. This manifests as various failures, such as hallucinations where the responses are outdated, biased or contain unverified facts. In this work, we try to understand the underlying reason for this poor context reliance, especially after instruction tuning. We observe an intriguing phenomenon: during instruction tuning, the context reliance initially increases as expected, but then gradually decreases as instruction finetuning progresses. We call this phenomenon context-parametric inversion and observe it across multiple general purpose instruction tuning datasets like TULU, Alpaca and Ultrachat, as well as model families such as Llama, Mistral and Pythia. In a simple theoretical setup, we isolate why context-parametric inversion occurs along the gradient descent trajectory of instruction finetuning. We tie this phenomena to examples in the instruction finetuning data mixture where the input context provides information that is already present in the model's parametric knowledge. Our analysis suggests natural mitigation strategies that provide some limited gains, while also validating our theoretical insights. We hope that our work serves as a starting point in addressing this failure mode in a staple part of LLM training.

[Arxiv](https://arxiv.org/abs/2410.10796)