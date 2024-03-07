# [本研究探讨了量化后的大型语言模型（LLM）的压缩潜力，深入分析其在降低存储需求和计算开销方面的可能性。](https://arxiv.org/abs/2403.01384)

> On the Compressibility of Quantized Large Language Models

发布时间：2024年03月02日

> 将LLMs部署至边缘或移动设备能有效提升数据隐私和实时处理性能，但受限于其庞大的内存需求，这一过程也遭遇难题。量化技术可在保证性能的基础上缩小模型规模，即便如此，部分量化后的LLMs仍可能因体积过大而无法完全容纳于设备有限的内存中，需要从存储中分段加载以完成推理任务，导致模型加载的I/O延迟成为影响LLM推理效率的关键制约因素。本文旨在初步研究如何运用数据压缩技术减少数据搬移，从而加快内存受限环境下量化LLM的推理速度，并特别关注量化LLMs的压缩潜力、压缩与性能间的平衡关系，以及如何协同优化这两方面的问题。

> Deploying Large Language Models (LLMs) on edge or mobile devices offers significant benefits, such as enhanced data privacy and real-time processing capabilities. However, it also faces critical challenges due to the substantial memory requirement of LLMs. Quantization is an effective way of reducing the model size while maintaining good performance. However, even after quantization, LLMs may still be too big to fit entirely into the limited memory of edge or mobile devices and have to be partially loaded from the storage to complete the inference. In this case, the I/O latency of model loading becomes the bottleneck of the LLM inference latency. In this work, we take a preliminary step of studying applying data compression techniques to reduce data movement and thus speed up the inference of quantized LLM on memory-constrained devices. In particular, we discussed the compressibility of quantized LLMs, the trade-off between the compressibility and performance of quantized LLMs, and opportunities to optimize both of them jointly.

`LLM应用`