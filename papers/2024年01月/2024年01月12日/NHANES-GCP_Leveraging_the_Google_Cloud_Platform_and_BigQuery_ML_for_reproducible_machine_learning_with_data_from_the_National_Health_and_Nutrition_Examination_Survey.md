# NHANES-GCP：借助Google Cloud Platform与BigQuery ML，我们能够对国家健康与营养检查调查的数据进行高效且可重复的机器学习。

发布时间：2024年01月12日

`LLM应用

理由：这篇论文介绍了NHANES-GCP，一个基于Google Cloud Platform (GCP) 的自动化数据工程和管理工具，旨在简化数据管理和清洗过程，提高研究效率和分析的可重复性。该工具特别强调了为统计、机器学习及大型语言模型（LLMs）的微调提供优质数据资源。这表明该论文主要关注于如何应用技术（如GCP和BigQuery ML）来优化数据处理流程，以支持LLMs的应用，因此属于LLM应用类别。` `健康与营养调查` `数据管理`

> NHANES-GCP: Leveraging the Google Cloud Platform and BigQuery ML for reproducible machine learning with data from the National Health and Nutrition Examination Survey

# 摘要

> NHANES，美国国家健康与营养检查调查，由CDC主导，旨在评估国民健康与营养状况。生物统计学家和临床科学家常用此数据研究美国健康趋势，但每次分析前的数据管理和清洗工作繁琐且耗时，影响研究效率和分析的可重复性。为此，我们开发了NHANES-GCP，一个基于GCP的自动化数据工程和管理工具，成本低廉（运行成本不足2美元，年度托管成本不足15美元），提供清洁数据表，便于大规模分析。通过BigQuery ML，我们展示了如何通过单一SQL查询实现数据选择、整合、模型训练及结果生成。NHANES-GCP旨在提升分析的可重复性，并为统计、机器学习及LLMs的微调提供优质数据资源。可用性与实施：NHANES-GCP可在https://github.com/In-Vivo-Group/NHANES-GCP获取。

> Summary: NHANES, the National Health and Nutrition Examination Survey, is a program of studies led by the Centers for Disease Control and Prevention (CDC) designed to assess the health and nutritional status of adults and children in the United States (U.S.). NHANES data is frequently used by biostatisticians and clinical scientists to study health trends across the U.S., but every analysis requires extensive data management and cleaning before use and this repetitive data engineering collectively costs valuable research time and decreases the reproducibility of analyses. Here, we introduce NHANES-GCP, a Cloud Development Kit for Terraform (CDKTF) Infrastructure-as-Code (IaC) and Data Build Tool (dbt) resources built on the Google Cloud Platform (GCP) that automates the data engineering and management aspects of working with NHANES data. With current GCP pricing, NHANES-GCP costs less than $2 to run and less than $15/yr of ongoing costs for hosting the NHANES data, all while providing researchers with clean data tables that can readily be integrated for large-scale analyses. We provide examples of leveraging BigQuery ML to carry out the process of selecting data, integrating data, training machine learning and statistical models, and generating results all from a single SQL-like query. NHANES-GCP is designed to enhance the reproducibility of analyses and create a well-engineered NHANES data resource for statistics, machine learning, and fine-tuning Large Language Models (LLMs).
  Availability and implementation" NHANES-GCP is available at https://github.com/In-Vivo-Group/NHANES-GCP

[Arxiv](https://arxiv.org/abs/2401.06967)