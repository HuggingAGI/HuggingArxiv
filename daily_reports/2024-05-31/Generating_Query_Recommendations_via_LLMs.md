# 利用大型语言模型打造智能查询推荐
发布时间：2024年05月30日

`推荐系统`
> Generating Query Recommendations via LLMs
>
> 在现代搜索引擎中，查询推荐系统无处不在，它们助力用户精准获取信息。但这些系统依赖大量数据，如海量文档和查询日志，才能提供优质推荐。特别是在冷启动情况下，查询日志和用户数据难以获取。为此，我们提出了一种创新的生成查询推荐（GQR）方法，它基于LLM，无需额外训练即可工作。我们设计的提示让LLM能够理解并执行推荐任务，即便仅有一个示例。进一步地，我们开发了检索增强型GQR（RA-GQR），它从查询日志中动态检索相似查询以优化提示。GQR方法简化了流程，使其更易于推向市场，即使在冷启动场景下也表现出色。我们的GQR在NDCG@10和清晰度评分上达到了行业领先水平，与两大商业搜索引擎及之前的方法相比，在Robust04和ClueWeb09B数据集上平均提升了约4%的NDCG@10性能。RA-GQR更进一步，将NDCG@10性能分别提升了约11%和6%。此外，在用户盲测中，我们的系统赢得了约59%的用户青睐，证明了其生成的查询极具吸引力。
>
> https://arxiv.org/abs/2405.19749


<hr />

- 论文原文: [https://arxiv.org/abs/2405.19749](https://arxiv.org/abs/2405.19749)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886