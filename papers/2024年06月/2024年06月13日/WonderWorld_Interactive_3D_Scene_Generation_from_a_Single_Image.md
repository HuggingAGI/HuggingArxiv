# WonderWorld：单图互动3D场景生成

发布时间：2024年06月13日

`LLM应用` `虚拟现实`

> WonderWorld: Interactive 3D Scene Generation from a Single Image

# 摘要

> 我们推出 WonderWorld，一个创新的交互式 3D 场景生成框架，让用户能即时指定场景内容与布局，并在低延迟下预览成果。核心挑战在于快速生成 3D 场景。现有方法因需逐步生成多视图与深度图，以及耗时的几何优化，速度受限。我们采用快速分层高斯 Surfels (FLAGS) 表示场景，并设计了从单视图生成的算法，无需多视图，且大幅缩短优化时间。此外，我们通过引导深度扩散，解决了生成连贯几何的难题。WonderWorld 在单 A6000 GPU 上 10 秒内即可呈现多样且相连的 3D 场景，实现实时互动与探索。我们展示了其在虚拟环境中用户主导创作与探索的潜力，并将公开代码与软件以供复现。项目网站：此链接。

> 
Abstract:We present WonderWorld, a novel framework for interactive 3D scene generation that enables users to interactively specify scene contents and layout and see the created scenes in low latency. The major challenge lies in achieving fast generation of 3D scenes. Existing scene generation approaches fall short of speed as they often require (1) progressively generating many views and depth maps, and (2) time-consuming optimization of the scene geometry representations. We introduce the Fast Layered Gaussian Surfels (FLAGS) as our scene representation and an algorithm to generate it from a single view. Our approach does not need multiple views, and it leverages a geometry-based initialization that significantly reduces optimization time. Another challenge is generating coherent geometry that allows all scenes to be connected. We introduce the guided depth diffusion that allows partial conditioning of depth estimation. WonderWorld generates connected and diverse 3D scenes in less than 10 seconds on a single A6000 GPU, enabling real-time user interaction and exploration. We demonstrate the potential of WonderWorld for user-driven content creation and exploration in virtual environments. We will release full code and software for reproducibility. Project website: this https URL.
    

[Arxiv](https://arxiv.org/pdf/2406.09394)