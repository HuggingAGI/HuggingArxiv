# W-RAG：开放域问答中的弱监督密集检索技术
发布时间：2024年08月15日

`RAG`
> W-RAG: Weakly Supervised Dense Retrieval in RAG for Open-domain Question Answering
>
> 在开放领域问答等知识密集型任务中，大型语言模型常因仅依赖内部知识而难以生成准确答案。为此，检索增强生成系统通过外部信息检索来强化模型，使检索器成为核心组件。尽管密集检索性能卓越，但其训练因缺乏真实证据而受阻，主要原因是人工标注成本高昂。本文提出W-RAG，利用模型排序能力为密集检索训练生成弱标签数据。我们通过评估模型基于问题和段落生成正确答案的概率，对BM25检索的top-$K$段落重新排序，并将最高排名的段落作为正训练样本。实验显示，与基线模型相比，我们的方法在检索和问答性能上均有显著提升。
>
> https://arxiv.org/abs/2408.08444

**点击公众号菜单加入大语言模型论文讨论**
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)
<hr />

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.08444/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.08444/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.08444/diff_llm.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2408.08444](https://arxiv.org/abs/2408.08444)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)