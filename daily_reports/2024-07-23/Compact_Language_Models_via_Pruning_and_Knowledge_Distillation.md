# 采用剪枝与知识蒸馏技术，打造精简型语言模型
发布时间：2024年07月19日

`动手训练`
> Compact Language Models via Pruning and Knowledge Distillation
>
> 本文探讨了通过剪枝现有大型语言模型（LLM）并利用少量原始训练数据进行再训练，作为全面再训练的替代方案的可行性。我们提出了一套结合多种剪枝技术和知识蒸馏的LLM压缩最佳实践，通过详细实验探索得出。应用这些实践，我们成功将Nemotron-4系列LLM压缩2-4倍，显著减少了训练所需的计算资源，实现了高达1.8倍的计算成本节省。Minitron模型在多项语言建模任务中表现优异，不仅在MMLU评分上领先，还与多个知名社区模型持平或超越，并开源了模型权重及示例代码，供学术和工业界共享。
>
> https://arxiv.org/abs/2407.14679

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.14679/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.14679/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.14679/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.14679/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.14679/x5.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.14679/x6.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.14679/x7.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.14679/x8.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.14679/x9.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.14679/x10.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.14679/x11.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2407.14679](https://arxiv.org/abs/2407.14679)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 加入社群，公众号回复LLM
- 最新论文订阅体验：公众号号菜单回复1