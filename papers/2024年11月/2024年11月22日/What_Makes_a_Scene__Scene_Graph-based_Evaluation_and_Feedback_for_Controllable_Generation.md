# 究竟是什么造就了一个场景？基于场景图的可控生成的评估与反馈

发布时间：2024年11月22日

`LLM应用` `图像生成` `场景图`

> What Makes a Scene ? Scene Graph-based Evaluation and Feedback for Controllable Generation

# 摘要

> 尽管文本到图像的生成已被深入研究，但从场景图生成图像这一领域仍相对缺乏探索，主要是因为在精准建模空间关系和对象交互上存在难题。为了弥补这一不足，我们推出了 Scene-Bench，这是一个用于评估和提升生成自然场景的事实一致性的综合性基准。Scene-Bench 涵盖了 MegaSG，这是一个拥有一百万张带有场景图标注的图像的大规模数据集，有利于在各种复杂场景中对模型进行训练和公平比较。另外，我们提出了 SGScore 这一新的评估指标，它借助多模态大型语言模型（LLMs）的思维链推理能力来评估对象的存在和关系的准确性，比传统的指标如 FID 和 CLIPScore 能更有效地衡量事实一致性。基于这个评估框架，我们构建了一个场景图反馈管道，通过识别并纠正场景图和图像之间的差异来逐步优化生成的图像。大量实验表明，与现有的基准相比，Scene-Bench 提供了更全面、更有效的评估框架，尤其在复杂场景生成方面。而且，我们的反馈策略极大地增强了图像生成模型的事实一致性，推动了可控图像生成领域的进步。

> While text-to-image generation has been extensively studied, generating images from scene graphs remains relatively underexplored, primarily due to challenges in accurately modeling spatial relationships and object interactions. To fill this gap, we introduce Scene-Bench, a comprehensive benchmark designed to evaluate and enhance the factual consistency in generating natural scenes. Scene-Bench comprises MegaSG, a large-scale dataset of one million images annotated with scene graphs, facilitating the training and fair comparison of models across diverse and complex scenes. Additionally, we propose SGScore, a novel evaluation metric that leverages chain-of-thought reasoning capabilities of multimodal large language models (LLMs) to assess both object presence and relationship accuracy, offering a more effective measure of factual consistency than traditional metrics like FID and CLIPScore. Building upon this evaluation framework, we develop a scene graph feedback pipeline that iteratively refines generated images by identifying and correcting discrepancies between the scene graph and the image. Extensive experiments demonstrate that Scene-Bench provides a more comprehensive and effective evaluation framework compared to existing benchmarks, particularly for complex scene generation. Furthermore, our feedback strategy significantly enhances the factual consistency of image generation models, advancing the field of controllable image generation.

[Arxiv](https://arxiv.org/abs/2411.15435)