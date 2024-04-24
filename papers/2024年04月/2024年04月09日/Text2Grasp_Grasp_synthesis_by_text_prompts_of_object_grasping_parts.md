# Text2Grasp：通过文字描述物体的抓握部位来实现抓取动作的合成

发布时间：2024年04月09日

`分类：Agent` `机器人技术` `人工智能`

> Text2Grasp: Grasp synthesis by text prompts of object grasping parts

# 摘要

> 手对于人类把握和操作物体至关重要，而精确的抓取合成则是顺利完成后续任务的关键。目前，依赖人类意图或任务导向语言信号的抓取方法存在固有的模糊性。为解决这一问题，我们提出了一种新颖的文本提示引导的抓取合成方法——Text2Grasp，它能够提供更为精细的控制。具体而言，我们设计了两步法：首先利用文本引导的扩散模型TextGraspDiff生成初步的抓取姿态；随后通过手-物体接触优化，确保抓取的可行性与多样性。此外，借助大型语言模型，我们的方法能够在无需额外手动标注的情况下，根据任务级和个性化的文本描述来引导抓取合成。广泛的实验结果证明，我们的方法不仅在部件级抓取控制上达到了精准度，而且在抓取质量上也展现了与现有技术相媲美的表现。

> The hand plays a pivotal role in human ability to grasp and manipulate objects and controllable grasp synthesis is the key for successfully performing downstream tasks. Existing methods that use human intention or task-level language as control signals for grasping inherently face ambiguity. To address this challenge, we propose a grasp synthesis method guided by text prompts of object grasping parts, Text2Grasp, which provides more precise control. Specifically, we present a two-stage method that includes a text-guided diffusion model TextGraspDiff to first generate a coarse grasp pose, then apply a hand-object contact optimization process to ensure both plausibility and diversity. Furthermore, by leveraging Large Language Model, our method facilitates grasp synthesis guided by task-level and personalized text descriptions without additional manual annotations. Extensive experiments demonstrate that our method achieves not only accurate part-level grasp control but also comparable performance in grasp quality.

[Arxiv](https://arxiv.org/abs/2404.15189)