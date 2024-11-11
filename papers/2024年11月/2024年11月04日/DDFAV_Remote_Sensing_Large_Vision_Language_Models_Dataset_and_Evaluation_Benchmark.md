# DDFAV：遥感大型视觉语言模型数据集和评估基准

发布时间：2024年11月04日

`LLM应用` `视觉语言模型`

> DDFAV: Remote Sensing Large Vision Language Models Dataset and Evaluation Benchmark

# 摘要

> 随着大型视觉语言模型（LVLMs）的快速发展，这些模型在各种多模态任务中都取得了出色的成果。由于 LVLMs 容易产生幻觉，并且目前专门为遥感设计的数据集和评估方法很少，因此它们在应用于遥感任务时的表现通常较差。为了解决这些问题，本文引入了一个高质量的遥感 LVLMs 数据集 DDFAV，它是使用数据增强和数据混合策略创建的。接下来，基于从所提出的数据集中选择的一些高质量遥感图像生成了一个训练指令集。最后，我们基于所提出的数据集开发了一种遥感 LVLMs 幻觉评估方法 RSPOPE，并评估了不同 LVLMs 的零样本能力。我们提出的数据集、指令集和评估方法文件可在 https://github.com/HaodongLi2024/rspope 上获取。

> With the rapid development of large vision language models (LVLMs), these models have shown excellent results in various multimodal tasks. Since LVLMs are prone to hallucinations and there are currently few datasets and evaluation methods specifically designed for remote sensing, their performance is typically poor when applied to remote sensing tasks. To address these issues, this paper introduces a high quality remote sensing LVLMs dataset, DDFAV, created using data augmentation and data mixing strategies. Next, a training instruction set is produced based on some high-quality remote sensing images selected from the proposed dataset. Finally, we develop a remote sensing LVLMs hallucination evaluation method RSPOPE based on the proposed dataset and evaluate the zero-shot capabilities of different LVLMs. Our proposed dataset, instruction set, and evaluation method files are available at https://github.com/HaodongLi2024/rspope.

[Arxiv](https://arxiv.org/abs/2411.02733)