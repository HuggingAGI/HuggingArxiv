# 通过针对特定领域的精细调整和循环推理，提升问答系统的性能：一项对比分析研究
发布时间：2024年04月17日
`RAG`
> 本研究深入探讨了特定领域模型微调和推理机制对基于大型语言模型（LLMs）和增强检索生成（RAG）技术的问答（Q&A）系统性能的影响。通过FinanceBench SEC财务文件数据集的分析，我们发现，对于RAG系统而言，将经过微调的嵌入模型与LLM相结合，能够比通用模型获得更高的准确度，尤其是微调的嵌入模型贡献了更多的性能提升。此外，引入RAG之上的推理迭代机制，能够显著提升系统性能，使Q&A系统的表现更趋近于人类专家水平。文章还讨论了这些发现的意义，提出了一个包含Q&A AI主要技术组件的结构化技术设计框架，并为这些组件的技术选择提供了建议。我们将继续这项工作，为AI团队提供实用的指导，并进一步探索特定领域增强在RAG中的作用以及代理AI的高级规划和推理能力。

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.11792/ooda.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.11792/ooda-rag.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.11792/ooda-financebench.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.11792/design-space.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.11792/financebench-categories.png)

[https://wx.zsxq.com/dweb2/index/topic_detail/2855288152528521](https://wx.zsxq.com/dweb2/index/topic_detail/2855288152528521)

[https://arxiv.org/abs/2404.11792](https://arxiv.org/abs/2404.11792)