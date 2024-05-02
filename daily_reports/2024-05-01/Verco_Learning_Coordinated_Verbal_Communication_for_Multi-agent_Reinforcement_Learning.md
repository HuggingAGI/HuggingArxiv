![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/imgs/follow2.gif)
# Verco：探索多智能体强化学习中的协同口头沟通技巧
发布时间：2024年04月27日

`多Agent应用`
> 近期，多智能体强化学习在各类游戏场景中实现了重大突破，激发了将其应用于更广泛领域的热情。面对部分可观测性的难题，通过智能体间数值嵌入的共享，通信驱动的算法显著提升了协作效果。尽管如此，我们对于如何形成协作机制的理解尚浅，设计出易于人类理解的通信机制成为了一个亟待解决的问题。本文提出了一种创新的多智能体强化学习算法，该算法将大型语言模型集成到智能体中，使其能够产生易于人类理解的语言交流。框架包含消息生成模块和动作选择模块。消息模块负责生成并向同伴发送口头信息，以促进信息的有效共享。为了提升消息模块的性能，我们引入了一个教师模型来从全局视角生成消息标签，并通过监督式微调（SFT）来训练学生模型。动作模块则根据接收到的信息和局部观察来决策行动。在Overcooked游戏中的实验结果证明，我们的方法不仅显著提升了学习效率和表现，还为人类理解多智能体协作过程提供了一种直观的工具。

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.17780/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.17780/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.17780/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.17780/x4.png)


- 论文原文: [https://arxiv.org/abs/2404.17780](https://arxiv.org/abs/2404.17780)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/imgs/qrcode.png)