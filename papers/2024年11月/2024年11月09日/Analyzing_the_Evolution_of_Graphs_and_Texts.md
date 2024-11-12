# 分析图形和文本的演变

发布时间：2024年11月09日

`其他` `图算法` `文本分析`

> Analyzing the Evolution of Graphs and Texts

# 摘要

> 随着图（例如，DeepWalk/GraphSage）和自然语言（例如，Word2Vec/BERT）表示学习算法的最新进展，最先进的模型甚至可以在许多下游任务中达到人类水平的性能，特别是对于节点和句子分类的任务。然而，大多数算法专注于静态图和文本语料库的大规模模型，而不考虑内在的动态特征或发现变化背后的原因。本论文旨在有效地对图（如社交网络和引文图）中的动态进行建模，并理解文本（特别是新闻标题和个人传记）中的变化。为了实现这一目标，我们利用著名的个性化 PageRank 算法为不断发展的图创建有效的动态网络嵌入。我们提出的方法显著提高了检测网络异常入侵者和发现大规模动态图中实体意义变化的运行时间和准确性。对于文本变化，我们分析新闻标题发布后的变化，以了解编辑背后的意图，并从信息完整性的角度讨论标题变化的潜在影响。此外，我们研究了 Twitter 用户传记中五年内自我呈现的职业身份，调查了人们披露工作时的工作声望和人口统计学影响，量化了过度代表的工作及其随时间的转变。

> With the recent advance of representation learning algorithms on graphs (e.g., DeepWalk/GraphSage) and natural languages (e.g., Word2Vec/BERT) , the state-of-the art models can even achieve human-level performance over many downstream tasks, particularly for the task of node and sentence classification. However, most algorithms focus on large-scale models for static graphs and text corpus without considering the inherent dynamic characteristics or discovering the reasons behind the changes. This dissertation aims to efficiently model the dynamics in graphs (such as social networks and citation graphs) and understand the changes in texts (specifically news titles and personal biographies). To achieve this goal, we utilize the renowned Personalized PageRank algorithm to create effective dynamic network embeddings for evolving graphs. Our proposed approaches significantly improve the running time and accuracy for both detecting network abnormal intruders and discovering entity meaning shifts over large-scale dynamic graphs. For text changes, we analyze the post-publication changes in news titles to understand the intents behind the edits and discuss the potential impact of titles changes from information integrity perspective. Moreover, we investigate self-presented occupational identities in Twitter users' biographies over five years, investigating job prestige and demographics effects in how people disclose jobs, quantifying over-represented jobs and their transitions over time.

[Arxiv](https://arxiv.org/abs/2411.06295)