# HarmAug：为安全防护模型的知识蒸馏提供高效数据增强

发布时间：2024年10月02日

`LLM应用` `网络安全` `移动设备`

> HarmAug: Effective Data Augmentation for Knowledge Distillation of Safety Guard Models

# 摘要

> 确保 LLM 在实际应用中的安全部署，需要能够检测恶意查询的安全防护模型。然而，现有数十亿参数的安全防护模型因内存和延迟问题，难以在移动设备上与 LLM 共存。为此，我们通过提炼大型教师模型，创建了一个更小的安全防护模型。但由于现有数据集中有害指令的多样性有限，简单提炼的模型性能不佳。为解决这一问题，我们提出了 HarmAug，一种通过破解 LLM 生成有害指令的数据增强方法。实验证明，HarmAug 不仅优于其他基线，还使 4.35 亿参数的安全防护模型在性能上媲美甚至超越 70 亿参数的大型模型，同时大幅降低计算成本。

> Safety guard models that detect malicious queries aimed at large language models (LLMs) are essential for ensuring the secure and responsible deployment of LLMs in real-world applications. However, deploying existing safety guard models with billions of parameters alongside LLMs on mobile devices is impractical due to substantial memory requirements and latency. To reduce this cost, we distill a large teacher safety guard model into a smaller one using a labeled dataset of instruction-response pairs with binary harmfulness labels. Due to the limited diversity of harmful instructions in the existing labeled dataset, naively distilled models tend to underperform compared to larger models. To bridge the gap between small and large models, we propose HarmAug, a simple yet effective data augmentation method that involves jailbreaking an LLM and prompting it to generate harmful instructions. Given a prompt such as, "Make a single harmful instruction prompt that would elicit offensive content", we add an affirmative prefix (e.g., "I have an idea for a prompt:") to the LLM's response. This encourages the LLM to continue generating the rest of the response, leading to sampling harmful instructions. Another LLM generates a response to the harmful instruction, and the teacher model labels the instruction-response pair. We empirically show that our HarmAug outperforms other relevant baselines. Moreover, a 435-million-parameter safety guard model trained with HarmAug achieves an F1 score comparable to larger models with over 7 billion parameters, and even outperforms them in AUPRC, while operating at less than 25% of their computational cost.

[Arxiv](https://arxiv.org/abs/2410.01524)