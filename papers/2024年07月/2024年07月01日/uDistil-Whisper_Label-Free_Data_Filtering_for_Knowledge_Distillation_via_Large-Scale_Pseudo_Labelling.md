# uDistil-Whisper：利用大规模伪标签技术，实现知识蒸馏中的无标签数据过滤。

发布时间：2024年07月01日

`LLM应用` `语音识别` `模型优化`

> uDistil-Whisper: Label-Free Data Filtering for Knowledge Distillation via Large-Scale Pseudo Labelling

# 摘要

> 近期研究通过伪标签将 Whisper 的知识精炼至小型模型，不仅性能出色，还成功缩减了模型体积达50%。这些模型虽小巧却高效且专注。然而，提炼过程中的关键一环——筛选高质量预测，依赖于真实数据进行不良示例的过滤，这使得整个流程带有监督性质。此外，大量数据需求也限制了其在资源匮乏环境中的应用。为此，我们创新性地提出了一个无需标签的无监督提炼框架，彻底摆脱了对标记数据的依赖。实验结果显示，我们的最佳提炼模型在WER指标上超越了原教师模型5-7分，且与采用监督数据筛选的模型相比，性能不相上下甚至更优。随着数据规模的扩大，我们的模型在性能上显著领先于所有零-shot和监督模型。本研究成果表明，无需任何标记数据，即可将庞大的Whisper模型精炼为更小巧的版本，同时保持甚至提升其性能，实现计算与内存效率的显著提升。

> Recent work on distilling Whisper's knowledge into small models using pseudo-labels shows promising performance while reducing the size by up to 50\%. This results in small, efficient, and dedicated models. However, a critical step of distillation from pseudo-labels involves filtering high-quality predictions and using only those during training. This step requires ground truth to compare and filter bad examples making the whole process supervised. In addition to that, the distillation process requires a large amount of data thereby limiting the ability to distil models in low-resource settings. To address this challenge, we propose an unsupervised or label-free framework for distillation, thus eliminating the requirement for labeled data altogether. Through experimentation, we show that our best distilled models outperform the teacher model by 5-7 points in terms of WER. Additionally, our models are on par with or better than similar supervised data filtering setup. When we scale the data, our models significantly outperform all zero-shot and supervised models. In this work, we demonstrate that it's possible to distill large Whisper models into relatively small models without using any labeled data. As a result, our distilled models are 25-50\% more compute and memory efficient while maintaining performance equal to or better than the teacher model.

[Arxiv](https://arxiv.org/abs/2407.01257)