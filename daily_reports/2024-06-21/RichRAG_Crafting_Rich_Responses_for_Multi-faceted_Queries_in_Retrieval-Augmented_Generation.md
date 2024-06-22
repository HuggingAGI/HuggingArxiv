# RichRAG：打造检索增强生成中的多面手，精准回应复杂查询
发布时间：2024年06月18日

`RAG`
> RichRAG: Crafting Rich Responses for Multi-faceted Queries in Retrieval-Augmented Generation
>
> Retrieval-augmented generation (RAG) 技术有效解决了大型语言模型中的静态知识和幻觉问题。然而，现有研究多聚焦于用户意图明确、答案简洁的问题场景，而忽视了用户常提出的广泛、开放式查询，他们期望得到涵盖多个相关方面的丰富长篇答案。为此，我们创新性地提出了RichRAG框架，它通过子方面探索器识别问题潜在子方面，利用多面体检索器构建相关外部文档候选池，并借助生成式列表排序器精选出前k个最有价值的文档，以满足生成器的偏好，从而产出丰富全面的回答。我们的排序器训练结合了监督微调与强化学习，确保文档覆盖全面且与LLM偏好对齐。实验证明，RichRAG能高效提供令用户满意的全面回答。
>
> https://arxiv.org/abs/2406.12566

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.12566/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.12566/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.12566/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.12566/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.12566/x5.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.12566/x6.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2406.12566](https://arxiv.org/abs/2406.12566)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 最新论文订阅体验：公众号号菜单回复1
- 最新论文订阅新人：公众号号菜单回复2