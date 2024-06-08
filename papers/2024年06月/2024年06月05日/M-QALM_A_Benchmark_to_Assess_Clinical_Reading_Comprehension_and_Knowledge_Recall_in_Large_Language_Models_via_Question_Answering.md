# M-QALM：大型语言模型临床阅读理解与知识回忆的问答评估基准

发布时间：2024年06月05日

`LLM应用

这篇论文主要关注大型语言模型（LLMs）在医疗等高风险领域的应用，特别是在临床和生物医学知识整合与回忆方面的能力。通过大规模实证研究，论文探讨了不同模型架构和知识来源下的表现，并发现了影响模型性能的关键因素。此外，论文还提到了领域适应模型的局限性和直接微调的效果，以及模型在知识回忆与整合方面的能力差距。这些内容主要涉及LLM在特定领域的应用和性能优化，因此归类为LLM应用。` `生物医学`

> M-QALM: A Benchmark to Assess Clinical Reading Comprehension and Knowledge Recall in Large Language Models via Question Answering

# 摘要

> 在医疗等高风险领域，大型语言模型（LLMs）的适应性研究十分活跃。尽管这些模型广受欢迎，但它们在临床和生物医学领域中如何有效回忆并整合知识的能力仍未被充分理解，这对下游任务的成功至关重要。为此，我们利用多项选择和摘要问答在22个数据集上进行了大规模实证研究，覆盖了三个通用和三个专业生物医学子领域。通过深入分析15个LLMs在不同子领域、知识来源和模型架构下的表现，我们发现了如指令调整等关键因素，这些因素显著提升了模型的回忆和理解能力。此外，我们发现尽管最新的领域适应模型可能知识储备不足，但在我们收集的医学知识数据集上直接微调却取得了积极成果，甚至能推广至未曾涉足的专业子领域。我们还通过技能导向的手动错误分析揭示了模型在简单回忆知识与结合上下文进行整合方面的能力差距。为了推动该领域的研究与合作，我们向研究社区开放了M-QALM，包括我们的资源、标准化方法和评估结果，旨在促进语言模型中临床知识表示学习的进步。

> There is vivid research on adapting Large Language Models (LLMs) to perform a variety of tasks in high-stakes domains such as healthcare. Despite their popularity, there is a lack of understanding of the extent and contributing factors that allow LLMs to recall relevant knowledge and combine it with presented information in the clinical and biomedical domain: a fundamental pre-requisite for success on down-stream tasks. Addressing this gap, we use Multiple Choice and Abstractive Question Answering to conduct a large-scale empirical study on 22 datasets in three generalist and three specialist biomedical sub-domains. Our multifaceted analysis of the performance of 15 LLMs, further broken down by sub-domain, source of knowledge and model architecture, uncovers success factors such as instruction tuning that lead to improved recall and comprehension. We further show that while recently proposed domain-adapted models may lack adequate knowledge, directly fine-tuning on our collected medical knowledge datasets shows encouraging results, even generalising to unseen specialist sub-domains. We complement the quantitative results with a skill-oriented manual error analysis, which reveals a significant gap between the models' capabilities to simply recall necessary knowledge and to integrate it with the presented context. To foster research and collaboration in this field we share M-QALM, our resources, standardised methodology, and evaluation results, with the research community to facilitate further advancements in clinical knowledge representation learning within language models.

[Arxiv](https://arxiv.org/abs/2406.03699)