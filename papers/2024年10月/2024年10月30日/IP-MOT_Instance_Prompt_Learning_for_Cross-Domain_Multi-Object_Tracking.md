# IP-MOT：针对跨域多目标跟踪的实例提示学习

发布时间：2024年10月30日

`LLM应用` `计算机视觉` `多目标跟踪`

> IP-MOT: Instance Prompt Learning for Cross-Domain Multi-Object Tracking

# 摘要

> 多目标跟踪（MOT）旨在关联视频帧中的多个对象，因其跟踪环境复杂，这是个颇具挑战的视觉任务。现有的多数方法都在单一域内训练和跟踪，致使对其他域的数据缺乏跨域泛化能力。虽有一些工作引入自然语言表示来弥合视觉跟踪中的域差距，可这些文本描述通常过于宏观，无法区分同一类中的不同实例。本文中，我们通过开发 IP-MOT 来解决此局限，这是一种用于 MOT 的端到端转换器模型，无需具体文本描述就能运行。我们的方法有两大关键创新：其一，借助预训练的视觉语言模型，通过提示调整获取实例级伪文本描述，其在不同跟踪场景中保持不变；其二，引入一种查询平衡策略，并借助知识蒸馏增强，进一步提升模型的泛化能力。在 MOT17、MOT20 和 DanceTrack 这三个广泛使用的 MOT 基准上开展的大量实验表明，与最先进的模型相比，我们的方法不仅在同域数据上表现出色，而且对于跨域输入，大幅提升了基于查询的跟踪器的性能。

> Multi-Object Tracking (MOT) aims to associate multiple objects across video frames and is a challenging vision task due to inherent complexities in the tracking environment. Most existing approaches train and track within a single domain, resulting in a lack of cross-domain generalizability to data from other domains. While several works have introduced natural language representation to bridge the domain gap in visual tracking, these textual descriptions often provide too high-level a view and fail to distinguish various instances within the same class. In this paper, we address this limitation by developing IP-MOT, an end-to-end transformer model for MOT that operates without concrete textual descriptions. Our approach is underpinned by two key innovations: Firstly, leveraging a pre-trained vision-language model, we obtain instance-level pseudo textual descriptions via prompt-tuning, which are invariant across different tracking scenes; Secondly, we introduce a query-balanced strategy, augmented by knowledge distillation, to further boost the generalization capabilities of our model. Extensive experiments conducted on three widely used MOT benchmarks, including MOT17, MOT20, and DanceTrack, demonstrate that our approach not only achieves competitive performance on same-domain data compared to state-of-the-art models but also significantly improves the performance of query-based trackers by large margins for cross-domain inputs.

[Arxiv](https://arxiv.org/abs/2410.23907)