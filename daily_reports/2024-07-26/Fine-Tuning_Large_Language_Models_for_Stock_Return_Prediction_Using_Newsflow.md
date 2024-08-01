# 通过新闻流微调大型语言模型以预测股票回报
发布时间：2024年07月25日


> Fine-Tuning Large Language Models for Stock Return Prediction Using Newsflow
>
> 大型语言模型（LLM）通过微调技术在语言理解和生成任务中表现卓越。本文聚焦于利用财经新闻流预测股票回报的 LLM 微调。在量化投资领域，准确的回报预测是选股和优化投资组合的关键。我们设计的模型包含文本表示和预测两个模块，并探讨了仅编码器和仅解码器 LLM 的不同文本生成方式对预测性能的影响。实验结果显示：(1) 从 LLM 词级别嵌入中聚合的表示能有效提升纯多头和多空组合的性能；(2) 在大型投资组合中，基于解码器 LLM 的模型表现更优，而在小型组合中则无明显优势。在研究的三种 LLM 中，Mistral 在不同组合中表现稳健；(3) LLM 文本表示得出的回报预测在投资组合构建中优于传统情绪分析。
>
> https://arxiv.org/abs/2407.18103

**点击公众号菜单加入大语言模型论文讨论**
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)
<hr />

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.18103/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.18103/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.18103/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.18103/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.18103/x5.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.18103/x6.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.18103/x7.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.18103/x8.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.18103/x9.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.18103/x10.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.18103/x11.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.18103/x12.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.18103/x13.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.18103/x14.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2407.18103](https://arxiv.org/abs/2407.18103)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)