# 通过硬绑定和软细化实现区域感知的文本到图像生成

发布时间：2024年11月10日

`RAG` `图像生成` `计算机视觉`

> Region-Aware Text-to-Image Generation via Hard Binding and Soft Refinement

# 摘要

> 摘要：在本文中，我们推出了 RAG，这是一种基于区域描述的区域感知式文本到图像生成方法，用于实现精准的布局组合。区域提示或组合生成能达成细粒度的空间把控，因其在现实应用中的实用性而备受关注。然而，过往的方法要么引入额外的可训练模块，所以只适用于特定模型，要么利用注意力掩码在交叉注意力层内对分数图加以操作，致使区域数量增多时控制力度受限。为应对这些局限，我们把多区域生成拆分为两个子任务，即保证区域提示得以正确执行的单个区域构建（区域硬绑定），以及消除视觉边界并强化相邻交互的区域整体细节优化（区域软优化）。此外，RAG 创新地让重绘得以实现，用户能够在上一轮生成中修改特定不满意的区域，同时保持其他区域不变，无需依赖额外的修复模型。我们的方法无需调试，适用于其他框架，可增强提示跟随属性。定量和定性实验表明，相比以往无需调试的方法，RAG 在属性绑定和对象关系方面表现更优。

> 
Abstract:In this paper, we present RAG, a Regional-Aware text-to-image Generation method conditioned on regional descriptions for precise layout composition. Regional prompting, or compositional generation, which enables fine-grained spatial control, has gained increasing attention for its practicality in real-world applications. However, previous methods either introduce additional trainable modules, thus only applicable to specific models, or manipulate on score maps within cross-attention layers using attention masks, resulting in limited control strength when the number of regions increases. To handle these limitations, we decouple the multi-region generation into two sub-tasks, the construction of individual region (Regional Hard Binding) that ensures the regional prompt is properly executed, and the overall detail refinement (Regional Soft Refinement) over regions that dismiss the visual boundaries and enhance adjacent interactions. Furthermore, RAG novelly makes repainting feasible, where users can modify specific unsatisfied regions in the last generation while keeping all other regions unchanged, without relying on additional inpainting models. Our approach is tuning-free and applicable to other frameworks as an enhancement to the prompt following property. Quantitative and qualitative experiments demonstrate that RAG achieves superior performance over attribute binding and object relationship than previous tuning-free methods.
    

[Arxiv](https://arxiv.org/pdf/2411.06558)