# 利用机器人终身经验的层次结构，实现情景记忆的言语表达

发布时间：2024年09月26日

`Agent` `机器人` `人机交互`

> Episodic Memory Verbalization using Hierarchical Representations of Life-Long Robot Experience

# 摘要

> 将机器人经验转化为语言，即总结和回答机器人过去的行为，是提升人机交互的关键。以往的研究多采用基于规则的系统或微调的深度模型，处理几分钟长的情节数据，但泛化和迁移能力有限。我们则利用大型预训练模型，仅需少量甚至零示例，专注于语言化机器人的终身经验。我们构建了一个树状数据结构，底层为原始感知数据，高层为自然语言概念，以此分层表示机器人经验。通过大型语言模型，我们能根据用户查询，动态搜索并扩展相关信息，计算成本低廉，适用于数月的机器人数据。实验表明，该方法在模拟家庭环境、人类视角视频及真实机器人记录中均表现出色，灵活且可扩展。

> Verbalization of robot experience, i.e., summarization of and question answering about a robot's past, is a crucial ability for improving human-robot interaction. Previous works applied rule-based systems or fine-tuned deep models to verbalize short (several-minute-long) streams of episodic data, limiting generalization and transferability. In our work, we apply large pretrained models to tackle this task with zero or few examples, and specifically focus on verbalizing life-long experiences. For this, we derive a tree-like data structure from episodic memory (EM), with lower levels representing raw perception and proprioception data, and higher levels abstracting events to natural language concepts. Given such a hierarchical representation built from the experience stream, we apply a large language model as an agent to interactively search the EM given a user's query, dynamically expanding (initially collapsed) tree nodes to find the relevant information. The approach keeps computational costs low even when scaling to months of robot experience data. We evaluate our method on simulated household robot data, human egocentric videos, and real-world robot recordings, demonstrating its flexibility and scalability.

[Arxiv](https://arxiv.org/abs/2409.17702)