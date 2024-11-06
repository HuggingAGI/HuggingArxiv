# MVPaint：用于绘制任何 3D 事物的同步多视图扩散

发布时间：2024年11月04日

`其他` `3D 资产` `纹理处理`

> MVPaint: Synchronized Multi-View Diffusion for Painting Anything 3D

# 摘要

> 摘要：纹理处理是 3D 资产生产工作流程中的关键步骤，它增强了 3D 资产的视觉吸引力和多样性。尽管在文本到纹理（T2T）生成方面最近取得了进展，但现有方法往往产生不佳的结果，主要是由于局部不连续性、多视图之间的不一致性以及它们对 UV 展开结果的严重依赖。为了应对这些挑战，我们提出了一种名为 MVPaint 的新型生成-细化 3D 纹理框架，它可以生成高分辨率、无缝的纹理，同时强调多视图一致性。MVPaint 主要由三个关键模块组成。1）同步多视图生成（SMG）。给定一个 3D 网格模型，MVPaint 首先通过使用 SMG 模型同时生成多视图图像，这导致由于缺少观察而产生带有未绘制部分的粗糙纹理结果。2）空间感知 3D 修复（S3I）。为了确保完整的 3D 纹理处理，我们引入了 S3I 方法，专门设计用于有效地处理先前未观察到的区域。3）UV 细化（UVR）。此外，MVPaint 采用 UVR 模块来提高 UV 空间中的纹理质量，它首先执行 UV 空间超分辨率，然后是空间感知接缝平滑算法，用于修正由 UV 展开引起的空间纹理不连续性。此外，我们分别基于从 Objaverse 数据集和整个 GSO 数据集中选择的高质量 3D 网格建立了两个 T2T 评估基准：Objaverse T2T 基准和 GSO T2T 基准。大量实验结果表明，MVPaint 超过了现有的最先进方法。值得注意的是，MVPaint 可以生成具有最小 Janus 问题和高度增强的跨视图一致性的高保真纹理。

> 
Abstract:Texturing is a crucial step in the 3D asset production workflow, which enhances the visual appeal and diversity of 3D assets. Despite recent advancements in Text-to-Texture (T2T) generation, existing methods often yield subpar results, primarily due to local discontinuities, inconsistencies across multiple views, and their heavy dependence on UV unwrapping outcomes. To tackle these challenges, we propose a novel generation-refinement 3D texturing framework called MVPaint, which can generate high-resolution, seamless textures while emphasizing multi-view consistency. MVPaint mainly consists of three key modules. 1) Synchronized Multi-view Generation (SMG). Given a 3D mesh model, MVPaint first simultaneously generates multi-view images by employing an SMG model, which leads to coarse texturing results with unpainted parts due to missing observations. 2) Spatial-aware 3D Inpainting (S3I). To ensure complete 3D texturing, we introduce the S3I method, specifically designed to effectively texture previously unobserved areas. 3) UV Refinement (UVR). Furthermore, MVPaint employs a UVR module to improve the texture quality in the UV space, which first performs a UV-space Super-Resolution, followed by a Spatial-aware Seam-Smoothing algorithm for revising spatial texturing discontinuities caused by UV unwrapping. Moreover, we establish two T2T evaluation benchmarks: the Objaverse T2T benchmark and the GSO T2T benchmark, based on selected high-quality 3D meshes from the Objaverse dataset and the entire GSO dataset, respectively. Extensive experimental results demonstrate that MVPaint surpasses existing state-of-the-art methods. Notably, MVPaint could generate high-fidelity textures with minimal Janus issues and highly enhanced cross-view consistency.
    

[Arxiv](https://arxiv.org/pdf/2411.02336)