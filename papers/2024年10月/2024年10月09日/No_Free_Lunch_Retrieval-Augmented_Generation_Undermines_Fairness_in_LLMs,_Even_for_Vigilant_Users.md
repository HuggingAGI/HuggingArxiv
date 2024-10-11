# 检索增强生成在大型语言模型中损害了公平性，即使是警惕的用户也无法幸免。

发布时间：2024年10月09日

`RAG` `人工智能` `数据科学`

> No Free Lunch: Retrieval-Augmented Generation Undermines Fairness in LLMs, Even for Vigilant Users

# 摘要

> RAG 因其有效性和成本效益被广泛用于提升 LLM 的生成能力，但这种“免费午餐”真的存在吗？我们通过构建一个三级威胁模型，从用户对公平性的意识角度，全面探讨了 RAG 的公平性成本。研究发现，不同程度的用户公平性意识会导致对外部数据集的不同审查程度。实验表明，即使使用完全审查的无偏数据集，RAG 仍可能产生偏见输出，无需微调或重新训练。这凸显了当前对齐方法的局限性，并呼吁开发新的公平性保障策略。我们提出了一些潜在的缓解措施，并呼吁进一步研究，以确保基于 RAG 的 LLM 的公平性。

> Retrieval-Augmented Generation (RAG) is widely adopted for its effectiveness and cost-efficiency in mitigating hallucinations and enhancing the domain-specific generation capabilities of large language models (LLMs). However, is this effectiveness and cost-efficiency truly a free lunch? In this study, we comprehensively investigate the fairness costs associated with RAG by proposing a practical three-level threat model from the perspective of user awareness of fairness. Specifically, varying levels of user fairness awareness result in different degrees of fairness censorship on the external dataset. We examine the fairness implications of RAG using uncensored, partially censored, and fully censored datasets. Our experiments demonstrate that fairness alignment can be easily undermined through RAG without the need for fine-tuning or retraining. Even with fully censored and supposedly unbiased external datasets, RAG can lead to biased outputs. Our findings underscore the limitations of current alignment methods in the context of RAG-based LLMs and highlight the urgent need for new strategies to ensure fairness. We propose potential mitigations and call for further research to develop robust fairness safeguards in RAG-based LLMs.

[Arxiv](https://arxiv.org/abs/2410.07589)