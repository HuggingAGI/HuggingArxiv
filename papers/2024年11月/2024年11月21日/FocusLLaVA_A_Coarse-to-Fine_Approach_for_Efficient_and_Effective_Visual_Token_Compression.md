# FocusLLaVA：一种实现高效且有效视觉标记压缩的从粗到细的方法

发布时间：2024年11月21日

`LLM应用` `计算机视觉` `多模态模型`

> FocusLLaVA: A Coarse-to-Fine Approach for Efficient and Effective Visual Token Compression

# 摘要

> 近期多模态大型语言模型的研究进展显示，高分辨率图像输入对模型能力，尤其是细粒度任务而言，极为关键。但高分辨率图像致使输入到LLM的视觉标记数量呈二次方增长，导致计算成本大幅增加。当下的工作开发了视觉标记压缩方法来提高效率，却常常牺牲了性能。我们主张消除视觉冗余能够同时提升效率和性能。我们构建了一种由粗到细的视觉标记压缩方法，配有用于压缩低信息密度冗余区域的视觉引导采样器，以及用于选取与用户指令强相关视觉标记的文本引导采样器。凭借这两个模块，所提出的FocusLLaVA在效率和性能上均有所提升。我们在众多评估数据集中验证了该方法的有效性。

> Recent advances on Multi-modal Large Language Models have demonstrated that high-resolution image input is crucial for model capabilities, especially for fine-grained tasks. However, high-resolution images lead to a quadratic increase in the number of visual tokens input into LLMs, resulting in significant computational costs. Current work develop visual token compression methods to achieve efficiency improvements, often at the expense of performance. We argue that removing visual redundancy can simultaneously improve both efficiency and performance. We build a coarse-to-fine visual token compression method, with a vision-guided sampler for compressing redundant regions with low information density, and a text-guided sampler for selecting visual tokens that are strongly correlated with the user instructions.With these two modules, the proposed FocusLLaVA achieves improvements in both efficiency and performance. We validate the effectiveness of our approach on a wide range of evaluation datasets.

[Arxiv](https://arxiv.org/abs/2411.14228)