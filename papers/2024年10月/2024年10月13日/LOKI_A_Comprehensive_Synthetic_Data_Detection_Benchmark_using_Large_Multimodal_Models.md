# LOKI：基于大型多模态模型的综合合成数据检测基准

发布时间：2024年10月13日

`LLM应用` `网络安全` `人工智能`

> LOKI: A Comprehensive Synthetic Data Detection Benchmark using Large Multimodal Models

# 摘要

> 随着AI生成内容的迅猛发展，未来网络可能充斥着合成数据，使得真实多模态数据的辨别愈发困难。合成数据检测因此备受关注，大型多模态模型（LMMs）在此任务中的表现尤为引人注目。LMMs不仅能判断真实性，还能提供自然语言解释，增强检测的可解释性。同时，区分真伪数据的任务考验了LMMs的感知、知识和推理能力。为此，我们推出了LOKI基准，全面评估LMMs在多模态中检测合成数据的能力。LOKI涵盖视频、图像、3D、文本和音频，包含18K个精心设计的问题，分布在26个子类别中，难度分明。该基准包括粗粒度判断、多项选择题及细粒度异常选择和解释任务，全面分析LMMs。我们在LOKI上测试了22个开源LMMs和6个闭源模型，既展示了其作为合成数据检测器的潜力，也揭示了LMM能力发展中的局限。更多LOKI信息，请访问https://opendatalab.github.io/LOKI/。

> With the rapid development of AI-generated content, the future internet may be inundated with synthetic data, making the discrimination of authentic and credible multimodal data increasingly challenging. Synthetic data detection has thus garnered widespread attention, and the performance of large multimodal models (LMMs) in this task has attracted significant interest. LMMs can provide natural language explanations for their authenticity judgments, enhancing the explainability of synthetic content detection. Simultaneously, the task of distinguishing between real and synthetic data effectively tests the perception, knowledge, and reasoning capabilities of LMMs. In response, we introduce LOKI, a novel benchmark designed to evaluate the ability of LMMs to detect synthetic data across multiple modalities. LOKI encompasses video, image, 3D, text, and audio modalities, comprising 18K carefully curated questions across 26 subcategories with clear difficulty levels. The benchmark includes coarse-grained judgment and multiple-choice questions, as well as fine-grained anomaly selection and explanation tasks, allowing for a comprehensive analysis of LMMs. We evaluated 22 open-source LMMs and 6 closed-source models on LOKI, highlighting their potential as synthetic data detectors and also revealing some limitations in the development of LMM capabilities. More information about LOKI can be found at https://opendatalab.github.io/LOKI/

[Arxiv](https://arxiv.org/abs/2410.09732)