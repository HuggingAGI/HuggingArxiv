# 本文探讨了逆运动学在人形机器人抓取任务中的应用，特别是针对具有人形体现的神经机器人代理。

发布时间：2024年04月12日

`Agent` `机器人` `运动规划`

> Inverse Kinematics for Neuro-Robotic Grasping with Humanoid Embodied Agents

# 摘要

> 本文提出了一种创新的零-shot运动规划技术，用户可借此迅速规划出机器人在笛卡尔空间的流畅动作。我们采用基于贝塞尔曲线的笛卡尔规划，并通过神经网络启发的逆运动学（IK）方法CycleIK，将其转换为关节空间轨迹，实现了对各种机器人设计的通用性。在NICO和NICOL两个人形机器人的实际操作中，我们对该运动规划器进行了人类参与的抓取任务评估。核心为大型语言模型（LLM）的具身代理被部署，我们将其从NICOL扩展至NICO。该代理能够执行一系列具体的物理动作，同时允许用户通过语音指令操控多种不同的机器人。我们为其动作库新增了一个抓取动作，使得家庭物品的精确操控成为可能。在模拟环境中，CycleIK方法与当前流行的数值IK求解器和神经IK方法相比，展现出了不相上下甚至更优的性能，尤其是在算法运行时间极短的情况下。此外，该抓取动作在NICO和NICOL机器人上的成功抓取率达到了72%至82%。

> This paper introduces a novel zero-shot motion planning method that allows users to quickly design smooth robot motions in Cartesian space. A Bézier curve-based Cartesian plan is transformed into a joint space trajectory by our neuro-inspired inverse kinematics (IK) method CycleIK, for which we enable platform independence by scaling it to arbitrary robot designs. The motion planner is evaluated on the physical hardware of the two humanoid robots NICO and NICOL in a human-in-the-loop grasping scenario. Our method is deployed with an embodied agent that is a large language model (LLM) at its core. We generalize the embodied agent, that was introduced for NICOL, to also be embodied by NICO. The agent can execute a discrete set of physical actions and allows the user to verbally instruct various different robots. We contribute a grasping primitive to its action space that allows for precise manipulation of household objects. The new CycleIK method is compared to popular numerical IK solvers and state-of-the-art neural IK methods in simulation and is shown to be competitive with or outperform all evaluated methods when the algorithm runtime is very short. The grasping primitive is evaluated on both NICOL and NICO robots with a reported grasp success of 72% to 82% for each robot, respectively.

![本文探讨了逆运动学在人形机器人抓取任务中的应用，特别是针对具有人形体现的神经机器人代理。](../../../paper_images/2404.08825/x1.jpg)

![本文探讨了逆运动学在人形机器人抓取任务中的应用，特别是针对具有人形体现的神经机器人代理。](../../../paper_images/2404.08825/generator_alt_.png)

![本文探讨了逆运动学在人形机器人抓取任务中的应用，特别是针对具有人形体现的神经机器人代理。](../../../paper_images/2404.08825/cycle_ik_overview__.png)

![本文探讨了逆运动学在人形机器人抓取任务中的应用，特别是针对具有人形体现的神经机器人代理。](../../../paper_images/2404.08825/nico_trajectory_top_.png)

![本文探讨了逆运动学在人形机器人抓取任务中的应用，特别是针对具有人形体现的神经机器人代理。](../../../paper_images/2404.08825/nico_nicol_grasp_success_alt___.png)

[Arxiv](https://arxiv.org/abs/2404.08825)