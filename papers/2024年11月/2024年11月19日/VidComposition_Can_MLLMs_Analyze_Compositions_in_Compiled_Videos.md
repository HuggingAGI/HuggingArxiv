# VidComposition：多模态大型语言模型能否解析编译视频中的构图？

发布时间：2024年11月19日

`LLM应用` `多模态理解`

> VidComposition: Can MLLMs Analyze Compositions in Compiled Videos?

# 摘要

> 多模态大型语言模型（MLLMs）的发展在多模态理解领域成果斐然，增强了其分析视频内容的能力。然而，现有的 MLLMs 评估基准多聚焦于抽象的视频理解，对其理解视频组合的能力，也就是对高度编译的视频情境中视觉元素如何组合及相互作用的细致解读，缺乏详尽评估。我们推出了 VidComposition 这一新基准，通过精心筛选的编译视频和电影级注释来评估 MLLMs 对视频组合的理解能力。VidComposition 涵盖 982 个视频和 1706 道选择题，涉及摄像机移动、角度、镜头大小、叙事结构、角色动作及情感等各类组合方面。我们对 33 个开源和专有 MLLMs 的全面评估表明，人类和模型的能力存在显著差距。这凸显了当前 MLLMs 在理解复杂的编译视频组合时的局限性，也为后续改进指明了方向。排行榜和评估代码可在 https://yunlong10.github.io/VidComposition/ 获取。

> The advancement of Multimodal Large Language Models (MLLMs) has enabled significant progress in multimodal understanding, expanding their capacity to analyze video content. However, existing evaluation benchmarks for MLLMs primarily focus on abstract video comprehension, lacking a detailed assessment of their ability to understand video compositions, the nuanced interpretation of how visual elements combine and interact within highly compiled video contexts. We introduce VidComposition, a new benchmark specifically designed to evaluate the video composition understanding capabilities of MLLMs using carefully curated compiled videos and cinematic-level annotations. VidComposition includes 982 videos with 1706 multiple-choice questions, covering various compositional aspects such as camera movement, angle, shot size, narrative structure, character actions and emotions, etc. Our comprehensive evaluation of 33 open-source and proprietary MLLMs reveals a significant performance gap between human and model capabilities. This highlights the limitations of current MLLMs in understanding complex, compiled video compositions and offers insights into areas for further improvement. The leaderboard and evaluation code are available at https://yunlong10.github.io/VidComposition/.

[Arxiv](https://arxiv.org/abs/2411.10979)