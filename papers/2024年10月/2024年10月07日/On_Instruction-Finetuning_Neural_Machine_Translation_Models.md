# 探索神经机器翻译模型的指令微调

发布时间：2024年10月07日

`LLM应用` `人工智能`

> On Instruction-Finetuning Neural Machine Translation Models

# 摘要

> 我们在这项研究中，通过指令微调技术，将大型语言模型的指令遵循能力融入到更小型的神经机器翻译模型中。这种微调方法不仅使翻译模型能够处理多样化的翻译任务，还能同时执行多个指令，甚至实现指令的零-shot 组合。此外，通过指令微调，传统上需要分别处理的任务，如形式控制翻译、多领域适应和多模态翻译，现在可以由单一的微调模型高效处理，性能媲美 GPT-3.5-Turbo。这项工作首次展示了传统 NMT 模型在指令遵循方面的潜力，为定制翻译的快速、经济和高效提供打开了新的大门。

> In this work, we introduce instruction finetuning for Neural Machine Translation (NMT) models, which distills instruction following capabilities from Large Language Models (LLMs) into orders-of-magnitude smaller NMT models. Our instruction-finetuning recipe for NMT models enables customization of translations for a limited but disparate set of translation-specific tasks. We show that NMT models are capable of following multiple instructions simultaneously and demonstrate capabilities of zero-shot composition of instructions. We also show that through instruction finetuning, traditionally disparate tasks such as formality-controlled machine translation, multi-domain adaptation as well as multi-modal translations can be tackled jointly by a single instruction finetuned NMT model, at a performance level comparable to LLMs such as GPT-3.5-Turbo. To the best of our knowledge, our work is among the first to demonstrate the instruction-following capabilities of traditional NMT models, which allows for faster, cheaper and more efficient serving of customized translations.

[Arxiv](https://arxiv.org/abs/2410.05553)