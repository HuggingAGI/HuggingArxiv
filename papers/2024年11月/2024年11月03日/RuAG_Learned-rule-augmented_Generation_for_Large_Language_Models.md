# RuAG：用于大型语言模型的学习规则增强生成

发布时间：2024年11月03日

`RAG`

> RuAG: Learned-rule-augmented Generation for Large Language Models

# 摘要

> In-context learning (ICL) 和 Retrieval-Augmented Generation (RAG) 因其能够通过结合外部知识来增强大型语言模型 (LLM) 的推理能力而受到关注，但受到有限的上下文窗口大小的限制，导致信息注入不足。为此，我们提出了一个新的框架 RuAG，将大量的离线数据自动提炼为可解释的一阶逻辑规则，这些规则被注入到 LLM 中以提高其推理能力。我们的方法首先依靠 LLM 的常识来制定搜索过程，其中 LLM 自动定义头部和主体谓词。然后，RuAG 应用蒙特卡罗树搜索 (MCTS) 来解决组合搜索空间，并有效地从数据中发现逻辑规则。所得的逻辑规则被转换为自然语言，允许有针对性的知识注入，并无缝集成到 LLM 提示中，用于 LLM 的下游任务推理。我们在公共和私人工业任务上评估我们的框架，包括自然语言处理、时间序列、决策和工业任务，证明了其在增强 LLM 在各种任务中的能力方面的有效性。

> In-context learning (ICL) and Retrieval-Augmented Generation (RAG) have gained attention for their ability to enhance LLMs' reasoning by incorporating external knowledge but suffer from limited contextual window size, leading to insufficient information injection. To this end, we propose a novel framework, RuAG, to automatically distill large volumes of offline data into interpretable first-order logic rules, which are injected into LLMs to boost their reasoning capabilities. Our method begins by formulating the search process relying on LLMs' commonsense, where LLMs automatically define head and body predicates. Then, RuAG applies Monte Carlo Tree Search (MCTS) to address the combinational searching space and efficiently discover logic rules from data. The resulting logic rules are translated into natural language, allowing targeted knowledge injection and seamless integration into LLM prompts for LLM's downstream task reasoning. We evaluate our framework on public and private industrial tasks, including natural language processing, time-series, decision-making, and industrial tasks, demonstrating its effectiveness in enhancing LLM's capability over diverse tasks.

[Arxiv](https://arxiv.org/abs/2411.03349)