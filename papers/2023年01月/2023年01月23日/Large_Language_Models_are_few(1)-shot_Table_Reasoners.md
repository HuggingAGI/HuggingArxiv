# 大型语言模型展现出在少次学习情境下进行表推理的卓越能力。

发布时间：2023年01月23日

`LLM应用

这篇论文主要探讨了大型语言模型（LLMs）在表格推理任务中的应用，特别是在少量样本上下文学习的情况下。研究通过在多个知名数据集上测试LLMs的表现，展示了它们在处理复杂表格结构推理任务时的有效性。此外，论文还强调了结合“思维链”提示策略的使用，以及LLMs在生成详尽长答案方面的优越性能。这些内容主要关注LLMs在实际应用中的表现和潜力，因此归类为LLM应用。` `数据分析`

> Large Language Models are few(1)-shot Table Reasoners

# 摘要

> 最新文献揭示，大型语言模型（LLMs）在处理文本推理任务时，展现出卓越的少量样本推理能力。但其在表格推理领域的潜力尚未充分挖掘。本研究聚焦于探究LLMs通过少量样本的上下文学习，在表格任务中的表现。我们在WikiTableQuestion、FetaQA、TabFact及FEVEROUS等知名数据集上对LLMs进行了测试，发现尽管未经专门表格数据预训练，LLMs仍能有效处理表格结构的复杂推理。结合“思维链”提示策略，LLMs仅凭一次演示便能取得显著成绩，与顶尖模型不相上下。特别是在FetaQA数据集上，LLMs生成详尽长答案的能力超越了调优后的T5-large。我们深入分析了LLMs生成的推理链，确认其与底层语义高度吻合。我们坚信，LLMs将成为未来研究中一个既简洁又通用的基准。相关代码和数据已公开于https://github.com/wenhuchen/TableCoT。

> Recent literature has shown that large language models (LLMs) are generally excellent few-shot reasoners to solve text reasoning tasks. However, the capability of LLMs on table reasoning tasks is yet to be explored. In this paper, we aim at understanding how well LLMs can perform table-related tasks with few-shot in-context learning. Specifically, we evaluated LLMs on popular table QA and fact verification datasets like WikiTableQuestion, FetaQA, TabFact, and FEVEROUS and found that LLMs are competent at complex reasoning over table structures, though these models are not pre-trained on any table corpus. When combined with `chain of thoughts' prompting, LLMs can achieve very strong performance with only a 1-shot demonstration, even on par with some SoTA models. We show that LLMs are even more competent at generating comprehensive long-form answers on FetaQA than tuned T5-large. We further manually studied the reasoning chains elicited from LLMs and found that these reasoning chains are highly consistent with the underlying semantic form. We believe that LLMs can serve as a simple yet generic baseline for future research. The code and data are released in https://github.com/wenhuchen/TableCoT.

[Arxiv](https://arxiv.org/abs/2210.06710)