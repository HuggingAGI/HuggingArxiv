# HARGPT 探究：LLMs 在零样本情况下能否胜任人类活动识别任务？

发布时间：2024年03月05日

`LLM应用`

> HARGPT: Are LLMs Zero-Shot Human Activity Recognizers?

> 当前热议的一个话题是LLMs能否成为与CPS紧密结合的基础模型，以无间断的方式解读现实世界的物理信息。本文通过对LLMs是否能实现零样本的人体活动识别（HAR）这一问题的研究，揭示了LLMs的巨大潜能。我们的HARGPT研究表明，在得到恰当的提示后，LLMs可以理解未经处理的IMU数据并以零样本的方式完成HAR任务。我们采用角色扮演及逐步思考的提示策略，将原始IMU数据输入至LLMs中，并在GPT4平台上利用两类具有不同类间相似度的公开数据集对HARGPT进行基准测试，同时对比了基于传统机器学习以及最前沿深度分类模型的各种基准方法。令人瞩目的是，LLMs不仅成功地从原始IMU数据中识别人体活动，而且在这两个数据集上的表现均显著优于所有基准模型。这一研究成果显示，通过巧妙设计提示方式，LLMs能根据自身的知识库解析物理世界的原始传感器数据，展现出高效分析此类数据的强大潜力。

> There is an ongoing debate regarding the potential of Large Language Models (LLMs) as foundational models seamlessly integrated with Cyber-Physical Systems (CPS) for interpreting the physical world. In this paper, we carry out a case study to answer the following question: Are LLMs capable of zero-shot human activity recognition (HAR). Our study, HARGPT, presents an affirmative answer by demonstrating that LLMs can comprehend raw IMU data and perform HAR tasks in a zero-shot manner, with only appropriate prompts. HARGPT inputs raw IMU data into LLMs and utilizes the role-play and think step-by-step strategies for prompting. We benchmark HARGPT on GPT4 using two public datasets of different inter-class similarities and compare various baselines both based on traditional machine learning and state-of-the-art deep classification models. Remarkably, LLMs successfully recognize human activities from raw IMU data and consistently outperform all the baselines on both datasets. Our findings indicate that by effective prompting, LLMs can interpret raw IMU data based on their knowledge base, possessing a promising potential to analyze raw sensor data of the physical world effectively.

[Arxiv](https://arxiv.org/abs/2403.02727)