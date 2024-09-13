# 迷宫为何如此迷宫？

发布时间：2024年09月12日

`LLM应用` `人工智能` `计算机视觉`

> What Makes a Maze Look Like a Maze?

# 摘要

> 人类视觉理解的一个独特之处在于，我们能灵活解读抽象概念，理解其象征意义，并在不同情境中运用这些概念进行推理。然而，现有的视觉语言模型虽能识别具体物体（如树枝），却难以理解复杂的视觉抽象（如树枝构成迷宫墙）。为此，我们提出了深度模式基础（DSG）框架，通过显式结构化表示来处理视觉抽象，进行基础和推理。DSG的核心是模式，即抽象概念的依赖图，将其分解为基本符号。我们利用大型语言模型提取模式，并结合视觉语言模型，将抽象概念逐步具体化到图像上。通过这种方式，DSG显著提升了视觉语言模型在抽象视觉推理上的表现，向实现与人类一致的视觉抽象理解迈出了重要一步。

> A unique aspect of human visual understanding is the ability to flexibly interpret abstract concepts: acquiring lifted rules explaining what they symbolize, grounding them across familiar and unfamiliar contexts, and making predictions or reasoning about them. While off-the-shelf vision-language models excel at making literal interpretations of images (e.g., recognizing object categories such as tree branches), they still struggle to make sense of such visual abstractions (e.g., how an arrangement of tree branches may form the walls of a maze). To address this challenge, we introduce Deep Schema Grounding (DSG), a framework that leverages explicit structured representations of visual abstractions for grounding and reasoning. At the core of DSG are schemas--dependency graph descriptions of abstract concepts that decompose them into more primitive-level symbols. DSG uses large language models to extract schemas, then hierarchically grounds concrete to abstract components of the schema onto images with vision-language models. The grounded schema is used to augment visual abstraction understanding. We systematically evaluate DSG and different methods in reasoning on our new Visual Abstractions Dataset, which consists of diverse, real-world images of abstract concepts and corresponding question-answer pairs labeled by humans. We show that DSG significantly improves the abstract visual reasoning performance of vision-language models, and is a step toward human-aligned understanding of visual abstractions.

[Arxiv](https://arxiv.org/abs/2409.08202)