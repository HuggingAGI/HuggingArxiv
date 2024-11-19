# Eurekaverse：借助大型语言模型进行环境课程的生成

发布时间：2024年11月03日

`LLM应用` `机器人` `环境设计`

> Eurekaverse: Environment Curriculum Generation via Large Language Models

# 摘要

> 近期工作显示，要让机器人学会众多复杂技能，一个很有前途的策略是在一系列难度渐增的环境中对其加以训练。然而，目前开发有效的环境分布课程需要大量专业知识，且每个新领域都得重新来一遍。我们的关键发现是，环境通常自然地以代码形式呈现。所以，我们探究能否借助大型语言模型（LLM）的代码生成来实现并自动化有效的环境课程设计。在本文中，我们引入了 Eurekaverse，这是一种无监督的环境设计算法，它利用 LLM 为技能训练采样难度渐增、多样且可学的环境。我们在四足跑酷学习领域验证了 Eurekaverse 的有效性，在该领域中，四足机器人得穿越各类障碍课程。Eurekaverse 设计的自动课程能让机器人在模拟中逐步掌握复杂的跑酷技能，并成功应用于现实世界，表现优于人类设计的手动训练课程。

> Recent work has demonstrated that a promising strategy for teaching robots a wide range of complex skills is by training them on a curriculum of progressively more challenging environments. However, developing an effective curriculum of environment distributions currently requires significant expertise, which must be repeated for every new domain. Our key insight is that environments are often naturally represented as code. Thus, we probe whether effective environment curriculum design can be achieved and automated via code generation by large language models (LLM). In this paper, we introduce Eurekaverse, an unsupervised environment design algorithm that uses LLMs to sample progressively more challenging, diverse, and learnable environments for skill training. We validate Eurekaverse's effectiveness in the domain of quadrupedal parkour learning, in which a quadruped robot must traverse through a variety of obstacle courses. The automatic curriculum designed by Eurekaverse enables gradual learning of complex parkour skills in simulation and can successfully transfer to the real-world, outperforming manual training courses designed by humans.

[Arxiv](https://arxiv.org/abs/2411.01775)