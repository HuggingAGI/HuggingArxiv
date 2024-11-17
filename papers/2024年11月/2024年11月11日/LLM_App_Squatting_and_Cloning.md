# LLM 应用的抢占与克隆

发布时间：2024年11月11日

`LLM应用` `移动应用` `语言模型`

> LLM App Squatting and Cloning

# 摘要

> 模仿策略，比如应用程序抢占和克隆，在移动应用商店中向来是棘手难题，恶意分子会利用热门应用的名号和声誉来蒙骗用户。随着 GPT Store 和 FlowGPT 等大型语言模型（LLM）商店的快速兴起，此类问题也接踵而至，给 LLM 应用生态系统的完整性带来威胁。在本次研究中，我们借助自研的 LLMappCrazy 工具，首次对 LLM 应用的抢占和克隆展开大规模分析。LLMappCrazy 涵盖 14 种抢占生成技术，还融合了莱文斯坦距离和基于 BERT 的语义分析，通过剖析应用的功能相似性来侦测克隆情况。利用此工具，我们生成了排名前 1000 的应用名称变体，在数据集中找出了 5000 多个抢占应用。另外，我们在六个主要平台上发现了 3509 个抢占应用和 9575 个克隆案例。经抽样发现，18.7%的抢占应用和 4.9%的克隆应用存在恶意行为，涵盖网络钓鱼、恶意软件传播、虚假内容散布以及激进的广告植入。

> Impersonation tactics, such as app squatting and app cloning, have posed longstanding challenges in mobile app stores, where malicious actors exploit the names and reputations of popular apps to deceive users. With the rapid growth of Large Language Model (LLM) stores like GPT Store and FlowGPT, these issues have similarly surfaced, threatening the integrity of the LLM app ecosystem. In this study, we present the first large-scale analysis of LLM app squatting and cloning using our custom-built tool, LLMappCrazy. LLMappCrazy covers 14 squatting generation techniques and integrates Levenshtein distance and BERT-based semantic analysis to detect cloning by analyzing app functional similarities. Using this tool, we generated variations of the top 1000 app names and found over 5,000 squatting apps in the dataset. Additionally, we observed 3,509 squatting apps and 9,575 cloning cases across six major platforms. After sampling, we find that 18.7% of the squatting apps and 4.9% of the cloning apps exhibited malicious behavior, including phishing, malware distribution, fake content dissemination, and aggressive ad injection.

[Arxiv](https://arxiv.org/abs/2411.07518)