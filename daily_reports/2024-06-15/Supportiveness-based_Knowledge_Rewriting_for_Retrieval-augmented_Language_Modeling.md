# 基于支持性的知识重写技术，用于提升检索增强型语言模型的性能
发布时间：2024年06月12日

`RAG`
> Supportiveness-based Knowledge Rewriting for Retrieval-augmented Language Modeling
>
> 检索增强型语言模型（RALMs）近期在解决大型语言模型（LLMs）中隐含知识的局限性方面展现出巨大潜力，如对最新专业知识更新不及时和长尾知识保留不可靠。然而，外部知识库和检索器的可靠性无法保证，可能导致检索到的知识对LLM生成无益甚至误导。本文提出了一种基于支持度的知识重写（SKR）方法，这是一种专为LLM生成优化的强大且可插拔的知识重写器。我们引入了“支持度”概念，衡量知识片段对下游任务的促进效果，并考虑其对白盒LLM响应文本的困惑度影响。通过设计训练数据精选策略，我们有效识别并过滤掉低支持度得分的重写，提升数据效用。采用直接偏好优化（DPO）算法，使重写内容与最佳支持度对齐，优化最终响应。在六个知识密集型任务和四个LLM上的评估显示，SKR不仅有效，且在仅7亿参数下，其知识重写能力超越了当前顶尖的通用LLM GPT-4。
>
> https://arxiv.org/abs/2406.08116

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.08116/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.08116/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.08116/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.08116/x4.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2406.08116](https://arxiv.org/abs/2406.08116)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886