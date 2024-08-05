# 探究超参数如何影响大型语言模型的推理性能：一项针对 vLLM 与 HuggingFace 管道的评估研究

发布时间：2024年08月02日

`LLM应用` `软件开发` `人工智能`

> The Impact of Hyperparameters on Large Language Model Inference Performance: An Evaluation of vLLM and HuggingFace Pipelines

# 摘要

> 随着开源大型语言模型 (LLM) 的兴起，开发者现在能够在确保隐私和合规性的同时，构建 AI 解决方案，并掌控模型部署的全过程。为了充分发挥这些 LLM 的潜力，推理引擎成为关键。这些引擎将模型权重加载至 GPU 等资源，高效处理查询并生成响应。LLM 的推理速度对实时应用至关重要，因其每秒需执行数百万乃至数十亿次浮点运算。近期，如 vLLM 等先进推理引擎崭露头角，通过高效内存管理等创新机制，实现了业界领先性能。本文通过 vLLM 和 HuggingFace 的 pipelines 两个推理库，深入分析了 20 个 LLM 的吞吐量性能。我们探讨了开发者必须调整的超参数如何影响推理效率。研究结果显示，吞吐量表现参差不齐，存在显著峰值，凸显了超参数优化的重要性。此外，我们发现，在更换 GPU 型号进行推理时，通过超参数优化，可分别提升 HuggingFace pipelines 吞吐量达 9.16% 和 13.7%。

> The recent surge of open-source large language models (LLMs) enables developers to create AI-based solutions while maintaining control over aspects such as privacy and compliance, thereby providing governance and ownership of the model deployment process. To utilize these LLMs, inference engines are needed. These engines load the model's weights onto available resources, such as GPUs, and process queries to generate responses. The speed of inference, or performance, of the LLM, is critical for real-time applications, as it computes millions or billions of floating point operations per inference. Recently, advanced inference engines such as vLLM have emerged, incorporating novel mechanisms such as efficient memory management to achieve state-of-the-art performance. In this paper, we analyze the performance, particularly the throughput (tokens generated per unit of time), of 20 LLMs using two inference libraries: vLLM and HuggingFace's pipelines. We investigate how various hyperparameters, which developers must configure, influence inference performance. Our results reveal that throughput landscapes are irregular, with distinct peaks, highlighting the importance of hyperparameter optimization to achieve maximum performance. We also show that applying hyperparameter optimization when upgrading or downgrading the GPU model used for inference can improve throughput from HuggingFace pipelines by an average of 9.16% and 13.7%, respectively.

[Arxiv](https://arxiv.org/abs/2408.01050)