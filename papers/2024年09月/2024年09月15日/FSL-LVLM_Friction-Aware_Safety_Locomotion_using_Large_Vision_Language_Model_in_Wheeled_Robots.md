# FSL-LVLM：借助大型视觉语言模型，轮式机器人实现摩擦感知的安全移动

发布时间：2024年09月15日

`Agent` `机器人` `人工智能`

> FSL-LVLM: Friction-Aware Safety Locomotion using Large Vision Language Model in Wheeled Robots

# 摘要

> 轮腿机器人虽具备出色的移动性和多功能性，但在滑溜地形上却面临严峻挑战。传统控制器假设无滑动，而强化学习虽能助四足机器人适应不同表面，但应对滑动仍具挑战，尤其在接触点少的系统中。本文提出一种创新的摩擦感知运动框架，结合大型视觉语言模型与强化学习策略，将摩擦系数纳入策略，使机器人能预判表面类型并调整行为。引入的视觉摩擦模块利用大型模型估算摩擦系数，无需大量数据与训练。实验证明，该框架通过智能调速提升任务成功率，并优化跟踪性能。此框架可轻松融入其他强化学习策略。

> Wheeled-legged robots offer significant mobility and versatility but face substantial challenges when operating on slippery terrains. Traditional model-based controllers for these robots assume no slipping. While reinforcement learning (RL) helps quadruped robots adapt to different surfaces, recovering from slips remains challenging, especially for systems with few contact points. Estimating the ground friction coefficient is another open challenge. In this paper, we propose a novel friction-aware safety locomotion framework that integrates Large Vision Language Models (LVLMs) with a RL policy. Our approach explicitly incorporates the estimated friction coefficient into the RL policy, enabling the robot to adapt its behavior in advance based on the surface type before reaching it. We introduce a Friction-From-Vision (FFV) module, which leverages LVLMs to estimate ground friction coefficients, eliminating the need for large datasets and extensive training. The framework was validated on a customized wheeled inverted pendulum, and experimental results demonstrate that our framework increases the success rate in completing driving tasks by adjusting speed according to terrain type, while achieving better tracking performance compared to baseline methods. Our framework can be simply integrated with any other RL policies.

[Arxiv](https://arxiv.org/abs/2409.09845)