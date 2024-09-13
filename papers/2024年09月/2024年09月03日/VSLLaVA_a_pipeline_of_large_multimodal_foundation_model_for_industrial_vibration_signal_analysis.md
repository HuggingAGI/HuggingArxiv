# VSLLaVA：专为工业振动信号分析设计的大型多模态基础模型管道

发布时间：2024年09月03日

`LLM应用` `信号处理`

> VSLLaVA: a pipeline of large multimodal foundation model for industrial vibration signal analysis

# 摘要

> 尽管大型多模态模型在图像识别中表现出色，但在工业振动信号分析领域，专业知识仍显匮乏。本文提出的 VSLLaVA 管道，通过大型语言模型整合专家知识，实现信号参数识别与故障诊断。首先，专家规则辅助信号生成器融合了专家信号与领域问答对，构建三元组。随后，利用低秩适应方法微调 CLIP 和大型语言模型，注入多模态信号处理知识。最终，结合语言模型与专家规则评估答案，显著提升信号参数分析与故障诊断能力。这一创新管道为未来工业信号分析与监控奠定了基础。

> Large multimodal foundation models have been extensively utilized for image recognition tasks guided by instructions, yet there remains a scarcity of domain expertise in industrial vibration signal analysis. This paper presents a pipeline named VSLLaVA that leverages a large language model to integrate expert knowledge for identification of signal parameters and diagnosis of faults. Within this pipeline, we first introduce an expert rule-assisted signal generator. The generator merges signal provided by vibration analysis experts with domain-specific parameter identification and fault diagnosis question-answer pairs to build signal-question-answer triplets. Then we use these triplets to apply low-rank adaptation methods for fine-tuning the linear layers of the Contrastive Language-Image Pretraining (CLIP) and large language model, injecting multimodal signal processing knowledge. Finally, the fine-tuned model is assessed through the combined efforts of large language model and expert rules to evaluate answer accuracy and relevance, which showcases enhanced performance in identifying, analyzing various signal parameters, and diagnosing faults. These enhancements indicate the potential of this pipeline to build a foundational model for future industrial signal analysis and monitoring.

[Arxiv](https://arxiv.org/abs/2409.07482)