# 双层检索增强生成框架：在低资源医疗问答中，通过 Reddit 数据验证其概念。
发布时间：2024年05月29日

`RAG`
> Two-layer retrieval augmented generation framework for low-resource medical question-answering: proof of concept using Reddit data
>
> 检索增强生成（RAG）通过提供相关上下文，有效约束了生成模型的输出，并降低了产生幻觉的风险。由于大型语言模型（LLM）的上下文令牌数量有限，这限制了生成答案的知识来源。我们提出了一种双层RAG框架，专门用于生成针对查询的答案，并在社交媒体论坛中针对新兴药物信息的查询焦点摘要生成任务上进行了概念验证评估。评估结果显示，在资源有限的环境下，该框架能有效帮助研究人员获取接近实时的用户数据。
>
> https://arxiv.org/abs/2405.19519

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19519/fig1v3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19519/coverage.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19519/coherence.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19519/relevance.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19519/length.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19519/hallucination.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19519/CLI.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19519/QTokenCount.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19519/ISTokenCount.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19519/CLI.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2405.19519](https://arxiv.org/abs/2405.19519)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886