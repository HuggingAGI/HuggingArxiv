# UMass-BioNLP 团队在 2024 年 MEDIQA-M3G 竞赛中推出了 DermPrompt，这是一个针对皮肤科诊断的系统化提示工程探索项目，利用 GPT-4V 技术深入挖掘和优化诊断流程。

发布时间：2024年04月26日

`分类：LLM应用` `人工智能`

> UMass-BioNLP at MEDIQA-M3G 2024: DermPrompt -- A Systematic Exploration of Prompt Engineering with GPT-4V for Dermatological Diagnosis

# 摘要

> 本论文展示了我们团队参与 MEDIQA-ClinicalNLP2024 共享任务 B 的成果。我们采用了一种创新的方法，通过融合大型多模态模型来诊断临床皮肤科病例，尤其是利用 GPT-4V 在检索和重排系统中的应用。研究发现，GPT-4V 作为检索工具时，能够凭借皮肤图像和患者简史，85% 的时间准确识别出正确的皮肤状况。我们还证实了，朴素链式思维（CoT）在检索中效果显著，而基于医学指南的 CoT 对于精确的皮肤科诊断至关重要。此外，我们引入了多代理对话（MAC）框架，并通过实验验证了其相较于最佳 CoT 策略的卓越性能和潜力。研究指出，结合朴素 CoT 检索和基于批评的多代理对话诊断，GPT-4V 有助于实现皮肤科疾病的早期和精确诊断。这项研究不仅推动了诊断流程的优化，还有助于皮肤科教育的发展，并为患者护理提供了一种高效、便捷、准确的诊断工具。

> This paper presents our team's participation in the MEDIQA-ClinicalNLP2024 shared task B. We present a novel approach to diagnosing clinical dermatology cases by integrating large multimodal models, specifically leveraging the capabilities of GPT-4V under a retriever and a re-ranker framework. Our investigation reveals that GPT-4V, when used as a retrieval agent, can accurately retrieve the correct skin condition 85% of the time using dermatological images and brief patient histories. Additionally, we empirically show that Naive Chain-of-Thought (CoT) works well for retrieval while Medical Guidelines Grounded CoT is required for accurate dermatological diagnosis. Further, we introduce a Multi-Agent Conversation (MAC) framework and show its superior performance and potential over the best CoT strategy. The experiments suggest that using naive CoT for retrieval and multi-agent conversation for critique-based diagnosis, GPT-4V can lead to an early and accurate diagnosis of dermatological conditions. The implications of this work extend to improving diagnostic workflows, supporting dermatological education, and enhancing patient care by providing a scalable, accessible, and accurate diagnostic tool.

![UMass-BioNLP 团队在 2024 年 MEDIQA-M3G 竞赛中推出了 DermPrompt，这是一个针对皮肤科诊断的系统化提示工程探索项目，利用 GPT-4V 技术深入挖掘和优化诊断流程。](../../../paper_images/2404.17749/method.png)

![UMass-BioNLP 团队在 2024 年 MEDIQA-M3G 竞赛中推出了 DermPrompt，这是一个针对皮肤科诊断的系统化提示工程探索项目，利用 GPT-4V 技术深入挖掘和优化诊断流程。](../../../paper_images/2404.17749/MAC_final.png)

[Arxiv](https://arxiv.org/abs/2404.17749)