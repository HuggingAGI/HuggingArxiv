# 探究 LLM 在多模态评估中的作用

发布时间：2024年10月16日

`LLM应用` `人工智能` `计算机视觉`

> Understanding the Role of LLMs in Multimodal Evaluation Benchmarks

# 摘要

> 多模态大型语言模型 (MLLM) 的迅猛发展催生了多种评估基准，但这些评估的真实性质及其对多模态推理的实际考察程度仍不明朗。本文深入探讨了 LLM 骨干在 MLLM 评估中的角色，特别关注两个核心问题：当前基准对多模态推理的真正评估程度，以及 LLM 先验知识对性能的影响。我们提出了一种改进的评估协议，以区分 LLM 骨干与多模态集成的贡献，并开发了一种自动知识识别技术，用于检测 LLM 是否具备处理多模态问题的必要知识。研究涵盖了四个不同基准和八个顶尖 MLLM。研究发现，某些基准即使缺乏视觉输入也能表现优异，且高达 50% 的错误率源于 LLM 骨干的世界知识不足，凸显了其对语言能力的过度依赖。为此，我们设计了一种知识增强流程，显著提升了性能，某些数据集上甚至提高了 60%，性能提升近 4 倍。本研究揭示了 LLM 骨干在 MLLM 中的关键作用，并呼吁采用更为精细的基准测试方法。

> The rapid advancement of Multimodal Large Language Models (MLLMs) has been accompanied by the development of various benchmarks to evaluate their capabilities. However, the true nature of these evaluations and the extent to which they assess multimodal reasoning versus merely leveraging the underlying Large Language Model (LLM) backbone remain unclear. This paper presents a comprehensive investigation into the role of LLM backbones in MLLM evaluation, focusing on two critical aspects: the degree to which current benchmarks truly assess multimodal reasoning and the influence of LLM prior knowledge on performance. Specifically, we introduce a modified evaluation protocol to disentangle the contributions of the LLM backbone from multimodal integration, and an automatic knowledge identification technique for diagnosing whether LLMs equip the necessary knowledge for corresponding multimodal questions. Our study encompasses four diverse MLLM benchmarks and eight state-of-the-art MLLMs. Key findings reveal that some benchmarks allow high performance even without visual inputs and up to 50\% of error rates can be attributed to insufficient world knowledge in the LLM backbone, indicating a heavy reliance on language capabilities. To address knowledge deficiencies, we propose a knowledge augmentation pipeline that achieves significant performance gains, with improvements of up to 60\% on certain datasets, resulting in a approximately 4x increase in performance. Our work provides crucial insights into the role of the LLM backbone in MLLMs, and highlights the need for more nuanced benchmarking approaches.

[Arxiv](https://arxiv.org/abs/2410.12329)