# 将大型语言模型提炼为 BERT 用于网络搜索排名的最佳实践

发布时间：2024年11月07日

`LLM应用`

> Best Practices for Distilling Large Language Models into BERT for Web Search Ranking

# 摘要

> 近期的研究强调了大型语言模型（LLMs）作为零样本相关性排序器的巨大潜力。这些方法主要利用提示学习，通过生成潜在文档的排名列表来评估查询和文档之间的相关性。尽管前景可观，但与 LLMs 相关的巨大成本对其在商业搜索系统中的直接应用构成了重大挑战。为了克服这一障碍并充分利用 LLMs 在文本排序方面的能力，我们探索了将 LLMs 的排序专业知识转移到类似于 BERT 的更紧凑模型的技术，使用排序损失来实现资源需求较低的模型的部署。具体而言，我们通过持续预训练来增强 LLMs 的训练，将查询作为输入，点击的标题和摘要作为输出。然后，我们使用排名损失对 LLMs 进行有监督的微调，将最后的标记作为整个句子的代表。鉴于自回归语言模型的固有特性，只有最后的标记 </s> 能够涵盖所有前面的标记。此外，我们引入了一种混合的逐点和边际 MSE 损失，将 LLMs 的排序知识转移到像 BERT 这样的较小模型。这种方法为资源严格受限的环境创造了可行的解决方案。离线和在线评估都证实了我们方法的有效性，截至 2024 年 2 月，我们的模型已成功集成到一个商业网络搜索引擎中。

> Recent studies have highlighted the significant potential of Large Language Models (LLMs) as zero-shot relevance rankers. These methods predominantly utilize prompt learning to assess the relevance between queries and documents by generating a ranked list of potential documents. Despite their promise, the substantial costs associated with LLMs pose a significant challenge for their direct implementation in commercial search systems. To overcome this barrier and fully exploit the capabilities of LLMs for text ranking, we explore techniques to transfer the ranking expertise of LLMs to a more compact model similar to BERT, using a ranking loss to enable the deployment of less resource-intensive models. Specifically, we enhance the training of LLMs through Continued Pre-Training, taking the query as input and the clicked title and summary as output. We then proceed with supervised fine-tuning of the LLM using a rank loss, assigning the final token as a representative of the entire sentence. Given the inherent characteristics of autoregressive language models, only the final token </s> can encapsulate all preceding tokens. Additionally, we introduce a hybrid point-wise and margin MSE loss to transfer the ranking knowledge from LLMs to smaller models like BERT. This method creates a viable solution for environments with strict resource constraints. Both offline and online evaluations have confirmed the efficacy of our approach, and our model has been successfully integrated into a commercial web search engine as of February 2024.

[Arxiv](https://arxiv.org/abs/2411.04539)