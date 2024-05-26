# RoPE基础对上下文长度设定了界限
发布时间：2024年05月23日

`动手训练`
> Base of RoPE Bounds Context Length
>
> 位置嵌入是大型语言模型的关键部分，其中旋转位置嵌入（RoPE）通过旋转矩阵编码位置信息，已成为众多模型的首选。RoPE不仅用于增强长上下文处理能力，还通过调整其基础参数来解决位置嵌入中的分布外问题。然而，本文揭示了一个现象：LLMs可能仅表面地增强了长上下文能力。我们重新评估了RoPE在模型中的作用，并发现了一种长期衰减的新特性，指出RoPE的基础参数实际上限制了上下文长度，存在一个绝对下限。这一发现不仅理论上有据，实践上也得到了验证，为未来长上下文模型的训练提供了新的视角。
>
> https://arxiv.org/abs/2405.14591


<hr />

- 论文原文: [https://arxiv.org/abs/2405.14591](https://arxiv.org/abs/2405.14591)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886