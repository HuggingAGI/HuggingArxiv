# 用于指导视觉装配的生成式时间线

发布时间：2024年11月19日

`LLM应用` `视频编辑`

> Generative Timelines for Instructed Visual Assembly

# 摘要

> 这项工作旨在借助自然语言指令操控视觉时间线（比如视频），让非专业人士甚至残障用户也能进行复杂的时间线编辑任务。我们将此任务称作“受指导的视觉组装”。该任务颇具挑战，因为它要求（一）在输入时间线中识别相关视觉内容，并在给定的输入（视频）集合里检索相关视觉内容；（二）理解输入的自然语言指令；（三）对输入的视觉时间线进行所需编辑，从而生成输出时间线。为应对这些挑战，我们提出了“时间线组装器”，这是一个用于执行受指导视觉组装任务的生成模型。本工作有三大贡献。其一，我们开发了一个大型多模态语言模型，旨在处理视觉内容、紧凑地呈现时间线并精准解读时间线编辑指令。其二，我们引入了一种全新的方法，能自动为视觉组装任务生成数据集，使模型无需人工标注数据就能高效训练。其三，我们通过为图像和视频组装创建两个新数据集来验证我们的方法，表明“时间线组装器”在各种受现实世界启发的场景中准确执行复杂组装指令方面，大幅优于包括近期的 GPT-4o 在内的既有基线模型。

> The objective of this work is to manipulate visual timelines (e.g. a video) through natural language instructions, making complex timeline editing tasks accessible to non-expert or potentially even disabled users. We call this task Instructed visual assembly. This task is challenging as it requires (i) identifying relevant visual content in the input timeline as well as retrieving relevant visual content in a given input (video) collection, (ii) understanding the input natural language instruction, and (iii) performing the desired edits of the input visual timeline to produce an output timeline. To address these challenges, we propose the Timeline Assembler, a generative model trained to perform instructed visual assembly tasks. The contributions of this work are three-fold. First, we develop a large multimodal language model, which is designed to process visual content, compactly represent timelines and accurately interpret timeline editing instructions. Second, we introduce a novel method for automatically generating datasets for visual assembly tasks, enabling efficient training of our model without the need for human-labeled data. Third, we validate our approach by creating two novel datasets for image and video assembly, demonstrating that the Timeline Assembler substantially outperforms established baseline models, including the recent GPT-4o, in accurately executing complex assembly instructions across various real-world inspired scenarios.

[Arxiv](https://arxiv.org/abs/2411.12293)