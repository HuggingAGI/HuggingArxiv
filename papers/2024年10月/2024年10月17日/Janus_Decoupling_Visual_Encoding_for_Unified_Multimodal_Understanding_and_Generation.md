# Janus：通过解耦视觉编码，实现多模态理解和生成的统一。

发布时间：2024年10月17日

`LLM应用` `人工智能` `多媒体`

> Janus: Decoupling Visual Encoding for Unified Multimodal Understanding and Generation

# 摘要

> 摘要：本文介绍的 Janus 是一个自回归框架，旨在统一多模态理解和生成。传统方法如 Chameleon 依赖单一视觉编码器，但因任务需求的信息粒度不同，常导致性能瓶颈，尤其是在多模态理解上。为此，Janus 将视觉编码解耦，同时保持单一转换器架构，既缓解了角色冲突，又提升了灵活性。实验显示，Janus 不仅超越了以往的一体化模型，还与特定任务模型性能相当甚至更优。其简洁、灵活且高效的特点，使 Janus 成为下一代多模态模型的有力竞争者。

> 
Abstract:In this paper, we introduce Janus, an autoregressive framework that unifies multimodal understanding and generation. Prior research often relies on a single visual encoder for both tasks, such as Chameleon. However, due to the differing levels of information granularity required by multimodal understanding and generation, this approach can lead to suboptimal performance, particularly in multimodal understanding. To address this issue, we decouple visual encoding into separate pathways, while still leveraging a single, unified transformer architecture for processing. The decoupling not only alleviates the conflict between the visual encoder's roles in understanding and generation, but also enhances the framework's flexibility. For instance, both the multimodal understanding and generation components can independently select their most suitable encoding methods. Experiments show that Janus surpasses previous unified model and matches or exceeds the performance of task-specific models. The simplicity, high flexibility, and effectiveness of Janus make it a strong candidate for next-generation unified multimodal models.
    

[Arxiv](https://arxiv.org/pdf/2410.13848)