# Quamba：专为选择性状态空间模型设计的后训练量化方案

发布时间：2024年10月17日

`LLM理论` `云计算` `边缘计算`

> Quamba: A Post-Training Quantization Recipe for Selective State Space Models

# 摘要

> 状态空间模型 (SSM) 作为 Transformer 的替代方案，在大型语言模型中表现出色，不仅准确性高，还能处理更长的上下文。然而，在云服务和边缘设备上提升 SSM 的效率仍具挑战。我们提出的 8 位量化方法，通过精细调整和消除异常值，成功提升了 SSM 的部署适应性，同时保持了高准确率。实验结果显示，在 Nvidia Orin Nano 8G 上，生成延迟显著降低，准确率仅轻微下降。这表明我们的方法在云和边缘平台上部署 SSM 模型具有广泛的应用前景。

> State Space Models (SSMs) have emerged as an appealing alternative to Transformers for large language models, achieving state-of-the-art accuracy with constant memory complexity which allows for holding longer context lengths than attention-based networks. The superior computational efficiency of SSMs in long sequence modeling positions them favorably over Transformers in many scenarios. However, improving the efficiency of SSMs on request-intensive cloud-serving and resource-limited edge applications is still a formidable task. SSM quantization is a possible solution to this problem, making SSMs more suitable for wide deployment, while still maintaining their accuracy. Quantization is a common technique to reduce the model size and to utilize the low bit-width acceleration features on modern computing units, yet existing quantization techniques are poorly suited for SSMs. Most notably, SSMs have highly sensitive feature maps within the selective scan mechanism (i.e., linear recurrence) and massive outliers in the output activations which are not present in the output of token-mixing in the self-attention modules. To address this issue, we propose a static 8-bit per-tensor SSM quantization method which suppresses the maximum values of the input activations to the selective SSM for finer quantization precision and quantizes the output activations in an outlier-free space with Hadamard transform. Our 8-bit weight-activation quantized Mamba 2.8B SSM benefits from hardware acceleration and achieves a 1.72x lower generation latency on an Nvidia Orin Nano 8G, with only a 0.9% drop in average accuracy on zero-shot tasks. The experiments demonstrate the effectiveness and practical applicability of our approach for deploying SSM-based models of all sizes on both cloud and edge platforms.

[Arxiv](https://arxiv.org/abs/2410.13229)