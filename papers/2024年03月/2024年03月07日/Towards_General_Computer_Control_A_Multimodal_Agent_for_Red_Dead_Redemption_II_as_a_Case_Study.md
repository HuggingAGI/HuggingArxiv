# [为了探索通用计算机控制的可能性，我们以《荒野大镖客2》为例，设计并研发了一个多模态智能体进行深度探究。通过该游戏作为案例研究，旨在揭示多模态智能体在复杂环境下的控制能力与适应性。](https://arxiv.org/abs/2403.03186)

发布时间：2024年03月07日

`Agent` `人工智能`

> Towards General Computer Control: A Multimodal Agent for Red Dead Redemption II as a Case Study

> 虽然现有大型模型及尖端工具支撑的基础智能体在特定任务和场景中表现出色，但在面对迥异场景时，由于观察与行动的巨大差异，它们往往难以适应。为此，本研究提出了通用计算机控制（GCC）设定，致力于构建一种能以类似人机交互方式，仅凭计算机屏幕图像（甚至结合音频）输入就能执行各种计算机任务、输出精准键盘和鼠标操作的基础智能体。实现GCC的关键难题主要包括四点：一是处理多模态观测信息进行决策；二是确保键盘鼠标操作的精准控制；三是具备长时记忆与推理能力；四是拥有高效的探索学习和自我提升机制。因此，我们创新设计了一个名为“摇篮”的智能体框架，它包含了六大核心模块：信息采集以提取多模态信息；自我反悔回顾过往经验；任务推理选取最优下一步；技能精选针对具体任务生成和更新所需技能；动作策划制定精确的键盘鼠标操作指令；记忆系统存储和检索以往经历及已掌握技能。为了验证“摇篮”的泛化性和自我完善性，我们将其应用于复杂AAA级游戏《荒野大镖客：救赎2》中，标志着向极具挑战性的GCC目标迈出了试探性的第一步。据我们了解，这项工作首开先河，让基于LMM的智能体能在几乎不依赖预先知识和资源的情况下，在复杂AAA游戏中跟随主线剧情并顺利完成实际任务。项目网址为https://baai-agents.github.io/Cradle/。

> Despite the success in specific tasks and scenarios, existing foundation agents, empowered by large models (LMs) and advanced tools, still cannot generalize to different scenarios, mainly due to dramatic differences in the observations and actions across scenarios. In this work, we propose the General Computer Control (GCC) setting: building foundation agents that can master any computer task by taking only screen images (and possibly audio) of the computer as input, and producing keyboard and mouse operations as output, similar to human-computer interaction. The main challenges of achieving GCC are: 1) the multimodal observations for decision-making, 2) the requirements of accurate control of keyboard and mouse, 3) the need for long-term memory and reasoning, and 4) the abilities of efficient exploration and self-improvement. To target GCC, we introduce Cradle, an agent framework with six main modules, including: 1) information gathering to extract multi-modality information, 2) self-reflection to rethink past experiences, 3) task inference to choose the best next task, 4) skill curation for generating and updating relevant skills for given tasks, 5) action planning to generate specific operations for keyboard and mouse control, and 6) memory for storage and retrieval of past experiences and known skills. To demonstrate the capabilities of generalization and self-improvement of Cradle, we deploy it in the complex AAA game Red Dead Redemption II, serving as a preliminary attempt towards GCC with a challenging target. To our best knowledge, our work is the first to enable LMM-based agents to follow the main storyline and finish real missions in complex AAA games, with minimal reliance on prior knowledge or resources. The project website is at https://baai-agents.github.io/Cradle/.

![为了探索通用计算机控制的可能性，我们以《荒野大镖客2》为例，设计并研发了一个多模态智能体进行深度探究。通过该游戏作为案例研究，旨在揭示多模态智能体在复杂环境下的控制能力与适应性。](../../../paper_images/2403.03186/x1.png)

![为了探索通用计算机控制的可能性，我们以《荒野大镖客2》为例，设计并研发了一个多模态智能体进行深度探究。通过该游戏作为案例研究，旨在揭示多模态智能体在复杂环境下的控制能力与适应性。](../../../paper_images/2403.03186/x2.png)

![为了探索通用计算机控制的可能性，我们以《荒野大镖客2》为例，设计并研发了一个多模态智能体进行深度探究。通过该游戏作为案例研究，旨在揭示多模态智能体在复杂环境下的控制能力与适应性。](../../../paper_images/2403.03186/x3.png)

![为了探索通用计算机控制的可能性，我们以《荒野大镖客2》为例，设计并研发了一个多模态智能体进行深度探究。通过该游戏作为案例研究，旨在揭示多模态智能体在复杂环境下的控制能力与适应性。](../../../paper_images/2403.03186/x4.png)

![为了探索通用计算机控制的可能性，我们以《荒野大镖客2》为例，设计并研发了一个多模态智能体进行深度探究。通过该游戏作为案例研究，旨在揭示多模态智能体在复杂环境下的控制能力与适应性。](../../../paper_images/2403.03186/x5.png)

![为了探索通用计算机控制的可能性，我们以《荒野大镖客2》为例，设计并研发了一个多模态智能体进行深度探究。通过该游戏作为案例研究，旨在揭示多模态智能体在复杂环境下的控制能力与适应性。](../../../paper_images/2403.03186/x6.png)

![为了探索通用计算机控制的可能性，我们以《荒野大镖客2》为例，设计并研发了一个多模态智能体进行深度探究。通过该游戏作为案例研究，旨在揭示多模态智能体在复杂环境下的控制能力与适应性。](../../../paper_images/2403.03186/x7.png)

![为了探索通用计算机控制的可能性，我们以《荒野大镖客2》为例，设计并研发了一个多模态智能体进行深度探究。通过该游戏作为案例研究，旨在揭示多模态智能体在复杂环境下的控制能力与适应性。](../../../paper_images/2403.03186/x8.png)

![为了探索通用计算机控制的可能性，我们以《荒野大镖客2》为例，设计并研发了一个多模态智能体进行深度探究。通过该游戏作为案例研究，旨在揭示多模态智能体在复杂环境下的控制能力与适应性。](../../../paper_images/2403.03186/x9.png)

![为了探索通用计算机控制的可能性，我们以《荒野大镖客2》为例，设计并研发了一个多模态智能体进行深度探究。通过该游戏作为案例研究，旨在揭示多模态智能体在复杂环境下的控制能力与适应性。](../../../paper_images/2403.03186/x10.png)

![为了探索通用计算机控制的可能性，我们以《荒野大镖客2》为例，设计并研发了一个多模态智能体进行深度探究。通过该游戏作为案例研究，旨在揭示多模态智能体在复杂环境下的控制能力与适应性。](../../../paper_images/2403.03186/x11.png)

![为了探索通用计算机控制的可能性，我们以《荒野大镖客2》为例，设计并研发了一个多模态智能体进行深度探究。通过该游戏作为案例研究，旨在揭示多模态智能体在复杂环境下的控制能力与适应性。](../../../paper_images/2403.03186/x12.png)

![为了探索通用计算机控制的可能性，我们以《荒野大镖客2》为例，设计并研发了一个多模态智能体进行深度探究。通过该游戏作为案例研究，旨在揭示多模态智能体在复杂环境下的控制能力与适应性。](../../../paper_images/2403.03186/x13.png)

![为了探索通用计算机控制的可能性，我们以《荒野大镖客2》为例，设计并研发了一个多模态智能体进行深度探究。通过该游戏作为案例研究，旨在揭示多模态智能体在复杂环境下的控制能力与适应性。](../../../paper_images/2403.03186/01_Follow_Dutch.jpeg)

![为了探索通用计算机控制的可能性，我们以《荒野大镖客2》为例，设计并研发了一个多模态智能体进行深度探究。通过该游戏作为案例研究，旨在揭示多模态智能体在复杂环境下的控制能力与适应性。](../../../paper_images/2403.03186/02_Hitch_horse.jpeg)

![为了探索通用计算机控制的可能性，我们以《荒野大镖客2》为例，设计并研发了一个多模态智能体进行深度探究。通过该游戏作为案例研究，旨在揭示多模态智能体在复杂环境下的控制能力与适应性。](../../../paper_images/2403.03186/03_Go_to_shed.jpeg)

![为了探索通用计算机控制的可能性，我们以《荒野大镖客2》为例，设计并研发了一个多模态智能体进行深度探究。通过该游戏作为案例研究，旨在揭示多模态智能体在复杂环境下的控制能力与适应性。](../../../paper_images/2403.03186/04_Choose_weapon.jpeg)

![为了探索通用计算机控制的可能性，我们以《荒野大镖客2》为例，设计并研发了一个多模态智能体进行深度探究。通过该游戏作为案例研究，旨在揭示多模态智能体在复杂环境下的控制能力与适应性。](../../../paper_images/2403.03186/05_Protect_Dutch.jpeg)

![为了探索通用计算机控制的可能性，我们以《荒野大镖客2》为例，设计并研发了一个多模态智能体进行深度探究。通过该游戏作为案例研究，旨在揭示多模态智能体在复杂环境下的控制能力与适应性。](../../../paper_images/2403.03186/06_Search_house.jpeg)

![为了探索通用计算机控制的可能性，我们以《荒野大镖客2》为例，设计并研发了一个多模态智能体进行深度探究。通过该游戏作为案例研究，旨在揭示多模态智能体在复杂环境下的控制能力与适应性。](../../../paper_images/2403.03186/07_Eat_something.jpeg)

![为了探索通用计算机控制的可能性，我们以《荒野大镖客2》为例，设计并研发了一个多模态智能体进行深度探究。通过该游戏作为案例研究，旨在揭示多模态智能体在复杂环境下的控制能力与适应性。](../../../paper_images/2403.03186/08_Investigate_barn.jpeg)

![为了探索通用计算机控制的可能性，我们以《荒野大镖客2》为例，设计并研发了一个多模态智能体进行深度探究。通过该游戏作为案例研究，旨在揭示多模态智能体在复杂环境下的控制能力与适应性。](../../../paper_images/2403.03186/09_Defeat_ODriscoll.jpeg)

![为了探索通用计算机控制的可能性，我们以《荒野大镖客2》为例，设计并研发了一个多模态智能体进行深度探究。通过该游戏作为案例研究，旨在揭示多模态智能体在复杂环境下的控制能力与适应性。](../../../paper_images/2403.03186/10_Pick_up_equipment.jpeg)

![为了探索通用计算机控制的可能性，我们以《荒野大镖客2》为例，设计并研发了一个多模态智能体进行深度探究。通过该游戏作为案例研究，旨在揭示多模态智能体在复杂环境下的控制能力与适应性。](../../../paper_images/2403.03186/11_Lead_horse.jpeg)

![为了探索通用计算机控制的可能性，我们以《荒野大镖客2》为例，设计并研发了一个多模态智能体进行深度探究。通过该游戏作为案例研究，旨在揭示多模态智能体在复杂环境下的控制能力与适应性。](../../../paper_images/2403.03186/12_Follow_Javier.jpeg)

![为了探索通用计算机控制的可能性，我们以《荒野大镖客2》为例，设计并研发了一个多模态智能体进行深度探究。通过该游戏作为案例研究，旨在揭示多模态智能体在复杂环境下的控制能力与适应性。](../../../paper_images/2403.03186/13_Equip_shotgun.jpeg)

![为了探索通用计算机控制的可能性，我们以《荒野大镖客2》为例，设计并研发了一个多模态智能体进行深度探究。通过该游戏作为案例研究，旨在揭示多模态智能体在复杂环境下的控制能力与适应性。](../../../paper_images/2403.03186/14_Look_for_John.jpeg)

![为了探索通用计算机控制的可能性，我们以《荒野大镖客2》为例，设计并研发了一个多模态智能体进行深度探究。通过该游戏作为案例研究，旨在揭示多模态智能体在复杂环境下的控制能力与适应性。](../../../paper_images/2403.03186/15_Shoot_wolves.jpeg)

![为了探索通用计算机控制的可能性，我们以《荒野大镖客2》为例，设计并研发了一个多模态智能体进行深度探究。通过该游戏作为案例研究，旨在揭示多模态智能体在复杂环境下的控制能力与适应性。](../../../paper_images/2403.03186/16_Protect_Javier_from_wolves.jpeg)

![为了探索通用计算机控制的可能性，我们以《荒野大镖客2》为例，设计并研发了一个多模态智能体进行深度探究。通过该游戏作为案例研究，旨在揭示多模态智能体在复杂环境下的控制能力与适应性。](../../../paper_images/2403.03186/17_Find_horse.jpeg)

![为了探索通用计算机控制的可能性，我们以《荒野大镖客2》为例，设计并研发了一个多模态智能体进行深度探究。通过该游戏作为案例研究，旨在揭示多模态智能体在复杂环境下的控制能力与适应性。](../../../paper_images/2403.03186/18_Generate_navigation_to_saloon.jpeg)

![为了探索通用计算机控制的可能性，我们以《荒野大镖客2》为例，设计并研发了一个多模态智能体进行深度探究。通过该游戏作为案例研究，旨在揭示多模态智能体在复杂环境下的控制能力与适应性。](../../../paper_images/2403.03186/19_Go_to_saloon.jpeg)

![为了探索通用计算机控制的可能性，我们以《荒野大镖客2》为例，设计并研发了一个多模态智能体进行深度探究。通过该游戏作为案例研究，旨在揭示多模态智能体在复杂环境下的控制能力与适应性。](../../../paper_images/2403.03186/20_Generate_navigation_to_shop.jpeg)

![为了探索通用计算机控制的可能性，我们以《荒野大镖客2》为例，设计并研发了一个多模态智能体进行深度探究。通过该游戏作为案例研究，旨在揭示多模态智能体在复杂环境下的控制能力与适应性。](../../../paper_images/2403.03186/21_Go_to_shop.jpeg)

![为了探索通用计算机控制的可能性，我们以《荒野大镖客2》为例，设计并研发了一个多模态智能体进行深度探究。通过该游戏作为案例研究，旨在揭示多模态智能体在复杂环境下的控制能力与适应性。](../../../paper_images/2403.03186/22_Enter_shop.jpeg)

![为了探索通用计算机控制的可能性，我们以《荒野大镖客2》为例，设计并研发了一个多模态智能体进行深度探究。通过该游戏作为案例研究，旨在揭示多模态智能体在复杂环境下的控制能力与适应性。](../../../paper_images/2403.03186/23_Talk_to_shopkeeper.jpeg)

![为了探索通用计算机控制的可能性，我们以《荒野大镖客2》为例，设计并研发了一个多模态智能体进行深度探究。通过该游戏作为案例研究，旨在揭示多模态智能体在复杂环境下的控制能力与适应性。](../../../paper_images/2403.03186/24_Buy_target_product.jpeg)

[Arxiv](https://arxiv.org/abs/2403.03186)