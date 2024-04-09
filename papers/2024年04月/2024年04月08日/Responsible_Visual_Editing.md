# 在视觉编辑领域，我们强调负责任的实践，旨在确保编辑过程不仅追求美观，而且兼顾道德和文化敏感性。

发布时间：2024年04月08日

`LLM应用` `视觉合成` `内容审查`

> Responsible Visual Editing

# 摘要

> 随着视觉合成领域的快速发展，我们越来越容易遇到带有负面影响的图像，比如传播仇恨、歧视或侵犯隐私的内容。如何将这些有害图像转化为负责任的图像，这一研究领域尚待开发。本文提出了一项新任务——负责任的视觉编辑，即在尽量保持原貌的前提下，对图像中的特定概念进行修改，使其更加妥当。但挑战在于，这些需要修改的概念往往是抽象的，难以确定和规划修改方案。为此，我们设计了一个名为CoEditor的认知编辑器，它通过两阶段的认知过程——首先是感知认知，识别需要修改的部分；其次是行为认知，制定修改策略——来利用大型多模态模型。为了减少有害图像对研究的不利影响，我们构建了一个名为AltBear的公开透明数据集，用泰迪熊代替真人来展示有害信息。实验证明，CoEditor能够准确把握复杂场景中的抽象概念，并在负责任的视觉编辑任务上大幅超越传统模型。AltBear数据集与现实中的有害内容高度吻合，为实验评估提供了稳定基础，为未来研究设立了安全标杆。此外，CoEditor在常规图像编辑任务上也展现了卓越的性能。相关代码和数据集已在https://github.com/kodenii/Responsible-Visual-Editing发布。

> With recent advancements in visual synthesis, there is a growing risk of encountering images with detrimental effects, such as hate, discrimination, or privacy violations. The research on transforming harmful images into responsible ones remains unexplored. In this paper, we formulate a new task, responsible visual editing, which entails modifying specific concepts within an image to render it more responsible while minimizing changes. However, the concept that needs to be edited is often abstract, making it challenging to locate what needs to be modified and plan how to modify it. To tackle these challenges, we propose a Cognitive Editor (CoEditor) that harnesses the large multimodal model through a two-stage cognitive process: (1) a perceptual cognitive process to focus on what needs to be modified and (2) a behavioral cognitive process to strategize how to modify. To mitigate the negative implications of harmful images on research, we create a transparent and public dataset, AltBear, which expresses harmful information using teddy bears instead of humans. Experiments demonstrate that CoEditor can effectively comprehend abstract concepts within complex scenes and significantly surpass the performance of baseline models for responsible visual editing. We find that the AltBear dataset corresponds well to the harmful content found in real images, offering a consistent experimental evaluation, thereby providing a safer benchmark for future research. Moreover, CoEditor also shows great results in general editing. We release our code and dataset at https://github.com/kodenii/Responsible-Visual-Editing.

[Arxiv](https://arxiv.org/abs/2404.05580)