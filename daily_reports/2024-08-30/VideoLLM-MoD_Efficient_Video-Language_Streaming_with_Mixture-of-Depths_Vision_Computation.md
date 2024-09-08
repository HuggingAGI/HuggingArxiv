# VideoLLM-MoD：利用深度混合视觉计算技术，实现视频语言流的高效处理
发布时间：2024年08月29日

`多模态大模型`
> VideoLLM-MoD: Efficient Video-Language Streaming with Mixture-of-Depths Vision Computation
>
> 在大型视觉-语言模型中，增加视觉标记虽能提升理解力，却也大幅增加了内存与计算负担，尤其是在处理长视频流时。尽管已有方法如Q-Former和Perceiver Resampler尝试减轻这一负担，但它们未能充分利用LLMs的键值缓存上下文，可能导致视觉线索的遗漏。本文提出了一种创新策略——VideoLLM-MoD，通过“跳过层”方式利用冗余视觉标记，而非简单减少标记数量，有效降低了计算需求。具体而言，我们训练模型跳过大部分视觉标记的计算，直接传递至下一层，从而显著提升效率，节省约42%的训练时间和30%的内存。这种方法不仅减少了计算量，还保持了视觉标记的数量，甚至在性能上超越了原始模型。实验结果显示，VideoLLM-MoD在多个数据集的叙述、预测和总结任务中均达到了业界领先水平。
>
> https://arxiv.org/abs/2408.16730

**如遇无法添加，请+ vx: iamxxn886**
<hr />

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.16730/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.16730/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.16730/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.16730/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.16730/x5.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.16730/x6.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.16730/x7.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.16730/vtoken.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.16730/ktoken.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.16730/ttoken.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2408.16730](https://arxiv.org/abs/2408.16730)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)