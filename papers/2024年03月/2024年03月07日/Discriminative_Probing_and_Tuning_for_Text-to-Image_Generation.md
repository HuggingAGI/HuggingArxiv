# 针对文本到图像生成任务，我们采用鉴别性探查和调整技术，以深入探究模型内部机制，并优化其生成效果。

发布时间：2024年03月07日

`Agent`

> Discriminative Probing and Tuning for Text-to-Image Generation

> 尽管T2I技术不断进步，但过往方法常遭遇生成图像与文本描述之间的关系混乱等问题。现有解决策略或是优化交叉注意力机制以加深组合理解，或是引入大型语言模型以提升布局设计。然而，T2I模型内在的文本-图像对齐能力仍有欠缺。观察生成模型与判别模型之间的关联，我们推测T2I模型在生成过程中的判别能力其实可反映其对文本-图像对齐的掌握程度。为此，我们主张强化T2I模型的判别能力，从而实现更精准的文本到图像生成对齐。我们提出一种基于T2I模型的判别性适配器，在两项典型任务上检验其判别性能，并运用判别式微调进一步提升文本-图像对齐效果。该判别适配器还自带一项自我修正机制，能在推理时巧妙运用判别梯度引导生成图像更紧密地贴合文本提示。我们在涵盖分布内和分布外情况的三大基准数据集上的全面评估显示，我们的方法在生成表现上出类拔萃，同时在所对比的判别任务中也刷新了当前最优判别性能纪录。

> Despite advancements in text-to-image generation (T2I), prior methods often face text-image misalignment problems such as relation confusion in generated images. Existing solutions involve cross-attention manipulation for better compositional understanding or integrating large language models for improved layout planning. However, the inherent alignment capabilities of T2I models are still inadequate. By reviewing the link between generative and discriminative modeling, we posit that T2I models' discriminative abilities may reflect their text-image alignment proficiency during generation. In this light, we advocate bolstering the discriminative abilities of T2I models to achieve more precise text-to-image alignment for generation. We present a discriminative adapter built on T2I models to probe their discriminative abilities on two representative tasks and leverage discriminative fine-tuning to improve their text-image alignment. As a bonus of the discriminative adapter, a self-correction mechanism can leverage discriminative gradients to better align generated images to text prompts during inference. Comprehensive evaluations across three benchmark datasets, including both in-distribution and out-of-distribution scenarios, demonstrate our method's superior generation performance. Meanwhile, it achieves state-of-the-art discriminative performance on the two discriminative tasks compared to other generative models.

[Arxiv](https://arxiv.org/abs/2403.04321)