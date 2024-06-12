# 个人属性推断的模拟数据集

发布时间：2024年06月11日

`Agent

这篇论文主要关注的是使用大型语言模型（LLMs）来创建合成个人资料的代理，并构建了一个模拟Reddit的框架，以生成一个包含手动标注个人属性的合成数据集（SynthPAI）。这个数据集的目的是为了研究基于LLM的个人属性推断，同时考虑到伦理和隐私问题。因此，这项工作更侧重于使用LLM作为工具来生成数据和模拟环境，以支持隐私研究，而不是深入探讨LLM的理论或应用，也不是关于代理的一般性研究。因此，将其归类为Agent是合适的。` `隐私保护` `数据集构建`

> A Synthetic Dataset for Personal Attribute Inference

# 摘要

> 近期，大型语言模型（LLMs）的强大功能已对全球数亿用户开放，但其强大的世界知识掌握能力也伴随着隐私风险。本研究聚焦于LLMs引发的新兴隐私威胁——从网络文本中精准推断个人信息的潜能。尽管基于LLM的作者分析日益受到重视，但伦理和隐私顾虑导致缺乏合适的公共数据集，阻碍了相关研究。为此，我们采取了两个策略：首先，我们利用合成个人资料的LLM代理，构建了一个模拟Reddit的框架；其次，通过该框架，我们创建了SynthPAI，一个包含7800多条手动标注个人属性的合成数据集。人类研究表明，人们难以区分我们的合成评论与真实评论。此外，我们证实了SynthPAI能有效支持个人属性推断研究，18个顶尖LLM的测试表明，我们的合成数据与真实数据得出的结论一致。这表明，我们的数据集和方法为未来研究提供了坚实且保护隐私的基础，以应对LLMs带来的隐私威胁。

> Recently, powerful Large Language Models (LLMs) have become easily accessible to hundreds of millions of users worldwide. However, their strong capabilities and vast world knowledge do not come without associated privacy risks. In this work, we focus on the emerging privacy threat LLMs pose - the ability to accurately infer personal information from online texts. Despite the growing importance of LLM-based author profiling, research in this area has been hampered by a lack of suitable public datasets, largely due to ethical and privacy concerns associated with real personal data. In this work, we take two steps to address this problem: (i) we construct a simulation framework for the popular social media platform Reddit using LLM agents seeded with synthetic personal profiles; (ii) using this framework, we generate SynthPAI, a diverse synthetic dataset of over 7800 comments manually labeled for personal attributes. We validate our dataset with a human study showing that humans barely outperform random guessing on the task of distinguishing our synthetic comments from real ones. Further, we verify that our dataset enables meaningful personal attribute inference research by showing across 18 state-of-the-art LLMs that our synthetic comments allow us to draw the same conclusions as real-world data. Together, this indicates that our dataset and pipeline provide a strong and privacy-preserving basis for future research toward understanding and mitigating the inference-based privacy threats LLMs pose.

[Arxiv](https://arxiv.org/abs/2406.07217)