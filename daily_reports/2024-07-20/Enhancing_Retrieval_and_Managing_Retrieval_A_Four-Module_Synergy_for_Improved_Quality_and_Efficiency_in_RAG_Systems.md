# 通过四模块协同，RAG 系统在增强检索和管理检索方面实现了质量和效率的双重提升。
发布时间：2024年07月15日

`RAG`
> Enhancing Retrieval and Managing Retrieval: A Four-Module Synergy for Improved Quality and Efficiency in RAG Systems
>
> RAG技术借助LLM的上下文学习能力，生成更精准、更贴切的回答。从最初的“检索-阅读”模式，RAG框架已进化为一个高度灵活且模块化的体系。其中，查询重写器模块通过生成易于搜索的查询，提升了知识检索的精准度，使问题与知识库更紧密契合。我们的研究发现，通过生成多重查询以突破单一查询的信息瓶颈，并通过重写问题消除歧义，可以进一步强化查询重写器模块，升级为查询重写器+。同时，针对RAG系统中存在的无关知识问题，我们提出了知识过滤器。这两个模块均基于Gemma-2B模型，共同提升回答质量。此外，针对冗余检索问题，我们引入了记忆知识库和检索器触发器，前者支持知识库的无参数动态扩展，后者优化了外部知识访问成本，提升了资源利用率和响应效率。这四大RAG模块协同作用，显著提升了RAG系统的响应质量和效率。相关实验和消融研究已在六个常见QA数据集上验证了这些模块的有效性。源代码可访问https://github.com/Ancientshi/ERM4获取。
>
> https://arxiv.org/abs/2407.10670

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.10670/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.10670/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.10670/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.10670/x4.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2407.10670](https://arxiv.org/abs/2407.10670)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 加入社群，公众号回复LLM
- 最新论文订阅体验：公众号号菜单回复1