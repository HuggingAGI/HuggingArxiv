# KaPQA：知识赋能的产品问答系统
发布时间：2024年07月22日

`RAG`
> KaPQA: Knowledge-Augmented Product Question-Answering
>
> 随着大型语言模型的进步，特定领域的问答应用备受瞩目。但准确评估这些应用的性能仍具挑战，关键在于缺乏能真实模拟现实情境的基准。为此，我们推出了两个针对 Adobe Acrobat 和 Photoshop 的问答数据集，旨在助力评估模型在特定领域问答任务中的表现。同时，我们创新性地提出了一个知识驱动的 RAG-QA 框架，以提升问答性能。实验显示，通过查询重构融入领域知识，相较于传统 RAG-QA 方法，检索与生成能力有所增强。尽管改进幅度不大，却凸显了新数据集带来的挑战性。
>
> https://arxiv.org/abs/2407.16073

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.16073/pipeline_rag_5.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.16073/ndcg_exp.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.16073/ps_ndcg_exp.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.16073/gpt4o_ndcg.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.16073/gpt4o_geval.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.16073/ps_gpt4o_ndcg.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.16073/ps_gpt4o_geval.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2407.16073](https://arxiv.org/abs/2407.16073)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 加入社群，公众号回复LLM
- 最新论文订阅体验：公众号号菜单回复1