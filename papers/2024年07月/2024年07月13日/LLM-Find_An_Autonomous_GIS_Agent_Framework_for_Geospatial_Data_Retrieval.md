# LLM-Find：一款自主式GIS代理框架，专为地理空间数据检索设计。

发布时间：2024年07月13日

`Agent` `地理信息系统` `数据检索`

> LLM-Find: An Autonomous GIS Agent Framework for Geospatial Data Retrieval

# 摘要

> 随着大型语言模型 (LLM) 的兴起，自主地理信息系统 (GIS) 代理展现出完成空间分析和制图任务的潜力。然而，如何使这些代理自主发现并下载地理空间分析所需的数据，仍是一个研究空白。为此，我们提出了 LLM-Find 框架，该框架通过生成、执行和调试程序，自主选择并获取所需地理空间数据。LLM-Find 以 LLM 为核心决策引擎，从预设数据源列表中精准选取数据，并高效获取。每个数据源配备详细手册，涵盖元数据和技术细节，确保数据检索的准确性。框架采用即插即用设计，便于灵活扩展，用户或数据爬虫可通过添加新手册轻松引入新数据源。我们开发的 LLM-Find 原型代理，已成功从多个权威数据源如 OpenStreetMap、美国人口普查局、ESRI 世界影像、商业天气数据提供商及 NYTimes GitHub 等，检索到包括 COVID-19 数据在内的各类地理空间信息。本研究标志着自主地理空间数据检索代理开发的创新尝试。

> Powered by the emerging large language models (LLMs), autonomous geographic information systems (GIS) agents have the potential to accomplish spatial analyses and cartographic tasks. However, a research gap exists to support fully autonomous GIS agents: how to enable agents to discover and download the necessary data for geospatial analyses. This study proposes LLM-Find, an autonomous GIS agent framework capable of selecting and fetching required geospatial data by generating, executing, and debugging programs. LLM-Find utilizes the LLM as the decision-maker, selects the appropriate data source (s) from a pre-defined source list, and fetches the data from the chosen source. Each data source has a handbook that records the metadata and technical details for data retrieval. The proposed framework is designed in a plug-and-play style to ensure flexibility and extensibility. Human users or autonomous data scrawlers can add a new data source by adding a new handbook. We developed a prototype agent based on LLM-Find, and experiment results demonstrate its capability of retrieving data from various sources including OpenStreetMap, administrative boundaries and demographic data from the US Census Bureau, satellite basemaps from ESRI World Imagery, weather data from a commercial provider, and the COVID-19 data from the NYTimes GitHub. Our study is among the first attempts to develop an autonomous geospatial data retrieval agent.

[Arxiv](https://arxiv.org/abs/2407.21024)