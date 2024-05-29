# 学习推理：程序生成、模拟与搜索的结合
发布时间：2024年05月25日

`代码编写`
> Learning to Reason via Program Generation, Emulation, and Search
>
> 语言模型（LMs）的程序合成能力已开启了一系列推理技能的大门；经过代码优化的LMs在生成解决多种算法符号操作任务（如单词拼接）的程序方面表现出色。然而，并非所有推理任务都能简单转化为代码，比如涉及常识推理、道德判断和讽刺理解的挑战。我们的目标是将LMs的程序合成技能扩展至这些领域，并通过伪程序（即Python程序，其中某些叶函数调用未定义）来评估成果。为此，我们开发了Code Generation and Emulated EXecution（CoGEX），它通过以下方式运作：(1) 训练LMs创造自己的伪程序，(2) 教导它们模拟这些程序的执行，包括未定义的叶函数，让LMs的知识填补执行的空白；(3) 利用它们在众多程序中寻找最优解。为了使CoGEX模型适应新任务，我们提出了一种程序搜索方法，以找到一个在应用于特定数据集的所有实例时能实现最优性能的程序。我们的方法在一系列算法和软推理任务上显著优于传统的上下文学习方法。这一成果展示了代码合成在更广泛问题类别中的应用潜力。我们发布的数据集、微调模型和实现细节可在\url{https://github.com/nweir127/CoGEX}获取。
>
> https://arxiv.org/abs/2405.16337

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.16337/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.16337/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.16337/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.16337/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.16337/x5.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2405.16337](https://arxiv.org/abs/2405.16337)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886