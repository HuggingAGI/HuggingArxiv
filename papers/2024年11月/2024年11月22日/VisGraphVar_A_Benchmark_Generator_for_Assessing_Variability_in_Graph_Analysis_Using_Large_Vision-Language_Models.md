# VisGraphVar：一个用于评估借助大型视觉语言模型进行图分析时的可变性的基准生成器

发布时间：2024年11月22日

`LLM应用` `视觉图形` `模型评估`

> VisGraphVar: A Benchmark Generator for Assessing Variability in Graph Analysis Using Large Vision-Language Models

# 摘要

> 大型视觉语言模型（LVLMs）发展迅猛，潜力巨大。这些模型处理抽象视觉任务的能力日益增强。几何结构，尤其是兼具灵活性与复杂性的图形，是评估模型预测能力的绝佳标准。虽说人类观察者能轻松识别细微的视觉细节并做出精准分析，但我们的研究发现，最前沿的LVLMs在特定视觉图形场景中存在一致的局限性，尤其在面对风格变化时。为应对这些挑战，我们推出了VisGraphVar（视觉图形可变性），这是一个可定制的基准生成器，能为七个不同任务类别（检测、分类、分割、模式识别、链接预测、推理、匹配）生成图形图像，旨在系统评估各个LVLMs的优劣。我们用VisGraphVar生成了990个图形图像，评估了六个LVLMs，并采用了零样本和思维链这两种不同的提示策略。结果表明，图像的视觉属性变化（如节点标注和布局）以及故意引入的视觉缺陷（如节点重叠）会显著影响模型性能。本研究强调了在图形相关任务中进行全面评估的重要性，不能只局限于推理。VisGraphVar提供了宝贵的见解，有助于指导开发更可靠、更强大、能进行高级视觉图形分析的系统。

> The fast advancement of Large Vision-Language Models (LVLMs) has shown immense potential. These models are increasingly capable of tackling abstract visual tasks. Geometric structures, particularly graphs with their inherent flexibility and complexity, serve as an excellent benchmark for evaluating these models' predictive capabilities. While human observers can readily identify subtle visual details and perform accurate analyses, our investigation reveals that state-of-the-art LVLMs exhibit consistent limitations in specific visual graph scenarios, especially when confronted with stylistic variations. In response to these challenges, we introduce VisGraphVar (Visual Graph Variability), a customizable benchmark generator able to produce graph images for seven distinct task categories (detection, classification, segmentation, pattern recognition, link prediction, reasoning, matching), designed to systematically evaluate the strengths and limitations of individual LVLMs. We use VisGraphVar to produce 990 graph images and evaluate six LVLMs, employing two distinct prompting strategies, namely zero-shot and chain-of-thought. The findings demonstrate that variations in visual attributes of images (e.g., node labeling and layout) and the deliberate inclusion of visual imperfections, such as overlapping nodes, significantly affect model performance. This research emphasizes the importance of a comprehensive evaluation across graph-related tasks, extending beyond reasoning alone. VisGraphVar offers valuable insights to guide the development of more reliable and robust systems capable of performing advanced visual graph analysis.

[Arxiv](https://arxiv.org/abs/2411.14832)