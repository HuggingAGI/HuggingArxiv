# 利用两阶段前缀增强的多模态LLM，为电影生成事件导向的归因

发布时间：2024年09月14日

`LLM应用` `社交媒体` `电影分析`

> Generating Event-oriented Attribution for Movies via Two-Stage Prefix-Enhanced Multimodal LLM

# 摘要

> 社交媒体的繁荣催生了对于语义丰富服务（如事件和故事线归属）的迫切需求。然而，现有研究多聚焦于片段级事件理解，忽略了整部电影中事件的因果分析。这成为一大难题，因为即便是最先进的多模态大型语言模型（MLLM）也受限于上下文长度，难以处理复杂的多模态信息。为此，我们提出了一种两阶段前缀增强的MLLM（TSPE）方法，旨在电影视频中连接事件与其因果语义。在局部阶段，我们通过交互感知前缀引导模型聚焦于单一片段内的相关信息，简要概括事件。在全局阶段，我们利用推理性知识图谱强化事件间的联系，并设计事件感知前缀，使模型专注于相关事件而非所有片段，从而实现精准的事件归属。实验证明，我们的框架在真实数据集上的表现超越了现有最先进的方法。

> The prosperity of social media platforms has raised the urgent demand for semantic-rich services, e.g., event and storyline attribution. However, most existing research focuses on clip-level event understanding, primarily through basic captioning tasks, without analyzing the causes of events across an entire movie. This is a significant challenge, as even advanced multimodal large language models (MLLMs) struggle with extensive multimodal information due to limited context length. To address this issue, we propose a Two-Stage Prefix-Enhanced MLLM (TSPE) approach for event attribution, i.e., connecting associated events with their causal semantics, in movie videos. In the local stage, we introduce an interaction-aware prefix that guides the model to focus on the relevant multimodal information within a single clip, briefly summarizing the single event. Correspondingly, in the global stage, we strengthen the connections between associated events using an inferential knowledge graph, and design an event-aware prefix that directs the model to focus on associated events rather than all preceding clips, resulting in accurate event attribution. Comprehensive evaluations of two real-world datasets demonstrate that our framework outperforms state-of-the-art methods.

[Arxiv](https://arxiv.org/abs/2409.09362)