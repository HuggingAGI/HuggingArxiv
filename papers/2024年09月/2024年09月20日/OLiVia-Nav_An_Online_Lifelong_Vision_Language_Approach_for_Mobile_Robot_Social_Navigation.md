# OLiVia-Nav：为移动机器人社交导航量身定制的在线终身视觉语言解决方案

发布时间：2024年09月20日

`Agent` `机器人`

> OLiVia-Nav: An Online Lifelong Vision Language Approach for Mobile Robot Social Navigation

# 摘要

> 在医院、办公楼和长期护理院等人性化环境中，服务机器人需要遵守社交规范进行导航，以确保与其共享空间的人们的安全和舒适。此外，它们还需适应新社交场景。本文提出了一种新颖的在线终身视觉语言架构OLiVia-Nav，将视觉语言模型与在线终身学习框架集成，用于机器人社交导航。我们引入了一种独特的蒸馏方法SC-CLIP，将大型VLM的社交推理能力转移到轻量级VLM，以便OLiVia-Nav在机器人导航期间直接编码社交和环境上下文。这些编码的嵌入用于生成和选择符合社交规范的机器人轨迹。SC-CLIP的终身学习能力使OLiVia-Nav能够随着时间的推移，用机器人轨迹预测更新轻量级VLM。我们在多种社交导航场景中进行了广泛的实际实验。结果显示，OLiVia-Nav在均方误差、Hausdorff损失和个人空间侵犯持续时间方面优于现有的最先进的DRL和VLM方法。消融研究也验证了OLiVia-Nav的设计选择。

> Service robots in human-centered environments such as hospitals, office buildings, and long-term care homes need to navigate while adhering to social norms to ensure the safety and comfortability of the people they are sharing the space with. Furthermore, they need to adapt to new social scenarios that can arise during robot navigation. In this paper, we present a novel Online Lifelong Vision Language architecture, OLiVia-Nav, which uniquely integrates vision-language models (VLMs) with an online lifelong learning framework for robot social navigation. We introduce a unique distillation approach, Social Context Contrastive Language Image Pre-training (SC-CLIP), to transfer the social reasoning capabilities of large VLMs to a lightweight VLM, in order for OLiVia-Nav to directly encode social and environment context during robot navigation. These encoded embeddings are used to generate and select robot social compliant trajectories. The lifelong learning capabilities of SC-CLIP enable OLiVia-Nav to update the lightweight VLM with robot trajectory predictions overtime as new social scenarios are encountered. We conducted extensive real-world experiments in diverse social navigation scenarios. The results showed that OLiVia-Nav outperformed existing state-of-the-art DRL and VLM methods in terms of mean squared error, Hausdorff loss, and personal space violation duration. Ablation studies also verified the design choices for OLiVia-Nav.

[Arxiv](https://arxiv.org/abs/2409.13675)