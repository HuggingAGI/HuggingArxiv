# Botfip-LLM：一个借助大型语言模型知识蒸馏的强化多模态科学计算框架

发布时间：2024年11月23日

`LLM应用` `科学计算` `多模态学习`

> Botfip-LLM: An Enhanced Multimodal Scientific Computing Framework Leveraging Knowledge Distillation from Large Language Models

# 摘要

> 近年来，AI 技术的引入为科学计算带来了颠覆性的变革。但 AI 模型往往聚焦于单任务和单模态数据处理，这限制了其应用。为此，多模态科学计算框架渐成趋势。Botfip 框架通过多模态训练让函数图像与符号操作树对齐，以提取深度科学信息。然而，Botfip 在处理公式字符串时颇为吃力，致使其在多模态学习中的理解不够到位。为强化 Botfip 对公式字符串的学习并拓展其在相关任务中的适用性，我们基于知识蒸馏提出了 Botfip-LLM 框架，融入了预训练的大型语言模型来对齐符号树数据。实验分析表明，LLM 的选择至关重要，ChatGLM-2 在训练和测试中均优于其他模型。Botfip-LLM 不仅在性能、泛化和外推上比原始 Botfip 模型更出色，还极大地增强了对公式字符串相关任务的适用性，能够应对更多样的任务。

> In recent years, the introduction of AI technologies has brought transformative changes to scientific computing. However, AI models typically focus on single-task and single-modal data processing, limiting their application. To address this, multimodal scientific computing frameworks have become a trend. The Botfip framework aligns function images with symbolic operation trees through multimodal training, extracting deep scientific information. However, Botfip struggles with processing Formula Strings, leading to inadequate understanding in multimodal learning. To enhance Botfip's learning of Formula Strings and expand its applicability to related tasks, we propose the Botfip-LLM framework based on knowledge distillation, incorporating pre-trained large language models for aligning symbolic tree data. Experimental analysis shows that the choice of LLM is crucial, with ChatGLM-2 outperforming others in training and testing. Botfip-LLM not only improves performance, generalization, and extrapolation over the original Botfip model but also significantly enhances applicability to Formula String-related tasks, enabling more diverse task handling.

[Arxiv](https://arxiv.org/abs/2411.15525)