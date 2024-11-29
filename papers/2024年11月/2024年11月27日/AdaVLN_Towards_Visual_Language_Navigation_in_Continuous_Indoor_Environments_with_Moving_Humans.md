# AdaVLN：致力于在有移动人类的连续室内环境中实现视觉语言导航

发布时间：2024年11月27日

`Agent` `机器人`

> AdaVLN: Towards Visual Language Navigation in Continuous Indoor Environments with Moving Humans

# 摘要

> 视觉语言导航是让机器人依据自然语言指令在现实环境中导航的任务。此前的研究多聚焦于静态场景，然而现实中的导航常常得应对动态的人类障碍物。于是，我们提出了该任务的拓展版——自适应视觉语言导航（AdaVLN），旨在缩小这一差距。AdaVLN 要求机器人在布满动态移动人类障碍物的复杂 3D 室内环境中导航，给导航任务增添了复杂性，更贴近现实。为助力对这一任务的探索，我们还推出了 AdaVLN 模拟器和 AdaR2R 数据集。AdaVLN 模拟器能将全动画的人类模型轻松融入诸如 Matterport3D 之类的常见数据集。我们还为导航任务和模拟器引入“冻结时间”机制，在代理推理时暂停世界状态更新，便于在不同硬件间进行公平比较和实现实验可重复性。我们在该任务上评估了若干基线模型，剖析了 AdaVLN 带来的独特挑战，展示了其在 VLN 研究中弥合模拟与现实差距的潜力。

> Visual Language Navigation is a task that challenges robots to navigate in realistic environments based on natural language instructions. While previous research has largely focused on static settings, real-world navigation must often contend with dynamic human obstacles. Hence, we propose an extension to the task, termed Adaptive Visual Language Navigation (AdaVLN), which seeks to narrow this gap. AdaVLN requires robots to navigate complex 3D indoor environments populated with dynamically moving human obstacles, adding a layer of complexity to navigation tasks that mimic the real-world. To support exploration of this task, we also present AdaVLN simulator and AdaR2R datasets. The AdaVLN simulator enables easy inclusion of fully animated human models directly into common datasets like Matterport3D. We also introduce a "freeze-time" mechanism for both the navigation task and simulator, which pauses world state updates during agent inference, enabling fair comparisons and experimental reproducibility across different hardware. We evaluate several baseline models on this task, analyze the unique challenges introduced by AdaVLN, and demonstrate its potential to bridge the sim-to-real gap in VLN research.

[Arxiv](https://arxiv.org/abs/2411.18539)