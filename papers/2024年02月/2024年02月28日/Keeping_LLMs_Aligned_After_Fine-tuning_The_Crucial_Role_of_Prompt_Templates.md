# 微调之后，如何确保大型语言模型保持其原有的校准状态？关键在于巧妙设计的提示模板。

发布时间：2024年02月28日

`分类：LLM应用` `人工智能安全` `聊天机器人`

> Keeping LLMs Aligned After Fine-tuning: The Crucial Role of Prompt Templates

# 摘要

> 公共大型语言模型（LLMs），例如 Llama 2-Chat，极大地激发了 LLM 研究领域的活跃度。这些模型经过了对齐训练，被认为安全性较高。然而，Qi 等研究者在 2023 年指出，即使是基于看似安全的数据库进行的良性微调，也可能引发模型的不安全行为。本文旨在探讨减少此类对齐偏差的方法和最佳实践。通过对多种聊天模型（包括 Meta 的 Llama 2-Chat、Mistral AI 的 Mistral 7B Instruct v0.2 和 OpenAI 的 GPT-3.5 Turbo）进行广泛的实验，我们发现微调和推理过程中使用的提示模板对于维持模型的安全对齐至关重要，并提出了“纯净微调，安全测试”（PTST）原则，即在没有安全提示的情况下进行模型微调，但在测试阶段加入安全提示。在 GSM8K、ChatDoctor 和 OpenOrca 上的微调实验结果表明，PTST 方法显著降低了不安全行为的发生，并在某些情况下几乎完全避免了这类问题。

> Public LLMs such as the Llama 2-Chat have driven huge activity in LLM research. These models underwent alignment training and were considered safe. Recently Qi et al. (2023) reported that even benign fine-tuning (e.g., on seemingly safe datasets) can give rise to unsafe behaviors in the models. The current paper is about methods and best practices to mitigate such loss of alignment. Through extensive experiments on several chat models (Meta's Llama 2-Chat, Mistral AI's Mistral 7B Instruct v0.2, and OpenAI's GPT-3.5 Turbo), this paper uncovers that the prompt templates used during fine-tuning and inference play a crucial role in preserving safety alignment, and proposes the "Pure Tuning, Safe Testing" (PTST) principle -- fine-tune models without a safety prompt, but include it at test time. Fine-tuning experiments on GSM8K, ChatDoctor, and OpenOrca show that PTST significantly reduces the rise of unsafe behaviors, and even almost eliminates them in some cases.

[Arxiv](https://arxiv.org/abs/2402.18540)