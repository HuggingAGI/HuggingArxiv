# AutoStudio：打造多轮交互图像生成中连贯的主体形象

发布时间：2024年06月03日

`Agent

理由：这篇论文介绍了一个多代理框架AutoStudio，用于处理多轮交互式图像生成任务。该框架集成了多个基于大型语言模型的代理，每个代理负责不同的任务，如主题管理、布局生成、监督和图像创作。这种使用多个代理来协同完成复杂任务的方法，符合Agent分类的定义。此外，论文中提到的代理之间的交互和协作，以及它们如何共同解决特定问题（如在多轮对话中保持图像多样性和主题一致性），进一步支持了这一分类。` `图像生成` `交互式系统`

> AutoStudio: Crafting Consistent Subjects in Multi-turn Interactive Image Generation

# 摘要

> 尖端的文本到图像生成模型在单张图像创作上已达到卓越水平，而更具挑战性的多轮交互式图像生成任务正逐渐成为研究热点。该任务要求模型通过多轮对话与用户互动，生成一系列连贯的图像。然而，用户可能频繁更换主题，使得在保持图像多样性的同时维持主题一致性成为难题。为此，我们推出了无需额外训练的AutoStudio多代理框架。AutoStudio集成了三个基于大型语言模型的代理来处理交互，并配备了一个基于稳定扩散的代理以生成高质量图像。框架内含主题管理者，负责解析对话并维护各主题的上下文；布局生成器，精细定位主题位置；监督者，优化布局建议；以及绘图员，完成图像创作。我们还创新性地引入了Parallel-UNet，以并行交叉注意力模块强化主题感知特征，并采用主题初始化技术，确保小主题的精准呈现。实验证明，AutoStudio在多轮交互中有效保持了多主题的一致性，并在平均Frechet Inception距离和字符-字符相似度上分别提升了13.65%和2.83%，刷新了行业标准。

> As cutting-edge Text-to-Image (T2I) generation models already excel at producing remarkable single images, an even more challenging task, i.e., multi-turn interactive image generation begins to attract the attention of related research communities. This task requires models to interact with users over multiple turns to generate a coherent sequence of images. However, since users may switch subjects frequently, current efforts struggle to maintain subject consistency while generating diverse images. To address this issue, we introduce a training-free multi-agent framework called AutoStudio. AutoStudio employs three agents based on large language models (LLMs) to handle interactions, along with a stable diffusion (SD) based agent for generating high-quality images. Specifically, AutoStudio consists of (i) a subject manager to interpret interaction dialogues and manage the context of each subject, (ii) a layout generator to generate fine-grained bounding boxes to control subject locations, (iii) a supervisor to provide suggestions for layout refinements, and (iv) a drawer to complete image generation. Furthermore, we introduce a Parallel-UNet to replace the original UNet in the drawer, which employs two parallel cross-attention modules for exploiting subject-aware features. We also introduce a subject-initialized generation method to better preserve small subjects. Our AutoStudio hereby can generate a sequence of multi-subject images interactively and consistently. Extensive experiments on the public CMIGBench benchmark and human evaluations show that AutoStudio maintains multi-subject consistency across multiple turns well, and it also raises the state-of-the-art performance by 13.65% in average Frechet Inception Distance and 2.83% in average character-character similarity.

[Arxiv](https://arxiv.org/abs/2406.01388)