# 谨慎困惑：通过选择性熵最大化策略消除文本序列记忆

发布时间：2024年08月09日

`LLM理论` `人工智能` `隐私保护`

> Get Confused Cautiously: Textual Sequence Memorization Erasure with Selective Entropy Maximization

# 摘要

> 大型语言模型 (LLM) 能够逐字记忆训练集中的文本，引发隐私和版权问题。为防止生成记忆文本，需规范 LLM 输出。然而，现有 TSM 删除方法未能有效遗忘大量样本，且可能损害模型效用。为此，我们提出基于选择性优化熵最大化 (EMSO) 的新框架，通过新颖对比梯度度量选择更新权重，无需额外模型或数据。实验证明，该方法在稳定优化过程的同时，有效保持模型效用，并能处理大规模遗忘请求，同时保留语言生成和推理能力。

> Large Language Models (LLMs) have been found to memorize and recite some of the textual sequences from their training set verbatim, raising broad concerns about privacy and copyright issues when using LLMs. This Textual Sequence Memorization (TSM) phenomenon leads to a high demand to regulate LLM output to prevent it from generating certain memorized text to meet user requirements. However, our empirical study reveals that existing methods for TSM erasure fail to forget massive memorized samples without substantially jeopardizing the model utility. To achieve a better trade-off between the effectiveness of TSM erasure and model utility in LLMs, our paper proposes a new framework based on Entropy Maximization with Selective Optimization (EMSO), where the updated weights are chosen with a novel contrastive gradient metric without any participation of additional model or data. Our analysis shows that training with the entropy maximization loss has a more stable optimization process and better keeps model utility than existing methods. The contrastive gradient metric localizes the most influential weight for TSM erasure by taking both the gradient magnitude and direction into consideration. Extensive experiments across three model scales demonstrate that our method excels in handling large-scale forgetting requests while preserving model ability in language generation and reasoning.

[Arxiv](https://arxiv.org/abs/2408.04983)