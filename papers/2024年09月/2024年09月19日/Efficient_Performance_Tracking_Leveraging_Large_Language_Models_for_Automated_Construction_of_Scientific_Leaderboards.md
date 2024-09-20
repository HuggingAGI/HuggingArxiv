# 借助大型语言模型，实现科学排行榜的自动化构建，提升性能追踪效率。

发布时间：2024年09月19日

`LLM应用` `科研评估` `数据集管理`

> Efficient Performance Tracking: Leveraging Large Language Models for Automated Construction of Scientific Leaderboards

# 摘要

> 科学排行榜是评估和比较竞争性方法的标准化系统。通常，排行榜由任务、数据集和评估指标（TDM）三元组定义，通过基准测试促进创新。然而，出版物的激增使得手动维护排行榜变得不切实际。自动构建排行榜应运而生，但现有数据集存在不完整和错误信息的问题。我们提出了SciLead，一个手工策划的科学排行榜数据集，解决了这些问题。基于此，我们设计了三种实验设置，模拟了TDM三元组在排行榜构建中的不同定义情况。我们开发了一个基于LLM的全面框架来应对这些多样化设置。实验表明，LLM能正确识别TDM三元组，但在提取结果值时遇到挑战。我们公开了代码和数据。

> Scientific leaderboards are standardized ranking systems that facilitate evaluating and comparing competitive methods. Typically, a leaderboard is defined by a task, dataset, and evaluation metric (TDM) triple, allowing objective performance assessment and fostering innovation through benchmarking. However, the exponential increase in publications has made it infeasible to construct and maintain these leaderboards manually. Automatic leaderboard construction has emerged as a solution to reduce manual labor. Existing datasets for this task are based on the community-contributed leaderboards without additional curation. Our analysis shows that a large portion of these leaderboards are incomplete, and some of them contain incorrect information. In this work, we present SciLead, a manually-curated Scientific Leaderboard dataset that overcomes the aforementioned problems. Building on this dataset, we propose three experimental settings that simulate real-world scenarios where TDM triples are fully defined, partially defined, or undefined during leaderboard construction. While previous research has only explored the first setting, the latter two are more representative of real-world applications. To address these diverse settings, we develop a comprehensive LLM-based framework for constructing leaderboards. Our experiments and analysis reveal that various LLMs often correctly identify TDM triples while struggling to extract result values from publications. We make our code and data publicly available.

[Arxiv](https://arxiv.org/abs/2409.12656)