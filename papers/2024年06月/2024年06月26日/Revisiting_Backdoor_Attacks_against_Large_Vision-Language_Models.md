# 再探大型视觉-语言模型遭遇的后门攻击

发布时间：2024年06月26日

`Agent

理由：这篇论文主要关注的是大型视觉-语言模型（LVLMs）在指令调优过程中可能遭受的后门攻击，以及这些攻击在不同领域间的泛化能力。研究的重点在于如何改进攻击策略以提高其在跨领域场景中的成功率，这涉及到对模型行为的操纵和控制，符合Agent类研究的特征，即关注模型作为自主实体的行为和决策过程。此外，论文中提到的后门攻击和泛化性分析，更多地是在探讨模型在特定条件下的行为，而不是理论研究或应用开发，因此更适合归类为Agent。` `人工智能安全` `图像处理`

> Revisiting Backdoor Attacks against Large Vision-Language Models

# 摘要

> 指令调优虽提升了大型视觉-语言模型（LVLMs）的性能，却也因开放性而潜藏后门攻击的风险。以往研究多聚焦于封闭环境，未考虑实际领域差异对攻击效果的影响。本研究首次实证分析了LVLMs在指令调优中后门攻击的泛化能力，并指出多数策略在实际应用中的局限。我们评估了六种典型攻击在不同LVLMs上的图像标题任务中的泛化性，考虑了视觉与文本领域的差异。研究发现，攻击泛化性受后门触发器与特定图像/模型无关性的正面影响，以及触发模式的相关性。基于此，我们改进了现有攻击，显著提高了跨领域场景的泛化性（攻击成功率提升86%）。尤为重要的是，即使不接触指令数据集，多模态指令集也能以极低污染率（0.2%）被成功植入后门，攻击成功率高达97%以上。这表明，即使是传统简单的后门策略，也对LVLMs构成重大威胁，亟需更多关注与深入研究。

> Instruction tuning enhances large vision-language models (LVLMs) but raises security risks through potential backdoor attacks due to their openness. Previous backdoor studies focus on enclosed scenarios with consistent training and testing instructions, neglecting the practical domain gaps that could affect attack effectiveness. This paper empirically examines the generalizability of backdoor attacks during the instruction tuning of LVLMs for the first time, revealing certain limitations of most backdoor strategies in practical scenarios. We quantitatively evaluate the generalizability of six typical backdoor attacks on image caption benchmarks across multiple LVLMs, considering both visual and textual domain offsets. Our findings indicate that attack generalizability is positively correlated with the backdoor trigger's irrelevance to specific images/models and the preferential correlation of the trigger pattern. Additionally, we modify existing backdoor attacks based on the above key observations, demonstrating significant improvements in cross-domain scenario generalizability (+86% attack success rate). Notably, even without access to the instruction datasets, a multimodal instruction set can be successfully poisoned with a very low poisoning rate (0.2%), achieving an attack success rate of over 97%. This paper underscores that even simple traditional backdoor strategies pose a serious threat to LVLMs, necessitating more attention and in-depth research.

![再探大型视觉-语言模型遭遇的后门攻击](../../../paper_images/2406.18844/x1.png)

![再探大型视觉-语言模型遭遇的后门攻击](../../../paper_images/2406.18844/x2.png)

![再探大型视觉-语言模型遭遇的后门攻击](../../../paper_images/2406.18844/x3.png)

![再探大型视觉-语言模型遭遇的后门攻击](../../../paper_images/2406.18844/x4.png)

![再探大型视觉-语言模型遭遇的后门攻击](../../../paper_images/2406.18844/x5.png)

![再探大型视觉-语言模型遭遇的后门攻击](../../../paper_images/2406.18844/x6.png)

![再探大型视觉-语言模型遭遇的后门攻击](../../../paper_images/2406.18844/x7.png)

![再探大型视觉-语言模型遭遇的后门攻击](../../../paper_images/2406.18844/x8.png)

![再探大型视觉-语言模型遭遇的后门攻击](../../../paper_images/2406.18844/x9.png)

[Arxiv](https://arxiv.org/abs/2406.18844)