# 智能副驾：一款基于视觉语言模型的自动驾驶辅助系统，它模仿人类驾驶员的行为，并能深刻理解复杂多变的道路环境。

发布时间：2024年05月09日

`Agent

这篇论文介绍了一个名为Co-driver的系统，它是基于大型语言模型的自动驾驶技术，旨在解决自动驾驶车辆在规划与控制方面的挑战。该系统通过理解道路场景来赋予车辆灵活的驾驶行为，并在模拟器和实际驾驶测试中展示了高效能。由于Co-driver系统是一个具体的应用实例，它涉及到自动驾驶车辆的控制和决策，因此它更符合Agent的分类，即一个能够执行任务和做出决策的智能实体。` `自动驾驶` `智能交通系统`

> Co-driver: VLM-based Autonomous Driving Assistant with Human-like Behavior and Understanding for Complex Road Scenes

# 摘要

> 基于大型语言模型的自动驾驶技术在规划与控制领域展现出光明前景，但计算资源的沉重负担和模型幻觉问题仍制约着精准轨迹预测与控制信号的指导。为此，我们创新性地推出了Co-driver系统，它通过理解道路场景，赋予自动驾驶车辆灵活的驾驶行为。我们通过CARLA模拟器与ROS2系统验证了Co-driver的效能，并巧妙地利用了Nvidia 4090 24G GPU的强大性能。此外，我们还提供了一个包含图像与提示的数据集，用于优化系统的视觉语言模型。在实际驾驶测试中，Co-driver在夜间与阴暗环境下的成功率分别高达96.16%与89.7%，表现出色。我们将在https://github.com/ZionGo6/Co-driver公开Co-driver数据集，以飨业界。

> Recent research about Large Language Model based autonomous driving solutions shows a promising picture in planning and control fields. However, heavy computational resources and hallucinations of Large Language Models continue to hinder the tasks of predicting precise trajectories and instructing control signals. To address this problem, we propose Co-driver, a novel autonomous driving assistant system to empower autonomous vehicles with adjustable driving behaviors based on the understanding of road scenes. A pipeline involving the CARLA simulator and Robot Operating System 2 (ROS2) verifying the effectiveness of our system is presented, utilizing a single Nvidia 4090 24G GPU while exploiting the capacity of textual output of the Visual Language Model. Besides, we also contribute a dataset containing an image set and a corresponding prompt set for fine-tuning the Visual Language Model module of our system. In the real-world driving dataset, our system achieved 96.16% success rate in night scenes and 89.7% in gloomy scenes regarding reasonable predictions. Our Co-driver dataset will be released at https://github.com/ZionGo6/Co-driver.

[Arxiv](https://arxiv.org/abs/2405.05885)