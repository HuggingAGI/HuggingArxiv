# 嘿，机器人！借助大型语言模型与模型预测控制，为机器人导航增添个性化色彩。

发布时间：2024年09月20日

`Agent` `机器人`

> Hey Robot! Personalizing Robot Navigation through Model Predictive Control with a Large Language Model

# 摘要

> 机器人导航方法让移动机器人能在仓库或医院等场景中运行。然而，现有方法大多不允许用户自定义机器人的行为和优先级，可能导致不良行为（如在医院内高速行驶）。我们提出了一种基于自然语言指令的新方法，通过视觉语言模型解读用户指令或环境图像，生成成本函数并调整控制器参数，将用户意图转化为机器人行为。这种方法能在动态复杂环境中安全高效导航。我们通过模拟和实际实验，验证了该方法在多种环境和用户需求下的有效性。

> Robot navigation methods allow mobile robots to operate in applications such as warehouses or hospitals. While the environment in which the robot operates imposes requirements on its navigation behavior, most existing methods do not allow the end-user to configure the robot's behavior and priorities, possibly leading to undesirable behavior (e.g., fast driving in a hospital). We propose a novel approach to adapt robot motion behavior based on natural language instructions provided by the end-user. Our zero-shot method uses an existing Visual Language Model to interpret a user text query or an image of the environment. This information is used to generate the cost function and reconfigure the parameters of a Model Predictive Controller, translating the user's instruction to the robot's motion behavior. This allows our method to safely and effectively navigate in dynamic and challenging environments. We extensively evaluate our method's individual components and demonstrate the effectiveness of our method on a ground robot in simulation and real-world experiments, and across a variety of environments and user specifications.

[Arxiv](https://arxiv.org/abs/2409.13393)