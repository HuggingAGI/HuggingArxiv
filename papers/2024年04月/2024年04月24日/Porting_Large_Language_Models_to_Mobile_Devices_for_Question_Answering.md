# 将大型语言模型迁移至移动设备，以实现问答功能

发布时间：2024年04月24日

`LLM应用` `移动设备` `问答系统`

> Porting Large Language Models to Mobile Devices for Question Answering

# 摘要

> 将大型语言模型（LLMs）应用于移动设备，实现了自然语言处理技术的全面移动化。在众多应用场景中，问答功能尤为关键，它能够针对用户的各种问题提供精确且贴合语境的答案。本文详细介绍了我们如何将顶尖的LLMs成功迁移至移动平台，并确保其在设备上顺畅运行。我们采用了llama.cpp这一灵活且完整的C++推理框架，针对LLMs进行了优化。我们选用了经过6位量化处理的Orca-Mini-3B模型，该模型参数量达30亿，并为该模型定制了合适的提示格式。实验数据显示，LLMs在Galaxy S21智能手机上的推理速度达到了交互级别，且在回答政治、地理、历史等多样化问题时，均能提供高质量的答案。

> Deploying Large Language Models (LLMs) on mobile devices makes all the capabilities of natural language processing available on the device. An important use case of LLMs is question answering, which can provide accurate and contextually relevant answers to a wide array of user queries. We describe how we managed to port state of the art LLMs to mobile devices, enabling them to operate natively on the device. We employ the llama.cpp framework, a flexible and self-contained C++ framework for LLM inference. We selected a 6-bit quantized version of the Orca-Mini-3B model with 3 billion parameters and present the correct prompt format for this model. Experimental results show that LLM inference runs in interactive speed on a Galaxy S21 smartphone and that the model delivers high-quality answers to user queries related to questions from different subjects like politics, geography or history.

[Arxiv](https://arxiv.org/abs/2404.15851)