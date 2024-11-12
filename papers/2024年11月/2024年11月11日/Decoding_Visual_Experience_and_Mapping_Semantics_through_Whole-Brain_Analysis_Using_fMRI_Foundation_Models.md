# 通过使用功能性磁共振成像（fMRI）基础模型进行全脑分析来解码视觉体验和映射语义

发布时间：2024年11月11日

`其他` `认知科学` `神经科学`

> Decoding Visual Experience and Mapping Semantics through Whole-Brain Analysis Using fMRI Foundation Models

# 摘要

> 神经解码，即理解大脑活动如何对应不同刺激的过程，一直是认知科学中的一个主要目标。在过去的三十年里，功能性磁共振成像和机器学习的进步极大地提高了我们将视觉刺激映射到大脑活动的能力，特别是在视觉皮层。同时，研究已经扩展到对整个大脑中更复杂的过程如语言和记忆的解码，利用技术来处理更大的变异性和提高信号准确性。我们认为，“看”不仅仅涉及将视觉刺激映射到视觉皮层；它涉及整个大脑，因为观察不同的场景可以产生各种情绪和认知状态。在本文中，我们开发算法，通过结合个体在接受视觉刺激时的全脑激活图来增强我们对视觉过程的理解。我们利用在大型公共数据集上预先训练的大规模 fMRI 编码器和图像生成模型，然后通过图像 - fMRI 对比学习进行微调。因此，我们的模型可以解码整个大脑皮层的视觉体验，超越了视觉皮层的传统界限。我们首先将我们的方法与最先进的视觉处理解码方法进行比较，并显示预测语义准确性提高了 43％。网络消融分析表明，除了视觉皮层，默认模式网络对解码刺激的贡献最大，这与该网络在意义理解和语义处理中提出的作用一致。此外，我们在一个额外的验证数据集上实施了零样本想象解码，实现了重建图像和真实文本刺激映射的 p 值为 0.0206，这证实了模型在各种场景中捕捉语义含义的能力。

> Neural decoding, the process of understanding how brain activity corresponds to different stimuli, has been a primary objective in cognitive sciences. Over the past three decades, advancements in functional Magnetic Resonance Imaging and machine learning have greatly improved our ability to map visual stimuli to brain activity, especially in the visual cortex. Concurrently, research has expanded into decoding more complex processes like language and memory across the whole brain, utilizing techniques to handle greater variability and improve signal accuracy. We argue that "seeing" involves more than just mapping visual stimuli onto the visual cortex; it engages the entire brain, as various emotions and cognitive states can emerge from observing different scenes. In this paper, we develop algorithms to enhance our understanding of visual processes by incorporating whole-brain activation maps while individuals are exposed to visual stimuli. We utilize large-scale fMRI encoders and Image generative models pre-trained on large public datasets, which are then fine-tuned through Image-fMRI contrastive learning. Our models hence can decode visual experience across the entire cerebral cortex, surpassing the traditional confines of the visual cortex. We first compare our method with state-of-the-art approaches to decoding visual processing and show improved predictive semantic accuracy by 43%. A network ablation analysis suggests that beyond the visual cortex, the default mode network contributes most to decoding stimuli, in line with the proposed role of this network in sense-making and semantic processing. Additionally, we implemented zero-shot imagination decoding on an extra validation dataset, achieving a p-value of 0.0206 for mapping the reconstructed images and ground-truth text stimuli, which substantiates the model's capability to capture semantic meanings across various scenarios.

[Arxiv](https://arxiv.org/abs/2411.07121)