# 提升基于LLM推荐模型的高阶交互感知能力

发布时间：2024年09月30日

`LLM应用` `推荐系统` `电子商务`

> Enhancing High-order Interaction Awareness in LLM-based Recommender Model

# 摘要

> LLM 通过将推荐任务转化为文本生成任务，展现了卓越的推理能力。然而，现有方法在处理用户与项目的高阶交互时表现不佳。为此，我们提出了 ELMRec，通过增强全词嵌入，使 LLM 更有效地理解图构建的交互，无需图预训练。这一创新可能启发将知识图谱融入 LLM 推荐系统。此外，我们发现 LLM 常基于用户早期而非最近的交互进行推荐，为此我们提出了重排序方案。ELMRec 在直接和顺序推荐任务中均超越了现有最先进方法。

> Large language models (LLMs) have demonstrated prominent reasoning capabilities in recommendation tasks by transforming them into text-generation tasks. % many NLP applications including However, existing approaches either disregard or ineffectively model the user--item high-order interactions. To this end, this paper presents an enhanced LLM-based recommender (ELMRec). We enhance whole-word embeddings to substantially enhance LLMs' interpretation of graph-constructed interactions for recommendations, without requiring graph pre-training. This finding may inspire endeavors to incorporate rich knowledge graphs into LLM-based recommenders via whole-word embedding. We also found that LLMs often recommend items based on users' earlier interactions rather than recent ones, and present a reranking solution. Our ELMRec outperforms state-of-the-art (SOTA) methods in both direct and sequential recommendations.

[Arxiv](https://arxiv.org/abs/2409.19979)