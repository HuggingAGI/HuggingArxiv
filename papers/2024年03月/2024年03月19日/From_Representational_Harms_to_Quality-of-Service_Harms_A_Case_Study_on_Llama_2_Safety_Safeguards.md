# 通过 Llama 2 安全防护机制的深入探究，本案例研究将视线从模型的表征伤害转移至服务质量层面的危害。

发布时间：2024年03月19日

`LLM应用` `社会影响与伦理`

> From Representational Harms to Quality-of-Service Harms: A Case Study on Llama 2 Safety Safeguards

# 摘要

> 近年来LLMs的发展推动了其在各领域的广泛应用，但也带来了附加的安全隐患，并引发了对它们可能加剧边缘化群体问题的担忧。尽管已有研究尝试采用诸如监督式安全微调及基于人类反馈的安全强化学习等策略减轻风险，但关于这些模型内含的安全性和偏见问题仍有诸多疑虑。值得注意的是，旨在提升安全性的模型常常矫枉过正，如过于保守地避免回应某些请求。学术界已明确指出这些模型在功能实用性与安全性之间存在明显的折衷现象。在本论文中，我们通过评估模型在处理已减轻偏见数据时的安全措施效果，更深入地探讨此类安全措施的功效。以Llama 2模型为例，我们揭示了即便是在LLMs的安全回复中也可能潜藏有害假设。为了验证这一点，我们构建了一系列非毒性提示语料，并用其对Llama系列模型进行了测试。借助我们新提出的LLMs响应用户请求的分类体系，我们观察到针对特定人群，安全性和有效性的权衡问题尤为突出，从而可能导致对边缘化群体的服务质量损害。

> Recent progress in large language models (LLMs) has led to their widespread adoption in various domains. However, these advancements have also introduced additional safety risks and raised concerns regarding their detrimental impact on already marginalized populations. Despite growing mitigation efforts to develop safety safeguards, such as supervised safety-oriented fine-tuning and leveraging safe reinforcement learning from human feedback, multiple concerns regarding the safety and ingrained biases in these models remain. Furthermore, previous work has demonstrated that models optimized for safety often display exaggerated safety behaviors, such as a tendency to refrain from responding to certain requests as a precautionary measure. As such, a clear trade-off between the helpfulness and safety of these models has been documented in the literature. In this paper, we further investigate the effectiveness of safety measures by evaluating models on already mitigated biases. Using the case of Llama 2 as an example, we illustrate how LLMs' safety responses can still encode harmful assumptions. To do so, we create a set of non-toxic prompts, which we then use to evaluate Llama models. Through our new taxonomy of LLMs responses to users, we observe that the safety/helpfulness trade-offs are more pronounced for certain demographic groups which can lead to quality-of-service harms for marginalized populations.

![通过 Llama 2 安全防护机制的深入探究，本案例研究将视线从模型的表征伤害转移至服务质量层面的危害。](../../../paper_images/2403.13213/illustration_method.png)

![通过 Llama 2 安全防护机制的深入探究，本案例研究将视线从模型的表征伤害转移至服务质量层面的危害。](../../../paper_images/2403.13213/categorieslastlast.png)

![通过 Llama 2 安全防护机制的深入探究，本案例研究将视线从模型的表征伤害转移至服务质量层面的危害。](../../../paper_images/2403.13213/heatmapanswers.png)

![通过 Llama 2 安全防护机制的深入探究，本案例研究将视线从模型的表征伤害转移至服务质量层面的危害。](../../../paper_images/2403.13213/plotmuslimnames.png)

[Arxiv](https://arxiv.org/abs/2403.13213)