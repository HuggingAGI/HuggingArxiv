# IoT-LLM：借助大型语言模型提升现实世界物联网任务的推理能力

发布时间：2024年10月03日

`LLM应用` `物联网` `人工智能`

> IoT-LLM: Enhancing Real-World IoT Task Reasoning with Large Language Models

# 摘要

> 大型语言模型（LLM）虽在文本和视觉领域表现出色，但常因违反物理定律而暴露出对现实世界的理解不足。借鉴人类认知中感知对推理的基础作用，我们尝试通过物联网（IoT）传感器数据和相关知识来强化LLM的感知能力，以提升其在物理世界中处理IoT任务的能力。我们系统研究了增强感知和知识库对LLM解决实际IoT任务的影响，并提出了统一框架IoT-LLM。该框架通过三个步骤优化LLM：将IoT数据预处理为适合LLM的格式，利用思维链提示和角色定义激活其常识知识，并通过基于上下文学习的IoT导向检索增强生成扩展其理解。为评估效果，我们设计了包含五种不同数据类型和难度的IoT任务基准，并测试了六个LLM。实验显示，现有LLM在纯文本输入下难以有效执行这些任务。而IoT-LLM显著提升了LLM在IoT任务中的表现，如GPT-4在各项任务中平均提升了65%。此外，LLM通过推理过程展示了理解IoT数据和物理定律的能力。我们工作的局限性也为未来研究提供了方向。

> Large Language Models (LLMs) have demonstrated remarkable capabilities across textual and visual domains but often generate outputs that violate physical laws, revealing a gap in their understanding of the physical world. Inspired by human cognition, where perception is fundamental to reasoning, we explore augmenting LLMs with enhanced perception abilities using Internet of Things (IoT) sensor data and pertinent knowledge for IoT task reasoning in the physical world. In this work, we systematically study LLMs capability to address real-world IoT tasks by augmenting their perception and knowledge base, and then propose a unified framework, IoT-LLM, to enhance such capability. In IoT-LLM, we customize three steps for LLMs: preprocessing IoT data into formats amenable to LLMs, activating their commonsense knowledge through chain-of-thought prompting and specialized role definitions, and expanding their understanding via IoT-oriented retrieval-augmented generation based on in-context learning. To evaluate the performance, We design a new benchmark with five real-world IoT tasks with different data types and reasoning difficulties and provide the benchmarking results on six open-source and close-source LLMs. Experimental results demonstrate the limitations of existing LLMs with naive textual inputs that cannot perform these tasks effectively. We show that IoT-LLM significantly enhances the performance of IoT tasks reasoning of LLM, such as GPT-4, achieving an average improvement of 65% across various tasks against previous methods. The results also showcase LLMs ability to comprehend IoT data and the physical law behind data by providing a reasoning process. Limitations of our work are claimed to inspire future research in this new era.

[Arxiv](https://arxiv.org/abs/2410.02429)