# 自组织的智能代理：构建面向极大规模代码生成与优化的多代理大型语言模型框架。
`Agent应用`
> 借助大型语言模型（LLM）代理实现的自动代码生成技术，正引领我们走向自动化软件开发的新纪元。然而，单一代理方法在处理庞大而复杂的代码库时，受限于上下文长度而显得力不从心。为突破这一局限，我们设计了自组织多代理框架（SoA），这一创新框架让大规模代码的生成与优化工作变得更加高效和可扩展。在SoA框架下，各代理能够独立生成及调整代码组件，并协同作业，共同构建完整的代码库。该框架的核心优势在于能够根据问题的复杂性自动扩充代理队伍，实现动态扩展。这意味着整体代码量可以随着代理数量的增加而无限扩展，而每位代理所管理的代码量则保持恒定。通过在HumanEval基准测试中的评估，我们发现SoA中的每位代理处理的代码量较单一代理系统大幅减少，但生成的代码总量却显著提升。更值得一提的是，SoA在Pass@1准确率上比单一代理基线提高了5%，展现出更为卓越的性能。
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.02183/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.02183/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.02183/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.02183/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.02183/x5.png)
