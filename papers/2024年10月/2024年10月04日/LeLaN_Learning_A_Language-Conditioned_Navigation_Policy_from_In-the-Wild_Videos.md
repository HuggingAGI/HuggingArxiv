# LeLaN：通过野外视频学习语言条件下的导航策略

发布时间：2024年10月04日

`Agent` `机器人` `人工智能`

> LeLaN: Learning A Language-Conditioned Navigation Policy from In-the-Wild Videos

# 摘要

> 世界万物纷繁复杂，机器人若想发挥作用，必须学会寻找人们描述的任意物体。本文介绍的 LeLaN 方法，通过未标记、无动作的第一人称数据，实现了可扩展的语言条件对象导航。LeLaN 结合大型视觉语言模型和机器人基础模型的语义知识，为室内外环境中的野外数据打上标签。我们处理了超过 130 小时的室内外真实数据，包括机器人观察、YouTube 视频和人类行走记录。经过 1000 多次真实试验，实验证明，LeLaN 从无标签视频中训练出的策略，不仅超越了现有最先进的机器人导航方法，推理速度更是其 4 倍。我们已在项目页面（https://learning-language-navigation.github.io/）开源模型、数据集，并附上补充视频。

> The world is filled with a wide variety of objects. For robots to be useful, they need the ability to find arbitrary objects described by people. In this paper, we present LeLaN(Learning Language-conditioned Navigation policy), a novel approach that consumes unlabeled, action-free egocentric data to learn scalable, language-conditioned object navigation. Our framework, LeLaN leverages the semantic knowledge of large vision-language models, as well as robotic foundation models, to label in-the-wild data from a variety of indoor and outdoor environments. We label over 130 hours of data collected in real-world indoor and outdoor environments, including robot observations, YouTube video tours, and human walking data. Extensive experiments with over 1000 real-world trials show that our approach enables training a policy from unlabeled action-free videos that outperforms state-of-the-art robot navigation methods, while being capable of inference at 4 times their speed on edge compute. We open-source our models, datasets and provide supplementary videos on our project page (https://learning-language-navigation.github.io/).

[Arxiv](https://arxiv.org/abs/2410.03603)