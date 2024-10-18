# AsymKV：利用层级不对称量化配置，实现 KV Cache 的 1-Bit 量化。

发布时间：2024年10月17日

`LLM理论` `机器学习` `数据压缩`

> AsymKV: Enabling 1-Bit Quantization of KV Cache with Layer-Wise Asymmetric Quantization Configurations

# 摘要

> 大型语言模型在文本生成和视频生成等任务中表现出色，但其庞大的参数数量导致存储需求巨大，限制了部署机器的性能。为解决这一问题，研究者提出通过量化技术压缩模型，即用整数替代浮点数。近期研究还建议对LLM的KV缓存进行量化，并设计等同处理关键和值矩阵的技术。本研究深入分析了KV缓存的不对称结构，发现变压器输出对关键矩阵量化更为敏感。我们系统研究了关键和值量化对注意力输出的影响，并提出不对称量化策略，通过差异化配置关键和值矩阵，实现KV缓存的1位量化。实验结果显示，我们的模型在保持性能的同时，可将多达75%的解码器层量化至1位。

> Large language models have shown exceptional capabilities in a wide range of tasks, such as text generation and video generation, among others. However, due to their massive parameter count, these models often require substantial storage space, imposing significant constraints on the machines deploying LLMs. To overcome this limitation, one research direction proposes to compress the models using integer replacements for floating-point numbers, in a process known as Quantization. Some recent studies suggest quantizing the key and value cache (KV Cache) of LLMs, and designing quantization techniques that treat the key and value matrices equivalently.
  This work delves deeper into the asymmetric structural roles of KV Cache, a phenomenon where the transformer's output loss is more sensitive to the quantization of key matrices. We conduct a systematic examination of the attention output error resulting from key and value quantization. The phenomenon inspires us to propose an asymmetric quantization strategy. Our approach allows for 1-bit quantization of the KV cache by implementing distinct configurations for key and value matrices. We carry out experiments across a variety of datasets, demonstrating that our proposed model allows for the quantization of up to 75% decoder layers with 1 bit, while simultaneously maintaining performance levels comparable to those of the models with floating parameters.

[Arxiv](https://arxiv.org/abs/2410.13212)