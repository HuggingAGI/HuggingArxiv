# LongSkywork：大型语言模型上下文长度扩展的高效训练秘籍
发布时间：2024年06月01日

`动手训练`
> LongSkywork: A Training Recipe for Efficiently Extending Context Length in Large Language Models
>
> 我们推出了LongSkywork，这是一种能够处理高达200,000个令牌的长上下文大型语言模型。我们提供了一套高效的训练方案，用以扩展LLM的上下文长度。关键在于，在标准SFT阶段后引入长上下文SFT阶段，仅需200次迭代即可将模型升级为长上下文处理能手。为了简化数据收集和标注的繁琐过程，我们创新性地开发了两种合成数据生成方法，这些方法在预训练和SFT阶段均得到应用，显著提升了训练效率。研究表明，这些合成的长上下文SFT数据在性能上甚至能超越人工精选数据。LongSkywork在多个长上下文基准测试中大放异彩，尤其在Needle测试中，模型在多个上下文跨度上实现了满分表现。在实际应用中，LongSkywork-13B与顶尖的长上下文模型Claude2.1并驾齐驱，充分验证了我们方法的卓越效果。
>
> https://arxiv.org/abs/2406.00605

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.00605/output.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.00605/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.00605/traing_loss.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2406.00605](https://arxiv.org/abs/2406.00605)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886