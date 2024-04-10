# 在实时搜索中，通过事件增强的检索技术能够更精准地满足用户需求。

发布时间：2024年04月08日

`LLM应用` `搜索系统` `信息检索`

> Event-enhanced Retrieval in Real-time Search

# 摘要

> 嵌入式检索（EBR）在搜索系统中扮演着核心角色，对于消除大型语言模型（LLM）的误解尤为关键。但现有模型常遭遇“语义漂移”并忽略关键信息，导致检索结果的应用受限。在实时搜索中，这一问题尤为突出，因为流行事件的多元表述让检索极度依赖事件关键信息。为此，本研究提出了EER新策略，通过优化传统EBR的双编码器模型，提升实时检索效率。结合对比和成对学习优化编码器，并通过解码器模块强化对事件关键信息的聚焦，同时引入基于提示调整的事件三元组生成机制，以及通过比较学习将事件与查询编码器优化相结合。该解码器在推理时可被移除。实验证明，EER显著提升了实时搜索性能，为信息检索开辟了新视野。相关代码和数据集已在 https://github.com/open-event-hub/Event-enhanced_Retrieval 上发布。

> The embedding-based retrieval (EBR) approach is widely used in mainstream search engine retrieval systems and is crucial in recent retrieval-augmented methods for eliminating LLM illusions. However, existing EBR models often face the "semantic drift" problem and insufficient focus on key information, leading to a low adoption rate of retrieval results in subsequent steps. This issue is especially noticeable in real-time search scenarios, where the various expressions of popular events on the Internet make real-time retrieval heavily reliant on crucial event information. To tackle this problem, this paper proposes a novel approach called EER, which enhances real-time retrieval performance by improving the dual-encoder model of traditional EBR. We incorporate contrastive learning to accompany pairwise learning for encoder optimization. Furthermore, to strengthen the focus on critical event information in events, we include a decoder module after the document encoder, introduce a generative event triplet extraction scheme based on prompt-tuning, and correlate the events with query encoder optimization through comparative learning. This decoder module can be removed during inference. Extensive experiments demonstrate that EER can significantly improve the real-time search retrieval performance. We believe that this approach will provide new perspectives in the field of information retrieval. The codes and dataset are available at https://github.com/open-event-hub/Event-enhanced_Retrieval .

![在实时搜索中，通过事件增强的检索技术能够更精准地满足用户需求。](../../../paper_images/2404.05989/x1.png)

![在实时搜索中，通过事件增强的检索技术能够更精准地满足用户需求。](../../../paper_images/2404.05989/x2.png)

![在实时搜索中，通过事件增强的检索技术能够更精准地满足用户需求。](../../../paper_images/2404.05989/x3.png)

![在实时搜索中，通过事件增强的检索技术能够更精准地满足用户需求。](../../../paper_images/2404.05989/x4.png)

![在实时搜索中，通过事件增强的检索技术能够更精准地满足用户需求。](../../../paper_images/2404.05989/x5.png)

[Arxiv](https://arxiv.org/abs/2404.05989)