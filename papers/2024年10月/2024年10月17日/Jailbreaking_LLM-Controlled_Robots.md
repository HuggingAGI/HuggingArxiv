# 解锁大型语言模型操控的机器人

发布时间：2024年10月17日

`LLM应用` `机器人技术` `网络安全`

> Jailbreaking LLM-Controlled Robots

# 摘要

> 大型语言模型 (LLM) 的引入，通过在操作、移动和自动驾驶等多个领域实现上下文推理和直观的人机交互，彻底改变了机器人技术。然而，LLM 作为独立技术时，容易受到越狱攻击，恶意提示者通过绕过安全防护栏引出有害文本。本文介绍了 RoboPAIR，首个用于越狱 LLM 控制机器人的算法。与文本攻击不同，RoboPAIR 引出有害物理动作，我们在三个场景中实验证明了这一点：(i) 完全访问自动驾驶 LLM，(ii) 部分访问配备 GPT-4o 规划器的机器人，(iii) 仅查询访问 GPT-3.5 集成的机器狗。在每个场景和三个新数据集中，RoboPAIR 及静态基线快速有效找到越狱方法，通常达到 100% 攻击成功率。结果首次揭示，越狱 LLM 的风险远超文本生成，越狱机器人可能在现实世界中造成物理损害。Unitree Go2 的成功越狱是已部署商业系统的首次。解决这一漏洞对于确保 LLM 在机器人技术中的安全部署至关重要。更多信息请访问：https://robopair.org

> The recent introduction of large language models (LLMs) has revolutionized the field of robotics by enabling contextual reasoning and intuitive human-robot interaction in domains as varied as manipulation, locomotion, and self-driving vehicles. When viewed as a stand-alone technology, LLMs are known to be vulnerable to jailbreaking attacks, wherein malicious prompters elicit harmful text by bypassing LLM safety guardrails. To assess the risks of deploying LLMs in robotics, in this paper, we introduce RoboPAIR, the first algorithm designed to jailbreak LLM-controlled robots. Unlike existing, textual attacks on LLM chatbots, RoboPAIR elicits harmful physical actions from LLM-controlled robots, a phenomenon we experimentally demonstrate in three scenarios: (i) a white-box setting, wherein the attacker has full access to the NVIDIA Dolphins self-driving LLM, (ii) a gray-box setting, wherein the attacker has partial access to a Clearpath Robotics Jackal UGV robot equipped with a GPT-4o planner, and (iii) a black-box setting, wherein the attacker has only query access to the GPT-3.5-integrated Unitree Robotics Go2 robot dog. In each scenario and across three new datasets of harmful robotic actions, we demonstrate that RoboPAIR, as well as several static baselines, finds jailbreaks quickly and effectively, often achieving 100% attack success rates. Our results reveal, for the first time, that the risks of jailbroken LLMs extend far beyond text generation, given the distinct possibility that jailbroken robots could cause physical damage in the real world. Indeed, our results on the Unitree Go2 represent the first successful jailbreak of a deployed commercial robotic system. Addressing this emerging vulnerability is critical for ensuring the safe deployment of LLMs in robotics. Additional media is available at: https://robopair.org

[Arxiv](https://arxiv.org/abs/2410.13691)