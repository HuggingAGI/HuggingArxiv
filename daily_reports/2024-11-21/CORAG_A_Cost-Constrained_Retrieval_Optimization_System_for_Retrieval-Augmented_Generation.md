# CORAG：一个用于检索增强生成的受成本限制的检索优化系统
发布时间：2024年11月01日

`RAG`
> CORAG: A Cost-Constrained Retrieval Optimization System for Retrieval-Augmented Generation
>
> 大型语言模型（LLMs）展现出了非凡的生成能力，然而却常常难以获取最新信息，进而可能产生幻觉。检索增强生成（RAG）通过引入外部数据库的知识来解决此问题，以实现更精准和相关的回应。鉴于LLMs的上下文窗口限制，直接把整个外部数据库的上下文输入模型并不现实。相反，只会有选择地检索最相关的信息，即所谓的“块”。不过，当下的RAG研究面临三大关键挑战。其一，现有的解决方案常常独立选取每个块，忽略了它们之间潜在的关联。其二，在实际应用中，块的效用是非单调的，意味着添加更多块可能会降低整体效用。传统方法着重于最大化所包含块的数量，这可能在不经意间影响性能。其三，每种类型的用户查询都有独特特性，需要定制化处理，而这是当前方法未充分考量的方面。为了攻克这些难题，我们提出了用于检索增强生成的成本受限检索优化系统CORAG。我们运用基于蒙特卡罗树搜索（MCTS）的策略框架，依次找到最优的块组合，从而能够全面考虑块之间的相关性。另外，我们并非将预算耗尽当作终止条件，而是把预算约束融入块组合的优化之中，有效解决了块效用的非单调性问题。
>
> https://arxiv.org/abs/2411.00744

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2411.00744](https://arxiv.org/abs/2411.00744)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)