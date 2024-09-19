# 通过多模态演示学习多阶段接触操作的任务规划

发布时间：2024年09月18日

`LLM应用` `机器人` `人工智能`

> Learning Task Planning from Multi-Modal Demonstration for Multi-Stage Contact-Rich Manipulation

# 摘要

> 大型语言模型 (LLM) 在长时程操作任务的规划中备受瞩目。为了提升 LLM 生成计划的合理性，视觉演示和在线视频被广泛用于指导规划过程。然而，对于涉及细微运动和丰富接触交互的任务，仅靠视觉感知可能不足以让 LLM 完全解读演示。此外，视觉数据在力相关参数和条件方面提供的信息有限，这对于在真实机器人上有效执行至关重要。本文中，我们引入了一个包含触觉和力矩信息的上下文学习框架，以增强 LLM 在新任务场景中生成计划的能力。我们提出了一种引导推理流程，依次整合每种模态，形成全面的任务计划，并将其作为新任务配置中规划的参考。实际实验表明，该框架有效提升了 LLM 对多模态演示的理解，并显著增强了整体规划性能。

> Large Language Models (LLMs) have gained popularity in task planning for long-horizon manipulation tasks. To enhance the validity of LLM-generated plans, visual demonstrations and online videos have been widely employed to guide the planning process. However, for manipulation tasks involving subtle movements but rich contact interactions, visual perception alone may be insufficient for the LLM to fully interpret the demonstration. Additionally, visual data provides limited information on force-related parameters and conditions, which are crucial for effective execution on real robots.
  In this paper, we introduce an in-context learning framework that incorporates tactile and force-torque information from human demonstrations to enhance LLMs' ability to generate plans for new task scenarios. We propose a bootstrapped reasoning pipeline that sequentially integrates each modality into a comprehensive task plan. This task plan is then used as a reference for planning in new task configurations. Real-world experiments on two different sequential manipulation tasks demonstrate the effectiveness of our framework in improving LLMs' understanding of multi-modal demonstrations and enhancing the overall planning performance.

[Arxiv](https://arxiv.org/abs/2409.11863)