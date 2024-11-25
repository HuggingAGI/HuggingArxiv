# AdaNeg：借助视觉语言模型的自适应负代理引导式 OOD 检测

发布时间：2024年10月26日

`LLM应用` `计算机视觉` `图像识别`

> AdaNeg: Adaptive Negative Proxy Guided OOD Detection with Vision-Language Models

# 摘要

> 近期研究显示，预训练的视觉语言模型借助负标签作指引，能有效识别分布外（OOD）样本。但在不同的 OOD 数据集采用统一的负标签，往往会造成语义偏差，因为这些文本标签或许无法精准反映 OOD 图像的实际空间。为解决此问题，我们引入了“自适应负代理”，它在测试时通过探索实际的 OOD 图像动态生成，从而更紧密地与底层的 OOD 标签空间契合，提升负代理指导的成效。具体而言，我们的方法利用特征存储库，有选择性地缓存测试图像中的判别性特征，代表目标 OOD 分布。这有利于创建能更好地与特定 OOD 数据集对齐的代理。任务自适应代理通过平均特征来体现每个数据集的独特特性，而样本自适应代理依据其与单个测试样本的相似度对特征进行加权，探究详细的样本级别细微差异。用于识别 OOD 样本的最终得分将静态负标签与我们提出的自适应代理相融合，有效地将文本和视觉知识结合起来以增强性能。我们的方法无需训练且无需标注，还能保持较快的测试速度。在各类基准上开展的大量实验证明了我们的方法（简称 AdaNeg）的有效性。特别要指出的是，在大规模的 ImageNet 基准上，我们的 AdaNeg 显著优于现有方法，AUROC 提高了 2.45%，FPR95 降低了 6.48%。代码可在 url{https://github.com/YBZh/OpenOOD-VLM}获取。

> Recent research has shown that pre-trained vision-language models are effective at identifying out-of-distribution (OOD) samples by using negative labels as guidance. However, employing consistent negative labels across different OOD datasets often results in semantic misalignments, as these text labels may not accurately reflect the actual space of OOD images. To overcome this issue, we introduce \textit{adaptive negative proxies}, which are dynamically generated during testing by exploring actual OOD images, to align more closely with the underlying OOD label space and enhance the efficacy of negative proxy guidance. Specifically, our approach utilizes a feature memory bank to selectively cache discriminative features from test images, representing the targeted OOD distribution. This facilitates the creation of proxies that can better align with specific OOD datasets. While task-adaptive proxies average features to reflect the unique characteristics of each dataset, the sample-adaptive proxies weight features based on their similarity to individual test samples, exploring detailed sample-level nuances. The final score for identifying OOD samples integrates static negative labels with our proposed adaptive proxies, effectively combining textual and visual knowledge for enhanced performance. Our method is training-free and annotation-free, and it maintains fast testing speed. Extensive experiments across various benchmarks demonstrate the effectiveness of our approach, abbreviated as AdaNeg. Notably, on the large-scale ImageNet benchmark, our AdaNeg significantly outperforms existing methods, with a 2.45\% increase in AUROC and a 6.48\% reduction in FPR95. Codes are available at url{https://github.com/YBZh/OpenOOD-VLM}.

[Arxiv](https://arxiv.org/abs/2410.20149)