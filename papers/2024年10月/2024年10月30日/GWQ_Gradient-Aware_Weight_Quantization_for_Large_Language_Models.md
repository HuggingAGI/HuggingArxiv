# GWQ：针对大型语言模型的梯度感知权重量化

发布时间：2024年10月30日

`LLM应用` `边缘计算` `模型量化`

> GWQ: Gradient-Aware Weight Quantization for Large Language Models

# 摘要

> 大型语言模型（LLMs）在解决复杂语言任务时表现抢眼。然而，其众多的参数给在边缘设备上部署和应用该模型带来了巨大挑战。把大型语言模型压缩至低位虽能使其在资源受限的设备上运行，但往往会致使性能降低。为应对此问题，我们提出了梯度感知权重量化（GWQ），这是首个用于低位权重量化的方法，它借助梯度来定位异常值，仅需少量校准数据来检测异常值。GWQ 优先以 FP16 精度保留对应于前 1%异常值的权重，其余非异常值权重则以低位格式存储。实验表明，在梯度定位模型中利用敏感权重，比在 Hessian 矩阵定位模型中利用敏感权重更科学。相较于当前的量化方法，GWQ 能应用于多种语言模型，并在 WikiText2 和 C4 数据集上实现更低的 PPL。在零样本任务中，GWQ 量化模型比其他量化方法的准确性更高。GWQ 还适用于多模态模型量化，量化的 Qwen-VL 系列模型比其他方法更精准。在零样本目标检测任务数据集 RefCOCO 上，GWQ 优于当前最先进的方法 SPQR。与原始模型相比，GWQ 实现了 1.2 倍的推理加速，有效减少了推理内存。

> Large language models (LLMs) show impressive performance in solving complex languagetasks. However, its large number of parameterspresent significant challenges for the deployment and application of the model on edge devices. Compressing large language models to low bits can enable them to run on resource-constrained devices, often leading to performance degradation. To address this problem, we propose gradient-aware weight quantization (GWQ), the first quantization approach for low-bit weight quantization that leverages gradients to localize outliers, requiring only a minimal amount of calibration data for outlier detection. GWQ retains the weights corresponding to the top 1% outliers preferentially at FP16 precision, while the remaining non-outlier weights are stored in a low-bit format. GWQ found experimentally that utilizing the sensitive weights in the gradient localization model is more scientific compared to utilizing the sensitive weights in the Hessian matrix localization model. Compared to current quantization methods, GWQ can be applied to multiple language models and achieves lower PPL on the WikiText2 and C4 dataset. In the zero-shot task, GWQ quantized models have higher accuracy compared to other quantization methods.GWQ is also suitable for multimodal model quantization, and the quantized Qwen-VL family model is more accurate than other methods. zero-shot target detection task dataset RefCOCO outperforms the current stat-of-the-arts method SPQR. GWQ achieves 1.2x inference speedup in comparison to the original model, and effectively reduces the inference memory.

[Arxiv](https://arxiv.org/abs/2411.00850)