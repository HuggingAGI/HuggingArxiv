# 轨迹增强语言模型（Traj-LLM）：探索预训练大型语言模型在轨迹预测领域的创新应用

发布时间：2024年05月08日

`Agent

这篇论文主要探讨了在自动驾驶领域中，如何利用大型语言模型（LLMs）来预测动态交通参与者的未来轨迹。它提出了一种名为Traj-LLM的方法，该方法通过稀疏上下文编码将代理与场景特征转化为LLMs可理解的形式，并利用LLMs的深层理解力来捕捉高级场景知识和交互信息。此外，论文还引入了车道感知概率学习和多模态拉普拉斯解码器来增强场景理解和实现多模态预测。因此，这篇论文更符合Agent分类，因为它关注的是如何利用LLMs来增强自动驾驶系统中的代理（Agent）的预测能力。` `自动驾驶` `交通预测`

> Traj-LLM: A New Exploration for Empowering Trajectory Prediction with Pre-trained Large Language Models

# 摘要

> 在自动驾驶领域，预测动态交通参与者的未来轨迹是一项基石任务。尽管已有研究取得了显著的性能提升，但在场景认知和复杂交通语义的理解上仍有差距。本文提出的Traj-LLM，首次尝试利用大型语言模型（LLMs），无需繁琐的提示工程，即可从过往轨迹和场景语义中预测未来运动。通过稀疏上下文编码，Traj-LLM将代理与场景特征转化为LLMs可理解的形式，进而挖掘LLMs的深层理解力，捕捉高级场景知识和交互信息。模仿人类对车道的自然关注，我们引入了车道感知概率学习，由创新的Mamba模块驱动，以增强场景理解。最后，我们设计了多模态拉普拉斯解码器，实现与场景相符的多模态预测。实验证明，Traj-LLM凭借LLMs的深厚知识库和理解力，以及车道感知学习，在各项评估中超越了现有技术。更令人瞩目的是，仅用一半数据，Traj-LLM就超越了多数全数据基准。本研究为轨迹预测任务注入了LLMs的高级能力，开辟了一种更为通用和灵活的代理运动预测新途径。

> Predicting the future trajectories of dynamic traffic actors is a cornerstone task in autonomous driving. Though existing notable efforts have resulted in impressive performance improvements, a gap persists in scene cognitive and understanding of the complex traffic semantics. This paper proposes Traj-LLM, the first to investigate the potential of using Large Language Models (LLMs) without explicit prompt engineering to generate future motion from agents' past/observed trajectories and scene semantics. Traj-LLM starts with sparse context joint coding to dissect the agent and scene features into a form that LLMs understand. On this basis, we innovatively explore LLMs' powerful comprehension abilities to capture a spectrum of high-level scene knowledge and interactive information. Emulating the human-like lane focus cognitive function and enhancing Traj-LLM's scene comprehension, we introduce lane-aware probabilistic learning powered by the pioneering Mamba module. Finally, a multi-modal Laplace decoder is designed to achieve scene-compliant multi-modal predictions. Extensive experiments manifest that Traj-LLM, fortified by LLMs' strong prior knowledge and understanding prowess, together with lane-aware probability learning, outstrips state-of-the-art methods across evaluation metrics. Moreover, the few-shot analysis further substantiates Traj-LLM's performance, wherein with just 50% of the dataset, it outperforms the majority of benchmarks relying on complete data utilization. This study explores equipping the trajectory prediction task with advanced capabilities inherent in LLMs, furnishing a more universal and adaptable solution for forecasting agent motion in a new way.

[Arxiv](https://arxiv.org/abs/2405.04909)