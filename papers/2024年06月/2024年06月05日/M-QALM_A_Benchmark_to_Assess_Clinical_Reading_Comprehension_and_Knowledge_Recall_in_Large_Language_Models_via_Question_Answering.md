# M-QALM：大型语言模型临床阅读理解与知识回忆的问答评估基准。

发布时间：2024年06月05日

`LLM应用

这篇论文主要关注大型语言模型（LLMs）在医疗等高风险领域的应用，特别是在临床和生物医学知识回忆与整合方面的研究。论文通过大规模实验和分析，探讨了如何通过指令调整和特定数据集微调来提升模型的性能，并揭示了模型在知识回忆与情境整合上的能力差距。此外，论文还提供了资源和标准化方法，以促进该领域的进一步发展。因此，这篇论文属于LLM应用类别。` `生物医学`

> M-QALM: A Benchmark to Assess Clinical Reading Comprehension and Knowledge Recall in Large Language Models via Question Answering

# 摘要

> 在医疗等高风险领域，大型语言模型（LLMs）的适应性研究十分活跃。尽管LLMs广受欢迎，但对其在临床和生物医学领域中如何有效回忆并整合知识的理解尚浅。为了深入探究，我们利用多项选择和摘要问答在22个数据集上进行了大规模研究，覆盖通用与专业生物医学子领域。通过细致分析15个LLMs的表现，我们发现了如指令调整等关键因素，这些因素显著提升了模型的知识回忆与理解能力。同时，我们发现直接在特定医学数据集上微调模型，不仅能提升性能，还能推广至未曾涉足的专业领域。此外，通过技能导向的错误分析，我们揭示了模型在知识回忆与情境整合上的能力差距。为了推动这一领域的进步，我们向研究社区开放了M-QALM资源，包括标准化方法和评估结果，以期在语言模型中推动临床知识表示学习的进一步发展。

> There is vivid research on adapting Large Language Models (LLMs) to perform a variety of tasks in high-stakes domains such as healthcare. Despite their popularity, there is a lack of understanding of the extent and contributing factors that allow LLMs to recall relevant knowledge and combine it with presented information in the clinical and biomedical domain: a fundamental pre-requisite for success on down-stream tasks. Addressing this gap, we use Multiple Choice and Abstractive Question Answering to conduct a large-scale empirical study on 22 datasets in three generalist and three specialist biomedical sub-domains. Our multifaceted analysis of the performance of 15 LLMs, further broken down by sub-domain, source of knowledge and model architecture, uncovers success factors such as instruction tuning that lead to improved recall and comprehension. We further show that while recently proposed domain-adapted models may lack adequate knowledge, directly fine-tuning on our collected medical knowledge datasets shows encouraging results, even generalising to unseen specialist sub-domains. We complement the quantitative results with a skill-oriented manual error analysis, which reveals a significant gap between the models' capabilities to simply recall necessary knowledge and to integrate it with the presented context. To foster research and collaboration in this field we share M-QALM, our resources, standardised methodology, and evaluation results, with the research community to facilitate further advancements in clinical knowledge representation learning within language models.

[Arxiv](https://arxiv.org/abs/2406.03699)