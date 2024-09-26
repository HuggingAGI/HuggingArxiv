# 累加器感知后训练量化技术

发布时间：2024年09月25日

`LLM理论` `半导体` `人工智能`

> Accumulator-Aware Post-Training Quantization

# 摘要

> 近期研究显示，低精度累加在多平台上提升了吞吐量、能效和面积利用率。然而，这些研究仅限于量化感知训练（QAT），即在量化过程中微调或重新训练模型。随着模型规模扩大，QAT 成本激增，推动了训练后量化（PTQ）的研究热潮。我们的研究首次在 PTQ 环境下正式探讨累加器感知量化。为此，我们推出了 AXE 框架，旨在增强现有逐层 PTQ 算法的溢出防护。理论支持下，AXE 在 GPFQ 和 OPTQ 算法上展示了其灵活性。此外，AXE 首次支持多阶段累加，为全面数据路径优化和大型语言模型（LLM）扩展铺平道路。实验表明，AXE 在图像分类和语言生成任务中，显著优化了累加器位宽与模型精度之间的平衡。

> Several recent studies have investigated low-precision accumulation, reporting improvements in throughput, power, and area across various platforms. However, the accompanying proposals have only considered the quantization-aware training (QAT) paradigm, in which models are fine-tuned or trained from scratch with quantization in the loop. As models continue to grow in size, QAT techniques become increasingly more expensive, which has motivated the recent surge in post-training quantization (PTQ) research. To the best of our knowledge, ours marks the first formal study of accumulator-aware quantization in the PTQ setting. To bridge this gap, we introduce AXE, a practical framework of accumulator-aware extensions designed to endow overflow avoidance guarantees to existing layer-wise PTQ algorithms. We theoretically motivate AXE and demonstrate its flexibility by implementing it on top of two state-of-the-art PTQ algorithms: GPFQ and OPTQ. We further generalize AXE to support multi-stage accumulation for the first time, opening the door for full datapath optimization and scaling to large language models (LLMs). We evaluate AXE across image classification and language generation models, and observe significant improvements in the trade-off between accumulator bit width and model accuracy over baseline methods.

[Arxiv](https://arxiv.org/abs/2409.17092)