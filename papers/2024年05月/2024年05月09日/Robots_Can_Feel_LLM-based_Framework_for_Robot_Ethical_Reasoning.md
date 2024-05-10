# 机器人亦有情：大型语言模型驱动的机器人伦理决策框架在

发布时间：2024年05月09日

`Agent

这篇论文介绍了一种创新的机器人伦理推理框架，名为“机器人能感受”，它通过融合逻辑与类人情感模拟来使机器人在面对道德难题时做出类似人类的决策。该框架的核心是情感权重系数的调控，这表明它是一个用于指导机器人（即Agent）行为的系统。因此，它属于Agent分类。虽然它涉及了LLM（大型语言模型）的测试，但这里的LLM是作为测试平台，而不是研究的主要焦点，因此它不属于LLM应用或LLM理论分类。同时，它也不属于RAG分类，因为RAG通常指的是检索增强生成模型，而这里并没有提及相关的检索增强生成技术。` `机器人伦理` `人工智能伦理`

> Robots Can Feel: LLM-based Framework for Robot Ethical Reasoning

# 摘要

> 本文推出了一种创新的机器人伦理推理框架，名为“机器人能感受”。该系统首次将逻辑与类人情感模拟融合，使机器人在面对道德难题时能做出类似人类的决策。其核心在于情感权重系数的调控，这一可调参数决定了情感在机器人决策中的分量。该系统旨在赋予各类机器人以接近人类标准的伦理行为，且不依赖于特定的基础模型。评估中，该系统在8个顶尖的LLM上进行了测试，涵盖了来自不同国家和公司的商业与开源模型。研究显示，不论模型如何，情感权重系数均能影响机器人的决策。ANOVA分析表明，在诸如饮食违规请求（F(4, 35) = 11.2, p = 0.0001）和动物同情等情境中，情感权重系数的不同设置显著影响了机器人的最终决策。演示代码库地址为：https://github.com/TemaLykov/robots_can_feel。

> This paper presents the development of a novel ethical reasoning framework for robots. "Robots Can Feel" is the first system for robots that utilizes a combination of logic and human-like emotion simulation to make decisions in morally complex situations akin to humans. The key feature of the approach is the management of the Emotion Weight Coefficient - a customizable parameter to assign the role of emotions in robot decision-making. The system aims to serve as a tool that can equip robots of any form and purpose with ethical behavior close to human standards. Besides the platform, the system is independent of the choice of the base model. During the evaluation, the system was tested on 8 top up-to-date LLMs (Large Language Models). This list included both commercial and open-source models developed by various companies and countries. The research demonstrated that regardless of the model choice, the Emotions Weight Coefficient influences the robot's decision similarly. According to ANOVA analysis, the use of different Emotion Weight Coefficients influenced the final decision in a range of situations, such as in a request for a dietary violation F(4, 35) = 11.2, p = 0.0001 and in an animal compassion situation F(4, 35) = 8.5441, p = 0.0001. A demonstration code repository is provided at: https://github.com/TemaLykov/robots_can_feel

[Arxiv](https://arxiv.org/abs/2405.05824)