# 借助LLM知识转移提升零-shot面部表情识别能力
发布时间：2024年05月29日

`多模态大模型`
> Enhancing Zero-Shot Facial Expression Recognition by LLM Knowledge Transfer
>
> 目前的面部表情识别模型多依赖于监督学习，受限于缺乏大量高质量标注的面部表情图像，导致在未见过的图像上泛化能力差。基于视觉-语言的零样本模型虽有潜力，但因缺乏针对面部表情识别的特定知识，未能优化处理细微表情。为此，我们提出了Exp-CLIP方法，通过从大型语言模型转移知识，增强零样本面部表情识别。该方法利用预训练的视觉-语言编码器，并引入一个投影头，将视觉-语言空间映射至捕捉面部动作特征的空间。通过将视觉表示与LLM编码器提取的任务特定语义对齐，并采用文本指令定制LLM知识，Exp-CLIP在七个野外FER数据集上超越了CLIP及其他大型视觉-语言模型，实现了卓越的零样本性能。相关代码和模型已公开于\url{https://github.com/zengqunzhao/Exp-CLIP}。
>
> https://arxiv.org/abs/2405.19100

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19100/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19100/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19100/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19100/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19100/x5.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19100/x6.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19100/x7.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19100/x8.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19100/x9.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19100/x10.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19100/x11.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19100/x12.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19100/x13.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19100/x14.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19100/x15.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19100/x16.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2405.19100](https://arxiv.org/abs/2405.19100)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886