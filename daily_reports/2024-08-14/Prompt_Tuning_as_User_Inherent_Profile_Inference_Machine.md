# Prompt Tuning：用户的内在特征推理机
发布时间：2024年08月12日

`提示工程`
> Prompt Tuning as User Inherent Profile Inference Machine
>
> 大型语言模型（LLM）凭借其丰富的世界知识和强大的推理能力，在推荐系统领域展现出显著潜力。然而，这些模型也面临着指令遵循不稳定、模态差异和高延迟推理等难题，这些问题不仅产生了文本噪声，还限制了其在推荐系统中的应用效果。为此，我们引入了UserIP-Tuning方法，该方法通过提示调优技术推断用户特征，巧妙地将用户特征与行为序列间的因果关系融入LLM提示中，并运用期望最大化算法推断潜在特征，有效减少了文本噪声。同时，通过配置文件量化码本，将特征嵌入分类为协同ID，提前存储以优化在线部署，从而提升了效率并降低了内存消耗。实验结果显示，UserIP-Tuning在多个公共数据集上超越了现有推荐算法，进一步的测试和案例分析也验证了其卓越的有效性、稳定性和可迁移性。
>
> https://arxiv.org/abs/2408.06577

**点击公众号菜单加入大语言模型论文讨论**
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)
<hr />

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.06577/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.06577/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.06577/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.06577/x5.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.06577/x6.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.06577/x7.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.06577/x8.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.06577/x9.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.06577/x10.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.06577/x11.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.06577/x12.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.06577/x13.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.06577/x14.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.06577/x15.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2408.06577](https://arxiv.org/abs/2408.06577)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)