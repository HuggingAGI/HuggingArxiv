# “少即是多”：优化用于边缘设备上 LLM 执行的函数调用

发布时间：2024年11月22日

`Agent` `边缘计算` `函数调用`

> Less is More: Optimizing Function Calling for LLM Execution on Edge Devices

# 摘要

> 基础模型具备的高级函数调用能力，为部署代理去执行复杂的 API 任务创造了新契机。但管理海量数据以及与众多 API 交互，致使函数调用硬件需求高、成本大，在边缘设备上尤甚。当下的大型语言模型（LLMs）于边缘进行函数调用时遭遇困境，因其难以处理复杂输入或有效管理多种工具。这致使任务完成准确率低下、延迟增多以及功耗升高。在此项工作中，我们推出了“少即是多”，这是一种全新的无需微调的函数调用方案，用于动态工具选择。我们的方法基于关键洞察：有选择性地减少提供给 LLMs 的工具数量，能显著提升其在边缘设备上的函数调用性能、执行时间和功率效率。在边缘硬件上运用最前沿的 LLMs 所做的实验结果显示，代理成功率得以提升，执行时间最多缩减 70%，功耗最多降低 40%。

> The advanced function-calling capabilities of foundation models open up new possibilities for deploying agents to perform complex API tasks. However, managing large amounts of data and interacting with numerous APIs makes function calling hardware-intensive and costly, especially on edge devices. Current Large Language Models (LLMs) struggle with function calling at the edge because they cannot handle complex inputs or manage multiple tools effectively. This results in low task-completion accuracy, increased delays, and higher power consumption. In this work, we introduce Less-is-More, a novel fine-tuning-free function-calling scheme for dynamic tool selection. Our approach is based on the key insight that selectively reducing the number of tools available to LLMs significantly improves their function-calling performance, execution time, and power efficiency on edge devices. Experimental results with state-of-the-art LLMs on edge hardware show agentic success rate improvements, with execution time reduced by up to 70% and power consumption by up to 40%.

[Arxiv](https://arxiv.org/abs/2411.15399)