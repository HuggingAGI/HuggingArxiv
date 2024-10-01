# VMAD：一种视觉增强的多模态大型语言模型，专为零-shot 异常检测而设计。

发布时间：2024年09月30日

`LLM应用` `制造业` `异常检测`

> VMAD: Visual-enhanced Multimodal Large Language Model for Zero-Shot Anomaly Detection

# 摘要

> 零-shot 异常检测 (ZSAD) 通过在文本提示和检查图像之间建立特征映射，识别并定位以前未见过的对象中的异常，在灵活的工业制造中展示了卓越的研究价值。然而，现有的 ZSAD 方法受限于封闭世界设置，难以处理预定义提示之外的未见缺陷。最近，将多模态大型语言模型 (MLLM) 应用于工业异常检测 (IAD) 提供了一个可行的解决方案。与固定提示方法不同，MLLM 表现出一种生成范式，具有开放式的文本解释，能够进行更适应的异常分析。然而，这种适应面临固有的挑战，因为异常通常表现为细粒度区域，并且与正常样本的视觉差异最小。为了应对这些挑战，我们提出了一种新的框架 VMAD (视觉增强的 MLLM 异常检测)，该框架通过基于视觉的 IAD 知识和细粒度感知来增强 MLLM，同时提供精确的检测和全面的异常分析。具体来说，我们设计了一种缺陷敏感结构学习方案，将视觉分支中的补丁相似性提示转移到我们的 MLLM 中，以提高异常辨别能力。此外，我们引入了一种新的视觉投影器，局部增强的令牌压缩，该投影器挖掘局部上下文中的多层次特征，以增强细粒度检测。此外，我们引入了真实工业异常检测 (RIAD)，这是一个全面的 IAD 数据集，包含详细的异常描述和分析，为基于 MLLM 的 IAD 开发提供了宝贵的资源。在包括 MVTec-AD、Visa、WFDD 和 RIAD 数据集在内的零-shot 基准上的广泛实验表明，我们的性能优于最先进的方法。代码和数据集将很快可用。

> Zero-shot anomaly detection (ZSAD) recognizes and localizes anomalies in previously unseen objects by establishing feature mapping between textual prompts and inspection images, demonstrating excellent research value in flexible industrial manufacturing. However, existing ZSAD methods are limited by closed-world settings, struggling to unseen defects with predefined prompts. Recently, adapting Multimodal Large Language Models (MLLMs) for Industrial Anomaly Detection (IAD) presents a viable solution. Unlike fixed-prompt methods, MLLMs exhibit a generative paradigm with open-ended text interpretation, enabling more adaptive anomaly analysis. However, this adaption faces inherent challenges as anomalies often manifest in fine-grained regions and exhibit minimal visual discrepancies from normal samples. To address these challenges, we propose a novel framework VMAD (Visual-enhanced MLLM Anomaly Detection) that enhances MLLM with visual-based IAD knowledge and fine-grained perception, simultaneously providing precise detection and comprehensive analysis of anomalies. Specifically, we design a Defect-Sensitive Structure Learning scheme that transfers patch-similarities cues from visual branch to our MLLM for improved anomaly discrimination. Besides, we introduce a novel visual projector, Locality-enhanced Token Compression, which mines multi-level features in local contexts to enhance fine-grained detection. Furthermore, we introduce the Real Industrial Anomaly Detection (RIAD), a comprehensive IAD dataset with detailed anomaly descriptions and analyses, offering a valuable resource for MLLM-based IAD development. Extensive experiments on zero-shot benchmarks, including MVTec-AD, Visa, WFDD, and RIAD datasets, demonstrate our superior performance over state-of-the-art methods. The code and dataset will be available soon.

[Arxiv](https://arxiv.org/abs/2409.20146)