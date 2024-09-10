# LLM 驱动的异构数据问答系统及其基准测试

发布时间：2024年09月09日

`LLM应用` `数据管理`

> A System and Benchmark for LLM-based Q\&A on Heterogeneous Data

# 摘要

> 在工业场景中，用户常需从电子表格、数据库或API等结构化数据源中寻找答案，却往往不知如何找到或访问这些数据。若需整合多个数据源，问题更为复杂。近期，借助大型语言模型的Text-to-SQL应用虽能以自然语言提问，但在处理数据源多样性上仍显不足。本文提出siwarex平台，实现对数据库和API的自然语言无缝访问，解决数据异质性问题。我们通过扩展Spider数据集，用API替代部分表格，验证了siwarex的有效性。修改后的Spider基准即将开放给研究社区。

> In many industrial settings, users wish to ask questions whose answers may be found in structured data sources such as a spreadsheets, databases, APIs, or combinations thereof. Often, the user doesn't know how to identify or access the right data source. This problem is compounded even further if multiple (and potentially siloed) data sources must be assembled to derive the answer. Recently, various Text-to-SQL applications that leverage Large Language Models (LLMs) have addressed some of these problems by enabling users to ask questions in natural language. However, these applications remain impractical in realistic industrial settings because they fail to cope with the data source heterogeneity that typifies such environments. In this paper, we address heterogeneity by introducing the siwarex platform, which enables seamless natural language access to both databases and APIs. To demonstrate the effectiveness of siwarex, we extend the popular Spider dataset and benchmark by replacing some of its tables by data retrieval APIs. We find that siwarex does a good job of coping with data source heterogeneity. Our modified Spider benchmark will soon be available to the research community

[Arxiv](https://arxiv.org/abs/2409.05735)