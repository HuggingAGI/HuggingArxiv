# D-RMGPT：大型多模态模型助力机器人辅助协作任务

发布时间：2024年08月21日

`Agent` `制造业` `机器人技术`

> D-RMGPT: Robot-assisted collaborative tasks driven by large multimodal models

# 摘要

> 协作机器人在辅助人类工作与日常任务中越来越受欢迎。然而，设计人机协作界面充满挑战，需整合感知、任务控制及硬件等多方面。这常导致依赖大量昂贵训练数据的定制化方案，与灵活通用接口的理想相悖。为解决此问题，本文推出基于大型多模态模型的机器人辅助装配规划器——检测-机器人管理GPT（D-RMGPT）。该系统无需标记或训练，即可助新手操作员完成装配。D-RMGPT包含DetGPT-V和R-ManGPT，前者通过单次图像分析感知环境并识别已装配组件，后者规划下一步骤并生成机器人动作。实验显示，D-RMGPT在组装玩具飞机时，不仅装配成功率达83%，还缩短了新手操作时间33%。

> Collaborative robots are increasingly popular for assisting humans at work and daily tasks. However, designing and setting up interfaces for human-robot collaboration is challenging, requiring the integration of multiple components, from perception and robot task control to the hardware itself. Frequently, this leads to highly customized solutions that rely on large amounts of costly training data, diverging from the ideal of flexible and general interfaces that empower robots to perceive and adapt to unstructured environments where they can naturally collaborate with humans. To overcome these challenges, this paper presents the Detection-Robot Management GPT (D-RMGPT), a robot-assisted assembly planner based on Large Multimodal Models (LMM). This system can assist inexperienced operators in assembly tasks without requiring any markers or previous training. D-RMGPT is composed of DetGPT-V and R-ManGPT. DetGPT-V, based on GPT-4V(vision), perceives the surrounding environment through one-shot analysis of prompted images of the current assembly stage and the list of components to be assembled. It identifies which components have already been assembled by analysing their features and assembly requirements. R-ManGPT, based on GPT-4, plans the next component to be assembled and generates the robot's discrete actions to deliver it to the human co-worker. Experimental tests on assembling a toy aircraft demonstrated that D-RMGPT is flexible and intuitive to use, achieving an assembly success rate of 83% while reducing the assembly time for inexperienced operators by 33% compared to the manual process. http://robotics-and-ai.github.io/LMMmodels/

[Arxiv](https://arxiv.org/abs/2408.11761)