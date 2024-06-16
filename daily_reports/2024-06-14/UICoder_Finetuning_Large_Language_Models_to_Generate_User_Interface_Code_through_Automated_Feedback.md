# UICoder：借助自动化反馈，微调大型语言模型，精准生成用户界面代码
发布时间：2024年06月11日

`代码编写`
> UICoder: Finetuning Large Language Models to Generate User Interface Code through Automated Feedback
>
> 大型语言模型（LLMs）在生成既可编译又具有视觉吸引力的UI代码时面临挑战。传统提升生成质量的方法往往依赖于昂贵的人工反馈或专有模型的精馏。本文提出了一种新策略，利用自动化反馈（如编译器和多模态模型）来优化LLMs生成高质量UI代码的能力。我们的方法首先利用现有LLM生成大量合成数据，随后通过自动化工具严格筛选、评分和去重，形成一个精炼的高质量数据集。通过在此数据集上对原始LLM进行微调，我们迭代地改进了模型。实验结果表明，采用此方法的开源LLMs在性能上不仅超越了所有其他可下载的基线模型，甚至接近了更大专有模型的水平。
>
> https://arxiv.org/abs/2406.07739

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.07739/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.07739/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.07739/winrate.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.07739/collage2.jpg)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.07739/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.07739/x4.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2406.07739](https://arxiv.org/abs/2406.07739)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 最新论文订阅体验（3天）：公众号号菜单回复1
- 最新论文订阅新人优惠：公众号号菜单回复2