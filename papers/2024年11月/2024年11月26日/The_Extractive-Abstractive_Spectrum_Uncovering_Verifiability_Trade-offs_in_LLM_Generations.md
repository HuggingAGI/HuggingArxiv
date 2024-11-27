# 提取-摘要频谱：揭示 LLM 生成中的可验证性的权衡之处

发布时间：2024年11月26日

`LLM应用` `学术研究` `信息共享`

> The Extractive-Abstractive Spectrum: Uncovering Verifiability Trade-offs in LLM Generations

# 摘要

> 在所有学术研究领域，专家分享信息时都会注明出处。然而，大型语言模型（LLMs）虽善于整合信息，却无法为信息来源提供可靠的引用，导致难以追溯和核实其提供信息的源头。相较而言，搜索引擎能让用户轻松获取来源，把整合信息的担子交给了用户。通过调查，我们发现，在高风险查询方面，用户更倾向于搜索引擎而非 LLMs，因为对信息出处的担忧超过了对 LLMs 回应的效用感知。为探究信息共享工具的可验证性与效用的相互关系，我们引入了抽取-摘要频谱，其中搜索引擎和 LLMs 是涵盖多个未探索中间操作点的两个极端。搜索引擎属于抽取式，因为它们通过带有指向原始网页链接（引用）的来源片段来回应查询。LLMs 属于摘要式，因为它们处理查询时给出的答案是对来自训练和上下文来源的相关信息进行综合与逻辑转换，且没有可靠引用。我们定义了跨越抽取-摘要频谱的五个操作点，并针对反映现实世界问答场景的四个不同查询分布中的七个系统进行了人工评估，包括网络搜索、语言简化、多步推理和医疗建议。随着输出愈发摘要化，我们发现感知效用最多可提高 200%，而正确引用句子的比例最多下降 50%，用户验证引用信息的时间最多延长至 3 倍。我们的研究成果为特定领域的 LLMs 系统推荐了不同的操作点，我们的失败分析也为高效用 LLMs 系统的方法提供了参考，让用户能够验证信息。

> Across all fields of academic study, experts cite their sources when sharing information. While large language models (LLMs) excel at synthesizing information, they do not provide reliable citation to sources, making it difficult to trace and verify the origins of the information they present. In contrast, search engines make sources readily accessible to users and place the burden of synthesizing information on the user. Through a survey, we find that users prefer search engines over LLMs for high-stakes queries, where concerns regarding information provenance outweigh the perceived utility of LLM responses. To examine the interplay between verifiability and utility of information-sharing tools, we introduce the extractive-abstractive spectrum, in which search engines and LLMs are extreme endpoints encapsulating multiple unexplored intermediate operating points. Search engines are extractive because they respond to queries with snippets of sources with links (citations) to the original webpages. LLMs are abstractive because they address queries with answers that synthesize and logically transform relevant information from training and in-context sources without reliable citation. We define five operating points that span the extractive-abstractive spectrum and conduct human evaluations on seven systems across four diverse query distributions that reflect real-world QA settings: web search, language simplification, multi-step reasoning, and medical advice. As outputs become more abstractive, we find that perceived utility improves by as much as 200%, while the proportion of properly cited sentences decreases by as much as 50% and users take up to 3 times as long to verify cited information. Our findings recommend distinct operating points for domain-specific LLM systems and our failure analysis informs approaches to high-utility LLM systems that empower users to verify information.

[Arxiv](https://arxiv.org/abs/2411.17375)