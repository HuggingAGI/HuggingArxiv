# 利用零样本大型语言模型在现实世界环境中推广端到端的自动驾驶

发布时间：2024年11月21日

`LLM应用` `自动驾驶`

> Generalizing End-To-End Autonomous Driving In Real-World Environments Using Zero-Shot LLMs

# 摘要

> 传统的自动驾驶方式采用模块化设计，把任务拆解成子任务。与此不同，端到端自动驾驶能直接从原始传感器数据输出动作，避免了误差的累积。不过，训练端到端模型需要完备的数据集，不然模型的泛化能力就不佳。近来，大型语言模型（LLMs）已被用于增强端到端驾驶模型的泛化能力。多数研究以开环的形式探索 LLMs，把输出动作和专家的动作作对比，没有来自真实世界的直接反馈，而其他研究仅在模拟中查看闭环结果。本文提出了一种高效架构，将多模态 LLMs 融入到在现实环境中闭环运行的端到端驾驶模型里。在我们的架构中，LLM 定期处理原始传感器数据以生成高级驾驶指令，有效地引导端到端模型，即便其处理速度比原始传感器数据慢。这种架构缓和了 LLM 延迟和推理质量之间的矛盾。它还让我们能从众多的 LLMs 里选择，以优化高级驾驶指令并降低微调成本。所以，我们的架构降低了数据收集的要求，因为 LLMs 不直接输出动作，我们只需训练一个简单的模仿学习模型来输出动作。在我们的实验中，现实环境中端到端模型的训练数据仅由带有一个交通锥的简单障碍物构成，而测试环境更复杂，包含多个处在不同位置的障碍物。实验表明，即便不对 LLM 进行微调，所提出的架构也提升了端到端模型的泛化能力。

> Traditional autonomous driving methods adopt a modular design, decomposing tasks into sub-tasks. In contrast, end-to-end autonomous driving directly outputs actions from raw sensor data, avoiding error accumulation. However, training an end-to-end model requires a comprehensive dataset; otherwise, the model exhibits poor generalization capabilities. Recently, large language models (LLMs) have been applied to enhance the generalization capabilities of end-to-end driving models. Most studies explore LLMs in an open-loop manner, where the output actions are compared to those of experts without direct feedback from the real world, while others examine closed-loop results only in simulations. This paper proposes an efficient architecture that integrates multimodal LLMs into end-to-end driving models operating in closed-loop settings in real-world environments. In our architecture, the LLM periodically processes raw sensor data to generate high-level driving instructions, effectively guiding the end-to-end model, even at a slower rate than the raw sensor data. This architecture relaxes the trade-off between the latency and inference quality of the LLM. It also allows us to choose from a wide variety of LLMs to improve high-level driving instructions and minimize fine-tuning costs. Consequently, our architecture reduces data collection requirements because the LLMs do not directly output actions; we only need to train a simple imitation learning model to output actions. In our experiments, the training data for the end-to-end model in a real-world environment consists of only simple obstacle configurations with one traffic cone, while the test environment is more complex and contains multiple obstacles placed in various positions. Experiments show that the proposed architecture enhances the generalization capabilities of the end-to-end model even without fine-tuning the LLM.

[Arxiv](https://arxiv.org/abs/2411.14256)