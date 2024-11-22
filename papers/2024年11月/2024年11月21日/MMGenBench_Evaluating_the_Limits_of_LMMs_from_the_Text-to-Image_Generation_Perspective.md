# MMGenBench：从文本到图像生成的视角评估 LMMs 的限度

发布时间：2024年11月21日

`LLM应用` `图像生成` `模型评估`

> MMGenBench: Evaluating the Limits of LMMs from the Text-to-Image Generation Perspective

# 摘要

> 大型多模态模型（LMMs）展现出了非凡的能力。然而，现有的评估 LMMs 的基准大多聚焦于图像理解，鲜少从图像生成的视角去评估。为应对此问题，我们提出了一条直接的自动化评估流程。具体而言，该流程要求 LMMs 依据给定的输入图像生成图像提示，随后利用文本到图像的生成模型基于这些提示创建新图像，最后通过对比原始图像和生成图像来评估 LMMs 的性能。此外，我们引入了 MMGenBench-Test，这是一个用于评估 13 种不同图像模式下 LMMs 的综合基准，还有 MMGenBench-Domain，旨在评估生成图像领域内 LMMs 的性能。对 50 多个热门 LMMs 的全面评估证明了该流程和基准的有效性与可靠性。我们的观察发现，不少在现有基准中表现优异的 LMMs 未能很好地完成与图像理解和描述相关的基础任务。这一发现凸显了当前 LMMs 在性能提升方面的巨大潜力，也为未来的模型优化指明了方向。同时，我们的流程仅通过图像输入就能助力高效评估 LMMs 在不同领域的性能。

> Large Multimodal Models (LMMs) have demonstrated remarkable capabilities. While existing benchmarks for evaluating LMMs mainly focus on image comprehension, few works evaluate them from the image generation perspective. To address this issue, we propose a straightforward automated evaluation pipeline. Specifically, this pipeline requires LMMs to generate an image-prompt from a given input image. Subsequently, it employs text-to-image generative models to create a new image based on these generated prompts. Finally, we evaluate the performance of LMMs by comparing the original image with the generated one. Furthermore, we introduce MMGenBench-Test, a comprehensive benchmark developed to evaluate LMMs across 13 distinct image patterns, and MMGenBench-Domain, targeting the performance evaluation of LMMs within the generative image domain. A thorough evaluation involving over 50 popular LMMs demonstrates the effectiveness and reliability in both the pipeline and benchmark. Our observations indicate that numerous LMMs excelling in existing benchmarks fail to adequately complete the basic tasks, related to image understanding and description. This finding highlights the substantial potential for performance improvement in current LMMs and suggests avenues for future model optimization. Concurrently, our pipeline facilitates the efficient assessment of LMMs performance across diverse domains by using solely image inputs.

[Arxiv](https://arxiv.org/abs/2411.14062)