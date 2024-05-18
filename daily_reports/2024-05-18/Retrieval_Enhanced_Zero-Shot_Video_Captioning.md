# 零-shot视频字幕生成通过检索增强技术得到提升，本研究探索了如何利用检索机制来优化视频内容的自动描述过程。
发布时间：2024年05月11日

`多模态大模型`
> Retrieval Enhanced Zero-Shot Video Captioning
>
> 尽管全监督视频字幕技术已取得显著成就，但零-shot方法的探索仍显不足。本文提出利用预训练的视觉与语言模型，通过测试时适应直接生成视频字幕。我们采用XCLIP、CLIP和GPT-2三个模型，因其源码开放，作为视频与文本的桥梁。关键挑战在于如何让GPT-2充分理解视频内容以生成恰当字幕。为此，我们提出使用可学习标记作为GPT-2与XCLIP、CLIP之间的沟通桥梁。不同于传统训练方式，我们通过精心设计的损失函数，利用推理数据的伪目标来训练这些标记，使其能够为GPT-2捕捉视频信息。这一过程仅需数轮迭代（实验中为16轮），无需真实数据。在MSR-VTT、MSVD和VATEX三个数据集上的实验表明，我们的方法在CIDEr指标上比现有技术提升了4%至20%。
>
> https://arxiv.org/abs/2405.07046


<hr />

- 论文原文: [https://arxiv.org/abs/2405.07046](https://arxiv.org/abs/2405.07046)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886