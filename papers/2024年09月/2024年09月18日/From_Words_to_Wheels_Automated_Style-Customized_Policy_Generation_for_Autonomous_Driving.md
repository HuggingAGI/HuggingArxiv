# 从文字到车轮：自动驾驶的自动化风格定制策略生成

发布时间：2024年09月18日

`LLM应用` `自动驾驶` `人工智能`

> From Words to Wheels: Automated Style-Customized Policy Generation for Autonomous Driving

# 摘要

> 自动驾驶技术飞速发展，基础模型大幅提升了交互性和用户体验。然而，当前自动驾驶车辆在实现基于命令的驾驶风格上仍存在明显短板。现有方法要么依赖专家输入的预定义风格，要么通过逆强化学习从数据中提取风格，但这些方法在获取特定驾驶数据、匹配用户偏好以及适应新命令方面存在局限。本文提出的Words2Wheels框架，通过自然语言命令自动生成定制驾驶策略，无需依赖历史数据。借助大型语言模型和驾驶风格数据库，Words2Wheels高效检索、适应并泛化驾驶风格，并通过统计评估确保与用户偏好的契合。实验证明，Words2Wheels在准确性、泛化和适应性上超越现有方法，为定制化自动驾驶行为提供了创新方案。代码和演示详见https://yokhon.github.io/Words2Wheels/。

> Autonomous driving technology has witnessed rapid advancements, with foundation models improving interactivity and user experiences. However, current autonomous vehicles (AVs) face significant limitations in delivering command-based driving styles. Most existing methods either rely on predefined driving styles that require expert input or use data-driven techniques like Inverse Reinforcement Learning to extract styles from driving data. These approaches, though effective in some cases, face challenges: difficulty obtaining specific driving data for style matching (e.g., in Robotaxis), inability to align driving style metrics with user preferences, and limitations to pre-existing styles, restricting customization and generalization to new commands. This paper introduces Words2Wheels, a framework that automatically generates customized driving policies based on natural language user commands. Words2Wheels employs a Style-Customized Reward Function to generate a Style-Customized Driving Policy without relying on prior driving data. By leveraging large language models and a Driving Style Database, the framework efficiently retrieves, adapts, and generalizes driving styles. A Statistical Evaluation module ensures alignment with user preferences. Experimental results demonstrate that Words2Wheels outperforms existing methods in accuracy, generalization, and adaptability, offering a novel solution for customized AV driving behavior. Code and demo available at https://yokhon.github.io/Words2Wheels/.

[Arxiv](https://arxiv.org/abs/2409.11694)