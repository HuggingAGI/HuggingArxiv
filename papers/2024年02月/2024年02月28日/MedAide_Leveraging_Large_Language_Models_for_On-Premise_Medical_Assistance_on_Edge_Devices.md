# MedAide项目旨在利用大型语言模型，在边缘设备上实现即时的本地医疗辅助功能。

发布时间：2024年02月28日

`LLM应用`

> MedAide: Leveraging Large Language Models for On-Premise Medical Assistance on Edge Devices

# 摘要

> LLMs以强大的NLP能力正引领各领域变革，但在资源有限的边缘计算及嵌入式系统中部署却面临不小挑战，特别是在医疗设施匮乏的偏远地区提供医疗帮助。为此，我们创新推出MedAide——一款本地健康聊天助手，它将微型LLMs与LangChain紧密结合，高效提供基于边缘计算的初步医疗诊断支持，且在无服务器架构下优化模型，实现对嵌入式设备极小内存占用和延迟的要求。我们运用低秩适应（LoRA）优化训练过程，并在多样化医疗数据集上训练模型，借助人类反馈强化学习（RLHF）提升专业领域性能。MedAide已成功搭载于各类消费级GPU及Nvidia Jetson开发板上，实现了77%的医疗咨询准确率和在USMLE基准测试中得分为56的优秀表现，构建了一款基于边缘计算、兼顾隐私保护、高效节能的医疗辅助平台，有力地赋能社区。

> Large language models (LLMs) are revolutionizing various domains with their remarkable natural language processing (NLP) abilities. However, deploying LLMs in resource-constrained edge computing and embedded systems presents significant challenges. Another challenge lies in delivering medical assistance in remote areas with limited healthcare facilities and infrastructure. To address this, we introduce MedAide, an on-premise healthcare chatbot. It leverages tiny-LLMs integrated with LangChain, providing efficient edge-based preliminary medical diagnostics and support. MedAide employs model optimizations for minimal memory footprint and latency on embedded edge devices without server infrastructure. The training process is optimized using low-rank adaptation (LoRA). Additionally, the model is trained on diverse medical datasets, employing reinforcement learning from human feedback (RLHF) to enhance its domain-specific capabilities. The system is implemented on various consumer GPUs and Nvidia Jetson development board. MedAide achieves 77\% accuracy in medical consultations and scores 56 in USMLE benchmark, enabling an energy-efficient healthcare assistance platform that alleviates privacy concerns due to edge-based deployment, thereby empowering the community.

[Arxiv](https://arxiv.org/abs/2403.00830)