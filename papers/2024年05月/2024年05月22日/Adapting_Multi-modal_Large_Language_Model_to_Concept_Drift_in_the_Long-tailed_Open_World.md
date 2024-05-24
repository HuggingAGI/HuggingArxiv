# 多模态大型语言模型在长尾开放世界中应对概念漂移的适应性调整

发布时间：2024年05月22日

`LLM应用

这篇论文主要探讨了多模态大型语言模型（MLLMs）在面对现实世界数据极端不平衡和包含分布外实例的情况下的表现和改进方法。论文提出了一种新的框架和方法来纠正模型在预训练和微调过程中由于尾部漂移和分布外漂移引起的偏差，并通过实验验证了这些改进的有效性。此外，论文还发布了一个新的多模态数据集OpenMMlo来支持其研究。这些内容主要关注于LLM在实际应用中的性能优化和数据处理，因此属于LLM应用分类。` `多模态学习` `数据偏差`

> Adapting Multi-modal Large Language Model to Concept Drift in the Long-tailed Open World

# 摘要

> 现实世界的数据往往极端不平衡且包含分布外实例，这严重影响了模型训练的公正性。尽管视觉和语言领域已对此进行了深入研究，但长尾开放世界对多模态大型语言模型（MLLMs）的影响却鲜为人知。本文首先揭示了视觉-语言模型在预训练和微调过程中，对尾部漂移和分布外漂移引起的偏差极为敏感。为了纠正这些偏差，我们构建了一个统一框架，将尾部漂移适应与OOD漂移检测相结合，并扩展了多模态的概念漂移理论。我们提出了一种基于T分布的漂移适配器，有效缓解了长尾问题带来的偏差，并帮助模型更准确地区分OOD数据。实验结果显示，我们的模型在应对尾部和OOD漂移方面取得了显著进步，同时提升了视觉语言模型在长尾开放世界场景中的图像-文本对齐效率和准确性。此外，我们专门为长尾开放世界场景定制了一套名为OpenMMlo的多模态数据集，以验证我们的研究成果。为了推动多模态领域的发展，我们已将OpenMMlo数据集及代码公开在：https://github.com/Anonymous0Knight/ConceptDriftMLLMs。

> Real-world data often exhibit extreme imbalances and out-of-distribution (OOD) instances, which significantly biases the model training. While it has been extensively studied in vision and language domains separately, the impact of long-tailed open worlds on multi-modal large language models (MLLMs) has been largely overlooked. In this paper, we first demonstrate the susceptibility and vulnerability of vision-language models to significant biases caused by tail drift and out-of-distribution (OOD) drift during both the pre-training and fine-tuning stages. To eliminate the bias from different sources, we integrate the tailed drift adaptation and OOD drift detection into a unified framework by extending the concept drift theory to multi-modal. Specifically, a T-distribution-based drift adapter is proposed to effectively mitigate the bias induced by the long-tailed problem, which also facilitates the model in distinguishing OOD data through explicit distribution modelling. Extensive experiments show significant improvements in our model's ability to adapt to tailed drift and OOD drift. Moreover, it enhances the efficiency and accuracy of image-text alignment in vision language model pre-training, particularly in the long-tail open world scenario. Furthermore, we create a set of multi-modal datasets called OpenMMlo, specifically tailored for the long-tailed open world scenario, to validate our findings. To foster the development of the multi-modal community, we have made both OpenMMlo datasets and our code publicly available at: https://github.com/Anonymous0Knight/ConceptDriftMLLMs.

[Arxiv](https://arxiv.org/abs/2405.13459)