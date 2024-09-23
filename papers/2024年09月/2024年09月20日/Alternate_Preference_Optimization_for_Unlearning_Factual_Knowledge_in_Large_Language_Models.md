# 大型语言模型中遗忘事实知识的替代偏好优化策略

发布时间：2024年09月20日

`LLM理论` `人工智能` `隐私保护`

> Alternate Preference Optimization for Unlearning Factual Knowledge in Large Language Models

# 摘要

> 机器遗忘的目标是高效地消除特定训练数据（遗忘集）对模型的影响。现有方法在处理大型语言模型（LLM）时，仅依赖负面反馈来抑制与遗忘集相关的响应，这往往导致输出无意义或不一致，降低模型效用并带来隐私风险。为此，我们提出了交替偏好优化（AltPO），结合负面反馈和遗忘集上的域内正面反馈。同时，我们引入了新的评估指标来衡量响应质量。实验证明，AltPO 不仅实现了有效遗忘，还避免了不良模型行为，保持了整体性能。

> Machine unlearning aims to efficiently eliminate the influence of specific training data, known as the forget set, from the model. However, existing unlearning methods for Large Language Models (LLMs) face a critical challenge: they rely solely on negative feedback to suppress responses related to the forget set, which often results in nonsensical or inconsistent outputs, diminishing model utility and posing potential privacy risks. To address this limitation, we propose a novel approach called Alternate Preference Optimization (AltPO), which combines negative feedback with in-domain positive feedback on the forget set. Additionally, we introduce new evaluation metrics to assess the quality of responses related to the forget set. Extensive experiments show that our approach not only enables effective unlearning but also avoids undesirable model behaviors while maintaining overall model performance.

[Arxiv](https://arxiv.org/abs/2409.13474)