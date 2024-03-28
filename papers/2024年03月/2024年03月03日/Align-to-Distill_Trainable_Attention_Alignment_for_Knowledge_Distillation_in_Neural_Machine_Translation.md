# 在神经机器翻译中，我们提出了一种名为“Align-to-Distill”的方法，它通过可训练的注意力对齐机制实现知识的有效蒸馏。这一创新技术旨在提升模型在知识转移过程中的性能和效率，特别是在神经机器翻译任务上。

发布时间：2024年03月03日

`Agent`

> Align-to-Distill: Trainable Attention Alignment for Knowledge Distillation in Neural Machine Translation

# 摘要

> 得益于大规模深度模型与大数据集的发展，神经机器翻译的表现得以大幅提升。知识蒸馏技术通过将教师模型的知识传递给结构更紧凑的学生模型来优化效率，但在应用于Transformer架构时，通常依赖于经验法则，尤其是在选择教师层进行知识提取方面。本文创新性地提出了“对齐以蒸馏”（A2D）策略，它在训练过程中动态调整学生注意力头与教师注意力头的一一对应关系，从而有效解决特征映射难题。A2D利用注意力对齐模块，密集对比学生与教师模型每一层间的注意力头，将原本复杂的组合映射规则转变为可学习的问题。实验证明了A2D的有效性，在WMT-2022德语到低地索布语及WMT-2014英语到德语的任务上，分别取得了最高+3.61和+0.63 BLEU分数的提升，远超Transformer基线模型。

> The advent of scalable deep models and large datasets has improved the performance of Neural Machine Translation. Knowledge Distillation (KD) enhances efficiency by transferring knowledge from a teacher model to a more compact student model. However, KD approaches to Transformer architecture often rely on heuristics, particularly when deciding which teacher layers to distill from. In this paper, we introduce the 'Align-to-Distill' (A2D) strategy, designed to address the feature mapping problem by adaptively aligning student attention heads with their teacher counterparts during training. The Attention Alignment Module in A2D performs a dense head-by-head comparison between student and teacher attention heads across layers, turning the combinatorial mapping heuristics into a learning problem. Our experiments show the efficacy of A2D, demonstrating gains of up to +3.61 and +0.63 BLEU points for WMT-2022 De->Dsb and WMT-2014 En->De, respectively, compared to Transformer baselines.

[Arxiv](https://arxiv.org/abs/2403.01479)