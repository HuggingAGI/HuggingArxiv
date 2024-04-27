# 通过利用大型语言模型的离线强化学习，我们培育出了见多识广的智能代理。

发布时间：2024年04月14日

`Agent` `人工智能`

> Knowledgeable Agents by Offline Reinforcement Learning from Large Language Model Rollouts

# 摘要

> 强化学习通过与环境的互动数据训练智能体以完成复杂任务，但其所处理的数据量也限制了其能力。要打造一个知识丰富的智能体，一个充满希望的途径是借助大型语言模型（LLMs）的洞见。尽管先前研究已尝试将LLMs与强化学习结合，两者之间的语义差异使得它们的完美融合颇具挑战。本文提出了一种创新方法——语言模型展开的知识智能体（KALM），它能够从LLMs中提取知识，形成易于智能体通过离线强化学习掌握的虚拟展开。KALM面临的主要难题是如何让LLMs与环境数据相匹配，因为LLMs通常只处理文本数据，而环境数据往往包含LLMs未曾接触过的数值向量。为此，KALM对LLMs进行微调，使其能够根据环境数据执行多样化任务，包括技能的自然语言描述与相应的展开数据之间的双向转换。这一匹配过程加深了LLMs对环境变化的理解，使其能够产生多样化且富有洞见的虚拟展开，反映出创新技能。在CLEVR-Robot环境上的初步实证评估显示，KALM能够使智能体完成复杂的任务目标重构，并将其能力拓展到需要全新最优行为的新任务上。KALM在执行未见目标任务时的成功率达到46%，显著超过了基线方法的26%。此外，KALM有效地促进了LLMs对环境动态的理解，生成了富有意义且反映新技能的虚拟展开，实现了大型语言模型与强化学习的和谐融合。

> Reinforcement learning (RL) trains agents to accomplish complex tasks through environmental interaction data, but its capacity is also limited by the scope of the available data. To obtain a knowledgeable agent, a promising approach is to leverage the knowledge from large language models (LLMs). Despite previous studies combining LLMs with RL, seamless integration of the two components remains challenging due to their semantic gap. This paper introduces a novel method, Knowledgeable Agents from Language Model Rollouts (KALM), which extracts knowledge from LLMs in the form of imaginary rollouts that can be easily learned by the agent through offline reinforcement learning methods. The primary challenge of KALM lies in LLM grounding, as LLMs are inherently limited to textual data, whereas environmental data often comprise numerical vectors unseen to LLMs. To address this, KALM fine-tunes the LLM to perform various tasks based on environmental data, including bidirectional translation between natural language descriptions of skills and their corresponding rollout data. This grounding process enhances the LLM's comprehension of environmental dynamics, enabling it to generate diverse and meaningful imaginary rollouts that reflect novel skills. Initial empirical evaluations on the CLEVR-Robot environment demonstrate that KALM enables agents to complete complex rephrasings of task goals and extend their capabilities to novel tasks requiring unprecedented optimal behaviors. KALM achieves a success rate of 46% in executing tasks with unseen goals, substantially surpassing the 26% success rate achieved by baseline methods. Furthermore, KALM effectively enables the LLM to comprehend environmental dynamics, resulting in the generation of meaningful imaginary rollouts that reflect novel skills and demonstrate the seamless integration of large language models and reinforcement learning.

![通过利用大型语言模型的离线强化学习，我们培育出了见多识广的智能代理。](../../../paper_images/2404.09248/x1.png)

![通过利用大型语言模型的离线强化学习，我们培育出了见多识广的智能代理。](../../../paper_images/2404.09248/x2.png)

![通过利用大型语言模型的离线强化学习，我们培育出了见多识广的智能代理。](../../../paper_images/2404.09248/x3.png)

![通过利用大型语言模型的离线强化学习，我们培育出了见多识广的智能代理。](../../../paper_images/2404.09248/clevr_demo_begin.png)

![通过利用大型语言模型的离线强化学习，我们培育出了见多识广的智能代理。](../../../paper_images/2404.09248/clevr_demo_end.png)

![通过利用大型语言模型的离线强化学习，我们培育出了见多识广的智能代理。](../../../paper_images/2404.09248/x4.png)

![通过利用大型语言模型的离线强化学习，我们培育出了见多识广的智能代理。](../../../paper_images/2404.09248/x5.png)

![通过利用大型语言模型的离线强化学习，我们培育出了见多识广的智能代理。](../../../paper_images/2404.09248/x6.png)

![通过利用大型语言模型的离线强化学习，我们培育出了见多识广的智能代理。](../../../paper_images/2404.09248/x7.png)

![通过利用大型语言模型的离线强化学习，我们培育出了见多识广的智能代理。](../../../paper_images/2404.09248/x8.png)

![通过利用大型语言模型的离线强化学习，我们培育出了见多识广的智能代理。](../../../paper_images/2404.09248/x9.png)

![通过利用大型语言模型的离线强化学习，我们培育出了见多识广的智能代理。](../../../paper_images/2404.09248/x10.png)

![通过利用大型语言模型的离线强化学习，我们培育出了见多识广的智能代理。](../../../paper_images/2404.09248/x11.png)

![通过利用大型语言模型的离线强化学习，我们培育出了见多识广的智能代理。](../../../paper_images/2404.09248/x12.png)

![通过利用大型语言模型的离线强化学习，我们培育出了见多识广的智能代理。](../../../paper_images/2404.09248/x13.png)

![通过利用大型语言模型的离线强化学习，我们培育出了见多识广的智能代理。](../../../paper_images/2404.09248/x14.png)

![通过利用大型语言模型的离线强化学习，我们培育出了见多识广的智能代理。](../../../paper_images/2404.09248/x15.png)

![通过利用大型语言模型的离线强化学习，我们培育出了见多识广的智能代理。](../../../paper_images/2404.09248/x16.png)

![通过利用大型语言模型的离线强化学习，我们培育出了见多识广的智能代理。](../../../paper_images/2404.09248/x17.png)

![通过利用大型语言模型的离线强化学习，我们培育出了见多识广的智能代理。](../../../paper_images/2404.09248/x18.png)

![通过利用大型语言模型的离线强化学习，我们培育出了见多识广的智能代理。](../../../paper_images/2404.09248/x19.png)

[Arxiv](https://arxiv.org/abs/2404.09248)