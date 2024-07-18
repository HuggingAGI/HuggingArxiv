# FlashAttention-3：借助异步处理与低精度计算，实现高效且精准的注意力机制。
发布时间：2024年07月11日


> FlashAttention-3: Fast and Accurate Attention with Asynchrony and Low-precision
>
> 注意力机制，作为Transformer架构的核心，已成为大型语言模型和长上下文应用的瓶颈。FlashAttention通过减少内存读写操作，提升了GPU上的注意力计算速度。然而，FlashAttention-2在最新的H100 GPU上仅达到35%的利用率，未能充分利用新硬件的潜力。为此，我们研发了三项关键技术，以进一步加速Hopper GPU上的注意力计算：首先，通过张量核心和TMA的异步特性，实现计算与数据移动的重叠；其次，交错执行块状矩阵乘法和softmax操作；最后，利用硬件对FP8低精度的支持，进行块量化和不连贯处理。实验表明，我们的FlashAttention-3方法在H100 GPU上实现了1.5至2.0倍的加速，FP16精度下达到740 TFLOPs/s（75%利用率），FP8精度下接近1.2 PFLOPs/s。此外，FP8 FlashAttention-3相比基准FP8注意力，数值误差降低了2.6倍。
>
> https://arxiv.org/abs/2407.08608

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.08608/pingpong_pipelining.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.08608/2_stage_pipelining.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.08608/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.08608/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.08608/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.08608/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.08608/x5.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.08608/x6.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.08608/x7.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.08608/x8.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.08608/x9.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.08608/x10.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.08608/3_stage_pipelining.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.08608/x11.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.08608/x12.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.08608/x13.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.08608/x14.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.08608/x15.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.08608/x16.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2407.08608](https://arxiv.org/abs/2407.08608)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 加入社群，公众号回复LLM
- 最新论文订阅体验：公众号号菜单回复1