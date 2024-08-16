# Polaris：借助 Syn2Real 视觉定位与大型语言模型，实现开放式交互机器人操作

发布时间：2024年08月15日

`Agent` `机器人` `自动化`

> Polaris: Open-ended Interactive Robotic Manipulation via Syn2Real Visual Grounding and Large Language Models

# 摘要

> 本文探讨了桌面场景下的开放式交互机器人操作任务。尽管大型语言模型 (LLM) 提升了机器人对指令的理解，但缺乏视觉基础限制了其与环境的实际互动。为此，我们推出了 Polaris 框架，结合 GPT-4 和视觉模型，实现感知与交互的融合。为确保操作精度，视觉模型需生成目标对象的详细姿态。我们提出的 Syn2Real 姿态估计流程，通过合成数据训练，成功应用于现实操作，展现了其广泛应用的潜力。真实机器人实验证明，Polaris 在抓取和多任务操作中表现卓越，预示着其向更复杂场景的扩展能力。更多详情和演示视频，请访问：https://star-uu-wang.github.io/Polaris/

> This paper investigates the task of the open-ended interactive robotic manipulation on table-top scenarios. While recent Large Language Models (LLMs) enhance robots' comprehension of user instructions, their lack of visual grounding constrains their ability to physically interact with the environment. This is because the robot needs to locate the target object for manipulation within the physical workspace. To this end, we introduce an interactive robotic manipulation framework called Polaris, which integrates perception and interaction by utilizing GPT-4 alongside grounded vision models. For precise manipulation, it is essential that such grounded vision models produce detailed object pose for the target object, rather than merely identifying pixels belonging to them in the image. Consequently, we propose a novel Synthetic-to-Real (Syn2Real) pose estimation pipeline. This pipeline utilizes rendered synthetic data for training and is then transferred to real-world manipulation tasks. The real-world performance demonstrates the efficacy of our proposed pipeline and underscores its potential for extension to more general categories. Moreover, real-robot experiments have showcased the impressive performance of our framework in grasping and executing multiple manipulation tasks. This indicates its potential to generalize to scenarios beyond the tabletop. More information and video results are available here: https://star-uu-wang.github.io/Polaris/

[Arxiv](https://arxiv.org/abs/2408.07975)