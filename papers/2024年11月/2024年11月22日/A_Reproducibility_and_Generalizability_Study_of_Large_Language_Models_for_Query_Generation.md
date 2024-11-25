# 一项针对大型语言模型在查询生成方面的可重复性与泛化性的研究

发布时间：2024年11月22日

`LLM应用` `信息检索` `文献综述`

> A Reproducibility and Generalizability Study of Large Language Models for Query Generation

# 摘要

> 系统文献综述（SLRs）堪称学术研究的基石，然而因其细致的文献整理流程，往往劳动强度大且耗时久。生成式人工智能与大型语言模型（LLMs）的出现，有望通过助力研究人员完成若干繁琐任务来变革这一流程，比如生成能筛选出纳入综述的出版物的有效布尔查询。本文针对运用LLMs进行系统综述中的布尔查询生成展开了广泛研究，复现并拓展了Wang等人和Alaniz等人的工作。我们的研究探究了使用ChatGPT生成查询结果的可重复性与可靠性，并将其性能与Mistral和Zephyr等开源替代品作比较，从而对用于生成查询的LLMs进行更全面的分析。
  故而，我们构建了一个管道，它借助先前定义的LLM为给定的综述主题自动创建布尔查询，从PubMed数据库中检索该查询的所有文档，而后评估结果。利用这个管道，我们先是评估使用ChatGPT生成查询所得结果是否可重复且一致。接着，我们通过分析和评估开源模型并衡量它们生成布尔查询的效能来推广我们的成果。
  最后，我们展开故障分析，以识别并探讨使用LLMs进行布尔查询生成的局限与不足。此次检查有助于明晰LLMs在信息检索任务应用中的差距及潜在的改进方向。我们的发现凸显了LLMs在信息检索和文献综述自动化领域的长处、局限和潜力。

> Systematic literature reviews (SLRs) are a cornerstone of academic research, yet they are often labour-intensive and time-consuming due to the detailed literature curation process. The advent of generative AI and large language models (LLMs) promises to revolutionize this process by assisting researchers in several tedious tasks, one of them being the generation of effective Boolean queries that will select the publications to consider including in a review. This paper presents an extensive study of Boolean query generation using LLMs for systematic reviews, reproducing and extending the work of Wang et al. and Alaniz et al. Our study investigates the replicability and reliability of results achieved using ChatGPT and compares its performance with open-source alternatives like Mistral and Zephyr to provide a more comprehensive analysis of LLMs for query generation.
  Therefore, we implemented a pipeline, which automatically creates a Boolean query for a given review topic by using a previously defined LLM, retrieves all documents for this query from the PubMed database and then evaluates the results. With this pipeline we first assess whether the results obtained using ChatGPT for query generation are reproducible and consistent. We then generalize our results by analyzing and evaluating open-source models and evaluating their efficacy in generating Boolean queries.
  Finally, we conduct a failure analysis to identify and discuss the limitations and shortcomings of using LLMs for Boolean query generation. This examination helps to understand the gaps and potential areas for improvement in the application of LLMs to information retrieval tasks. Our findings highlight the strengths, limitations, and potential of LLMs in the domain of information retrieval and literature review automation.

[Arxiv](https://arxiv.org/abs/2411.14914)