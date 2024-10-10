# Trans4D：实现几何感知的真实过渡，助力组合式文本到4D合成

发布时间：2024年10月09日

`LLM应用` `视频产业`

> Trans4D: Realistic Geometry-Aware Transition for Compositional Text-to-4D Synthesis

# 摘要

> 扩散模型的进步在图像和视频生成领域表现出色，提升了4D合成的效率。现有的4D生成技术能根据用户需求生成高质量的4D物体或场景，对游戏和视频产业大有裨益。然而，这些技术在处理复杂4D过渡和场景内交互的显著变形时显得力不从心。为此，我们推出了Trans4D，一个创新的文本到4D合成框架，专为实现真实且复杂的场景过渡设计。首先，我们利用多模态大型语言模型（MLLMs）生成物理感知的场景描述，用于4D场景初始化和过渡时间规划。接着，我们设计了一个几何感知的4D过渡网络，根据规划实现复杂的场景级4D过渡，包含丰富的几何物体变形。实验结果显示，Trans4D在生成精准且高品质的4D场景过渡方面，始终领先于现有最先进技术，证明了其卓越性能。代码链接：https://github.com/YangLing0818/Trans4D

> Recent advances in diffusion models have demonstrated exceptional capabilities in image and video generation, further improving the effectiveness of 4D synthesis. Existing 4D generation methods can generate high-quality 4D objects or scenes based on user-friendly conditions, benefiting the gaming and video industries. However, these methods struggle to synthesize significant object deformation of complex 4D transitions and interactions within scenes. To address this challenge, we propose Trans4D, a novel text-to-4D synthesis framework that enables realistic complex scene transitions. Specifically, we first use multi-modal large language models (MLLMs) to produce a physic-aware scene description for 4D scene initialization and effective transition timing planning. Then we propose a geometry-aware 4D transition network to realize a complex scene-level 4D transition based on the plan, which involves expressive geometrical object deformation. Extensive experiments demonstrate that Trans4D consistently outperforms existing state-of-the-art methods in generating 4D scenes with accurate and high-quality transitions, validating its effectiveness. Code: https://github.com/YangLing0818/Trans4D

[Arxiv](https://arxiv.org/abs/2410.07155)