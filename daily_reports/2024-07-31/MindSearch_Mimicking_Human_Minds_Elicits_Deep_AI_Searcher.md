# MindSearch：模拟人脑，激发深度AI搜索潜能
发布时间：2024年07月29日


> MindSearch: Mimicking Human Minds Elicits Deep AI Searcher
>
> 信息寻求与整合是一项复杂的认知任务，耗时且费力。受大型语言模型进步的启发，近期研究尝试结合LLMs与搜索引擎来解决这一难题。然而，由于以下挑战，这些方法效果仍不尽如人意：（1）复杂请求难以一次性被搜索引擎准确完整检索；（2）相关信息分散在多个网页，混杂大量噪音；（3）冗长网页内容可能迅速超出LLMs的上下文限制。借鉴人类解决此类问题的认知过程，我们开发了MindSearch，模拟人类在网络信息处理中的思维，通过一个基于LLM的高效多代理框架实现。WebPlanner将多步骤信息寻求过程模型化为动态图构建，分解用户查询为子问题节点，并基于WebSearcher的搜索结果扩展图。WebSearcher负责分层信息检索，为WebPlanner收集关键信息。MindSearch的多代理架构使其能在3分钟内并行处理超过300个网页，效率相当于人类3小时的工作。在封闭与开放集QA问题上，MindSearch在响应的深度与广度上均有显著提升。此外，基于InternLM2.5-7B的MindSearch生成的响应更受人类喜爱，超越了ChatGPT-Web和Perplexity.ai，显示出其在专属AI搜索引擎领域的竞争力。
>
> https://arxiv.org/abs/2407.20183

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.20183/framework.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.20183/planner_demo.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.20183/searcher.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.20183/openset.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.20183/openset_demo.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2407.20183](https://arxiv.org/abs/2407.20183)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 加入社群，公众号回复LLM
- 最新论文订阅体验：公众号号菜单回复1