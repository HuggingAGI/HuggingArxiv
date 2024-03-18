# RLingua 是一项研究，借助大型语言模型提升机器人操作领域强化学习的样本效率，从而改进了机器人的操控性能。

发布时间：2024年03月11日

`Agent`

> RLingua: Improving Reinforcement Learning Sample Efficiency in Robotic Manipulations With Large Language Models

> 强化学习（RL）虽然能解决众多任务，却因低效样本问题饱受诟病。本研究提出RLingua框架，巧妙利用大型语言模型（LLMs）的内嵌智慧，以提升机器人操作中RL的样本效率。我们首先揭示如何运用提示工程技术抽取LLMs的预置知识，进而为特定任务自动生成初步的规则导向机器人控制器。即使这种由LLM产生的控制器并非尽善尽美，它仍能在rollouts阶段按递减概率生成动作样例，有效提升RL的样本利用率。我们在actor-critic框架基础上调整actor损失函数，引导策略学习朝向LLM生成的控制器优化。RLingua还创新性地引入RL机制来逐步完善LLM生成的机器人控制器。实验证明，RLingua在panda_gym与RLBench的机器人任务中，能显著降低TD3所需的样本量，并在后者稀疏奖励环境下实现高成功率，而常规TD3在此类任务中则宣告失败。同时，通过Sim2Real在真实世界机器人实验上的验证，进一步证实了RLingua所学策略能够成功迁移到实际机器人任务中。欲了解更多详情及观看相关视频，请访问我们的项目网站https://rlingua.github.io。

> Reinforcement learning (RL) has demonstrated its capability in solving various tasks but is notorious for its low sample efficiency. In this paper, we propose RLingua, a framework that can leverage the internal knowledge of large language models (LLMs) to reduce the sample complexity of RL in robotic manipulations. To this end, we first present how to extract the prior knowledge of LLMs by prompt engineering so that a preliminary rule-based robot controller for a specific task can be generated. Despite being imperfect, the LLM-generated robot controller is utilized to produce action samples during rollouts with a decaying probability, thereby improving RL's sample efficiency. We employ the actor-critic framework and modify the actor loss to regularize the policy learning towards the LLM-generated controller. RLingua also provides a novel method of improving the imperfect LLM-generated robot controllers by RL. We demonstrated that RLingua can significantly reduce the sample complexity of TD3 in the robot tasks of panda_gym and achieve high success rates in sparsely rewarded robot tasks in RLBench, where the standard TD3 fails. Additionally, We validated RLingua's effectiveness in real-world robot experiments through Sim2Real, demonstrating that the learned policies are effectively transferable to real robot tasks. Further details and videos about our work are available at our project website https://rlingua.github.io.

[Arxiv](https://arxiv.org/abs/2403.06420)