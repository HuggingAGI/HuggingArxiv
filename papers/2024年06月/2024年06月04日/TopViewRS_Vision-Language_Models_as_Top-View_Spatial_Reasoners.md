# TopViewRS：视觉-语言模型作为顶视图空间推理者，探索其在空间推理任务中的应用潜力。

发布时间：2024年06月04日

`Agent

这篇论文主要关注的是大型视觉语言模型在顶视图视角下的空间推理能力，特别是在定位和导航方面的应用。它通过引入TopViewRS数据集来评估模型的表现，并探讨了提升这些模型空间推理能力的必要性。虽然涉及到视觉语言模型，但重点在于模型的应用层面，即如何增强模型在特定任务（如定位和导航）中的表现，而不是模型的理论研究或生成式对抗网络（RAG）的相关内容。因此，这篇论文更适合归类为Agent，因为它探讨的是模型作为代理在特定任务中的应用和改进。` `地图导航` `空间推理`

> TopViewRS: Vision-Language Models as Top-View Spatial Reasoners

# 摘要

> 顶视图视角是人类阅读和推理地图的典型方式，对人类及大型视觉语言模型支持的“非人类”代理的定位和导航至关重要。然而，这些模型的空间推理能力尚未得到充分探索。本研究聚焦于它们从顶视图理解并推理空间关系的能力，并引入了TopViewRS数据集，包含11,384个多选题，以真实或语义顶视图地图为视觉输入。我们通过该数据集评估了4种感知和推理任务中的视觉语言模型，发现与人类表现相比，这些模型的表现差距显著，甚至有时低于随机水平。尽管思维链推理能小幅提升模型能力，但整体表现仍有限。我们的研究强调了提升模型顶视图空间推理能力的必要性，并为未来研究设定了方向，以期视觉语言模型能在多模态任务中达到人类水平。

> Top-view perspective denotes a typical way in which humans read and reason over different types of maps, and it is vital for localization and navigation of humans as well as of `non-human' agents, such as the ones backed by large Vision-Language Models (VLMs). Nonetheless, spatial reasoning capabilities of modern VLMs remain unattested and underexplored. In this work, we thus study their capability to understand and reason over spatial relations from the top view. The focus on top view also enables controlled evaluations at different granularity of spatial reasoning; we clearly disentangle different abilities (e.g., recognizing particular objects versus understanding their relative positions). We introduce the TopViewRS (Top-View Reasoning in Space) dataset, consisting of 11,384 multiple-choice questions with either realistic or semantic top-view map as visual input. We then use it to study and evaluate VLMs across 4 perception and reasoning tasks with different levels of complexity. Evaluation of 10 representative open- and closed-source VLMs reveals the gap of more than 50% compared to average human performance, and it is even lower than the random baseline in some cases. Although additional experiments show that Chain-of-Thought reasoning can boost model capabilities by 5.82% on average, the overall performance of VLMs remains limited. Our findings underscore the critical need for enhanced model capability in top-view spatial reasoning and set a foundation for further research towards human-level proficiency of VLMs in real-world multimodal tasks.

![TopViewRS：视觉-语言模型作为顶视图空间推理者，探索其在空间推理任务中的应用潜力。](../../../paper_images/2406.02537/front_fig.png)

![TopViewRS：视觉-语言模型作为顶视图空间推理者，探索其在空间推理任务中的应用潜力。](../../../paper_images/2406.02537/x1.png)

![TopViewRS：视觉-语言模型作为顶视图空间推理者，探索其在空间推理任务中的应用潜力。](../../../paper_images/2406.02537/x2.png)

![TopViewRS：视觉-语言模型作为顶视图空间推理者，探索其在空间推理任务中的应用潜力。](../../../paper_images/2406.02537/x3.png)

![TopViewRS：视觉-语言模型作为顶视图空间推理者，探索其在空间推理任务中的应用潜力。](../../../paper_images/2406.02537/x4.png)

![TopViewRS：视觉-语言模型作为顶视图空间推理者，探索其在空间推理任务中的应用潜力。](../../../paper_images/2406.02537/x5.png)

![TopViewRS：视觉-语言模型作为顶视图空间推理者，探索其在空间推理任务中的应用潜力。](../../../paper_images/2406.02537/x6.png)

![TopViewRS：视觉-语言模型作为顶视图空间推理者，探索其在空间推理任务中的应用潜力。](../../../paper_images/2406.02537/x7.png)

[Arxiv](https://arxiv.org/abs/2406.02537)