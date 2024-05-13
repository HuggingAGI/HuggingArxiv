# ProCIS：对话主动检索的标杆在这篇文章中，我们将介绍ProCIS，这是一个专为对话中主动检索设计的基准。它旨在评估和推动对话系统在主动检索信息方面的能力，以提高交互的自然性和效率。通过ProCIS，研究者可以更好地理解和改进对话系统在处理复杂查询和提供即时信息时的表现。

发布时间：2024年05月10日

`Agent

这篇论文主要关注的是主动式对话信息检索系统，这是一种能够监控并适时介入多方对话，提供有用资源和建议的系统。这种系统可以被视为一种智能代理（Agent），因为它能够主动地执行任务，而不仅仅是响应用户的查询。论文中提到的数据集构建、评估指标的提出以及模型的开发，都是为了推动这种主动式系统的研究和应用。因此，这篇论文更符合Agent分类。` `对话系统` `信息检索`

> ProCIS: A Benchmark for Proactive Retrieval in Conversations

# 摘要

> 对话信息检索领域正迅速成为学术界和工业界的热点，它通过自然语言交互重塑了我们与搜索引擎的互动方式。现有研究多聚焦于反应式系统，仅对用户查询做出回应。然而，主动式系统，即能够监控并适时介入多方对话，提供有用资源和建议的系统，尚待深入探索。本文推出一个包含280万对话的大型数据集，用于主动文档检索，并通过众包实验获取高质量的相关性判断。我们还收集了对话与文档关联部分的注释，以评估主动检索系统。我们提出了npDCG作为评估指标，并展示了多种模型的基准结果，包括我们为此任务开发的新模型。我们相信，名为ProCIS的数据集将为主动对话信息检索系统的发展奠定基础。

> The field of conversational information seeking, which is rapidly gaining interest in both academia and industry, is changing how we interact with search engines through natural language interactions. Existing datasets and methods are mostly evaluating reactive conversational information seeking systems that solely provide response to every query from the user. We identify a gap in building and evaluating proactive conversational information seeking systems that can monitor a multi-party human conversation and proactively engage in the conversation at an opportune moment by retrieving useful resources and suggestions. In this paper, we introduce a large-scale dataset for proactive document retrieval that consists of over 2.8 million conversations. We conduct crowdsourcing experiments to obtain high-quality and relatively complete relevance judgments through depth-k pooling. We also collect annotations related to the parts of the conversation that are related to each document, enabling us to evaluate proactive retrieval systems. We introduce normalized proactive discounted cumulative gain (npDCG) for evaluating these systems, and further provide benchmark results for a wide range of models, including a novel model we developed for this task. We believe that the developed dataset, called ProCIS, paves the path towards developing proactive conversational information seeking systems.

[Arxiv](https://arxiv.org/abs/2405.06460)