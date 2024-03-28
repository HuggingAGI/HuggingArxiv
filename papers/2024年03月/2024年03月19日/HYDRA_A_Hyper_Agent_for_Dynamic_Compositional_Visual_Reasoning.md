# HYDRA——专为解决动态组合视觉推理问题而生的超强智能体，它在复杂视觉场景中展现出卓越的推理能力。

发布时间：2024年03月19日

`Agent` `视觉推理`

> HYDRA: A Hyper Agent for Dynamic Compositional Visual Reasoning

# 摘要

> 近期VR技术借助大型VLMs取得了显著进步，但需处理大数据集及如高昂计算成本、有限泛化能力等问题。尽管组合式视觉推理法崭露头角，却过于倚重LLMs中的常识知识进行规划与推理，忽视了决策对视觉推理过程的实际影响，易导致误差或流程失败。为此，我们推出了一款名为HYDRA的创新框架，它是一个灵活多阶段的动态组合式视觉推理系统，专为实现稳定渐进的一般推理能力而设计。HYDRA由三大核心模块构成：规划器、充当智能控制器的RL代理，以及推理器。其中，规划器和推理器巧妙运用LLM分别生成指导示例和可执行指令，而RL代理则通过反馈循环记忆的历史状态信息，实时与各模块互动，作出选取最优指导示例的高级决策。这样的自适应设计使得HYDRA能够在推理过程中依据过往反馈不断调整行动策略，产出更为精准的推理结果，进而全面提升其整体效能。经验证，此框架在四个广泛应用的数据集上，在多种VR任务中均展现出业界领先的性能水平。

> Recent advances in visual reasoning (VR), particularly with the aid of Large Vision-Language Models (VLMs), show promise but require access to large-scale datasets and face challenges such as high computational costs and limited generalization capabilities. Compositional visual reasoning approaches have emerged as effective strategies; however, they heavily rely on the commonsense knowledge encoded in Large Language Models (LLMs) to perform planning, reasoning, or both, without considering the effect of their decisions on the visual reasoning process, which can lead to errors or failed procedures. To address these challenges, we introduce HYDRA, a multi-stage dynamic compositional visual reasoning framework designed for reliable and incrementally progressive general reasoning. HYDRA integrates three essential modules: a planner, a Reinforcement Learning (RL) agent serving as a cognitive controller, and a reasoner. The planner and reasoner modules utilize an LLM to generate instruction samples and executable code from the selected instruction, respectively, while the RL agent dynamically interacts with these modules, making high-level decisions on selection of the best instruction sample given information from the historical state stored through a feedback loop. This adaptable design enables HYDRA to adjust its actions based on previous feedback received during the reasoning process, leading to more reliable reasoning outputs and ultimately enhancing its overall effectiveness. Our framework demonstrates state-of-the-art performance in various VR tasks on four different widely-used datasets.

[Arxiv](https://arxiv.org/abs/2403.12884)