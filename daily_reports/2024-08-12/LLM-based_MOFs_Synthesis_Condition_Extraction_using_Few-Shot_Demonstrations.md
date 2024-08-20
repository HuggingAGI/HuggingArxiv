# 利用少量示例演示提取基于 LLM 的 MOFs 合成条件
发布时间：2024年08月06日

`RAG`
> LLM-based MOFs Synthesis Condition Extraction using Few-Shot Demonstrations
>
> 提取金属有机框架（MOFs）的合成条件，一直是科研难题，对设计新型MOFs至关重要。大型语言模型（LLMs）的兴起，为这一难题带来了革命性解决方案，最新研究显示，从MOFs文献中提取条件的准确率超过90%。然而，我们发现，多数现有方法仍依赖于基础的零-shot学习，缺乏专业知识可能导致性能下降。为此，我们创新性地引入了少-shot情境学习范式，优化了LLM在材料合成条件提取中的应用。首先，我们设计了人机协同的数据筛选流程，确保少-shot学习的高质量示例。接着，我们采用基于RAG技术的BM25算法，智能挑选适用于每个MOF提取的少-shot示例。实验结果显示，在随机抽取的84,898个MOFs数据集中，我们的少-shot方法在自动评估下，相比原生零-shot LLM，平均F1性能提升了14.8%，且评估更为客观。此外，实际材料实验验证，我们的方法在MOFs结构推断性能上，较基准零-shot LLM平均提升了29.4%。
>
> https://arxiv.org/abs/2408.04665

**点击公众号菜单加入大语言模型论文讨论**
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)
<hr />

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.04665/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.04665/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.04665/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.04665/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.04665/x5.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.04665/x6.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.04665/x7.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.04665/x8.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.04665/x9.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.04665/x10.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.04665/x11.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.04665/x12.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2408.04665](https://arxiv.org/abs/2408.04665)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)