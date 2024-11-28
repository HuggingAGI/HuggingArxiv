# DexDiffuser：针对自适应灵巧操作的交互感知式扩散规划

发布时间：2024年11月27日

`Agent` `机器人` `物理交互`

> DexDiffuser: Interaction-aware Diffusion Planning for Adaptive Dexterous Manipulation

# 摘要

> 对于高级机器人技术而言，带有丰富接触交互的灵巧操作至关重要。尽管近来基于扩散的规划方法在较简单的操作任务中颇具潜力，但它们往往会产生不切实际的幽灵状态（比如物体在没有手接触的情况下自动移动），或者在应对复杂的顺序交互时适应性不足。在本研究中，我们推出了 DexDiffuser，这是一个用于自适应灵巧操作的交互感知扩散规划框架。DexDiffuser 通过包含交互前接触对齐和接触后目标导向控制的双阶段扩散过程，对联合状态-动作动态进行建模，实现了目标自适应的通用灵巧操作。此外，我们融入了基于动力学模型的双重引导，并借助大型语言模型生成自动引导功能，增强了物理交互的通用性，还通过语言线索促进了多样化的目标适应。在开门、笔和块重新定向以及锤击等物理交互任务上的实验表明，DexDiffuser 对于训练分布之外的目标成效显著，平均成功率是现有方法的两倍多（59.2%对比29.5%）。我们的框架在 30 度开门任务上的成功率达 70.0%，在笔和块半侧重新定向任务上分别为 40.0%和 36.7%，在锤钉半驱动任务上为 46.7%，凸显了其在丰富接触操作中的稳健性与灵活性。

> Dexterous manipulation with contact-rich interactions is crucial for advanced robotics. While recent diffusion-based planning approaches show promise for simpler manipulation tasks, they often produce unrealistic ghost states (e.g., the object automatically moves without hand contact) or lack adaptability when handling complex sequential interactions. In this work, we introduce DexDiffuser, an interaction-aware diffusion planning framework for adaptive dexterous manipulation. DexDiffuser models joint state-action dynamics through a dual-phase diffusion process which consists of pre-interaction contact alignment and post-contact goal-directed control, enabling goal-adaptive generalizable dexterous manipulation. Additionally, we incorporate dynamics model-based dual guidance and leverage large language models for automated guidance function generation, enhancing generalizability for physical interactions and facilitating diverse goal adaptation through language cues. Experiments on physical interaction tasks such as door opening, pen and block re-orientation, and hammer striking demonstrate DexDiffuser's effectiveness on goals outside training distributions, achieving over twice the average success rate (59.2% vs. 29.5%) compared to existing methods. Our framework achieves 70.0% success on 30-degree door opening, 40.0% and 36.7% on pen and block half-side re-orientation respectively, and 46.7% on hammer nail half drive, highlighting its robustness and flexibility in contact-rich manipulation.

[Arxiv](https://arxiv.org/abs/2411.18562)