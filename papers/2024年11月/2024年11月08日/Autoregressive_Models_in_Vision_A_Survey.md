# 视觉中的自回归模型：一项调查

发布时间：2024年11月08日

`其他` `计算机视觉`

> Autoregressive Models in Vision: A Survey

# 摘要

> 自回归建模在自然语言处理（NLP）领域取得了巨大成功。最近，自回归模型在计算机视觉领域成为了一个重要的关注焦点，它们在生成高质量视觉内容方面表现出色。NLP 中的自回归模型通常在子词标记上运行。然而，计算机视觉中的表示策略在不同级别可能会有所不同，即像素级、标记级或规模级，这反映了与语言的顺序结构相比，视觉数据的多样性和层次性。本调查全面研究了应用于视觉的自回归模型的文献。为了提高来自不同研究背景的研究人员的可读性，我们从视觉中的初步序列表示和建模开始。接下来，我们根据表示策略将视觉自回归模型的基本框架分为三个一般子类别，包括基于像素的、基于标记的和基于规模的模型。然后，我们探讨了自回归模型与其他生成模型之间的相互联系。此外，我们对计算机视觉中的自回归模型进行了多方面的分类，包括图像生成、视频生成、3D 生成和多模态生成。我们还详细阐述了它们在不同领域的应用，包括新兴领域，如具身 AI 和 3D 医疗 AI，约有 250 个相关参考文献。最后，我们强调了视觉自回归模型目前面临的挑战，并提出了潜在研究方向的建议。我们还在 Github 上建立了一个存储库来组织本调查中包含的论文，网址为：url{https://github.com/ChaofanTao/Autoregressive-Models-in-Vision-Survey}。

> Autoregressive modeling has been a huge success in the field of natural language processing (NLP). Recently, autoregressive models have emerged as a significant area of focus in computer vision, where they excel in producing high-quality visual content. Autoregressive models in NLP typically operate on subword tokens. However, the representation strategy in computer vision can vary in different levels, \textit{i.e.}, pixel-level, token-level, or scale-level, reflecting the diverse and hierarchical nature of visual data compared to the sequential structure of language. This survey comprehensively examines the literature on autoregressive models applied to vision. To improve readability for researchers from diverse research backgrounds, we start with preliminary sequence representation and modeling in vision. Next, we divide the fundamental frameworks of visual autoregressive models into three general sub-categories, including pixel-based, token-based, and scale-based models based on the strategy of representation. We then explore the interconnections between autoregressive models and other generative models. Furthermore, we present a multi-faceted categorization of autoregressive models in computer vision, including image generation, video generation, 3D generation, and multi-modal generation. We also elaborate on their applications in diverse domains, including emerging domains such as embodied AI and 3D medical AI, with about 250 related references. Finally, we highlight the current challenges to autoregressive models in vision with suggestions about potential research directions. We have also set up a Github repository to organize the papers included in this survey at: url{https://github.com/ChaofanTao/Autoregressive-Models-in-Vision-Survey}.

[Arxiv](https://arxiv.org/abs/2411.05902)