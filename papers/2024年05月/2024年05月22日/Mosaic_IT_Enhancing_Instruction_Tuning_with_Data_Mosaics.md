# Mosaic IT：通过数据马赛克提升指令调优效果

发布时间：2024年05月22日

`LLM应用

理由：这篇论文介绍了一种新的方法Mosaic Instruction Tuning（Mosaic-IT），用于微调大型语言模型（LLM），以提高其遵循指令的能力。这种方法特别强调了其高效性和成本效益，通过创造性的数据处理和训练策略来增强模型的性能。由于该研究主要关注于应用层面的改进和优化，即如何更有效地训练和调整LLM以适应特定的指令遵循任务，因此将其归类为LLM应用。` `机器学习`

> Mosaic IT: Enhancing Instruction Tuning with Data Mosaics

# 摘要

> 通过多样化的指令-响应对微调大型语言模型，显著提升了其遵循指令的能力。然而，现有的指令调优方法多依赖昂贵且不可持续的人工或模型干预。为此，我们提出了Mosaic Instruction Tuning（Mosaic-IT），一种无需外部干预的高效方法，能从现有数据中创造出丰富多样的增强内容，进一步提升LLM的性能。Mosaic-IT通过随机组合多个指令数据，并结合高级元指令训练模型，有效强化了其多步骤和格式遵循能力。实验证明，Mosaic-IT不仅在多个测试中持续提升性能，还大幅降低了80%的训练成本。相关代码和数据已公开于https://github.com/tianyi-lab/Mosaic-IT。

> Finetuning large language models with a variety of instruction-response pairs has enhanced their capability to understand and follow instructions. Current instruction tuning primarily relies on teacher models or human intervention to generate and refine the instructions and responses, which are costly, non-sustainable, and may lack diversity. In this paper, we introduce Mosaic Instruction Tuning (Mosaic-IT), a human/model-free method that can efficiently create rich and diverse augmentations from existing instruction tuning data to enhance the finetuned LLM.Mosaic-IT randomly concatenates multiple instruction data into one and trains the model to produce the corresponding responses with predefined higher-level meta-instructions to strengthen its multi-step instruction-following and format-following skills. Our extensive evaluations demonstrate a superior performance and training efficiency of Mosaic-IT, which achieves consistent performance improvements over various benchmarks and an 80% reduction in training costs compared with original instruction tuning. Our codes and data are available at https://github.com/tianyi-lab/Mosaic-IT.

[Arxiv](https://arxiv.org/abs/2405.13326)