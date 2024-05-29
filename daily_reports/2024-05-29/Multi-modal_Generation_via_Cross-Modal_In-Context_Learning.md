# 跨模态上下文学习驱动多模态内容生成
发布时间：2024年05月28日

`多模态大模型`
> Multi-modal Generation via Cross-Modal In-Context Learning
>
> 本研究探讨了如何从复杂的多元模态提示序列中创造新颖图像。尽管现有技术在文本到图像转换上表现不俗，但它们在处理长篇提示时难以捕捉细微之处，且难以维持提示序列的上下文连贯性。特别是当提示涉及多个对象时，生成的图像往往与提示不符。为此，我们开发了一种名为MGCC的新方法，它结合了大型语言模型和扩散模型的力量，通过跨模态上下文学习来生成图像。MGCC包含一个创新的跨模态细化模块，专门用于学习文本与图像在LLM嵌入空间中的相互依赖，以及一个上下文对象定位模块，旨在为多对象场景精确生成对象边界框。MGCC不仅能够生成新颖图像，还能促进多模态对话和文本创作。实验结果显示，在VIST和VisDial两个数据集上，MGCC的表现均优于现有技术，分别达到0.652和0.660的CLIP相似度分数，显著超越了SOTA方法的0.641和0.645。代码已公开：https://github.com/VIROBO-15/MGCC。
>
> https://arxiv.org/abs/2405.18304

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.18304/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.18304/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.18304/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.18304/x5.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.18304/x6.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.18304/x7.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2405.18304](https://arxiv.org/abs/2405.18304)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886