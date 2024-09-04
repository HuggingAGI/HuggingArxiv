# TinyAgent：边缘环境下的函数调用技术

发布时间：2024年09月01日

`Agent` `边缘计算` `智能助手`

> TinyAgent: Function Calling at the Edge

# 摘要

> 最新的大型语言模型 (LLM) 推动了高级代理系统的发展，这些系统能整合多种工具和 API，通过函数调用来响应用户需求。然而，这些模型因体积庞大和计算需求高，通常依赖云基础设施，尚未在边缘设备上得到应用。为此，我们推出了 TinyAgent 框架，专门用于训练和部署小型语言模型代理，使其能在边缘设备上进行函数调用，驱动代理系统。我们首先利用 LLMCompiler 框架，为开源模型实现了精准的函数调用功能。接着，我们精心构建了一个高质量的函数调用数据集，用于微调 TinyAgent-1.1B 和 7B 两个小型模型。为提升推理效率，我们创新性地采用了工具检索方法缩短输入提示，并结合量化技术加快推理速度。作为实际应用，我们为 MacBook 开发了一个类似 Siri 的本地助手系统，支持文本和语音输入执行用户指令。实验表明，我们的模型在函数调用能力上不逊于甚至超越了大型模型如 GPT-4-Turbo，且完全支持边缘部署。我们公开了数据集、模型及相关安装包，并提供了演示视频，展示了 MacBook 助手代理的实际应用。

> Recent large language models (LLMs) have enabled the development of advanced agentic systems that can integrate various tools and APIs to fulfill user queries through function calling. However, the deployment of these LLMs on the edge has not been explored since they typically require cloud-based infrastructure due to their substantial model size and computational demands. To this end, we present TinyAgent, an end-to-end framework for training and deploying task-specific small language model agents capable of function calling for driving agentic systems at the edge. We first show how to enable accurate function calling for open-source models via the LLMCompiler framework. We then systematically curate a high-quality dataset for function calling, which we use to fine-tune two small language models, TinyAgent-1.1B and 7B. For efficient inference, we introduce a novel tool retrieval method to reduce the input prompt length and utilize quantization to further accelerate the inference speed. As a driving application, we demonstrate a local Siri-like system for Apple's MacBook that can execute user commands through text or voice input. Our results show that our models can achieve, and even surpass, the function-calling capabilities of larger models like GPT-4-Turbo, while being fully deployed at the edge. We open-source our dataset, models, and installable package and provide a demo video for our MacBook assistant agent.

[Arxiv](https://arxiv.org/abs/2409.00608)