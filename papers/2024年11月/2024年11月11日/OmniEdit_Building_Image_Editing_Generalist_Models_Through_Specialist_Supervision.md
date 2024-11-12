# OmniEdit：通过专家监督构建图像编辑通才模型

发布时间：2024年11月11日

`其他` `图像编辑` `计算机视觉`

> OmniEdit: Building Image Editing Generalist Models Through Specialist Supervision

# 摘要

> 指令引导的图像编辑方法通过在自动合成或手动注释的图像编辑对上训练扩散模型，已经显示出巨大的潜力。然而，这些方法距离实际的现实应用还很远。我们确定了造成这种差距的三个主要挑战。首先，由于合成过程存在偏差，现有模型的编辑技能有限。其次，这些方法是使用大量噪声和伪影的数据集进行训练的。这是由于应用了像 CLIP-score 这样的简单过滤方法。第三，所有这些数据集都局限于单一的低分辨率和固定的纵横比，限制了处理现实世界用例的通用性。在本文中，我们提出了\omniedit，这是一个全能的编辑器，可以无缝处理具有任何纵横比的七种不同图像编辑任务。我们的贡献有四个方面：（1）\omniedit 通过利用来自七个不同专业模型的监督进行训练，以确保任务覆盖。（2）我们利用基于大型多模态模型（如 GPT-4o）提供的分数的重要性采样，而不是 CLIP-score，来提高数据质量。（3）我们提出了一种称为 EditNet 的新编辑架构，大大提高了编辑成功率，（4）我们提供具有不同纵横比的图像，以确保我们的模型能够处理野外的任何图像。我们策划了一个包含不同纵横比图像的测试集，并伴有各种指令以涵盖不同的任务。自动评估和人工评估都表明，\omniedit 能够显著优于所有现有的模型。我们的代码、数据集和模型将在 url{https://tiger-ai-lab.github.io/OmniEdit/} 上提供。

> Instruction-guided image editing methods have demonstrated significant potential by training diffusion models on automatically synthesized or manually annotated image editing pairs. However, these methods remain far from practical, real-life applications. We identify three primary challenges contributing to this gap. Firstly, existing models have limited editing skills due to the biased synthesis process. Secondly, these methods are trained with datasets with a high volume of noise and artifacts. This is due to the application of simple filtering methods like CLIP-score. Thirdly, all these datasets are restricted to a single low resolution and fixed aspect ratio, limiting the versatility to handle real-world use cases. In this paper, we present \omniedit, which is an omnipotent editor to handle seven different image editing tasks with any aspect ratio seamlessly. Our contribution is in four folds: (1) \omniedit is trained by utilizing the supervision from seven different specialist models to ensure task coverage. (2) we utilize importance sampling based on the scores provided by large multimodal models (like GPT-4o) instead of CLIP-score to improve the data quality. (3) we propose a new editing architecture called EditNet to greatly boost the editing success rate, (4) we provide images with different aspect ratios to ensure that our model can handle any image in the wild. We have curated a test set containing images of different aspect ratios, accompanied by diverse instructions to cover different tasks. Both automatic evaluation and human evaluations demonstrate that \omniedit can significantly outperform all the existing models. Our code, dataset and model will be available at url{https://tiger-ai-lab.github.io/OmniEdit/}

[Arxiv](https://arxiv.org/abs/2411.07199)