# 借助隐式思维链解码，加速并提升大型语言模型的推理能力。

发布时间：2024年09月13日

`LLM应用` `人工智能`

> Expediting and Elevating Large Language Model Reasoning via Hidden Chain-of-Thought Decoding

# 摘要

> 大型语言模型 (LLM) 通过链式思维 (CoT) 提示，在推理和多步骤问题解决任务中表现出色。然而，生成完整 CoT 过程会显著增加输出长度，导致推理时的计算成本和延迟上升。为此，我们提出了一种通过语义对齐压缩 CoT 过程的新方法，既保留了 CoT 推理的优势，又提高了解码效率。我们引入了一个辅助 CoT 模型，该模型能将完整的思维过程压缩成与原始输出语义对齐的紧凑标记。这种压缩表示随后被集成到隐藏链式思维 (HCoT) 模型的输入中。训练分两阶段进行：首先，优化 CoT 模型以生成与真实 CoT 输出对齐的压缩标记；然后，在 CoT 模型参数冻结的情况下，微调 HCoT 模型以基于前缀指令和压缩的 CoT 表示生成准确预测。实验表明，我们的方法在数学推理、代理调用和问答等领域的性能与完整 CoT 基线相当或更优，同时解码速度提升至少 1.5 倍。此外，对比学习进一步提升了压缩表示的质量，从而改善了 CoT 提示和任务准确性。我们的研究为在广泛应用中更高效地利用 LLM 的多步骤推理能力奠定了基础。

> Large language models (LLMs) have demonstrated remarkable capabilities in tasks requiring reasoning and multi-step problem-solving through the use of chain-of-thought (CoT) prompting. However, generating the full CoT process results in significantly longer output sequences, leading to increased computational costs and latency during inference. To address this challenge, we propose a novel approach to compress the CoT process through semantic alignment, enabling more efficient decoding while preserving the benefits of CoT reasoning. Our method introduces an auxiliary CoT model that learns to generate and compress the full thought process into a compact special token representation semantically aligned with the original CoT output. This compressed representation is then integrated into the input of the Hidden Chain-of-Thought (HCoT) model. The training process follows a two-stage procedure: First, the CoT model is optimized to generate the compressed token representations aligned with the ground-truth CoT outputs using a contrastive loss. Subsequently, with the CoT model parameters frozen, the HCoT model is fine-tuned to generate accurate subsequent predictions conditioned on the prefix instruction and the compressed CoT representations from the CoT model. Extensive experiments across three challenging domains - mathematical reasoning, agent invocation, and question answering - demonstrate that our semantic compression approach achieves competitive or improved performance compared to the full CoT baseline, while providing significant speedups of at least 1.5x in decoding time. Moreover, incorporating contrastive learning objectives further enhances the quality of the compressed representations, leading to better CoT prompting and improved task accuracy. Our work paves the way for more efficient exploitation of multi-step reasoning capabilities in LLMs across a wide range of applications.

[Arxiv](https://arxiv.org/abs/2409.08561)