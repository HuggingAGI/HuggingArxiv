# 图像中究竟有何内容？对视觉语言模型的视觉进行深度剖析

发布时间：2024年11月26日

`LLM理论` `视觉处理` `模型分析`

> What's in the Image? A Deep-Dive into the Vision of Vision Language Models

# 摘要

> 视觉语言模型（VLMs）近来在理解复杂视觉内容上表现出了惊人的能力。然而，VLMs 处理视觉信息的内在机制在很大程度上尚未被探究清楚。在本文中，我们展开了全面的实证分析，着重于各层的注意力模块。我们揭示了有关这些模型处理视觉数据的若干关键洞察：（i）查询令牌的内部表征（比如“描述图像”的表征），被 VLMs 用来存储全局图像信息；我们证实这些模型仅依靠这些令牌就能生成出人意料的描述性回应，无需直接触及图像令牌。（ii）跨模态的信息流主要受中间层（约占所有层的 25%）影响，而早期和晚期层的贡献微乎其微。（iii）细粒度的视觉属性和对象细节以空间局部化的方式直接从图像令牌中提取，也就是说，与特定对象或属性相关的生成令牌会强烈关注图像中对应的区域。我们提出了新颖的定量评估来验证我们的观察，借助现实世界中的复杂视觉场景。最后，我们展示了我们的发现对于推动最先进的 VLMs 中高效视觉处理的潜力。

> Vision-Language Models (VLMs) have recently demonstrated remarkable capabilities in comprehending complex visual content. However, the mechanisms underlying how VLMs process visual information remain largely unexplored. In this paper, we conduct a thorough empirical analysis, focusing on attention modules across layers. We reveal several key insights about how these models process visual data: (i) the internal representation of the query tokens (e.g., representations of "describe the image"), is utilized by VLMs to store global image information; we demonstrate that these models generate surprisingly descriptive responses solely from these tokens, without direct access to image tokens. (ii) Cross-modal information flow is predominantly influenced by the middle layers (approximately 25% of all layers), while early and late layers contribute only marginally.(iii) Fine-grained visual attributes and object details are directly extracted from image tokens in a spatially localized manner, i.e., the generated tokens associated with a specific object or attribute attend strongly to their corresponding regions in the image. We propose novel quantitative evaluation to validate our observations, leveraging real-world complex visual scenes. Finally, we demonstrate the potential of our findings in facilitating efficient visual processing in state-of-the-art VLMs.

[Arxiv](https://arxiv.org/abs/2411.17491)