# LongLLaVA 利用混合架构，高效地将多模态大型语言模型扩展至处理 1000 张图像。

发布时间：2024年09月04日

`LLM应用` `计算机视觉` `人工智能`

> LongLLaVA: Scaling Multi-modal LLMs to 1000 Images Efficiently via Hybrid Architecture

# 摘要

> 为了提升多模态大型语言模型（MLLMs）在长上下文处理上的能力，我们进行了一系列创新优化，包括模型架构的革新、数据构建的精细化以及训练策略的优化。我们特别关注了“图像增多导致性能下降”和“高计算成本”等难题。通过将模型架构升级为Mamba与Transformer的混合体，并结合多图像间的时间与空间依赖性进行数据构建，我们采用了渐进式训练策略。新发布的LongLLaVA模型，作为首个混合型MLLM，不仅在效率与效果间找到了理想平衡点，更在多项基准测试中表现卓越，同时保持了高吞吐量与低内存消耗。尤为值得一提的是，LongLLaVA能在单个A100 80GB GPU上高效处理近千张图像，预示着其在众多任务中的广阔应用潜力。

> Expanding the long-context capabilities of Multi-modal Large Language Models~(MLLMs) is crucial for video understanding, high-resolution image understanding, and multi-modal agents. This involves a series of systematic optimizations, including model architecture, data construction and training strategy, particularly addressing challenges such as \textit{degraded performance with more images} and \textit{high computational costs}. In this paper, we adapt the model architecture to a hybrid of Mamba and Transformer blocks, approach data construction with both temporal and spatial dependencies among multiple images and employ a progressive training strategy. The released model \textbf{LongLLaVA}~(\textbf{Long}-Context \textbf{L}arge \textbf{L}anguage \textbf{a}nd \textbf{V}ision \textbf{A}ssistant) is the first hybrid MLLM, which achieved a better balance between efficiency and effectiveness. LongLLaVA not only achieves competitive results across various benchmarks, but also maintains high throughput and low memory consumption. Especially, it could process nearly a thousand images on a single A100 80GB GPU, showing promising application prospects for a wide range of tasks.

[Arxiv](https://arxiv.org/abs/2409.02889)