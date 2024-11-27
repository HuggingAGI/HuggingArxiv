# SketchAgent：由语言驱动的顺序式草图生成

发布时间：2024年11月26日

`Agent` `人机交互` `内容创作`

> SketchAgent: Language-Driven Sequential Sketch Generation

# 摘要

> 草图绘制堪称将想法具象化的多面手工具，能在众多学科领域实现快速探索与视觉交流。尽管人工系统在内容创作和人机交互领域取得了显著进步，但捕捉人类草图绘制的动态及抽象特质仍颇具挑战。在本项工作中，我们推出了 SketchAgent，这是一种由语言驱动的顺序式草图生成方法，能让用户通过动态的对话式交互来创建、修改和优化草图。我们的方法无需训练或微调，而是借助现成多模态大型语言模型（LLMs）的顺序特性和丰富的先验知识。我们提出了一种直观的草图语言，通过上下文示例引入模型，使其能够凭借基于字符串的动作来“作画”。这些动作会被处理为矢量图形，然后渲染在像素画布上生成草图，该草图可再次用于后续任务。通过一笔一划地描绘，我们的代理捕捉到了草图绘制所固有的不断演变的动态特质。我们证实，SketchAgent 能够依据各类提示生成草图，参与对话驱动的绘图，并与人类用户展开富有意义的协作。

> Sketching serves as a versatile tool for externalizing ideas, enabling rapid exploration and visual communication that spans various disciplines. While artificial systems have driven substantial advances in content creation and human-computer interaction, capturing the dynamic and abstract nature of human sketching remains challenging. In this work, we introduce SketchAgent, a language-driven, sequential sketch generation method that enables users to create, modify, and refine sketches through dynamic, conversational interactions. Our approach requires no training or fine-tuning. Instead, we leverage the sequential nature and rich prior knowledge of off-the-shelf multimodal large language models (LLMs). We present an intuitive sketching language, introduced to the model through in-context examples, enabling it to "draw" using string-based actions. These are processed into vector graphics and then rendered to create a sketch on a pixel canvas, which can be accessed again for further tasks. By drawing stroke by stroke, our agent captures the evolving, dynamic qualities intrinsic to sketching. We demonstrate that SketchAgent can generate sketches from diverse prompts, engage in dialogue-driven drawing, and collaborate meaningfully with human users.

[Arxiv](https://arxiv.org/abs/2411.17673)