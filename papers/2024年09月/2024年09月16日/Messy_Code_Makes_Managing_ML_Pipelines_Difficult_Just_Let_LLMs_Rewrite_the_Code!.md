# 代码混乱不堪，管理机器学习管道难上加难？交给大型语言模型，让它帮你重写代码，轻松搞定！

发布时间：2024年09月16日

`LLM应用` `数据管理`

> Messy Code Makes Managing ML Pipelines Difficult? Just Let LLMs Rewrite the Code!

# 摘要

> 机器学习应用越来越多地用于自动化重要决策，但往往难以有效管理关键数据和遵守新规。问题根源在于，现有 ML 库和云服务的数据管道缺乏声明性和数据中心化的基本抽象。近期研究表明，这些抽象能助力来源追踪和自动检查等技术，但因需使用声明性 API 编写的整洁代码，而现实中数据科学家常用的是混乱的 Python 代码，故难以推广。  我们认为，要求数据科学家改变习惯不切实际。因此，我们提出利用大型语言模型的代码生成能力，绕过“代码抽象差距”。我们的方案是将杂乱的数据科学代码重写为定制的声明性管道抽象，并在 Lester 原型中验证。通过一个合规管理的挑战性案例，我们展示了 LLM 将混乱代码转化为声明性代码的潜力，如识别 Python 中的手工连接并转换为数据帧连接，或从 NumPy 代码生成声明性特征编码器。

> Machine learning (ML) applications that learn from data are increasingly used to automate impactful decisions. Unfortunately, these applications often fall short of adequately managing critical data and complying with upcoming regulations. A technical reason for the persistence of these issues is that the data pipelines in common ML libraries and cloud services lack fundamental declarative, data-centric abstractions. Recent research has shown how such abstractions enable techniques like provenance tracking and automatic inspection to help manage ML pipelines. Unfortunately, these approaches lack adoption in the real world because they require clean ML pipeline code written with declarative APIs, instead of the messy imperative Python code that data scientists typically write for data preparation.
  We argue that it is unrealistic to expect data scientists to change their established development practices. Instead, we propose to circumvent this "code abstraction gap" by leveraging the code generation capabilities of large language models (LLMs). Our idea is to rewrite messy data science code to a custom-tailored declarative pipeline abstraction, which we implement as a proof-of-concept in our prototype Lester. We detail its application for a challenging compliance management example involving "incremental view maintenance" of deployed ML pipelines. The code rewrites for our running example show the potential of LLMs to make messy data science code declarative, e.g., by identifying hand-coded joins in Python and turning them into joins on dataframes, or by generating declarative feature encoders from NumPy code.

[Arxiv](https://arxiv.org/abs/2409.10081)