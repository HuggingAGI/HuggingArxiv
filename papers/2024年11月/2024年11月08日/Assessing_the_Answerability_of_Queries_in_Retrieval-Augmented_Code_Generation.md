# 评估检索增强型代码生成中查询的可回答性

发布时间：2024年11月08日

`LLM应用` `软件开发` `代码生成`

> Assessing the Answerability of Queries in Retrieval-Augmented Code Generation

# 摘要

> 由于大型语言模型（LLM）前所未有的语言理解和生成能力，检索增强代码生成（RaCG）最近在软件开发人员中得到了广泛应用。虽然这提高了生产力，但仍然经常提供错误的代码。特别是，对于用户的查询，如果给定的查询和 API 描述无法回答，就会生成看似合理但不正确的代码。本研究提出了一个评估可回答性的任务，该任务评估在 RaCG 中是否可以根据用户的查询和检索到的 API 生成有效答案。此外，我们构建了一个名为检索增强代码生成能力评估（RaCGEval）的基准数据集，以评估执行此任务的模型的性能。实验结果表明，此任务仍处于非常具有挑战性的水平，基线模型的性能低至 46.7％。此外，本研究讨论了可以显著提高性能的方法。

> Thanks to unprecedented language understanding and generation capabilities of large language model (LLM), Retrieval-augmented Code Generation (RaCG) has recently been widely utilized among software developers. While this has increased productivity, there are still frequent instances of incorrect codes being provided. In particular, there are cases where plausible yet incorrect codes are generated for queries from users that cannot be answered with the given queries and API descriptions. This study proposes a task for evaluating answerability, which assesses whether valid answers can be generated based on users' queries and retrieved APIs in RaCG. Additionally, we build a benchmark dataset called Retrieval-augmented Code Generability Evaluation (RaCGEval) to evaluate the performance of models performing this task. Experimental results show that this task remains at a very challenging level, with baseline models exhibiting a low performance of 46.7%. Furthermore, this study discusses methods that could significantly improve performance.

[Arxiv](https://arxiv.org/abs/2411.05547)