# [为解决视觉-语言模型在连续学习中的挑战，我们提出“选择并提炼”策略，通过精心设计的选择性双教师知识迁移机制，有效促进模型对新任务的学习与旧知识的保持。](https://arxiv.org/abs/2403.09296)

发布时间：2024年03月14日

`Agent`

`机器学习`

`持续学习`

> Select and Distill: Selective Dual-Teacher Knowledge Transfer for Continual Learning on Vision-Language Models

> 大规模VLMs展现出对未知领域数据的强大零样本泛化能力，但在不断适应下游任务的过程中，易遗忘已学知识并降低零样本分类性能。针对此问题，我们创新性地提出了“选择性双教师知识迁移”框架，借助最新微调模型与原始预训练模型作为双重教师，分别保护已学知识和零样本能力。即使仅能访问未标注的参考数据集，本框架也能通过比较双教师VLMs的特征差异，实施选择性知识提炼机制。因此，这种选择性双教师知识蒸馏能够有效缓解对已有知识的灾难性遗忘，并从预训练VLMs中保持零样本能力。在一系列基准数据集上的大量实验证明，相较于当前最先进的持续学习方法，我们提出的框架更有利于防止灾难性遗忘和零样本性能衰退。

> Large-scale vision-language models (VLMs) have shown a strong zero-shot generalization capability on unseen-domain data. However, when adapting pre-trained VLMs to a sequence of downstream tasks, they are prone to forgetting previously learned knowledge and degrade their zero-shot classification capability. To tackle this problem, we propose a unique Selective Dual-Teacher Knowledge Transfer framework that leverages the most recent fine-tuned and the original pre-trained VLMs as dual teachers to preserve the previously learned knowledge and zero-shot capabilities, respectively. With only access to an unlabeled reference dataset, our proposed framework performs a selective knowledge distillation mechanism by measuring the feature discrepancy from the dual teacher VLMs. Consequently, our selective dual-teacher knowledge distillation would mitigate catastrophic forgetting of previously learned knowledge while preserving the zero-shot capabilities from pre-trained VLMs. Through extensive experiments on benchmark datasets, we show that our proposed framework is favorable against state-of-the-art continual learning approaches for preventing catastrophic forgetting and zero-shot degradation.

![为解决视觉-语言模型在连续学习中的挑战，我们提出“选择并提炼”策略，通过精心设计的选择性双教师知识迁移机制，有效促进模型对新任务的学习与旧知识的保持。](../../../paper_images/2403.09296/x1.png)

![为解决视觉-语言模型在连续学习中的挑战，我们提出“选择并提炼”策略，通过精心设计的选择性双教师知识迁移机制，有效促进模型对新任务的学习与旧知识的保持。](../../../paper_images/2403.09296/x2.png)

![为解决视觉-语言模型在连续学习中的挑战，我们提出“选择并提炼”策略，通过精心设计的选择性双教师知识迁移机制，有效促进模型对新任务的学习与旧知识的保持。](../../../paper_images/2403.09296/x3.png)

![为解决视觉-语言模型在连续学习中的挑战，我们提出“选择并提炼”策略，通过精心设计的选择性双教师知识迁移机制，有效促进模型对新任务的学习与旧知识的保持。](../../../paper_images/2403.09296/x4.png)

![为解决视觉-语言模型在连续学习中的挑战，我们提出“选择并提炼”策略，通过精心设计的选择性双教师知识迁移机制，有效促进模型对新任务的学习与旧知识的保持。](../../../paper_images/2403.09296/x5.png)

![为解决视觉-语言模型在连续学习中的挑战，我们提出“选择并提炼”策略，通过精心设计的选择性双教师知识迁移机制，有效促进模型对新任务的学习与旧知识的保持。](../../../paper_images/2403.09296/x6.png)

![为解决视觉-语言模型在连续学习中的挑战，我们提出“选择并提炼”策略，通过精心设计的选择性双教师知识迁移机制，有效促进模型对新任务的学习与旧知识的保持。](../../../paper_images/2403.09296/x7.png)

![为解决视觉-语言模型在连续学习中的挑战，我们提出“选择并提炼”策略，通过精心设计的选择性双教师知识迁移机制，有效促进模型对新任务的学习与旧知识的保持。](../../../paper_images/2403.09296/fgvc-aircraft.png)

![为解决视觉-语言模型在连续学习中的挑战，我们提出“选择并提炼”策略，通过精心设计的选择性双教师知识迁移机制，有效促进模型对新任务的学习与旧知识的保持。](../../../paper_images/2403.09296/stanford-cars.png)

![为解决视觉-语言模型在连续学习中的挑战，我们提出“选择并提炼”策略，通过精心设计的选择性双教师知识迁移机制，有效促进模型对新任务的学习与旧知识的保持。](../../../paper_images/2403.09296/flowers-102.png)

![为解决视觉-语言模型在连续学习中的挑战，我们提出“选择并提炼”策略，通过精心设计的选择性双教师知识迁移机制，有效促进模型对新任务的学习与旧知识的保持。](../../../paper_images/2403.09296/food-101.png)

![为解决视觉-语言模型在连续学习中的挑战，我们提出“选择并提炼”策略，通过精心设计的选择性双教师知识迁移机制，有效促进模型对新任务的学习与旧知识的保持。](../../../paper_images/2403.09296/x8.png)

![为解决视觉-语言模型在连续学习中的挑战，我们提出“选择并提炼”策略，通过精心设计的选择性双教师知识迁移机制，有效促进模型对新任务的学习与旧知识的保持。](../../../paper_images/2403.09296/x9.png)

![为解决视觉-语言模型在连续学习中的挑战，我们提出“选择并提炼”策略，通过精心设计的选择性双教师知识迁移机制，有效促进模型对新任务的学习与旧知识的保持。](../../../paper_images/2403.09296/x10.png)

![为解决视觉-语言模型在连续学习中的挑战，我们提出“选择并提炼”策略，通过精心设计的选择性双教师知识迁移机制，有效促进模型对新任务的学习与旧知识的保持。](../../../paper_images/2403.09296/x11.png)

![为解决视觉-语言模型在连续学习中的挑战，我们提出“选择并提炼”策略，通过精心设计的选择性双教师知识迁移机制，有效促进模型对新任务的学习与旧知识的保持。](../../../paper_images/2403.09296/x12.png)

![为解决视觉-语言模型在连续学习中的挑战，我们提出“选择并提炼”策略，通过精心设计的选择性双教师知识迁移机制，有效促进模型对新任务的学习与旧知识的保持。](../../../paper_images/2403.09296/x13.png)

![为解决视觉-语言模型在连续学习中的挑战，我们提出“选择并提炼”策略，通过精心设计的选择性双教师知识迁移机制，有效促进模型对新任务的学习与旧知识的保持。](../../../paper_images/2403.09296/x14.png)

![为解决视觉-语言模型在连续学习中的挑战，我们提出“选择并提炼”策略，通过精心设计的选择性双教师知识迁移机制，有效促进模型对新任务的学习与旧知识的保持。](../../../paper_images/2403.09296/x15.png)

![为解决视觉-语言模型在连续学习中的挑战，我们提出“选择并提炼”策略，通过精心设计的选择性双教师知识迁移机制，有效促进模型对新任务的学习与旧知识的保持。](../../../paper_images/2403.09296/x16.png)

![为解决视觉-语言模型在连续学习中的挑战，我们提出“选择并提炼”策略，通过精心设计的选择性双教师知识迁移机制，有效促进模型对新任务的学习与旧知识的保持。](../../../paper_images/2403.09296/x17.png)

![为解决视觉-语言模型在连续学习中的挑战，我们提出“选择并提炼”策略，通过精心设计的选择性双教师知识迁移机制，有效促进模型对新任务的学习与旧知识的保持。](../../../paper_images/2403.09296/x18.png)

![为解决视觉-语言模型在连续学习中的挑战，我们提出“选择并提炼”策略，通过精心设计的选择性双教师知识迁移机制，有效促进模型对新任务的学习与旧知识的保持。](../../../paper_images/2403.09296/x19.png)

![为解决视觉-语言模型在连续学习中的挑战，我们提出“选择并提炼”策略，通过精心设计的选择性双教师知识迁移机制，有效促进模型对新任务的学习与旧知识的保持。](../../../paper_images/2403.09296/x20.png)

![为解决视觉-语言模型在连续学习中的挑战，我们提出“选择并提炼”策略，通过精心设计的选择性双教师知识迁移机制，有效促进模型对新任务的学习与旧知识的保持。](../../../paper_images/2403.09296/x21.png)

![为解决视觉-语言模型在连续学习中的挑战，我们提出“选择并提炼”策略，通过精心设计的选择性双教师知识迁移机制，有效促进模型对新任务的学习与旧知识的保持。](../../../paper_images/2403.09296/x22.png)

![为解决视觉-语言模型在连续学习中的挑战，我们提出“选择并提炼”策略，通过精心设计的选择性双教师知识迁移机制，有效促进模型对新任务的学习与旧知识的保持。](../../../paper_images/2403.09296/x23.png)