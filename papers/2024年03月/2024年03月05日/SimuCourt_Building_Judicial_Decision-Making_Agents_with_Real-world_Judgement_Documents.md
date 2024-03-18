# SimuCourt项目致力于通过真实世界司法判决文档，打造能够进行司法决策制定的智能代理。

发布时间：2024年03月05日

`Agent`

> SimuCourt: Building Judicial Decision-Making Agents with Real-world Judgement Documents

> 深度学习时代，自然语言处理技术有力推动了司法行业各个环节效率升级，但当前研究大多只聚焦单一司法阶段，忽略了跨阶段协作的重要性。随着搭载大型语言模型的智能体日益智能化，在实际场景中展现出对复杂裁决的驾驭能力，为司法智慧带来全新启示。本文首先介绍了SimuCourt这一司法基准平台，它汇集了420份真实的判决文书，覆盖三大常见司法案例类型，并创新性地提出了“司法决策制定”任务，借助我们精心构建的大型司法知识库JudicialKB来评测智能体的司法分析与决策效能。其次，我们设计出名为AgentsCourt的新型多智能体框架，它仿照现实法院庭审流程，通过模拟法庭辩论、检索法律信息及细化判决意见等步骤，生动再现法官的决策过程。最后，我们进行了一系列深入实验，结果显示，相较于现有前沿方法，我们的框架在多个维度上均有出色表现，特别是在生成法律依据方面，分别在第一审和第二审情境下获得了高达8.6%和9.1%的F1分数显著提升。

> With the development of deep learning, natural language processing technology has effectively improved the efficiency of various aspects of the traditional judicial industry. However, most current efforts focus solely on individual judicial stage, overlooking cross-stage collaboration. As the autonomous agents powered by large language models are becoming increasingly smart and able to make complex decisions in real-world settings, offering new insights for judicial intelligence. In this paper, (1) we introduce SimuCourt, a judicial benchmark that encompasses 420 judgment documents from real-world, spanning the three most common types of judicial cases, and a novel task Judicial Decision-Making to evaluate the judicial analysis and decision-making power of agents. To support this task, we construct a large-scale judicial knowledge base, JudicialKB, with multiple legal knowledge. (2) we propose a novel multi-agent framework, AgentsCourt. Our framework follows the real-world classic court trial process, consisting of court debate simulation, legal information retrieval and judgement refinement to simulate the decision-making of judge. (3) we perform extensive experiments, the results demonstrate that, our framework outperforms the existing advanced methods in various aspects, especially in generating legal grounds, where our model achieves significant improvements of 8.6% and 9.1% F1 score in the first and second instance settings, respectively.

[Arxiv](https://arxiv.org/abs/2403.02959)