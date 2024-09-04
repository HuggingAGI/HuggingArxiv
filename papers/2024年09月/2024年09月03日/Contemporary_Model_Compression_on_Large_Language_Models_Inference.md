# 大语言模型推理中的现代模型压缩技术

发布时间：2024年09月03日

`LLM理论` `移动设备` `边缘计算`

> Contemporary Model Compression on Large Language Models Inference

# 摘要

> 大型语言模型（LLM）在自然语言处理领域取得了突破性进展，但高内存消耗和慢处理速度等计算需求限制了其在资源有限设备上的应用。高效推理是实现LLM广泛部署的关键，特别是在移动和边缘设备上。  本调查深入分析了模型压缩技术，这些技术通过减小模型尺寸和计算需求，同时保持性能，有效应对了这些挑战。我们重点探讨了量化、知识蒸馏和剪枝等模型级压缩方法，以及KV缓存高效设计等系统级优化。这些方法从降低数值精度到模型间知识传递，再到简化神经网络结构，各具特色。此外，我们还探讨了系统设计的最新趋势，这些趋势进一步提升了LLM推理的效率。本调查旨在全面展示模型压缩领域的最新进展，并探讨其如何使LLM更加实用和普及。

> Large Language Models (LLMs) have revolutionized natural language processing by achieving state-of-the-art results across a variety of tasks. However, the computational demands of LLM inference, including high memory consumption and slow processing speeds, pose significant challenges for real-world applications, particularly on resource-constrained devices. Efficient inference is crucial for scaling the deployment of LLMs to a broader range of platforms, including mobile and edge devices.
  This survey explores contemporary techniques in model compression that address these challenges by reducing the size and computational requirements of LLMs while maintaining their performance. We focus on model-level compression methods, including quantization, knowledge distillation, and pruning, as well as system-level optimizations like KV cache efficient design. Each of these methodologies offers a unique approach to optimizing LLMs, from reducing numerical precision to transferring knowledge between models and structurally simplifying neural networks. Additionally, we discuss emerging trends in system-level design that further enhance the efficiency of LLM inference. This survey aims to provide a comprehensive overview of current advancements in model compression and their potential to make LLMs more accessible and practical for diverse applications.

[Arxiv](https://arxiv.org/abs/2409.01990)