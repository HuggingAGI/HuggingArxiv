# AnySynth：借助图像合成数据生成的力量来完成广义视觉语言任务

发布时间：2024年11月23日

`LLM应用` `计算机视觉`

> AnySynth: Harnessing the Power of Image Synthetic Data Generation for Generalized Vision-Language Tasks

# 摘要

> 近来，扩散模型被用于生成高品质图像，降低了手动收集数据的需求，在对象检测、实例分割和图像感知等任务中提升了模型的泛化能力。但由于图像布局、内容及注释格式的多样要求，合成框架往往要针对每个任务精心人工设计，这限制了合成数据在更普遍场景中的应用。本文中，我们提出了 AnySynth 这一统一框架，它整合了适应性强、全面且高度可控的组件，能依据不同需求生成任意类型的合成数据。具体来说，先是引入特定任务布局生成模块，借助大型语言模型的生成能力和真实世界图像的布局先验，为不同任务生成合理布局。接着开发了统一控制的图像生成模块，基于生成的布局创建可控的高质量合成图像。另外，用户特定的参考图像和风格图像可按任务要求融入生成过程。最后，面向任务的注释模块为不同任务生成的图像提供精准详细的注释。我们已在少样本对象检测、跨域对象检测、零样本组合图像检索以及多模态图像感知和基础等各类任务中验证了框架的性能。我们框架合成的特定数据显著提升了这些任务中的模型性能，彰显了框架的通用性和有效性。

> Diffusion models have recently been employed to generate high-quality images, reducing the need for manual data collection and improving model generalization in tasks such as object detection, instance segmentation, and image perception. However, the synthetic framework is usually designed with meticulous human effort for each task due to various requirements on image layout, content, and annotation formats, restricting the application of synthetic data on more general scenarios. In this paper, we propose AnySynth, a unified framework integrating adaptable, comprehensive, and highly controllable components capable of generating an arbitrary type of synthetic data given diverse requirements. Specifically, the Task-Specific Layout Generation Module is first introduced to produce reasonable layouts for different tasks by leveraging the generation ability of large language models and layout priors of real-world images. A Uni-Controlled Image Generation Module is then developed to create high-quality synthetic images that are controllable and based on the generated layouts. In addition, user specific reference images, and style images can be incorporated into the generation to task requirements. Finally, the Task-Oriented Annotation Module offers precise and detailed annotations for the generated images across different tasks. We have validated our framework's performance across various tasks, including Few-shot Object Detection, Cross-domain Object Detection, Zero-shot Composed Image Retrieval, and Multi-modal Image Perception and Grounding. The specific data synthesized by our framework significantly improves model performance in these tasks, demonstrating the generality and effectiveness of our framework.

[Arxiv](https://arxiv.org/abs/2411.16749)