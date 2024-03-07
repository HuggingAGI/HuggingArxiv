# [NoMAD-Attention技术致力于提升CPU环境下LLM推理效率，它采用无需乘加操作的注意力机制，实现大型语言模型在CPU上的高效推理。](https://arxiv.org/abs/2403.01273)

> NoMAD-Attention: Efficient LLM Inference on CPUs Through Multiply-add-free Attention

发布时间：2024年03月02日

> 由于大规模的注意力计算需要进行大量的昂贵乘加运算，因此在CPU上对大型语言模型进行推理颇具挑战性。然而，现代CPU中隐藏着一项利器——单指令多数据流（SIMD）寄存器，它能够实现批处理中近乎瞬时的查找。借此优势，我们提出了NoMAD-Attention这一高效注意力算法，用寄存器内快速查询替代了繁重的MAD运算。经过精心设计，NoMAD-Attention能够在SIMD寄存器容量有限的情况下，通过连续高速访问完成注意力得分的计算。更令人惊喜的是，NoMAD-Attention无需对预训练的基于注意力机制的LLM进行微调也能顺利应用。实验证明，使用NoMAD-Attention后，模型质量得以良好保持，并且在16k的上下文长度下，可将4位量化LLaMA-7B模型的推理速度提升高达两倍。相关研究成果已在https://github.com/tonyzhang617/nomad-dist提供给各位查阅和复现。

> Large language model inference on Central Processing Units (CPU) is challenging due to the vast quantities of expensive Multiply-Add (MAD) matrix operations in the attention computations. In this paper, we argue that there is a rare gem in modern CPUs, Single-Instruction-Multiple-Data (SIMD) registers, which allow for ultra-low-latency lookups in batch. We leverage this unique capability of CPUs to propose NoMAD-Attention, an efficient attention algorithm that replaces MAD operations with in-register lookups. Through hardware-aware algorithmic designs, NoMAD-Attention achieves the computation of attention scores using repeated fast accesses to SIMD registers despite their highly limited sizes. Moreover, NoMAD-Attention works with pre-trained attention-based LLMs without model finetuning. Empirical evaluations demonstrate that NoMAD-Attention maintains the quality of the original LLMs well, and speeds up the 4-bit quantized LLaMA-7B-based model by up to 2$\times$ at 16k context length. Our results are reproducible at https://github.com/tonyzhang617/nomad-dist.

`Agent`