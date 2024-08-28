# 利用大型语言模型，通过评论驱动个性化偏好推理，提升推荐系统性能。
发布时间：2024年08月12日

`推荐系统`
> Review-driven Personalized Preference Reasoning with Large Language Models for Recommendation
>
> 大型语言模型 (LLM) 的最新进展在众多任务中表现卓越，激发了将其应用于推荐系统的兴趣。然而，现有方法未能充分挖掘 LLM 的潜力，常因输入信息有限或未能充分利用其高级推理能力而受限。为此，我们推出了 EXP3RT，一种基于 LLM 的新型推荐系统，旨在利用用户和商品评论中的丰富偏好信息。EXP3RT 通过从教师 LLM 中提取知识进行微调，依次执行三大关键任务：首先，从原始评论中提取并整合主观偏好，形成用户和商品档案；接着，结合用户/商品档案和商品描述中的主观与客观信息，进行详尽的推理，并预测评分，实现推理增强的评分预测。EXP3RT 的个性化偏好推理不仅提升了评分预测的准确性，还为推荐提供了合理且可信的解释。实验证明，EXP3RT 在评分预测和 top-k 推荐中的商品重排序方面均超越现有方法，大幅提升了推荐系统的可解释性。
>
> https://arxiv.org/abs/2408.06276

**点击公众号菜单加入大语言模型论文讨论**
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)
<hr />

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.06276/intro.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.06276/image.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.06276/humaneval3.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2408.06276](https://arxiv.org/abs/2408.06276)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)