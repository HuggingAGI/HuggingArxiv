# 利用跨层注意力优化Transformer键值缓存尺寸
发布时间：2024年05月21日

`动手训练`
> Reducing Transformer Key-Value Cache Size with Cross-Layer Attention
>
> 键值缓存是加速基于变换器的自回归大型语言模型解码的关键技术。但随着序列长度和批量增大，其内存需求激增。为此，多查询注意力（MQA）和分组查询注意力（GQA）应运而生，它们通过共享查询头，显著减少了键值头的数量，且对准确性影响甚微。本文提出了一种新的跨层注意力（CLA）设计，通过在相邻层间共享键值头，进一步压缩了KV缓存的大小，同时几乎不损失准确性。实验表明，CLA在内存与准确性的权衡上实现了优化，使得模型能在更大的批量和更长的序列上进行推理，这是传统MQA所不及的。
>
> https://arxiv.org/abs/2405.12981


<hr />

- 论文原文: [https://arxiv.org/abs/2405.12981](https://arxiv.org/abs/2405.12981)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886