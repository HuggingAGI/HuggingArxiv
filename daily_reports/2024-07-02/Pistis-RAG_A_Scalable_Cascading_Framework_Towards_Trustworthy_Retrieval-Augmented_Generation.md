# Pistis-RAG：一款可扩展的级联框架，致力于提升检索增强生成的可信度
发布时间：2024年06月21日

`RAG`
> Pistis-RAG: A Scalable Cascading Framework Towards Trustworthy Retrieval-Augmented Generation
>
> 在希腊神话中，Pistis 代表诚信与信任，与 LLM 系统中 RAG 的核心理念相契合。Pistis-RAG 框架通过多阶段设计，有效应对大规模 RAG 挑战。各阶段分工明确：匹配精炼搜索范围，预排序聚焦语义相关文档，排序则迎合 LLM 偏好。推理与聚合阶段更支持复杂思维链方法的实施。我们指出，LLM 与外部知识排序间的弱关联，源于 RAG 框架的模型中心倾向。而内容中心策略则强调 LLM 与外部信息的无缝融合，优化任务特定内容转换。我们的排序阶段创新性地认识到，仅凭语义相关性未必能提升生成质量，这一洞察基于少数样本提示顺序的敏感性。为此，我们设计了专为 RAG 系统定制的排序阶段，兼顾信息检索原则与 LLM 偏好及用户反馈。通过整合上下文学习与推理步骤，确保用户反馈的有效融入，实现高效对齐。MMLU 基准测试显示性能提升 9.3%，模型与代码将开源。大规模实际数据实验证实了框架的可扩展性。
>
> https://arxiv.org/abs/2407.00072

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.00072/rag_generation.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.00072/ir_vs_rag.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.00072/content-centric.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.00072/model-centric.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.00072/GMSC_online.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.00072/simulate_feedback.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2407.00072](https://arxiv.org/abs/2407.00072)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 加入社群，公众号回复LLM
- 最新论文订阅体验：公众号号菜单回复1