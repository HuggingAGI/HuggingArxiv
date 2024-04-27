# 通过从大型语言模型的模拟中进行离线强化学习，培育出知识渊博的代理。

发布时间：2024年04月14日

`Agent` `人工智能`

> Knowledgeable Agents by Offline Reinforcement Learning from Large Language Model Rollouts

# 摘要

> 强化学习（RL）通过与环境的互动数据训练智能体以完成复杂任务，但其效能受限于现有数据的范围。为了打造知识丰富的智能体，一种充满希望的策略是借助大型语言模型（LLMs）的洞见。尽管先前的研究尝试将LLMs与RL结合，两者的无缝融合却因语义差异而面临挑战。本文提出了一种创新方法——语言模型展开的知识智能体（KALM），它能够从LLMs中提取知识，形成智能体可通过离线强化学习轻松掌握的虚拟展开。KALM面临的主要难题是LLM的落地问题，因为LLM主要处理文本数据，而环境数据则常常包含LLM未曾接触过的数值向量。为此，KALM对LLM进行微调，使其能够根据环境数据执行多样化任务，包括将技能的自然语言描述与其对应的展开数据进行双向转换。这一落地过程加深了LLM对环境变化的理解，使其能够产生多样化且富有深意的虚拟展开，这些展开展现了创新技能。在CLEVR-Robot环境中的初步实证评估显示，KALM能够使智能体完成复杂的任务目标重构，并将能力拓展到需要前所未有最优行为的新任务上。KALM在执行未见目标任务时的成功率达到46%，显著超过了基线方法26%的成功率。此外，KALM有效地促进了LLM对环境动态的理解，生成了富有深意的虚拟展开，这些展开不仅反映了新技能，也展示了大型语言模型与强化学习结合的流畅性。

> Reinforcement learning (RL) trains agents to accomplish complex tasks through environmental interaction data, but its capacity is also limited by the scope of the available data. To obtain a knowledgeable agent, a promising approach is to leverage the knowledge from large language models (LLMs). Despite previous studies combining LLMs with RL, seamless integration of the two components remains challenging due to their semantic gap. This paper introduces a novel method, Knowledgeable Agents from Language Model Rollouts (KALM), which extracts knowledge from LLMs in the form of imaginary rollouts that can be easily learned by the agent through offline reinforcement learning methods. The primary challenge of KALM lies in LLM grounding, as LLMs are inherently limited to textual data, whereas environmental data often comprise numerical vectors unseen to LLMs. To address this, KALM fine-tunes the LLM to perform various tasks based on environmental data, including bidirectional translation between natural language descriptions of skills and their corresponding rollout data. This grounding process enhances the LLM's comprehension of environmental dynamics, enabling it to generate diverse and meaningful imaginary rollouts that reflect novel skills. Initial empirical evaluations on the CLEVR-Robot environment demonstrate that KALM enables agents to complete complex rephrasings of task goals and extend their capabilities to novel tasks requiring unprecedented optimal behaviors. KALM achieves a success rate of 46% in executing tasks with unseen goals, substantially surpassing the 26% success rate achieved by baseline methods. Furthermore, KALM effectively enables the LLM to comprehend environmental dynamics, resulting in the generation of meaningful imaginary rollouts that reflect novel skills and demonstrate the seamless integration of large language models and reinforcement learning.

![通过从大型语言模型的模拟中进行离线强化学习，培育出知识渊博的代理。](../../../paper_images/2404.09248/x1.png)

![通过从大型语言模型的模拟中进行离线强化学习，培育出知识渊博的代理。](../../../paper_images/2404.09248/x2.png)

![通过从大型语言模型的模拟中进行离线强化学习，培育出知识渊博的代理。](../../../paper_images/2404.09248/x3.png)

![通过从大型语言模型的模拟中进行离线强化学习，培育出知识渊博的代理。](../../../paper_images/2404.09248/clevr_demo_begin.png)

![通过从大型语言模型的模拟中进行离线强化学习，培育出知识渊博的代理。](../../../paper_images/2404.09248/clevr_demo_end.png)

![通过从大型语言模型的模拟中进行离线强化学习，培育出知识渊博的代理。](../../../paper_images/2404.09248/x4.png)

![通过从大型语言模型的模拟中进行离线强化学习，培育出知识渊博的代理。](../../../paper_images/2404.09248/x5.png)

![通过从大型语言模型的模拟中进行离线强化学习，培育出知识渊博的代理。](../../../paper_images/2404.09248/x6.png)

![通过从大型语言模型的模拟中进行离线强化学习，培育出知识渊博的代理。](../../../paper_images/2404.09248/x7.png)

![通过从大型语言模型的模拟中进行离线强化学习，培育出知识渊博的代理。](../../../paper_images/2404.09248/x8.png)

![通过从大型语言模型的模拟中进行离线强化学习，培育出知识渊博的代理。](../../../paper_images/2404.09248/x9.png)

![通过从大型语言模型的模拟中进行离线强化学习，培育出知识渊博的代理。](../../../paper_images/2404.09248/x10.png)

![通过从大型语言模型的模拟中进行离线强化学习，培育出知识渊博的代理。](../../../paper_images/2404.09248/x11.png)

![通过从大型语言模型的模拟中进行离线强化学习，培育出知识渊博的代理。](../../../paper_images/2404.09248/x12.png)

![通过从大型语言模型的模拟中进行离线强化学习，培育出知识渊博的代理。](../../../paper_images/2404.09248/x13.png)

![通过从大型语言模型的模拟中进行离线强化学习，培育出知识渊博的代理。](../../../paper_images/2404.09248/x14.png)

![通过从大型语言模型的模拟中进行离线强化学习，培育出知识渊博的代理。](../../../paper_images/2404.09248/x15.png)

![通过从大型语言模型的模拟中进行离线强化学习，培育出知识渊博的代理。](../../../paper_images/2404.09248/x16.png)

![通过从大型语言模型的模拟中进行离线强化学习，培育出知识渊博的代理。](../../../paper_images/2404.09248/x17.png)

![通过从大型语言模型的模拟中进行离线强化学习，培育出知识渊博的代理。](../../../paper_images/2404.09248/x18.png)

![通过从大型语言模型的模拟中进行离线强化学习，培育出知识渊博的代理。](../../../paper_images/2404.09248/x19.png)

[Arxiv](https://arxiv.org/abs/2404.09248)