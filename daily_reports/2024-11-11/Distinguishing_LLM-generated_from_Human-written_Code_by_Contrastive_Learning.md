# 通过对比学习区分大型语言模型生成的代码和人类编写的代码
发布时间：2024年11月07日

`代码编写`
> Distinguishing LLM-generated from Human-written Code by Contrastive Learning
>
> 大型语言模型（LLM），如 OpenAI 发布的 ChatGPT，由于其在各种任务中生成高质量内容的能力而受到了工业界和学术界的极大关注。尽管 LLM 具有令人印象深刻的能力，但人们对其在新闻、教育和软件工程等各个领域的潜在风险越来越担忧。最近，已经提出了几个商业和开源的 LLM 生成内容检测器，然而，这些检测器主要是为检测自然语言内容而设计的，没有考虑程序代码的特定特征。本文旨在通过提出一种基于对比学习框架和使用 UniXcoder 构建的语义编码器的新型 ChatGPT 生成代码检测器 CodeGPTSensor 来填补这一空白。为了评估 CodeGPTSensor 在区分 ChatGPT 生成的代码和人工编写的代码方面的有效性，我们首先策划了一个大规模的人机比较语料库（HMCorp），其中包括 55 万对人工编写和 ChatGPT 生成的代码（即 28.8 万对 Python 代码对和 22.2 万对 Java 代码对）。基于 HMCorp 数据集，我们对 ChatGPT 生成代码的特征进行的定性和定量分析揭示了区分 ChatGPT 生成的代码和人工编写的代码及其代表性特征所面临的挑战和机遇。我们的实验结果表明，CodeGPTSensor 能够有效地识别 ChatGPT 生成的代码，优于所有选定的基线。
>
> https://arxiv.org/abs/2411.04704

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2411.04704](https://arxiv.org/abs/2411.04704)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)