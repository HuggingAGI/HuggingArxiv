# 探究具身模型基于LLM在决策层面抵御对抗性攻击的鲁棒性。

发布时间：2024年05月30日

`Agent

这篇论文主要探讨了基于大型语言模型（LLMs）的具身智能代理在面对操纵提示时的鲁棒性问题，并为此构建了一个专门的数据集（EIRAD）来评估这些模型的鲁棒性。论文中提到的具身智能代理、攻击策略、数据集构建以及评估方法等内容，都与Agent的行为和性能评估紧密相关，因此将其归类为Agent。` `机器人技术` `人工智能安全`

> Exploring the Robustness of Decision-Level Through Adversarial Attacks on LLM-Based Embodied Models

# 摘要

> 具身智能赋予代理深刻的感知能力，使其能够精准应对现实世界的挑战。大型语言模型（LLMs）深入解析语言指令，为复杂任务制定计划。基于LLM的具身模型因此提升了代理的信息处理能力。然而，这种结合也带来了新的挑战，尤其是攻击者可以通过操纵提示诱导LLMs产生无关或恶意输出。面对这一挑战，我们发现缺乏全面评估基于LLM的具身模型鲁棒性的多模态数据集。为此，我们专门为鲁棒性评估构建了具身智能机器人攻击数据集（EIRAD），并设计了无目标和有目标两种攻击策略，模拟多样化的攻击场景。在攻击过程中，我们利用BLIP2模型设计了一种新的攻击成功评估方法，以确保攻击效果的准确性。考虑到GCG算法在攻击中的高成本，我们提出了一种基于任务的提示后缀初始化方案，加速了算法的收敛。实验证明，我们的方法在攻击基于LLM的具身模型时具有更高的成功率，揭示了这些模型在决策层面的鲁棒性不足。

> Embodied intelligence empowers agents with a profound sense of perception, enabling them to respond in a manner closely aligned with real-world situations. Large Language Models (LLMs) delve into language instructions with depth, serving a crucial role in generating plans for intricate tasks. Thus, LLM-based embodied models further enhance the agent's capacity to comprehend and process information. However, this amalgamation also ushers in new challenges in the pursuit of heightened intelligence. Specifically, attackers can manipulate LLMs to produce irrelevant or even malicious outputs by altering their prompts. Confronted with this challenge, we observe a notable absence of multi-modal datasets essential for comprehensively evaluating the robustness of LLM-based embodied models. Consequently, we construct the Embodied Intelligent Robot Attack Dataset (EIRAD), tailored specifically for robustness evaluation. Additionally, two attack strategies are devised, including untargeted attacks and targeted attacks, to effectively simulate a range of diverse attack scenarios. At the same time, during the attack process, to more accurately ascertain whether our method is successful in attacking the LLM-based embodied model, we devise a new attack success evaluation method utilizing the BLIP2 model. Recognizing the time and cost-intensive nature of the GCG algorithm in attacks, we devise a scheme for prompt suffix initialization based on various target tasks, thus expediting the convergence process. Experimental results demonstrate that our method exhibits a superior attack success rate when targeting LLM-based embodied models, indicating a lower level of decision-level robustness in these models.

[Arxiv](https://arxiv.org/abs/2405.19802)