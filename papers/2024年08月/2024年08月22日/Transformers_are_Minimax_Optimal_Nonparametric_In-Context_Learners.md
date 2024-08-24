# Transformer 模型在上下文学习方面表现出色，是非参数学习中的极小极大最优选择。

发布时间：2024年08月22日

`LLM理论` `人工智能` `机器学习`

> Transformers are Minimax Optimal Nonparametric In-Context Learners

# 摘要

> 大型语言模型的上下文学习（ICL）通过少数示范示例学习新任务，效果惊人。本文从统计学习理论视角探讨ICL效率，为深度神经网络与线性注意力层构成的变换器设定近似与泛化误差界限，该变换器预训练于涵盖Besov空间与分段$γ$-光滑类的非参数回归任务。研究表明，充分训练的变换器能通过预训练编码关键基表示，达到甚至超越最小最大最优估计风险。分析涵盖高维与序列数据，明确区分预训练与上下文泛化差距。同时，为元学习者确立信息论下界，关联任务数量与上下文示例，揭示任务多样性与表示学习对ICL的关键作用。

> In-context learning (ICL) of large language models has proven to be a surprisingly effective method of learning a new task from only a few demonstrative examples. In this paper, we study the efficacy of ICL from the viewpoint of statistical learning theory. We develop approximation and generalization error bounds for a transformer composed of a deep neural network and one linear attention layer, pretrained on nonparametric regression tasks sampled from general function spaces including the Besov space and piecewise $γ$-smooth class. We show that sufficiently trained transformers can achieve -- and even improve upon -- the minimax optimal estimation risk in context by encoding the most relevant basis representations during pretraining. Our analysis extends to high-dimensional or sequential data and distinguishes the \emph{pretraining} and \emph{in-context} generalization gaps. Furthermore, we establish information-theoretic lower bounds for meta-learners w.r.t. both the number of tasks and in-context examples. These findings shed light on the roles of task diversity and representation learning for ICL.

[Arxiv](https://arxiv.org/abs/2408.12186)