# 运用链式思考提示策略，提升医疗错误检测与修正的效率。
发布时间：2024年06月13日

`提示工程`
> Chain-of-Though (CoT) prompting strategies for medical error detection and correction
>
> 本文介绍了我们参与MEDIQA-CORR 2024共享任务的情况，该任务旨在自动识别并修正临床笔记中的医疗错误。我们采用了三种结合思维链（CoT）和推理提示的少样本情境学习（ICL）方法，并利用大型语言模型（LLM）进行增强。首先，我们通过分析训练和验证数据集的一部分，手动设计了三个CoT提示，以识别临床笔记中的错误类型。其次，我们利用训练数据引导LLM推断错误的原因，并将这些CoT和原因与ICL示例结合，以完成错误检测、定位和修正任务。最后，我们通过基于规则的集成方法将这两种策略融合。在三个子任务中，我们的集成方法在子任务1和2中均获得第三名，在子任务3中排名第七。
>
> https://arxiv.org/abs/2406.09103

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09103/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09103/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09103/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09103/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09103/x5.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09103/x6.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2406.09103](https://arxiv.org/abs/2406.09103)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 最新论文订阅体验（3天）：公众号号菜单回复1
- 最新论文订阅新人优惠：公众号号菜单回复2