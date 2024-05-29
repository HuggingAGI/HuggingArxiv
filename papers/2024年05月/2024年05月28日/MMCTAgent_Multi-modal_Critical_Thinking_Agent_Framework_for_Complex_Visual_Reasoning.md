# MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。

发布时间：2024年05月28日

`Agent

这篇论文介绍了一个名为MMCTAgent的创新框架，它是一个多模态批判性思维代理，专门设计来解决多模态大型语言模型（MLLMs）在复杂视觉推理任务中的局限性。该代理通过迭代分析、问题分解、策略规划及动态推理进化来提升处理能力，并引入了批判性思维元素，如答案验证和自我反思，以强化决策过程。因此，这篇论文属于Agent分类，因为它描述了一个具体的代理框架及其在多模态任务中的应用。` `视觉推理` `人工智能`

> MMCTAgent: Multi-modal Critical Thinking Agent Framework for Complex Visual Reasoning

# 摘要

> 多模态大型语言模型（MLLMs）在视觉与语言结合的任务中取得了显著进步，但仍面临多模态理解的细节挑战、复杂任务的解析及多模态信息的推理难题。为此，我们推出了MMCTAgent，一个创新的多模态批判性思维代理框架，旨在突破MLLMs在复杂视觉推理中的局限。借鉴人类认知与批判性思维，MMCTAgent通过迭代分析、问题分解、策略规划及动态推理进化，提升了处理能力。它还引入了批判性思维元素，如答案验证和基于视觉批评者的自我反思，以及任务特定评估标准，从而强化了决策过程。在多个图像和视频理解基准的严格测试中，MMCTAgent（无论是否配备批评者）均超越了基础MLLMs及其他增强工具的管道。

> Recent advancements in Multi-modal Large Language Models (MLLMs) have significantly improved their performance in tasks combining vision and language. However, challenges persist in detailed multi-modal understanding, comprehension of complex tasks, and reasoning over multi-modal information. This paper introduces MMCTAgent, a novel multi-modal critical thinking agent framework designed to address the inherent limitations of current MLLMs in complex visual reasoning tasks. Inspired by human cognitive processes and critical thinking, MMCTAgent iteratively analyzes multi-modal information, decomposes queries, plans strategies, and dynamically evolves its reasoning. Additionally, MMCTAgent incorporates critical thinking elements such as verification of final answers and self-reflection through a novel approach that defines a vision-based critic and identifies task-specific evaluation criteria, thereby enhancing its decision-making abilities. Through rigorous evaluations across various image and video understanding benchmarks, we demonstrate that MMCTAgent (with and without the critic) outperforms both foundational MLLMs and other tool-augmented pipelines.

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/x1.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/x2.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/x3.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/x4.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/x5.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/x6.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/x7.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/x8.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/x9.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/x10.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/x11.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/36_0.jpg)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/36_1.jpg)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/36_2.jpg)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/x12.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/x13.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/frame_0.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/frame_1.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/frame_2.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/frame_3.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/frame_4.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/frame_5.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/frame_6.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/frame_7.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/frame_8.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/frame_9.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/frame_0.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/frame_1.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/frame_2.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/frame_3.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/frame_4.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/frame_5.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/frame_6.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/frame_7.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/frame_8.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/frame_9.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/frame_0.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/frame_1.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/frame_2.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/frame_3.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/frame_4.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/frame_5.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/frame_6.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/frame_7.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/frame_8.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/frame_9.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/frame_0.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/frame_1.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/frame_2.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/frame_3.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/frame_4.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/frame_5.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/frame_6.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/frame_7.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/frame_8.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/frame_9.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/frame_0.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/frame_1.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/frame_2.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/frame_3.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/frame_4.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/frame_5.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/frame_6.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/frame_7.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/frame_8.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/frame_9.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/frame_0.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/frame_1.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/frame_2.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/frame_3.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/frame_4.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/frame_5.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/frame_6.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/frame_7.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/frame_8.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/frame_9.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/x14.png)

![MMCTAgent：复杂视觉推理的多模态批判性思维框架，旨在通过多模态输入提升批判性思维能力。](../../../paper_images/2405.18358/x15.png)

[Arxiv](https://arxiv.org/abs/2405.18358)