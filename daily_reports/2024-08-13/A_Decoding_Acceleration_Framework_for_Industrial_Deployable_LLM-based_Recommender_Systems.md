# 工业级基于LLM推荐系统的解码加速框架
发布时间：2024年08月10日

`推荐系统`
> A Decoding Acceleration Framework for Industrial Deployable LLM-based Recommender Systems
>
> 近期，基于大型语言模型的推荐系统备受瞩目，但其工业应用尚在探索阶段。多数应用将LLM作为特征增强工具，在离线环节生成知识增补。然而，在用户与项目众多的推荐场景中，即便离线生成也耗时耗力。这一低效源于LLM的自回归特性，而推测解码——一种“草拟-验证”模式，能提升每步解码的令牌产出，成为加速的希望所在。本文首先指出，推荐知识的生成适宜采用基于检索的推测解码。接着，我们发现两大特点：一是推荐系统中项目与用户的广泛性导致检索效率低下，二是系统对LLM生成文本的多样性容忍度高。据此，我们提出DARE框架，通过定制检索池提升检索效率，通过宽松验证提高草拟令牌的接受率。实验证明，DARE能实现3-5倍提速，且兼容多种框架与LLM核心。此外，DARE已成功应用于大规模商业环境的在线广告场景，提速3.45倍，同时保持了推荐效果。
>
> https://arxiv.org/abs/2408.05676

**点击公众号菜单加入大语言模型论文讨论**
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2408.05676](https://arxiv.org/abs/2408.05676)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)