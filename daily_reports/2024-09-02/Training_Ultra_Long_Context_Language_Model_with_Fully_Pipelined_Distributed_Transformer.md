# 采用全流水线分布式Transformer技术，我们成功训练了超长上下文语言模型。
发布时间：2024年08月29日

`动手训练`
> Training Ultra Long Context Language Model with Fully Pipelined Distributed Transformer
>
> 在自然语言处理和计算生物学领域，具备长上下文能力的大型语言模型（LLM）对于复杂任务至关重要，如文本生成和蛋白质序列分析。然而，直接在极长上下文上训练这些模型需要大量GPU资源和内存，成本高昂且复杂。本文提出全流水线分布式变换器（FPDT），旨在高效训练长上下文LLM，实现极端硬件效率。对于GPT和Llama模型，我们实现了在相同硬件上训练序列长度提升16倍。借助专用序列块流水线设计，我们能在4个GPU上训练200万序列长度的8B LLM，同时保持55%以上的MFU。FPDT独立于现有训练技术，已在多种LLM模型中证明其高效性。
>
> https://arxiv.org/abs/2408.16978

**点击公众号菜单加入大语言模型论文讨论**
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2408.16978](https://arxiv.org/abs/2408.16978)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)