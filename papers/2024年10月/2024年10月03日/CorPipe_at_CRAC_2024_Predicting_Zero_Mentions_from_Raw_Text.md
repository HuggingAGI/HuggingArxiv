# CorPipe 亮相 CRAC 2024，挑战从原始文本中预测零提及。

发布时间：2024年10月03日

`LLM应用` `共指消解`

> CorPipe at CRAC 2024: Predicting Zero Mentions from Raw Text

# 摘要

> 我们带来了 CorPipe 24，这是 CRAC 2024 多语言共指消解任务的冠军之作。今年的任务新增了预测零共指提及所需的空节点，使得共指消解可以直接应用于原始文本。我们测试了两种模型：两阶段方法和单阶段方法。无论哪种方法，CorPipe 都以显著优势（3.9 和 2.8 个百分点）领先其他参赛者。源代码和训练模型已公开，访问 https://github.com/ufal/crac2024-corpipe 即可获取。

> We present CorPipe 24, the winning entry to the CRAC 2024 Shared Task on Multilingual Coreference Resolution. In this third iteration of the shared task, a novel objective is to also predict empty nodes needed for zero coreference mentions (while the empty nodes were given on input in previous years). This way, coreference resolution can be performed on raw text. We evaluate two model variants: a~two-stage approach (where the empty nodes are predicted first using a pretrained encoder model and then processed together with sentence words by another pretrained model) and a single-stage approach (where a single pretrained encoder model generates empty nodes, coreference mentions, and coreference links jointly). In both settings, CorPipe surpasses other participants by a large margin of 3.9 and 2.8 percent points, respectively. The source code and the trained model are available at https://github.com/ufal/crac2024-corpipe .

[Arxiv](https://arxiv.org/abs/2410.02756)