# CBR-RAG：案例推理辅助生成，提升大型语言模型在法律问答中的检索能力
`RAG`
> 检索增强生成（RAG）技术通过引入先验知识作为输入上下文，提升了大型语言模型（LLM）的输出质量。这在法律问答等需要专业知识和证据支持的任务中尤为有效。基于案例的推理（CBR）在LLM的RAG流程中起到了关键的结构化检索作用。我们提出了CBR-RAG模型，利用CBR的检索阶段、索引词汇和相似性知识库，为LLM查询提供具有上下文相关性的案例，从而丰富了原始查询。我们对CBR-RAG进行了评估，并探讨了在法律问答任务中，不同表示方法（如通用和领域特定嵌入）及比较方法（如内部、内部和混合相似性）的效果。研究结果显示，CBR提供的案例上下文增强了问题与证据之间的相似性，显著提升了生成答案的质量。

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.04302/CBR-RAG.jpg)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.04302/case_act_frequency_distribution.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.04302/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.04302/legal_sim_dist.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.04302/f_score_heatmap_per_k.png)

[https://wx.zsxq.com/dweb2/index/topic_detail/1522421411484252](https://wx.zsxq.com/dweb2/index/topic_detail/1522421411484252)

[https://arxiv.org/abs/2404.04302](https://arxiv.org/abs/2404.04302)