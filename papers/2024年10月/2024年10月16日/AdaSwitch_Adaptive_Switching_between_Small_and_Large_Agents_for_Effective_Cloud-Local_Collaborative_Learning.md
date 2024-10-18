# AdaSwitch：智能切换小代理与大代理，实现高效的云与本地协作学习

发布时间：2024年10月16日

`Agent` `云计算` `人工智能`

> AdaSwitch: Adaptive Switching between Small and Large Agents for Effective Cloud-Local Collaborative Learning

# 摘要

> 大型语言模型 (LLM) 的最新进展令人瞩目。用户面临在生成质量的云端 LLM 和计算成本较低的本地部署 LLM 之间做出选择。前者通常成本高且效率低，而后者通常无法在需要深思熟虑的推理步骤中提供令人满意的性能。在这项工作中，我们提出了一种新颖的 LLM 利用范式，促进了大型云端 LLM 和小型本地部署 LLM 的协同操作。我们的框架包括两个主要模块：本地代理，使用相对较小的 LLM，处理较不复杂的推理步骤，以及云端代理，配备较大的 LLM，管理更复杂的推理步骤。这种协同处理通过自适应机制实现，本地代理自省识别错误并主动向云端代理寻求帮助，从而有效整合本地部署和云端 LLM 的优势，显著提升任务完成性能和效率。我们评估了 AdaSwitch 在 7 个基准测试中的表现，涵盖数学推理和复杂问答，使用各种类型的 LLM 实例化本地和云端代理。实证结果显示，AdaSwitch 有效地提升了本地代理的性能，并且在使用较少的计算开销时，有时能达到与云端代理相当的竞争结果。

> Recent advancements in large language models (LLMs) have been remarkable. Users face a choice between using cloud-based LLMs for generation quality and deploying local-based LLMs for lower computational cost. The former option is typically costly and inefficient, while the latter usually fails to deliver satisfactory performance for reasoning steps requiring deliberate thought processes. In this work, we propose a novel LLM utilization paradigm that facilitates the collaborative operation of large cloud-based LLMs and smaller local-deployed LLMs. Our framework comprises two primary modules: the local agent instantiated with a relatively smaller LLM, handling less complex reasoning steps, and the cloud agent equipped with a larger LLM, managing more intricate reasoning steps. This collaborative processing is enabled through an adaptive mechanism where the local agent introspectively identifies errors and proactively seeks assistance from the cloud agent, thereby effectively integrating the strengths of both locally-deployed and cloud-based LLMs, resulting in significant enhancements in task completion performance and efficiency. We evaluate AdaSwitch across 7 benchmarks, ranging from mathematical reasoning and complex question answering, using various types of LLMs to instantiate the local and cloud agents. The empirical results show that AdaSwitch effectively improves the performance of the local agent, and sometimes achieves competitive results compared to the cloud agent while utilizing much less computational overhead.

[Arxiv](https://arxiv.org/abs/2410.13181)