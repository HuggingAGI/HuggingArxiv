# 开放词汇多标签视频分类技术
发布时间：2024年07月12日

`文本分类`
> Open Vocabulary Multi-Label Video Classification
>
> 预训练的视觉-语言模型（VLMs）在图像分类、目标检测等开放词汇计算机视觉任务中取得了显著进展。近期研究还将VLMs应用于视频中的开放词汇单标签动作分类。然而，在需要同时识别视频中多个动作和实体的全面视频理解方面，现有方法尚显不足。为此，我们提出了开放词汇多标签视频分类问题，并设计了一种方法，使预训练的VLM（如CLIP）能够适应这一挑战。我们借助大型语言模型（LLMs）为VLM提供类别标签的语义指导，以提升其开放词汇性能。具体来说，我们设计了一种端到端架构，引导LLM生成软属性，帮助CLIP文本编码器识别新类别；同时，我们为CLIP视觉编码器引入了时间建模模块，有效捕捉视频概念的时空动态，并通过一种新颖的正则化微调技术，确保视频领域中卓越的开放词汇分类性能。实验结果表明，我们的方法在多个基准数据集上表现出色。
>
> https://arxiv.org/abs/2407.09073

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.09073/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.09073/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.09073/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.09073/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.09073/x5.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.09073/x6.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.09073/x7.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.09073/x8.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.09073/x9.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.09073/x10.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.09073/x11.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.09073/x12.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.09073/x13.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.09073/x14.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2407.09073](https://arxiv.org/abs/2407.09073)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 加入社群，公众号回复LLM
- 最新论文订阅体验：公众号号菜单回复1