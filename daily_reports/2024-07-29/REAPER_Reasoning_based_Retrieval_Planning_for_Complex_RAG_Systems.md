# REAPER：为复杂 RAG 系统设计的基于推理的检索规划工具
发布时间：2024年07月26日

`RAG`
> REAPER: Reasoning based Retrieval Planning for Complex RAG Systems
>
> 复杂的对话系统常借助检索证据来提供准确回答。RAG系统从庞大的异构数据源中检索信息，这些数据源通常由多个索引或API构成，而非单一整体数据库。针对特定查询，系统需从众多可能的检索源中筛选出相关证据。复杂查询甚至可能涉及多步骤检索，例如，零售网站上的对话代理在回答过往订单相关问题时，需先检索订单信息，再结合产品上下文提取相关证据。多数RAG系统通过交替推理与检索步骤来应对这类思维链任务，但每一步推理都会增加系统延迟，对于大型模型而言，延迟可达数秒。多代理系统虽能将查询定向至特定检索源的代理，但小型分类模型的性能却制约了大型语言模型的发挥。为此，我们推出了REAPER——一种基于LLM的规划器，用于生成对话系统中的检索计划，显著降低了延迟，并能灵活适应新场景。该方法虽适用于各类RAG系统，但我们以亚马逊的对话购物助手Rufus为例，展示了其应用成效。
>
> https://arxiv.org/abs/2407.18553


<hr />

- 论文原文: [https://arxiv.org/abs/2407.18553](https://arxiv.org/abs/2407.18553)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 加入社群，公众号回复LLM
- 最新论文订阅体验：公众号号菜单回复1