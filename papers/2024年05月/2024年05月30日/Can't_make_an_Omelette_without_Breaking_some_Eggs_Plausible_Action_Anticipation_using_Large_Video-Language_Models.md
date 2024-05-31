# 欲制煎蛋卷，必先破蛋壳：借助大型视频-语言模型，精准预见动作之可能。

发布时间：2024年05月30日

`Agent

理由：这篇论文介绍了一种名为PlausiVL的大型视频-语言模型，专门设计用于预测现实世界中合理的动作序列。它通过引入新的目标函数和约束来提高模型对动作序列合理性的理解和预测能力。这种模型可以被视为一个智能Agent，因为它能够理解和预测环境中的动作，并据此做出决策。这与Agent的定义相符，即一个能够感知环境并采取行动以达到目标的系统。因此，这篇论文更适合归类到Agent分类中。` `视频分析` `动作预测`

> Can't make an Omelette without Breaking some Eggs: Plausible Action Anticipation using Large Video-Language Models

# 摘要

> 我们推出了 PlausiVL，一种专为预测现实世界中合理动作序列而设计的大型视频-语言模型。尽管已有许多努力致力于预测未来动作，但以往方法往往忽略了动作序列的合理性。为此，我们深入研究了大型视频-语言模型的生成潜力，并引入了两个创新的目标函数：基于反事实的合理动作序列学习损失和长期动作重复损失，以深化对动作序列合理性的理解。通过结合时间逻辑约束和动词-名词动作对逻辑约束，我们构建了不合理/反事实的动作序列，用于训练模型，使其能够区分并学习合理与不合理的动作序列，同时捕捉到对动作预测至关重要的隐含时间线索。长期动作重复损失则对那些在长时间窗口内易重复的动作施加更重的惩罚，促使模型生成既多样又合理的动作序列。我们在 Ego4D 和 EPIC-Kitchens-100 两个大规模数据集上验证了这一方法，显著提升了动作预测的性能。

> We introduce PlausiVL, a large video-language model for anticipating action sequences that are plausible in the real-world. While significant efforts have been made towards anticipating future actions, prior approaches do not take into account the aspect of plausibility in an action sequence. To address this limitation, we explore the generative capability of a large video-language model in our work and further, develop the understanding of plausibility in an action sequence by introducing two objective functions, a counterfactual-based plausible action sequence learning loss and a long-horizon action repetition loss. We utilize temporal logical constraints as well as verb-noun action pair logical constraints to create implausible/counterfactual action sequences and use them to train the model with plausible action sequence learning loss. This loss helps the model to differentiate between plausible and not plausible action sequences and also helps the model to learn implicit temporal cues crucial for the task of action anticipation. The long-horizon action repetition loss puts a higher penalty on the actions that are more prone to repetition over a longer temporal window. With this penalization, the model is able to generate diverse, plausible action sequences. We evaluate our approach on two large-scale datasets, Ego4D and EPIC-Kitchens-100, and show improvements on the task of action anticipation.

![欲制煎蛋卷，必先破蛋壳：借助大型视频-语言模型，精准预见动作之可能。](../../../paper_images/2405.20305/x1.png)

![欲制煎蛋卷，必先破蛋壳：借助大型视频-语言模型，精准预见动作之可能。](../../../paper_images/2405.20305/x2.png)

![欲制煎蛋卷，必先破蛋壳：借助大型视频-语言模型，精准预见动作之可能。](../../../paper_images/2405.20305/x3.png)

![欲制煎蛋卷，必先破蛋壳：借助大型视频-语言模型，精准预见动作之可能。](../../../paper_images/2405.20305/x4.png)

![欲制煎蛋卷，必先破蛋壳：借助大型视频-语言模型，精准预见动作之可能。](../../../paper_images/2405.20305/x5.png)

![欲制煎蛋卷，必先破蛋壳：借助大型视频-语言模型，精准预见动作之可能。](../../../paper_images/2405.20305/graph.png)

![欲制煎蛋卷，必先破蛋壳：借助大型视频-语言模型，精准预见动作之可能。](../../../paper_images/2405.20305/x6.png)

![欲制煎蛋卷，必先破蛋壳：借助大型视频-语言模型，精准预见动作之可能。](../../../paper_images/2405.20305/x7.png)

![欲制煎蛋卷，必先破蛋壳：借助大型视频-语言模型，精准预见动作之可能。](../../../paper_images/2405.20305/x8.png)

[Arxiv](https://arxiv.org/abs/2405.20305)