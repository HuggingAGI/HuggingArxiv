# 利用大型语言模型，构建了一个可扩展的数据驱动框架，用于系统分析 SEC 10-K 文件。

发布时间：2024年09月26日

`LLM应用` `数据分析`

> A Scalable Data-Driven Framework for Systematic Analysis of SEC 10-K Filings Using Large Language Models

# 摘要

> 随着纽约证券交易所上市公司数量的激增，市场分析师、交易员和股东面临着巨大的挑战，他们需要定期监控和评估大量公司的业绩和战略变化。为此，我们提出了一种基于大型语言模型（LLM）的数据驱动方法，通过分析公司的 SEC 10-K 文件，系统地评估公司业绩。这些文件不仅提供了详细的财务报告，还涵盖了公司的战略方向，是评估公司健康状况的宝贵数据源。我们还开发了一个自动化系统，用于提取和预处理 10-K 文件，确保关键信息的准确提取。通过将这些数据输入到 Cohere 的 Command-R+ LLM 中，我们能够生成全面的绩效评级，并通过可视化工具提供可操作的见解。最终，我们实现了一个交互式无代码解决方案，用户可以轻松运行数据管道并创建可视化报告，直观展示公司业绩的年度对比。

> The number of companies listed on the NYSE has been growing exponentially, creating a significant challenge for market analysts, traders, and stockholders who must monitor and assess the performance and strategic shifts of a large number of companies regularly. There is an increasing need for a fast, cost-effective, and comprehensive method to evaluate the performance and detect and compare many companies' strategy changes efficiently. We propose a novel data-driven approach that leverages large language models (LLMs) to systematically analyze and rate the performance of companies based on their SEC 10-K filings. These filings, which provide detailed annual reports on a company's financial performance and strategic direction, serve as a rich source of data for evaluating various aspects of corporate health, including confidence, environmental sustainability, innovation, and workforce management. We also introduce an automated system for extracting and preprocessing 10-K filings. This system accurately identifies and segments the required sections as outlined by the SEC, while also isolating key textual content that contains critical information about the company. This curated data is then fed into Cohere's Command-R+ LLM to generate quantitative ratings across various performance metrics. These ratings are subsequently processed and visualized to provide actionable insights. The proposed scheme is then implemented on an interactive GUI as a no-code solution for running the data pipeline and creating the visualizations. The application showcases the rating results and provides year-on-year comparisons of company performance.

[Arxiv](https://arxiv.org/abs/2409.17581)