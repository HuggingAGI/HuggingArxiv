# 大型语言模型协调结构化推理达到 Kaggle 特级大师水平

发布时间：2024年11月05日

`Agent` `数据科学`

> Large Language Models Orchestrating Structured Reasoning Achieve Kaggle Grandmaster Level

# 摘要

> 我们推出了 Agent K v1.0，这是一个端到端的自主数据科学代理，旨在实现各种数据科学任务的自动化、优化和通用化。完全自动化的 Agent K v1.0 通过从经验中学习来管理整个数据科学生命周期。它利用高度灵活的结构化推理框架，使其能够动态地处理嵌套结构中的内存，有效地从存储的积累经验中学习，以处理复杂的推理任务。它通过有选择地存储和检索关键信息来优化长期和短期记忆，根据环境奖励指导未来的决策。这种迭代方法允许它在无需微调或反向传播的情况下改进决策，通过经验学习实现持续改进。我们使用 Kaggle 竞赛作为案例研究来评估我们代理的能力。按照完全自动化的协议，Agent K v1.0 系统地处理复杂和多模态的数据科学任务，采用贝叶斯优化进行超参数调整和特征工程。我们新的评估框架严格评估 Agent K v1.0 从 Kaggle 竞赛 URL 开始生成和发送提交的端到端能力。结果表明，Agent K v1.0 在涵盖表格、计算机视觉、NLP 和多模态领域的任务中成功率达到 92.5％。通过为每个人计算 Elo-MMR 分数与 5856 名人类 Kaggle 竞争对手进行基准测试，Agent K v1.0 排名在前 38％，展示出与专家级用户相当的总体技能水平。值得注意的是，它的 Elo-MMR 分数落在人类特级大师得分的第一个和第三个四分位数之间。此外，我们的结果表明，Agent K v1.0 已经达到了与 Kaggle 特级大师相当的性能水平，按照 Kaggle 的晋升系统，获得了 6 枚金牌、3 枚银牌和 7 枚铜牌的记录。

> We introduce Agent K v1.0, an end-to-end autonomous data science agent designed to automate, optimise, and generalise across diverse data science tasks. Fully automated, Agent K v1.0 manages the entire data science life cycle by learning from experience. It leverages a highly flexible structured reasoning framework to enable it to dynamically process memory in a nested structure, effectively learning from accumulated experience stored to handle complex reasoning tasks. It optimises long- and short-term memory by selectively storing and retrieving key information, guiding future decisions based on environmental rewards. This iterative approach allows it to refine decisions without fine-tuning or backpropagation, achieving continuous improvement through experiential learning. We evaluate our agent's apabilities using Kaggle competitions as a case study. Following a fully automated protocol, Agent K v1.0 systematically addresses complex and multimodal data science tasks, employing Bayesian optimisation for hyperparameter tuning and feature engineering. Our new evaluation framework rigorously assesses Agent K v1.0's end-to-end capabilities to generate and send submissions starting from a Kaggle competition URL. Results demonstrate that Agent K v1.0 achieves a 92.5\% success rate across tasks, spanning tabular, computer vision, NLP, and multimodal domains. When benchmarking against 5,856 human Kaggle competitors by calculating Elo-MMR scores for each, Agent K v1.0 ranks in the top 38\%, demonstrating an overall skill level comparable to Expert-level users. Notably, its Elo-MMR score falls between the first and third quartiles of scores achieved by human Grandmasters. Furthermore, our results indicate that Agent K v1.0 has reached a performance level equivalent to Kaggle Grandmaster, with a record of 6 gold, 3 silver, and 7 bronze medals, as defined by Kaggle's progression system.

[Arxiv](https://arxiv.org/abs/2411.03562)