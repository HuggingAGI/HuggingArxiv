# 基于分治策略的截图自动生成UI代码方法
发布时间：2024年06月24日

`代码编写`
> Automatically Generating UI Code from Screenshot: A Divide-and-Conquer-Based Approach
>
> 在数字化时代，网站的重要性不言而喻，全球活跃网站超过11亿，每天新增约252,000个。将网站设计图转换为实用的UI代码，虽耗时却至关重要。传统的手动转换方法对非专业人士来说挑战重重。为此，我们研究了GPT-4o，并发现了UI代码生成中的三大问题：元素遗漏、变形和错位。我们发现，聚焦于小视觉片段能帮助多模态大型语言模型（MLLMs）减少这些错误。本文介绍了DCGen，一种基于分而治之的策略，能自动将网页设计转化为UI代码。DCGen首先将截图细分为小片段，为每个片段生成描述，再整合成完整的UI代码。通过大量测试，我们发现DCGen在视觉相似性上比其他方法提升了14%。DCGen是首个基于分段感知的提示方法，能直接从截图生成UI代码。
>
> https://arxiv.org/abs/2406.16386

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.16386/annotation.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.16386/omission.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.16386/hallucination.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.16386/misarrange.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.16386/pilot_direct.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.16386/pilot_divide.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.16386/pilot_original.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.16386/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.16386/example.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.16386/example_cut1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.16386/example_cut2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.16386/hard_line.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.16386/soft_line.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.16386/subdivision.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.16386/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.16386/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.16386/RQ1_detail.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.16386/case_study.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.16386/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.16386/RQ3_clip.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.16386/RQ3_bleu.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.16386/RQ3_merge.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2406.16386](https://arxiv.org/abs/2406.16386)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 最新论文订阅体验：公众号号菜单回复1
- 最新论文订阅新人：公众号号菜单回复2