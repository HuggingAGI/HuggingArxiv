# 利用大型语言模型，强化推荐系统的个性化提示

发布时间：2024年07月24日

`LLM应用` `个性化推荐` `人工智能`

> Reinforced Prompt Personalization for Recommendation with Large Language Models

# 摘要

> 设计精妙的提示能助力 LLMs 深入洞察用户喜好，并凭借其意图解读与知识运用的双重优势，精准推荐。然而，当前研究多聚焦于任务导向的提示设计，采用包含角色扮演、历史记录、推理引导及输出格式四种模式的固定模板，统一应用于所有用户。这种便捷之法却忽视了用户间的独特性，可能导致用户偏好捕捉的偏差。为此，我们创新提出实例导向的提示策略，为每位用户量身定制个性化提示，并借助强化提示个性化（RPP）技术，通过多代理强化学习（MARL）精细调整四种模式。RPP 将提示个性化视为在四种模式间全局择优，而非逐字逐句的微调，确保了提示的高质量。同时，RPP 针对特定推荐任务，从多角度精心雕琢每种模式的表达方式。此外，RPP+ 的提出，进一步通过迭代过程中的动态动作优化，提升了动作空间的灵活性。实验证明，RPP/RPP+ 在多数据集的排名任务中表现卓越，超越了传统推荐模型及基于提示的其他方法，凸显了实例导向提示在 LLMs 推荐领域的关键作用，并证实了 RPP/RPP+ 的实效性。代码已公开于 https://github.com/maowenyu-11/RPP。

> Designing effective prompts can empower LLMs to understand user preferences and provide recommendations by leveraging LLMs' intent comprehension and knowledge utilization capabilities. However, existing research predominantly concentrates on task-wise prompting, developing fixed prompt templates composed of four patterns (i.e., role-playing, history records, reasoning guidance, and output format) and applying them to all users for a given task. Although convenient, task-wise prompting overlooks individual user differences, leading to potential mismatches in capturing user preferences. To address it, we introduce the concept of instance-wise prompting to personalize discrete prompts for individual users and propose Reinforced Prompt Personalization (RPP) to optimize the four patterns in prompts using multi-agent reinforcement learning (MARL). To boost efficiency, RPP formulates prompt personalization as selecting optimal sentences holistically across the four patterns, rather than optimizing word-by-word. To ensure the quality of prompts, RPP meticulously crafts diverse expressions for each of the four patterns, considering multiple analytical perspectives for specific recommendation tasks. In addition to RPP, our proposal of RPP+ aims to enhance the scalability of action space by dynamically refining actions with LLMs throughout the iterative process. We evaluate the effectiveness of RPP/RPP+ in ranking tasks over various datasets. Experimental results demonstrate the superiority of RPP/RPP+ over traditional recommender models, few-shot methods, and other prompt-based methods, underscoring the significance of instance-wise prompting for LLMs in recommendation tasks and validating the effectiveness of RPP/RPP+. Our code is available at https://github.com/maowenyu-11/RPP.

![利用大型语言模型，强化推荐系统的个性化提示](../../../paper_images/2407.17115/x1.png)

![利用大型语言模型，强化推荐系统的个性化提示](../../../paper_images/2407.17115/x2.png)

![利用大型语言模型，强化推荐系统的个性化提示](../../../paper_images/2407.17115/x3.png)

![利用大型语言模型，强化推荐系统的个性化提示](../../../paper_images/2407.17115/x4.png)

![利用大型语言模型，强化推荐系统的个性化提示](../../../paper_images/2407.17115/x5.png)

![利用大型语言模型，强化推荐系统的个性化提示](../../../paper_images/2407.17115/x6.png)

![利用大型语言模型，强化推荐系统的个性化提示](../../../paper_images/2407.17115/x7.png)

![利用大型语言模型，强化推荐系统的个性化提示](../../../paper_images/2407.17115/x8.png)

![利用大型语言模型，强化推荐系统的个性化提示](../../../paper_images/2407.17115/x9.png)

![利用大型语言模型，强化推荐系统的个性化提示](../../../paper_images/2407.17115/x10.png)

![利用大型语言模型，强化推荐系统的个性化提示](../../../paper_images/2407.17115/x11.png)

![利用大型语言模型，强化推荐系统的个性化提示](../../../paper_images/2407.17115/x12.png)

![利用大型语言模型，强化推荐系统的个性化提示](../../../paper_images/2407.17115/x13.png)

![利用大型语言模型，强化推荐系统的个性化提示](../../../paper_images/2407.17115/x14.png)

[Arxiv](https://arxiv.org/abs/2407.17115)