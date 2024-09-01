# PromptSmooth：利用提示学习确保医疗视觉-语言模型的稳健性
发布时间：2024年08月29日

`多模态大模型`
> PromptSmooth: Certifying Robustness of Medical Vision-Language Models via Prompt Learning
>
> 医学视觉-语言模型（Med-VLMs）经过大量医学图像-文本对数据集的训练和特定任务的微调，已成为医学图像分析的主流。但近期研究指出，这些模型易受对抗性攻击，引发安全与鲁棒性担忧。随机平滑技术虽能提升模型对抗扰动的鲁棒性，但需重新训练模型以适应Gaussian噪声，这在实际中常难以实现。为此，我们提出PromptSmooth框架，利用提示学习，高效提升Med-VLMs的鲁棒性。该框架通过学习文本提示，使预训练模型能零-shot或few-shot适应Gaussian噪声，平衡准确性与鲁棒性，并减少计算负担。此外，PromptSmooth仅需单一模型处理多噪声水平，显著降低传统方法的计算成本。综合实验显示，PromptSmooth在多种成像模式的六个数据集上表现出色。相关代码与模型已公开于https://github.com/nhussein/promptsmooth。
>
> https://arxiv.org/abs/2408.16769

**点击公众号菜单加入大语言模型论文讨论**
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2408.16769](https://arxiv.org/abs/2408.16769)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)