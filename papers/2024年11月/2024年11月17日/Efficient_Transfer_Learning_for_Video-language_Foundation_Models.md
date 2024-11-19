# 关于视频语言基础模型的高效迁移学习

发布时间：2024年11月17日

`LLM应用` `动作识别`

> Efficient Transfer Learning for Video-language Foundation Models

# 摘要

> 预训练的视觉语言模型为各类下游任务的高效迁移学习筑牢根基。在视频动作识别领域，主流方法往往引入额外的参数模块来捕捉时间信息。虽说这些新增参数带来的模型容量扩充有助于更贴合视频特有的归纳偏差，可现有方法需要学习众多参数，还容易对原始的通用知识造成灾难性遗忘。本文中，我们提出了一种简便且有效的多模态时空适配器（MSTA），用于增进文本和视觉分支表征之间的对齐，达成通用知识与任务特定知识的平衡。另外，为降低过拟合并增强泛化能力，我们引入了时空描述引导的一致性约束。此约束涵盖将模板输入（比如“一个$\{	extbf{cls}\}$的视频”）输入到可训练的语言分支，而由LLM生成的时空描述则输入到预训练的语言分支，强制两个分支的输出保持一致。这种机制避免了对下游任务的过拟合，提升了时空语义空间中可训练分支的可区分性。我们在零样本迁移、少样本学习、基础到新的泛化以及全监督学习这四项任务中评估了我们方法的成效。与众多前沿方法相比，我们的MSTA在所有评估中均表现出色，且在原始模型中仅使用2 - 7％的可训练参数。代码可在https://github.com/chenhaoxing/ETL4Video获取。

> Pre-trained vision-language models provide a robust foundation for efficient transfer learning across various downstream tasks. In the field of video action recognition, mainstream approaches often introduce additional parameter modules to capture temporal information. While the increased model capacity brought by these additional parameters helps better fit the video-specific inductive biases, existing methods require learning a large number of parameters and are prone to catastrophic forgetting of the original generalizable knowledge. In this paper, we propose a simple yet effective Multi-modal Spatio-Temporal Adapter (MSTA) to improve the alignment between representations in the text and vision branches, achieving a balance between general knowledge and task-specific knowledge. Furthermore, to mitigate over-fitting and enhance generalizability, we introduce a spatio-temporal description-guided consistency constraint. This constraint involves feeding template inputs (i.e., ``a video of $\{\textbf{cls}\}$'') into the trainable language branch, while LLM-generated spatio-temporal descriptions are input into the pre-trained language branch, enforcing consistency between the outputs of the two branches. This mechanism prevents over-fitting to downstream tasks and improves the distinguishability of the trainable branch within the spatio-temporal semantic space. We evaluate the effectiveness of our approach across four tasks: zero-shot transfer, few-shot learning, base-to-novel generalization, and fully-supervised learning. Compared to many state-of-the-art methods, our MSTA achieves outstanding performance across all evaluations, while using only 2-7\% of the trainable parameters in the original model. Code will be avaliable at https://github.com/chenhaoxing/ETL4Video.

[Arxiv](https://arxiv.org/abs/2411.11223)