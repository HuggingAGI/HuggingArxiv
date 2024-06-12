# 探究大型语言模型在表格信息检索中的局限性
发布时间：2024年06月06日

`图表问答`
> Uncovering Limitations of Large Language Models in Information Seeking from Tables
>
> 表格因其信息密度高且应用广泛，成为不可或缺的信息源。大型语言模型（LLMs）从表格中提取信息（TIS）的能力至关重要，支撑着基于知识的问答系统。但目前该领域评估不足，缺乏可靠性。为此，本文推出了一个更为可靠的表格信息检索（TabIS）基准，采用单选题形式（每题两选项），避免了基于文本相似度的评估不准确性。我们构建了一套高效的选项生成机制，确保题目难度与质量。实验涵盖12种LLMs，结果显示，尽管GPT-4-turbo表现尚可，其他模型则不尽人意。深入分析发现，LLMs在理解表格结构上存在短板，且在TIS性能与抵御伪相关表格（检索增强系统中常见）的鲁棒性之间难以取舍。这些发现揭示了LLMs在表格信息检索方面的局限与挑战。我们已公开数据与代码，以期推动该领域的深入研究。
>
> https://arxiv.org/abs/2406.04113

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.04113/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.04113/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.04113/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.04113/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.04113/x5.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.04113/x6.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.04113/x7.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.04113/x8.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.04113/x9.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.04113/x10.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.04113/x11.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.04113/x12.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.04113/x13.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.04113/x14.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.04113/x15.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2406.04113](https://arxiv.org/abs/2406.04113)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886