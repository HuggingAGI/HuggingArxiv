# 别用 LLMs 做相关性判断。

发布时间：2024年09月23日

`LLM应用` `信息检索`

> Don't Use LLMs to Make Relevance Judgments

# 摘要

> TREC 风格测试集合的相关性判断既复杂又昂贵，通常需要六名承包商工作数周，并接受培训和监督。随着大型语言模型生成类人文本的能力日益增强，信息检索研究者开始探索其在相关性判断中的应用。在 ACM SIGIR 2024 会议的“LLM4Eval”工作坊上，我们重现了 TREC 深度学习赛道的判断，并探讨了这一问题。我的主题演讲总结道：在 TREC 风格评估中，不宜使用 LLM 进行相关性判断。

> Making the relevance judgments for a TREC-style test collection can be complex and expensive. A typical TREC track usually involves a team of six contractors working for 2-4 weeks. Those contractors need to be trained and monitored. Software has to be written to support recording relevance judgments correctly and efficiently. The recent advent of large language models that produce astoundingly human-like flowing text output in response to a natural language prompt has inspired IR researchers to wonder how those models might be used in the relevance judgment collection process. At the ACM SIGIR 2024 conference, a workshop ``LLM4Eval'' provided a venue for this work, and featured a data challenge activity where participants reproduced TREC deep learning track judgments, as was done by Thomas et al (arXiv:2408.08896, arXiv:2309.10621). I was asked to give a keynote at the workshop, and this paper presents that keynote in article form. The bottom-line-up-front message is, don't use LLMs to create relevance judgments for TREC-style evaluations.

[Arxiv](https://arxiv.org/abs/2409.15133)