# SOK-Bench：融合开放世界知识的情景视频推理新标杆

发布时间：2024年05月15日

`Agent

这篇论文介绍了一个新的基准测试SOK-Bench，用于评估动态、开放世界和结构化知识的推理能力，这是人工智能领域中Agent（智能体）的一个重要方面。Agent通常指的是能够感知环境并采取行动以达到目标的系统。在这篇论文中，研究者开发了一种自动生成方法，利用大型语言模型（LLMs）和多模态语言模型（MLLMs）来创建问答对、知识图谱和推理理由，这些都是Agent在处理视觉场景和进行常识推理时可能使用的技术。因此，这篇论文更符合Agent的分类，因为它关注的是如何通过构建新的基准和使用先进的模型来提升Agent在现实世界视觉场景中的推理能力。` `人工智能` `视觉推理`

> SOK-Bench: A Situated Video Reasoning Benchmark with Aligned Open-World Knowledge

# 摘要

> 为了推进人工智能，从现实世界的视觉场景中学习常识推理至关重要。但现有的视频推理基准因其局限于事实或特定情境推理而显得不足。我们的研究深入探讨了动态、开放世界和结构化知识的推理评估。我们推出了SOK-Bench，一个包含44,000个问题和10,000个情境的新基准，视频中的实例级注释为推理提供了丰富的素材。我们开发了一种自动生成方法，利用LLMs和MLLMs的组合来创造问答对、知识图谱和推理理由，确保了数据集的生成既高效又可扩展。我们的方法首先从视频中提取情境知识，进而拓展到更广泛的开放世界知识。通过精心设计的自提示和演示，我们迭代地生成并完善了任务。最终，通过人工审核确保了数据集的质量。我们对主流的视觉-语言模型进行了评估，并得出了深刻的见解。欲了解更多，请访问我们的基准网站www.bobbywu.com/SOKBench。

> Learning commonsense reasoning from visual contexts and scenes in real-world is a crucial step toward advanced artificial intelligence. However, existing video reasoning benchmarks are still inadequate since they were mainly designed for factual or situated reasoning and rarely involve broader knowledge in the real world. Our work aims to delve deeper into reasoning evaluations, specifically within dynamic, open-world, and structured context knowledge. We propose a new benchmark (SOK-Bench), consisting of 44K questions and 10K situations with instance-level annotations depicted in the videos. The reasoning process is required to understand and apply situated knowledge and general knowledge for problem-solving. To create such a dataset, we propose an automatic and scalable generation method to generate question-answer pairs, knowledge graphs, and rationales by instructing the combinations of LLMs and MLLMs. Concretely, we first extract observable situated entities, relations, and processes from videos for situated knowledge and then extend to open-world knowledge beyond the visible content. The task generation is facilitated through multiple dialogues as iterations and subsequently corrected and refined by our designed self-promptings and demonstrations. With a corpus of both explicit situated facts and implicit commonsense, we generate associated question-answer pairs and reasoning processes, finally followed by manual reviews for quality assurance. We evaluated recent mainstream large vision-language models on the benchmark and found several insightful conclusions. For more information, please refer to our benchmark at www.bobbywu.com/SOKBench.

![SOK-Bench：融合开放世界知识的情景视频推理新标杆](../../../paper_images/2405.09713/x1.png)

![SOK-Bench：融合开放世界知识的情景视频推理新标杆](../../../paper_images/2405.09713/x2.png)

![SOK-Bench：融合开放世界知识的情景视频推理新标杆](../../../paper_images/2405.09713/x3.png)

![SOK-Bench：融合开放世界知识的情景视频推理新标杆](../../../paper_images/2405.09713/x4.png)

![SOK-Bench：融合开放世界知识的情景视频推理新标杆](../../../paper_images/2405.09713/x5.png)

[Arxiv](https://arxiv.org/abs/2405.09713)