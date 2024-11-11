# 使用 VLM 的精确驱动：PRCV 2024 驱动 LM 挑战赛的一等奖解决方案

发布时间：2024年11月05日

`其他` `自动驾驶` `模型训练`

> Precise Drive with VLM: First Prize Solution for PRCV 2024 Drive LM challenge

# 摘要

> 这份技术报告概述了我们为 PRCV 挑战赛所应用的方法，重点是驾驶场景中的认知和决策。我们采用了 InternVL-2.0，这是一个开创性的开源多模态模型，并通过改进模型输入和训练方法来增强它。对于输入数据，我们有策略地连接和格式化了多视图图像。值得一提的是，我们使用了未经变换的原始图像的坐标。在模型训练方面，我们首先在公开的自动驾驶场景数据集中对模型进行预训练，以增强其对挑战任务的对齐能力，然后在 DriveLM-nuscenes 数据集上进行微调。在微调阶段，我们创新性地修改了损失函数，以提高模型在预测坐标值方面的精度。这些方法确保我们的模型在驾驶场景中具有先进的认知和决策能力。因此，我们的模型在比赛的最终结果中获得了 0.6064 的分数，获得了一等奖。

> This technical report outlines the methodologies we applied for the PRCV Challenge, focusing on cognition and decision-making in driving scenarios. We employed InternVL-2.0, a pioneering open-source multi-modal model, and enhanced it by refining both the model input and training methodologies. For the input data, we strategically concatenated and formatted the multi-view images. It is worth mentioning that we utilized the coordinates of the original images without transformation. In terms of model training, we initially pre-trained the model on publicly available autonomous driving scenario datasets to bolster its alignment capabilities of the challenge tasks, followed by fine-tuning on the DriveLM-nuscenes Dataset. During the fine-tuning phase, we innovatively modified the loss function to enhance the model's precision in predicting coordinate values. These approaches ensure that our model possesses advanced cognitive and decision-making capabilities in driving scenarios. Consequently, our model achieved a score of 0.6064, securing the first prize on the competition's final results.

[Arxiv](https://arxiv.org/abs/2411.02999)