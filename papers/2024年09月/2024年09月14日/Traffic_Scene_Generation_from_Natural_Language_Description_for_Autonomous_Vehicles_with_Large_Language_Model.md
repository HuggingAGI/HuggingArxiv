# 利用大型语言模型，从自然语言描述中生成自动驾驶车辆的交通场景

发布时间：2024年09月14日

`Agent` `自动驾驶`

> Traffic Scene Generation from Natural Language Description for Autonomous Vehicles with Large Language Model

# 摘要

> 传统的文本到场景生成方法依赖于预定路径，限制了环境多样性和定制灵活性。为此，我们提出了一种创新的文本到交通场景框架，利用大型语言模型在 Carla 模拟器中生成多样化的交通场景。用户可自定义天气、车辆类型等参数，而系统则自主选择起点和场景细节，无需依赖预定路径。该框架不仅支持关键交通场景，还涵盖日常场景，提升了适用性。实验显示，我们的方法显著提升了代理规划和道路选择的多样性，并降低了 16% 的平均碰撞率。相关成果已在 https://basiclab.github.io/TTSG 公开发布。

> Text-to-scene generation, transforming textual descriptions into detailed scenes, typically relies on generating key scenarios along predetermined paths, constraining environmental diversity and limiting customization flexibility. To address these limitations, we propose a novel text-to-traffic scene framework that leverages a large language model to generate diverse traffic scenarios within the Carla simulator based on natural language descriptions. Users can define specific parameters such as weather conditions, vehicle types, and road signals, while our pipeline can autonomously select the starting point and scenario details, generating scenes from scratch without relying on predetermined locations or trajectories. Furthermore, our framework supports both critical and routine traffic scenarios, enhancing its applicability. Experimental results indicate that our approach promotes diverse agent planning and road selection, enhancing the training of autonomous agents in traffic environments. Notably, our methodology has achieved a 16% reduction in average collision rates. Our work is made publicly available at https://basiclab.github.io/TTSG.

[Arxiv](https://arxiv.org/abs/2409.09575)