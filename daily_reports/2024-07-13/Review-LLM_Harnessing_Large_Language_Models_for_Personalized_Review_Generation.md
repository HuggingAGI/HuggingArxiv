# Review-LLM：借助大型语言模型，打造个性化评论生成工具
发布时间：2024年07月10日


> Review-LLM: Harnessing Large Language Models for Personalized Review Generation
>
> 产品评论生成在推荐系统中至关重要，能为推荐增添解释与说服力。近期，大型语言模型如ChatGPT展现了出色的文本建模与生成能力，有望应用于评论生成领域。然而，直接利用这些模型可能因“礼貌”现象而难以产出个性化评论，如负面评价。为此，我们提出Review-LLM，专为个性化评论生成定制。首先，通过整合用户历史行为（含项目标题与评论）构建输入提示，助模型捕捉用户兴趣与评论风格。其次，引入评分作为满意度指标，深化模型对用户偏好的理解及评论情感控制。最终，借助监督微调，使模型针对特定用户与项目生成个性化评论。实验表明，我们的模型在真实数据集上表现优于现有闭源LLMs，评论生成效果更佳。
>
> https://arxiv.org/abs/2407.07487

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.07487/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.07487/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.07487/x3.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2407.07487](https://arxiv.org/abs/2407.07487)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 加入社群，公众号回复LLM
- 最新论文订阅体验：公众号号菜单回复1