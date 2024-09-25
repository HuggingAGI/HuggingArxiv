# DataGpt-SQL-7B：一款专为文本转SQL设计的开源语言模型

发布时间：2024年09月24日

`LLM应用` `数据分析` `数据库`

> DataGpt-SQL-7B: An Open-Source Language Model for Text-to-SQL

# 摘要

> 我们提出了一套精简且微调的模型和自精炼机制，旨在让非专家用户也能轻松访问和分析数据，同时降低闭源大型语言模型的风险。通过构建超过20,000个样本的Text-to-SQL数据集，我们显著提升了SQL生成的效率。此外，模型中集成的代码校正器进一步确保了代码的准确性。我们的DataGpt-sql系统在spider-dev测试中达到了87.2%的准确率，充分证明了其在Text-to-SQL转换任务中的高效性。所有相关资源均可通过\url{https://github.com/CainiaoTechAi/datagpt-sql-7b}获取。

> In addressing the pivotal role of translating natural language queries into SQL commands, we propose a suite of compact, fine-tuned models and self-refine mechanisms to democratize data access and analysis for non-expert users, mitigating risks associated with closed-source Large Language Models. Specifically, we constructed a dataset of over 20K sample for Text-to-SQL as well as the preference dateset, to improve the efficiency in the domain of SQL generation. To further ensure code validity, a code corrector was integrated into the model. Our system, DataGpt-sql, achieved 87.2\% accuracy on the spider-dev, respectively, showcasing the effectiveness of our solution in text-to-SQL conversion tasks. Our code, data, and models are available at \url{https://github.com/CainiaoTechAi/datagpt-sql-7b}

[Arxiv](https://arxiv.org/abs/2409.15985)