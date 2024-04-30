# WorldGPT：赋予大型语言模型多模态世界建模能力

发布时间：2024年04月28日

`分类：LLM应用` `环境模拟` `人工智能`

> WorldGPT: Empowering LLM as Multimodal World Model

# 摘要

> 世界模型正广泛应用于环境模拟到复杂场景构建等多个领域。现有模型多基于特定领域的状态和动作训练，且限于单一模态的表示。本文提出了 WorldGPT，一个基于多模态大型语言模型（MLLM）构建的通用世界模型，它通过分析数百万跨领域的视频来理解世界动态。为了提升其在特定场景和长期任务中的性能，我们引入了一种融合记忆卸载、知识检索和上下文反思的认知架构。我们构建了 WorldNet，一个多模态状态转换预测基准，覆盖了多种真实场景，用以评估 WorldGPT 的性能。评估结果证明了 WorldGPT 在准确模拟和预测复杂场景动态方面的能力。此外，我们还探讨了 WorldGPT 作为世界模拟器的潜力，它能够通过合成可靠的多模态指令实例，帮助多模态代理泛化到新领域，这些实例在微调中与真实数据同样有效。项目详情可访问 \url{https://github.com/DCDmllm/WorldGPT}。

> World models are progressively being employed across diverse fields, extending from basic environment simulation to complex scenario construction. However, existing models are mainly trained on domain-specific states and actions, and confined to single-modality state representations. In this paper, We introduce WorldGPT, a generalist world model built upon Multimodal Large Language Model (MLLM). WorldGPT acquires an understanding of world dynamics through analyzing millions of videos across various domains. To further enhance WorldGPT's capability in specialized scenarios and long-term tasks, we have integrated it with a novel cognitive architecture that combines memory offloading, knowledge retrieval, and context reflection. As for evaluation, we build WorldNet, a multimodal state transition prediction benchmark encompassing varied real-life scenarios. Conducting evaluations on WorldNet directly demonstrates WorldGPT's capability to accurately model state transition patterns, affirming its effectiveness in understanding and predicting the dynamics of complex scenarios. We further explore WorldGPT's emerging potential in serving as a world simulator, helping multimodal agents generalize to unfamiliar domains through efficiently synthesising multimodal instruction instances which are proved to be as reliable as authentic data for fine-tuning purposes. The project is available on \url{https://github.com/DCDmllm/WorldGPT}.

[Arxiv](https://arxiv.org/abs/2404.18202)