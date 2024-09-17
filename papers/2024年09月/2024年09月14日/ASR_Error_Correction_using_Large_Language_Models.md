# 利用大型语言模型纠正 ASR 错误

发布时间：2024年09月14日

`LLM应用` `语音识别`

> ASR Error Correction using Large Language Models

# 摘要

> 错误纠正模型在提升自动语音识别转录的质量和可读性方面至关重要。无需深入底层代码或模型权重，EC 模型就能为黑箱 ASR 系统带来性能提升和领域适应。本文探讨了在多样场景中应用大型语言模型进行错误纠正的可能性。通常，EC 模型以 1-最佳 ASR 假设为输入，但我们提出利用 ASR N-最佳列表构建更强大的 EC 模型，以提供更丰富的上下文信息。此外，标准 EC 模型的生成过程不受限制，但在某些场景（如未见领域）中，这种灵活性可能影响性能。为此，我们提出基于 N-最佳列表或 ASR 网格的约束解码方法。大多数 EC 模型需针对特定 ASR 系统进行训练，而本文探讨了 EC 模型在不同 ASR 系统输出上的通用性，并进一步扩展到使用 LLM（如 ChatGPT）进行零-shot 错误纠正。实验结果表明，我们的方法在 Transducer 和基于注意力的编码器-解码器 ASR 系统中均表现出色，并可作为有效的模型集成手段。

> Error correction (EC) models play a crucial role in refining Automatic Speech Recognition (ASR) transcriptions, enhancing the readability and quality of transcriptions. Without requiring access to the underlying code or model weights, EC can improve performance and provide domain adaptation for black-box ASR systems. This work investigates the use of large language models (LLMs) for error correction across diverse scenarios. 1-best ASR hypotheses are commonly used as the input to EC models. We propose building high-performance EC models using ASR N-best lists which should provide more contextual information for the correction process. Additionally, the generation process of a standard EC model is unrestricted in the sense that any output sequence can be generated. For some scenarios, such as unseen domains, this flexibility may impact performance. To address this, we introduce a constrained decoding approach based on the N-best list or an ASR lattice. Finally, most EC models are trained for a specific ASR system requiring retraining whenever the underlying ASR system is changed. This paper explores the ability of EC models to operate on the output of different ASR systems. This concept is further extended to zero-shot error correction using LLMs, such as ChatGPT. Experiments on three standard datasets demonstrate the efficacy of our proposed methods for both Transducer and attention-based encoder-decoder ASR systems. In addition, the proposed method can serve as an effective method for model ensembling.

[Arxiv](https://arxiv.org/abs/2409.09554)