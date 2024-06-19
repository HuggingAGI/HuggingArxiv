# 利用语言模型的参数知识生成表格
发布时间：2024年06月16日

`图表问答`
> Generating Tables from the Parametric Knowledge of Language Models
>
> 我们研究如何利用大型语言模型（LLMs）的参数知识生成事实准确的结构化表格，这在金融和医疗等关键领域尤为重要。我们测试了GPT-3.5、GPT-4、Llama2-13B和Llama2-70B这四种顶尖LLMs的表格生成能力，并采用了三种提示策略：全表格、逐行和逐单元格。为了准确评估，我们创建了WikiTabGen这一新基准，包含100个精心挑选的维基百科表格，并确保其事实正确性，同时附有手动编写的自然语言描述。研究结果显示，尽管GPT-4的准确率最高，达到19.6%，但表格生成仍充满挑战。我们的深入分析揭示了表格属性（如大小、流行度和数值内容）对生成效果的影响。这项研究不仅揭示了LLM在表格生成方面的特殊挑战，还为后续研究提供了一个全面的评估框架。所有相关代码、提示和数据已公开发布：https://github.com/analysis-bots/WikiTabGen
>
> https://arxiv.org/abs/2406.10922

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.10922/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.10922/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.10922/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.10922/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.10922/x5.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.10922/x6.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.10922/x7.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.10922/cost.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.10922/x8.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.10922/x9.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.10922/x10.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.10922/x11.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.10922/x12.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.10922/x13.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.10922/x14.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.10922/x15.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.10922/x16.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.10922/x17.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.10922/x18.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.10922/x19.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2406.10922](https://arxiv.org/abs/2406.10922)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 最新论文订阅体验（3天）：公众号号菜单回复1
- 最新论文订阅新人优惠：公众号号菜单回复2