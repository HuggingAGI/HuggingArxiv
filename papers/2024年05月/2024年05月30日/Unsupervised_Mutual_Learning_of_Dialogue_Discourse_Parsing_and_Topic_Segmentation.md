# 对话话语解析与话题分割的无监督相互学习

发布时间：2024年05月30日

`Agent

这篇论文主要关注的是对话系统的发展，特别是在商务领域中面向任务的对话系统。它提出了一种无监督学习框架，用于更好地解析话语和主题结构，并通过图神经网络整合修辞结构，以提高对话系统的性能。这种研究更偏向于开发和优化对话系统（Agent），以满足特定任务的需求，而不是专注于LLM的理论研究或应用。因此，将其归类为Agent是合适的。` `对话系统`

> Unsupervised Mutual Learning of Dialogue Discourse Parsing and Topic Segmentation

# 摘要

> 随着大型语言模型（LLMs）的进步，对话系统迎来了新的发展机遇。不同于仅满足用户偏好的ChatGPT类助手模型，面向任务的对话系统在商务领域面临更高要求：它们需在每次对话中精准回应，同时达成任务目标。通过解析话语和主题结构，对话系统能更有效地规划策略。尽管修辞与主题结构同属话语范畴，但以往研究多单独处理或辅助建模，忽视了它们的互动。为此，我们提出了一种无监督学习框架，利用全局与局部联系促进两种结构的相互学习。我们扩展了非相邻话语单元间的主题建模，确保全局结构相关性，并通过图神经网络整合修辞结构，维持局部连贯。实验证明，我们的方法在多个数据集上超越了现有技术。

> The advancement of large language models (LLMs) has propelled the development of dialogue systems. Unlike the popular ChatGPT-like assistant model, which only satisfies the user's preferences, task-oriented dialogue systems have also faced new requirements and challenges in the broader business field. They are expected to provide correct responses at each dialogue turn, at the same time, achieve the overall goal defined by the task. By understanding rhetorical structures and topic structures via topic segmentation and discourse parsing, a dialogue system may do a better planning to achieve both objectives. However, while both structures belong to discourse structure in linguistics, rhetorical structure and topic structure are mostly modeled separately or with one assisting the other in the prior work. The interaction between these two structures has not been considered for joint modeling and mutual learning. Furthermore, unsupervised learning techniques to achieve the above are not well explored. To fill this gap, we propose an unsupervised mutual learning framework of two structures leveraging the global and local connections between them. We extend the topic modeling between non-adjacent discourse units to ensure global structural relevance with rhetorical structures. We also incorporate rhetorical structures into the topic structure through a graph neural network model to ensure local coherence consistency. Finally, we utilize the similarity between the two fused structures for mutual learning. The experimental results demonstrate that our methods outperform all strong baselines on two dialogue rhetorical datasets (STAC and Molweni), as well as dialogue topic datasets (Doc2Dial and TIAGE).

![对话话语解析与话题分割的无监督相互学习](../../../paper_images/2405.19799/rhetorical_sample.png)

![对话话语解析与话题分割的无监督相互学习](../../../paper_images/2405.19799/main2.png)

![对话话语解析与话题分割的无监督相互学习](../../../paper_images/2405.19799/rhe_stac.png)

![对话话语解析与话题分割的无监督相互学习](../../../paper_images/2405.19799/rhe_molweni.png)

![对话话语解析与话题分割的无监督相互学习](../../../paper_images/2405.19799/stac_dt.png)

![对话话语解析与话题分割的无监督相互学习](../../../paper_images/2405.19799/molweni_dt.png)

![对话话语解析与话题分割的无监督相互学习](../../../paper_images/2405.19799/top_ana2.png)

![对话话语解析与话题分割的无监督相互学习](../../../paper_images/2405.19799/topic2.png)

![对话话语解析与话题分割的无监督相互学习](../../../paper_images/2405.19799/rhe_before.png)

![对话话语解析与话题分割的无监督相互学习](../../../paper_images/2405.19799/top_before.png)

![对话话语解析与话题分割的无监督相互学习](../../../paper_images/2405.19799/rhe_top_before.png)

![对话话语解析与话题分割的无监督相互学习](../../../paper_images/2405.19799/top_rhe_before.png)

![对话话语解析与话题分割的无监督相互学习](../../../paper_images/2405.19799/rhe_after.png)

![对话话语解析与话题分割的无监督相互学习](../../../paper_images/2405.19799/top_after.png)

![对话话语解析与话题分割的无监督相互学习](../../../paper_images/2405.19799/rhe_top_after.png)

![对话话语解析与话题分割的无监督相互学习](../../../paper_images/2405.19799/top_rhe_after.png)

![对话话语解析与话题分割的无监督相互学习](../../../paper_images/2405.19799/cs1.png)

![对话话语解析与话题分割的无监督相互学习](../../../paper_images/2405.19799/cs2.png)

![对话话语解析与话题分割的无监督相互学习](../../../paper_images/2405.19799/cs3.png)

![对话话语解析与话题分割的无监督相互学习](../../../paper_images/2405.19799/cs5.png)

![对话话语解析与话题分割的无监督相互学习](../../../paper_images/2405.19799/x1.png)

[Arxiv](https://arxiv.org/abs/2405.19799)