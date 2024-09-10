# 机器人效用模型：为新环境中的零-shot 部署提供通用策略

发布时间：2024年09月09日

`Agent` `机器人` `自动化`

> Robot Utility Models: General Policies for Zero-Shot Deployment in New Environments

# 摘要

> 最近，通过大量数据训练的机器人模型展示了丰富的现实操作和导航能力。研究表明，在充足的环境数据下，机器人策略能泛化到环境变化。然而，每个新环境都需要微调，这与零-shot部署的语言或视觉模型形成对比。为此，我们提出了机器人效用模型（RUMs），一个无需微调即可泛化到新环境的零-shot策略框架。我们开发了快速数据收集工具，整合多模态模仿学习，并在廉价机器人上部署策略，外部验证器用于重试。我们训练了五个效用模型，用于打开橱柜门、抽屉、拿起餐巾纸、纸袋和重新定位倒下的物体。系统在新环境中平均成功率达90%，且在不同设置中无需额外数据或训练。我们的经验强调了数据质量、多样化演示和机器人内省重试的重要性。所有资源已开源，详见项目网站：https://robotutilitymodels.com

> Robot models, particularly those trained with large amounts of data, have recently shown a plethora of real-world manipulation and navigation capabilities. Several independent efforts have shown that given sufficient training data in an environment, robot policies can generalize to demonstrated variations in that environment. However, needing to finetune robot models to every new environment stands in stark contrast to models in language or vision that can be deployed zero-shot for open-world problems. In this work, we present Robot Utility Models (RUMs), a framework for training and deploying zero-shot robot policies that can directly generalize to new environments without any finetuning. To create RUMs efficiently, we develop new tools to quickly collect data for mobile manipulation tasks, integrate such data into a policy with multi-modal imitation learning, and deploy policies on-device on Hello Robot Stretch, a cheap commodity robot, with an external mLLM verifier for retrying. We train five such utility models for opening cabinet doors, opening drawers, picking up napkins, picking up paper bags, and reorienting fallen objects. Our system, on average, achieves 90% success rate in unseen, novel environments interacting with unseen objects. Moreover, the utility models can also succeed in different robot and camera set-ups with no further data, training, or fine-tuning. Primary among our lessons are the importance of training data over training algorithm and policy class, guidance about data scaling, necessity for diverse yet high-quality demonstrations, and a recipe for robot introspection and retrying to improve performance on individual environments. Our code, data, models, hardware designs, as well as our experiment and deployment videos are open sourced and can be found on our project website: https://robotutilitymodels.com

[Arxiv](https://arxiv.org/abs/2409.05865)