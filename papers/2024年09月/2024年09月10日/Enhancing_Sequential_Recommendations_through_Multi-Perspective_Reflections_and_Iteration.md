# 通过多视角反思与迭代，提升序列推荐效果

发布时间：2024年09月10日

`LLM应用` `电子商务` `推荐系统`

> Enhancing Sequential Recommendations through Multi-Perspective Reflections and Iteration

# 摘要

> 序列推荐 (SeqRec) 旨在通过理解用户意图和利用协同过滤信息来预测用户的下一个交互项目。大型语言模型 (LLM) 通过基于提示、固定反射库和微调技术在推荐任务中展现出巨大潜力。然而，这些方法面临缺乏监督、无法优化反射源、对多样化用户需求的灵活性不足以及高计算成本等挑战。当前研究主要关注用户显式偏好（如项目标题），而忽略了隐式偏好（如品牌）和协同过滤信息，这阻碍了对偏好变化和动态用户行为的捕捉。此外，现有方法缺乏反射评估和迭代的机制，导致推荐效果不佳。为此，我们提出了混合反射器 (MoRE) 框架，旨在在 SeqRec 中建模和学习动态用户偏好。MoRE 引入了三个反射器，分别处理显式偏好、隐式偏好和协同信号，并通过“提炼与迭代”策略进行自我改进。此外，元反射器采用上下文强盗算法，选择最适合每个用户的专家和反射，有效捕捉动态偏好。实验表明，MoRE 在三个真实数据集上始终优于最先进方法，且训练时间和 GPU 内存消耗更少。

> Sequence recommendation (SeqRec) aims to predict the next item a user will interact with by understanding user intentions and leveraging collaborative filtering information. Large language models (LLMs) have shown great promise in recommendation tasks through prompt-based, fixed reflection libraries, and fine-tuning techniques. However, these methods face challenges, including lack of supervision, inability to optimize reflection sources, inflexibility to diverse user needs, and high computational costs. Despite promising results, current studies primarily focus on reflections of users' explicit preferences (e.g., item titles) while neglecting implicit preferences (e.g., brands) and collaborative filtering information. This oversight hinders the capture of preference shifts and dynamic user behaviors. Additionally, existing approaches lack mechanisms for reflection evaluation and iteration, often leading to suboptimal recommendations. To address these issues, we propose the Mixture of REflectors (MoRE) framework, designed to model and learn dynamic user preferences in SeqRec. Specifically, MoRE introduces three reflectors for generating LLM-based reflections on explicit preferences, implicit preferences, and collaborative signals. Each reflector incorporates a self-improving strategy, termed refining-and-iteration, to evaluate and iteratively update reflections. Furthermore, a meta-reflector employs a contextual bandit algorithm to select the most suitable expert and corresponding reflections for each user's recommendation, effectively capturing dynamic preferences. Extensive experiments on three real-world datasets demonstrate that MoRE consistently outperforms state-of-the-art methods, requiring less training time and GPU memory compared to other LLM-based approaches in SeqRec.

[Arxiv](https://arxiv.org/abs/2409.06377)