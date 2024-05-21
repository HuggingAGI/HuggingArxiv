# xFinder：大型语言模型中精准答案提取的稳健之选
发布时间：2024年05月20日

`应用案例`
> xFinder: Robust and Pinpoint Answer Extraction for Large Language Models
>
> 随着大型语言模型（LLMs）技术的飞速发展，如何公平可靠地评估其性能已成为一个日益突出的问题。特别是诸如测试集泄露和提示格式过度拟合等作弊现象，严重威胁了LLMs评估的可靠性。由于评估框架常依赖正则表达式（RegEx）提取答案，一些模型可能因此调整答案格式以迎合RegEx的提取需求，但这也导致了基于RegEx的答案提取模块频繁出错。本文深入分析了LLM评估的全过程，并指出通过优化关键答案提取模块，不仅能提升提取准确性，减少对特定答案格式的依赖，还能增强评估的整体可靠性。为此，我们开发了xFinder模型，专为关键答案提取设计，并配套创建了Key Answer Finder（KAF）数据集以支持模型的有效训练与评估。实测结果显示，即便是最小规模的xFinder模型，其答案提取准确率也高达93.42%，远超最佳评估框架中RegEx的74.38%。xFinder在鲁棒性和准确性上均优于现有评估框架，其所有资源已公开于\url{https://github.com/IAAR-Shanghai/xFinder}。
>
> https://arxiv.org/abs/2405.11874

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.11874/weakness_eval.jpg)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.11874/example.jpg)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.11874/framework.jpg)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.11874/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.11874/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.11874/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.11874/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.11874/x5.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.11874/x6.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.11874/x7.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.11874/x8.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.11874/x9.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.11874/x10.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.11874/x11.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.11874/x12.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.11874/x13.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.11874/x14.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.11874/x15.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.11874/x16.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.11874/x17.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.11874/x18.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.11874/x19.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.11874/x20.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.11874/x21.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2405.11874](https://arxiv.org/abs/2405.11874)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 公众号回复关键词获取论文原文： 4844515844225128