# 交错场景图用于交错式文本与图像生成的评估

发布时间：2024年11月26日

`LLM应用` `视觉语言` `模型评估`

> Interleaved Scene Graph for Interleaved Text-and-Image Generation Assessment

# 摘要

> 许多现实世界中的用户查询（比如“如何做蛋炒饭？”）能从可生成带有文本步骤及配套图像的响应的系统中获益，就像一本食谱那样。旨在生成交错文本与图像的模型在保证这些模式内部及之间的一致性上遭遇难题。为应对这些挑战，我们推出了 ISG，这是一个针对交错文本和图像生成的综合评估框架。ISG 借助场景图结构来捕捉文本和图像块的关系，从四个粒度层级评估响应：整体、结构、块级以及特定图像。这种多层级评估能够对一致性、连贯性和准确性进行精细评估，并提供可解释的问答反馈。结合 ISG，我们引入了基准 ISG-Bench，涵盖 8 个类别和 21 个子类别中的 1150 个样本。该基准数据集包含复杂的语言 - 视觉依赖关系和标准答案，能有效评估模型在以视觉为核心的任务（如风格转换）上的表现，这是当前模型面临的一个挑战领域。通过 ISG-Bench，我们表明近期的统一视觉语言模型在生成交错内容方面表现欠佳。虽然将单独的语言和图像模型相结合的组合方法在整体水平上比统一模型有 111%的提升，但在块级和图像级的表现仍不理想。为推动未来工作，我们开发了 ISG-Agent，这是一个采用“计划 - 执行 - 优化”流程调用工具的基线代理，实现了 122%的性能提升。

> Many real-world user queries (e.g. "How do to make egg fried rice?") could benefit from systems capable of generating responses with both textual steps with accompanying images, similar to a cookbook. Models designed to generate interleaved text and images face challenges in ensuring consistency within and across these modalities. To address these challenges, we present ISG, a comprehensive evaluation framework for interleaved text-and-image generation. ISG leverages a scene graph structure to capture relationships between text and image blocks, evaluating responses on four levels of granularity: holistic, structural, block-level, and image-specific. This multi-tiered evaluation allows for a nuanced assessment of consistency, coherence, and accuracy, and provides interpretable question-answer feedback. In conjunction with ISG, we introduce a benchmark, ISG-Bench, encompassing 1,150 samples across 8 categories and 21 subcategories. This benchmark dataset includes complex language-vision dependencies and golden answers to evaluate models effectively on vision-centric tasks such as style transfer, a challenging area for current models. Using ISG-Bench, we demonstrate that recent unified vision-language models perform poorly on generating interleaved content. While compositional approaches that combine separate language and image models show a 111% improvement over unified models at the holistic level, their performance remains suboptimal at both block and image levels. To facilitate future work, we develop ISG-Agent, a baseline agent employing a "plan-execute-refine" pipeline to invoke tools, achieving a 122% performance improvement.

[Arxiv](https://arxiv.org/abs/2411.17188)