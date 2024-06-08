# TopViewRS：视觉-语言模型在顶视图空间推理中的应用

发布时间：2024年06月04日

`LLM应用

这篇论文主要探讨了大型视觉语言模型在顶视图空间推理能力方面的应用和评估。通过引入TopViewRS数据集，研究者评估了这些模型在理解和推理空间关系方面的表现，并指出了当前模型性能与人类水平的差距。这表明研究关注的是LLM在特定应用场景（即空间推理）中的实际表现和改进需求，因此属于LLM应用分类。` `地图导航` `空间推理`

> TopViewRS: Vision-Language Models as Top-View Spatial Reasoners

# 摘要

> 顶视图视角是人类解读地图的常用方式，对人类及依赖大型视觉语言模型的非人类实体的定位与导航至关重要。尽管如此，现代视觉语言模型的空间推理能力仍未得到充分验证和探索。本研究聚焦于这些模型从顶视图理解并推理空间关系的能力，并引入了TopViewRS数据集，包含11,384个多选题，以真实或语义顶视图地图为视觉输入。通过此数据集，我们评估了4种不同复杂度的感知与推理任务中的视觉语言模型。对10个代表性模型的评估显示，其性能与人类平均水平相差超过50%，某些情况下甚至不及随机选择。尽管思维链推理能平均提升模型性能5.82%，但整体表现仍显不足。我们的研究强调了提升模型顶视图空间推理能力的迫切性，并为实现视觉语言模型在多模态任务中达到人类水平奠定了基础。

> Top-view perspective denotes a typical way in which humans read and reason over different types of maps, and it is vital for localization and navigation of humans as well as of `non-human' agents, such as the ones backed by large Vision-Language Models (VLMs). Nonetheless, spatial reasoning capabilities of modern VLMs remain unattested and underexplored. In this work, we thus study their capability to understand and reason over spatial relations from the top view. The focus on top view also enables controlled evaluations at different granularity of spatial reasoning; we clearly disentangle different abilities (e.g., recognizing particular objects versus understanding their relative positions). We introduce the TopViewRS (Top-View Reasoning in Space) dataset, consisting of 11,384 multiple-choice questions with either realistic or semantic top-view map as visual input. We then use it to study and evaluate VLMs across 4 perception and reasoning tasks with different levels of complexity. Evaluation of 10 representative open- and closed-source VLMs reveals the gap of more than 50% compared to average human performance, and it is even lower than the random baseline in some cases. Although additional experiments show that Chain-of-Thought reasoning can boost model capabilities by 5.82% on average, the overall performance of VLMs remains limited. Our findings underscore the critical need for enhanced model capability in top-view spatial reasoning and set a foundation for further research towards human-level proficiency of VLMs in real-world multimodal tasks.

![TopViewRS：视觉-语言模型在顶视图空间推理中的应用](../../../paper_images/2406.02537/front_fig.png)

![TopViewRS：视觉-语言模型在顶视图空间推理中的应用](../../../paper_images/2406.02537/x1.png)

![TopViewRS：视觉-语言模型在顶视图空间推理中的应用](../../../paper_images/2406.02537/x2.png)

![TopViewRS：视觉-语言模型在顶视图空间推理中的应用](../../../paper_images/2406.02537/x3.png)

![TopViewRS：视觉-语言模型在顶视图空间推理中的应用](../../../paper_images/2406.02537/x4.png)

![TopViewRS：视觉-语言模型在顶视图空间推理中的应用](../../../paper_images/2406.02537/x5.png)

![TopViewRS：视觉-语言模型在顶视图空间推理中的应用](../../../paper_images/2406.02537/x6.png)

![TopViewRS：视觉-语言模型在顶视图空间推理中的应用](../../../paper_images/2406.02537/x7.png)

[Arxiv](https://arxiv.org/abs/2406.02537)