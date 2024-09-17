# Householder 伪旋转：一种新颖的 LLM 激活编辑方法，从方向与幅度视角出发。

发布时间：2024年09月16日

`LLM理论` `人工智能` `机器学习`

> Householder Pseudo-Rotation: A Novel Approach to Activation Editing in LLMs with Direction-Magnitude Perspective

# 摘要

> 激活编辑，通过直接修改 LLM 的内部表示来改变其行为，已成为研究热点。现有方法主要通过添加转向向量来调整激活点，但难以在提升性能的同时保持激活幅度的一致性。为此，我们提出了一种新方法，从方向和幅度角度处理激活，名为 Householder 伪旋转 (HPR)。该方法模拟旋转变换，保持激活范数，从而在安全基准测试中表现更佳。

> Activation Editing, which involves directly editting the internal representations of large language models (LLMs) to alter their behaviors and achieve desired properties, has emerged as a promising area of research. Existing works primarily treat LLMs' activations as points in space and modify them by adding steering vectors. However, this approach is limited in its ability to achieve greater performance improvement while maintaining the necessary consistency of activation magnitudes. To overcome these issues, we propose a novel editing method that views activations in terms of their directions and magnitudes. Our method, named Householder Pseudo-Rotation (HPR), mimics the rotation transformation, thus preserving activation norms and resulting in an improved performance on various safety benchmarks.

[Arxiv](https://arxiv.org/abs/2409.10053)