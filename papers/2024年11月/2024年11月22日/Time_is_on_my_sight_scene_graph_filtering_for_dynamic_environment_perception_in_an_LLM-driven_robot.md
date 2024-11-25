# 时间尽在掌握：LLM 驱动的机器人动态环境感知中的场景图过滤

发布时间：2024年11月22日

`LLM应用` `机器人` `人机交互`

> Time is on my sight: scene graph filtering for dynamic environment perception in an LLM-driven robot

# 摘要

> 机器人在工作场所、医院和家庭等动态环境中的运用愈发频繁。所以，与机器人的交互得简单直观，机器人的感知要能高效适应人类引发的变化。本文呈现了一种机器人控制架构，应对了人机交互中的关键难题，尤其聚焦于机器人状态表征的动态创建与持续更新。此架构借助大型语言模型整合各类信息源，涵盖自然语言指令、机器人技能表征、感知场景的实时动态语义映射。这让机器人在复杂动态环境中能够展现出灵活且自适应的行为。传统机器人系统往往依赖静态、预先编程的指令和设置，限制了其对动态环境和实时协作的适应能力。相较而言，该架构利用LLM来解读复杂的高级指令，并生成可执行的计划，以强化人机协作。该系统的核心在于感知模块，它运用RGB-D传感器数据生成并持续更新语义场景图，为环境提供详尽且结构化的呈现。采用粒子滤波器确保在动态的真实环境中实现精准的对象定位。规划器模块凭借这一最新的语义图将高级任务拆解为子任务，并将它们与机器人技能（如导航、对象操作（比如，拾取和放置）和移动（比如，前往））相连接。通过融合实时感知、状态跟踪以及LLM驱动的通信和任务规划，该架构在动态环境中提升了适应性、任务效率和人机协作水平。

> Robots are increasingly being used in dynamic environments like workplaces, hospitals, and homes. As a result, interactions with robots must be simple and intuitive, with robots perception adapting efficiently to human-induced changes. This paper presents a robot control architecture that addresses key challenges in human-robot interaction, with a particular focus on the dynamic creation and continuous update of the robot state representation. The architecture uses Large Language Models to integrate diverse information sources, including natural language commands, robotic skills representation, real-time dynamic semantic mapping of the perceived scene. This enables flexible and adaptive robotic behavior in complex, dynamic environments. Traditional robotic systems often rely on static, pre-programmed instructions and settings, limiting their adaptability to dynamic environments and real-time collaboration. In contrast, this architecture uses LLMs to interpret complex, high-level instructions and generate actionable plans that enhance human-robot collaboration. At its core, the system Perception Module generates and continuously updates a semantic scene graph using RGB-D sensor data, providing a detailed and structured representation of the environment. A particle filter is employed to ensure accurate object localization in dynamic, real-world settings. The Planner Module leverages this up-to-date semantic map to break down high-level tasks into sub-tasks and link them to robotic skills such as navigation, object manipulation (e.g., PICK and PLACE), and movement (e.g., GOTO). By combining real-time perception, state tracking, and LLM-driven communication and task planning, the architecture enhances adaptability, task efficiency, and human-robot collaboration in dynamic environments.

[Arxiv](https://arxiv.org/abs/2411.15027)