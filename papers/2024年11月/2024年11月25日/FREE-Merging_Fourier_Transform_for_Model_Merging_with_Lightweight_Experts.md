# FREE-Merging：用于结合轻量级专家的模型的傅里叶变换

发布时间：2024年11月25日

`其他` `人工智能` `模型合并`

> FREE-Merging: Fourier Transform for Model Merging with Lightweight Experts

# 摘要

> 在当下模型规模快速扩张的时期，各类任务的开源模型权重愈发容易获取。然而，单个微调模型的能力常常难以满足多元的部署需求。于是，模型合并作为一种广受瞩目的方法应运而生，旨在从现存模型中高效构建一个适配多个任务组合的单一模型。但现有的模型合并方式在性能和部署成本之间面临艰难的权衡，主要源于合并网络中的任务冲突。我们对神经网络的剖析表明，微调引入的某些特定任务信息对性能的提升微乎其微，却严重影响泛化能力，进而引发任务冲突。为降低这些信息的影响，我们提出了 FR-Merging 这一创新手段，借助频域信息有效过滤有害的特定信息，以最小成本将任务冲突对骨干网络的影响降至最低。鉴于免费合并方法难免造成性能损失，我们引入了一个轻量级的特定任务专家，它能够在推理时动态整合，以弥补信息缺失。这个 FREE-Merging 框架（FR-Merging 搭配轻量级专家），在训练成本、推理速度、存储要求和性能之间达成了平衡的取舍。我们在 CV、NLP 和多模态领域的多项任务中验证了 FR-Merging 和 FREE-Merging 的有效性，并表明它们能够灵活适配以满足特定需求。

> In the current era of rapid expansion in model scale, there is an increasing availability of open-source model weights for various tasks. However, the capabilities of a single fine-tuned model often fall short of meeting diverse deployment needs. Model merging has thus emerged as a widely focused method for efficiently building a single model tailored for multiple tasks combined from existing models. Nevertheless, existing model merging methods face challenging trade-offs between performance and deployment costs, primarily due to task conflicts within the merged network. Our analysis of neural networks reveals that some task-specific information introduced by fine-tuning minimally enhances performance but heavily impacts generalization, leading to task conflicts. To mitigate the impact of this information, we propose FR-Merging, an innovative method that leverages frequency domain information to efficiently filter harmful specialized information, thereby minimizing the impact of task conflicts on the backbone with minimal cost. Since performance loss is inevitable with cost-free merging methods, we introduce a lightweight task-specific expert that can be dynamically integrated during inference to compensate for information loss. This framework, FREE-Merging (FR-Merging with lightweight experts), strikes a balanced trade-off between training cost, inference speed, storage requirements, and performance. We demonstrate the effectiveness of both FR-Merging and FREE-Merging on multiple tasks across CV, NLP, and Multi-Modal domains and show that they can be flexibly adapted to meet specific needs.

[Arxiv](https://arxiv.org/abs/2411.16815)