# 本研究致力于探索如何让大型语言模型在推荐场景中实现高效且有效的遗忘学习，即针对已学习内容进行有效“反学习”。（注：此处将“unlearning”翻译为“遗忘学习”或“反学习”，是因为在AI领域中，“unlearning”通常指的是对模型已经学到的内容进行去除或更新的过程。）

发布时间：2024年03月06日

`LLM应用`

> Towards Efficient and Effective Unlearning of Large Language Models for Recommendation

# 摘要

> 随着LLMs的重大突破，一种极具潜力的研究路径应运而生，即将LLMs应用于推荐系统领域，形成LLMRec。LLMRec的成功在于其内嵌的开放世界知识与强大的推理能力，并能通过用户交互数据进行指令调整以获得推荐功能。然而，在保障用户隐私和提升系统实用性方面，LLMRec还需学会有针对性地遗忘特定用户数据，这一过程被称为推荐遗忘。在LLMs的时代背景下，推荐遗忘对LLMRec提出了新的挑战，体现在其难以实现高效、有效遗忘。现有方法往往需耗费大量资源更新LLMRec中的数十亿参数，且在遗忘过程中难免损伤模型原有性能。因此，我们创新性地提出了首个针对LLMRec的高效且有效的遗忘解决方案——\textbf{E2URec}。E2URec通过仅针对性地更新少量附加LoRA参数显著提升了遗忘效率，并借助教师-学生框架，通过维护多组教师网络指导遗忘进程，从而改善了遗忘效果。大量的实验表明，E2URec在两个实际应用场景的数据集上均超越了当前最优基准方法，尤其值得一提的是，E2URec能够在不损害推荐性能的前提下高效地遗忘特定数据。项目源代码已上传至\url{https://github.com/justarter/E2URec}。

> The significant advancements in large language models (LLMs) give rise to a promising research direction, i.e., leveraging LLMs as recommenders (LLMRec). The efficacy of LLMRec arises from the open-world knowledge and reasoning capabilities inherent in LLMs. LLMRec acquires the recommendation capabilities through instruction tuning based on user interaction data. However, in order to protect user privacy and optimize utility, it is also crucial for LLMRec to intentionally forget specific user data, which is generally referred to as recommendation unlearning. In the era of LLMs, recommendation unlearning poses new challenges for LLMRec in terms of \textit{inefficiency} and \textit{ineffectiveness}. Existing unlearning methods require updating billions of parameters in LLMRec, which is costly and time-consuming. Besides, they always impact the model utility during the unlearning process. To this end, we propose \textbf{E2URec}, the first \underline{E}fficient and \underline{E}ffective \underline{U}nlearning method for LLM\underline{Rec}. Our proposed E2URec enhances the unlearning efficiency by updating only a few additional LoRA parameters, and improves the unlearning effectiveness by employing a teacher-student framework, where we maintain multiple teacher networks to guide the unlearning process. Extensive experiments show that E2URec outperforms state-of-the-art baselines on two real-world datasets. Specifically, E2URec can efficiently forget specific data without affecting recommendation performance. The source code is at \url{https://github.com/justarter/E2URec}.

[Arxiv](https://arxiv.org/abs/2403.03536)