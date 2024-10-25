# IPO：为视觉-语言模型打造的可解释提示优化
发布时间：2024年10月20日


> IPO: Interpretable Prompt Optimization for Vision-Language Models
>
> 预训练的视觉-语言模型如 CLIP 在下游任务中表现出色，但其性能高度依赖于输入文本提示的特异性，这需要精巧的提示模板设计。当前的提示优化方法通过梯度下降学习提示，但往往导致过拟合和生成的提示难以理解。本文提出了一种简单且可解释的提示优化器（IPO），利用大型语言模型（LLM）动态生成文本提示。我们设计了一个提示优化提示，不仅指导 LLM 创建有效提示，还存储了过去提示及其性能指标，提供丰富的上下文信息。此外，我们引入大型多模态模型（LMM），通过生成图像描述来增强文本与视觉模态的交互。这使得 IPO 能够创建特定于数据集的提示，提高泛化性能，同时保持人类理解。在 11 个数据集上的广泛测试显示，IPO 不仅提升了现有基于梯度下降的提示学习方法的准确性，还显著增强了生成提示的可解释性。通过利用 LLM 的优势，我们的方法确保提示保持人类可理解，从而为视觉-语言模型提供更好的透明度和监督。
>
> https://arxiv.org/abs/2410.15397

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2410.15397](https://arxiv.org/abs/2410.15397)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)